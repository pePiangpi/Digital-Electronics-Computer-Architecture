# Unit 5: PLD Digital Door Lock System

## 🔒 Project Overview
This project demonstrates the design of a digital security system using Programmable Logic Device (PLD) principles. The circuit simulates a door lock that requires a specific input sequence to grant access.
Here is the circuit design for the PLD Door Lock System:

### System Status: Access Denied
![Security system showing incorrect passcode attempt](./Digital-Electronics-Computer-Architecture/red.png)

### System Status: Access Granted
![Security system showing successful authentication](./Digital-Electronics-Computer-Architecture/green.png)


## 🕹️ Functionality
The system monitors input pins and evaluates them against a preset "key" logic:
* **Input Stage:** Accepts binary input representing a security code.
* **Comparison Logic:** Uses XOR/AND gates to verify the input against the stored key.
* **Status Indicators:** * **Green LED:** Access Granted (Correct code).
  * **Red LED:** Access Denied (Incorrect code).
* **Reset Feature:** Allows the user to clear the current input and try again.

## 🏗️ Technical Architecture
* **Gates:** Implemented using standard logic gates (AND, OR, NOT, XOR).
* **Control:** Uses a comparator circuit to match inputs to a 4-bit or 8-bit security key.
* **Output:** Connected to digital probes and LEDs for real-time feedback.

## 🛠️ How to Test
1. Open `Unit5DoorLockSystem.circ` in Logisim.
2. Use the **Poke Tool** to toggle the input switches.
3. Observe the LED outputs to verify if the logic correctly identifies the valid passcode.
