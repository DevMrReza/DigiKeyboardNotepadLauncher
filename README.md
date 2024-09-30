# DigiKeyboard Notepad Launcher

This project is a simple Arduino script that uses the `DigiKeyboard` library to simulate keyboard inputs to a computer. The program opens Notepad by pressing the **Windows + R** key combination and then types a message into it.

## Project Contents

- **Main Code**: Contains commands to open Notepad and send a message.

## Prerequisites

To use this project, you will need:

- A compatible Arduino device (such as **Digispark** or **USB Rubber Ducky**).
- The `DigiKeyboard` library, which should be installed via the Arduino Library Manager.

## Installation

1. Install the `DigiKeyboard` library from the Arduino Library Manager.
2. Copy the code into a new file in the Arduino IDE.
3. Connect your Arduino device to your computer.
4. Upload the code to the device.

## Usage

Once the code is uploaded, plug the Arduino device into a USB port on the target computer. The device will automatically execute the following actions:

1. Open the **Run** dialog by simulating the **Windows + R** key press.
2. Type "notepad" and hit **Enter** to open Notepad.
3. Type the message "You Have Been Hacked By VN !" in the Notepad window.

## Disclaimer

This script is intended for educational purposes and should be used responsibly. Misuse of this code for unauthorized access or malicious intent is illegal and unethical.
