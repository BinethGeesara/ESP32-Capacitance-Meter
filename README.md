# 📏 ESP32 Capacitance Meter (pF/nF Range)
This project is a custom capacitance meter built using the ESP32 microcontroller. It can measure small capacitance values in the picoFarad (pF) and nanoFarad (nF) range with improved stability using a Schmitt trigger (74HC14) for pulse shaping and noise rejection.

🔧 Features
📐 Measures capacitance in the ~1pF to 1000nF range
🧠 Uses ESP32 for fast pulse timing and calculation
⚡ Based on RC charge-discharge timing method
🔁 Customizable measurement range by changing reference resistor
📊 OLED or serial output support for live readings
🧱 4HC14 Schmitt trigger for signal conditioning and edge sharpening

🧪 How It Works
Capacitor charges/discharges through a known resistor
Time taken is measured using micros() function
Capacitance calculated from the RC time constant formula
Schmitt trigger creates clean square wave transitions for accurate timing

🧰 Components
🧠 ESP32 (DevKit board)
🔘 74HC14 IC
📎 Reference resistor(s) (1kΩ – 1MΩ depending on range)
📦 Capacitor under test
OLED display or serial monitor for readings
