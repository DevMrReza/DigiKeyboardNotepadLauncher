<div align="center">

# ⚡ DigiKeyboard Notepad Launcher  
### _USB HID Automation Script (Educational PoC)_

A lightweight PoC demonstrating how a USB HID device (such as **Digispark**) can automate keystrokes, execute commands, and interact with the operating system without user input.

<br>

<img src="https://img.shields.io/badge/Platform-DigiSpark-orange?style=for-the-badge">
<img src="https://img.shields.io/badge/Type-USB_HID_Attack-blue?style=for-the-badge">
<img src="https://img.shields.io/badge/Use-EDUCATIONAL_ONLY-red?style=for-the-badge">
<img src="https://img.shields.io/badge/Language-Arduino-green?style=for-the-badge">

<br>
</div>

---

## 📝 Overview

This project uses the **DigiKeyboard** library to simulate keyboard input on a Windows machine.  
When plugged in, the device:

1. Opens the Windows **Run** dialog (`Win + R`)
2. Launches **Notepad**
3. Types the message:

```

You Have Been Hacked By VN !

```

This example demonstrates how HID-based devices can automate tasks and why USB security awareness is important.

---

## 📂 Project Contents

- **Main Script** – Contains the DigiKeyboard commands  
- **PoC Demo** – Simulated keystrokes for Notepad automation  
- **Educational Reference** – Demonstrates real-world USB HID attack behavior  

---

## 🔧 Requirements

You will need:

- ✔️ A **Digispark** (or similar USB HID attack device)
- ✔️ Arduino IDE installed
- ✔️ **DigiKeyboard** library  
  (`Tools → Manage Libraries → Search "DigiKeyboard"`)

---

## 🚀 Installation & Setup

1. Install the **DigiKeyboard** library from Arduino Library Manager  
2. Create a new `.ino` file in Arduino IDE  
3. Paste the provided code into your sketch  
4. Connect your Digispark board  
5. Upload the script (the board resets after upload)

---

## ▶️ How It Works (Execution Flow)

Once the device is plugged into a computer, it will automatically:

### 1️⃣ Trigger the Run Dialog
Simulates the keystroke:  
`Windows Key + R`

### 2️⃣ Launch Notepad
Types:

```

notepad

```

then presses **Enter**

### 3️⃣ Send the Message
Types into Notepad:

```

You Have Been Hacked By VN !

```

⚡ **No drivers needed** — Windows automatically detects DigiSpark as a keyboard.

---

## ⚠️ Ethical Disclaimer

This project is for:

- 🧪 Cybersecurity education  
- 🛡️ Awareness training  
- 🎓 Classroom demonstrations  
- 🔍 USB HID security research  

**Do NOT use on any system without explicit permission.**  
Unauthorized deployment is illegal, unethical, and punishable by law.  
You are responsible for all actions performed using this code.

---

<div align="center">

</div>
