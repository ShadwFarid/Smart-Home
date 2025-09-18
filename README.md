# 🏠 Smart Home with Arduino

A smart home automation project using **Arduino** to control lights, sensors, and electrical devices remotely and automatically.

---

## ⚙️ Features

- Smart Lock System:
   Automated door opening/closing using servo
   motor and keypad
- 🔥 Fire & Heat Alarm:
  Detection of fire or high temperature with
   buzzer & LED alerts.
- Smart Lighting System:
   Automated lights controlled by sensors or 
  user input for better energy saving.
- 🚨 Emergency Alert Button:
   Manual push button for instant warning
   
---

## 🧩 Components Used
1. Arduino UNO
2. Wires ,Resistors and Breadboard
3. Power Supply
4. 2 IR Sensors
5. 2 Servo Motors
6. Keypad (2x1 Matrix)
7. LCD (with I2C to reduce number of pins used and lines of code)
8. 2 Buzzers, LEDs and LDR
9.  Temperature Sensor (DHT11)
10. DC fan (with transistor)
11. Push Button
 

---

## 🛠️ How to Run

1) **Approach Detection (Door Control)**
- When someone approaches the door, two IR sensors detect their position.
- The door automatically opens in the opposite direction using a servo motor.
2) **Password Authentication**
- Enter the password using a 2x1 keypad.
- Correct password: A green LED turns on, the LCD screen displays “Welcome”, and the door opens.
- Wrong password: A buzzer sounds, and the LCD shows “Wrong Password” — you must re-enter the password.
3) **Temperature Monitoring & Fan Control**
- A temperature sensor continuously measures the room temperature (shown on the LCD).
- If temperature exceeds the set threshold → fan turns ON.
When it drops below the threshold → the fan turns OFF.
- If temperature goes beyond a critical level → an alarm is triggered and must be turned off manually using a push button.



4) **Light Intensity Control**
- An LDR sensor measures sunlight level.
- Based on the reading, the LED brightness is automatically adjusted (and shown on the LCD).
---

## 💻 Technologies

- Arduino (C/C++ language)
- Arduino IDE
- Standard Arduino libraries for sensors and output modules


---

## 📷 Project Images

```markdown
Smart Home>>(https://github.com/ShadwFarid/Smart-Home/commit/508916c7108d2bb1532d114b77373a0d5feb80c3)
