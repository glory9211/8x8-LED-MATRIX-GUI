# 8x8-LED-MATRIX-GUI
A simple tkinter Led GUI for generating C++ code to drive a single Max 7219 Led Matrix

By either Selecting LED's or Writing text

## Getting Started
Clone the Repository to your local machine
``` 
Navigate to dist\8x8 Matrix GUI\
```
Then Locate the file 8x8 Matrix GUI.exe

``` 
Run 8x8 Matrix GUI.exe 
```

### Prerequisites

You will Require the Arduino IDE to run the code.

Download the lastest version from

```
https://www.arduino.cc/en/Main/Software
```
You can setup the Arduino UNO by following the tutorial on

 ```
 https://www.arduino.cc/en/Guide/ArduinoUno
 ```
## Arduino Pin configuration

The pins are configured as

```
int DIN_PIN = 8;      // data in pin
int CS_PIN = 9;       // load (CS) pin
int CLK_PIN = 10;      // clock pin
```
You can change these in the beginnig of the code

## Using the GUI

The GUI has 2 Tabs.

Matrix Tab  --> Design the custom patterns easily

Text Tab    --> Write text and Choose the Delay to show the it on the LED

### Important Note

The text is diplayed as one char each (not implemented scrolling feature yet)
The space between words is shown by
```
******************
*                *
*                *
*                *
*                *
*       00       *
*     000000     *
******************
```
The End of text is displayed as

```
******************            ********************
*    |           *            *            |     *
*____|           *            *            |____ *
*                *     ---->  *                  *
*         _____  *            * ____             *
*        |       *            *     |            *
*        |       *            *     |            *
******************            ********************
```
### Recipe
The project is using the modules

```
Tkinter
pyperclip
```
And for making the executable
``` py2installer ```  is used.
## Acknowledgments
The code for the Arduino UNO is acquired from different online resources

For more fun you can visit

```
https://www.instructables.com/id/8x8-LED-Matrix-several-sketches-to-try-out/

https://www.brainy-bits.com/how-to-control-max7219-led-matrix/
```
