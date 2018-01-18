# VSCode for Arduino
Introduction to programming your microcontroller using Visual Studio Code (VSCode) instead of the Arduino IDE.

## VSCode Introduction
VSCode is a lightweight code editor by Microsoft that supports many languages and has many built in features including:

* Integrated terminal (Git Bash, PowerShell)
* Syntax highlighting
* Code refactoring
* Version control
* Built in debugger
* Custom keyboard shortcuts
* *Editor's Note:* Looks *prettier* than the Arduino IDE, that's for sure!

## Pre-requisites
You will need to download two things:

* [Visual Studio Code](https://code.visualstudio.com/download)
* [Arduino IDE](https://www.arduino.cc/en/Main/Software) Yes, we need it for the VSCode integration, but we won't use this to code.

## Things to do
### VSCode
**Install Arduino Extension**

Go to Extensions -> Search for "Arduino", select and install the extension by Microsoft.

**Configure Intellisense**

![Screen Shot](https://favoriot.github.io/image/Capture.PNG)

Press F1 (Command Palette) -> Search for "User Settings", and on the right panel *User Settings*, add 
`"C_Cpp.intelliSenseEngine": "Tag Parser",` before the next item in the object.
*Note: Intellisense with Arduino still has some bugs and is prone to issues.


**Set Board Type, Port Number**

To change the board settings, access it at F1 -> Arduino: Board Config and select your board there.

To change the port number, access the port settings at F1 -> Change serial port and select the port which the arduino is connected to.

## Accessing Arduino IDE functions through VSCode
Most if not all of Arduino IDE's special features can be access through F1 followed by searching its name. However, here's a handy cheat sheet for using shortcut keys instead (Changable)

* Verify: Ctrl + Alt + R
* Upload: Ctrl + Alt + U
* Open Serial Monitor: Search for "Open Serial Monitor" in the command palette
* Close Serial Monitor: Search for "Close Serial Monitor" in the command palette
