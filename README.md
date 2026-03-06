

# TP6 – Motion Detection System Using PIR Sensor

## Objective

In this practical lab, students will:

* Learn how a **PIR motion sensor** works
* Connect a PIR sensor to an Arduino
* Control an LED using motion detection
* Monitor motion using Serial Monitor
* Understand digital input/output behavior

---

# Required Components

Students must use:

* Arduino board (UNO)
* PIR Motion Sensor
* LED
* Breadboard

---

# System Behavior

The system works as follows:

When motion is detected:

* PIR output = HIGH
* LED turns ON
* Serial prints: `"Motion detected!"`

When motion stops:

* PIR output = LOW
* LED turns OFF
* Serial prints: `"Motion ended!"`

---

# Wiring Connection

| PIR Sensor | Arduino |
| ---------- | ------- |
| VCC        | 5V      |
| GND        | GND     |
| OUT        | Pin 2   |

| LED | Arduino               |
| --- | --------------------- |
| +   | Pin 13                |
| -   | GND                   |

-

---

# Optional Improvements (Advanced Level)

Students can improve the project by:

* Adding a buzzer alarm
* Adding LCD display
* Sending motion data via MQTT
* Sending data to a cloud dashboard


---

# Submission Requirements

Students must submit:



