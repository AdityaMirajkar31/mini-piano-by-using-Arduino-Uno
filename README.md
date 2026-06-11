# 🎹 Arduino Mini Piano

A compact, 8-key electronic mini piano built using an Arduino Uno, pushbuttons, and a piezo speaker/buzzer. Each button is mapped to a specific musical note from C4 to C5.

## 🔌 Components Used
* **Microcontroller:** Arduino Uno
* **Output:** 1x Piezo Buzzer / Speaker
* **Inputs:** 8x Tactile Pushbuttons
* **Miscellaneous:** Breadboard, Jumper wires

## 📐 Circuit Connection Mapping

| Component | Arduino Pin | Note |
| :--- | :--- | :--- |
| Buzzer / Speaker (+) | Pin 8 | - |
| Button 1 | Pin 12 | C4 |
| Button 2 | Pin 11 | D4 |
| Button 3 | Pin 10 | E4 |
| Button 4 | Pin 9 | F4 |
| Button 5 | Pin 7 | G4 |
| Button 6 | Pin 6 | A4 |
| Button 7 | Pin 5 | B4 |
| Button 8 | Pin 4 | C5 |

*Note: The other side of all pushbuttons and the negative (-) pin of the buzzer must be connected to the Arduino's **GND** pin.*
