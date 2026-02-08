🔐 Password-Based Authentication & Entry Monitoring System
Digital Logic Design Project

A digital logic–based security system that authenticates users using a password stored in a CD4043 SR latch, triggers alerts for unauthorized access, and automatically counts valid entries using a laser–LDR sensor mechanism.

📌 Project Overview

This project implements a password-protected access control system combined with an automatic entry monitoring unit. Only users who enter the correct password are granted access, after which the system counts the number of people entering the secured area in real time. Incorrect password attempts activate both visual and audio alerts, acting as a thief detection mechanism.

The design is implemented using basic digital logic components, making it cost-effective, reliable, and suitable for academic and small-scale security applications.

🎯 Objectives

Prevent unauthorized access using password authentication

Securely store the password using a CD4043 SR latch

Generate alerts for incorrect password attempts

Detect and count authorized entries automatically

Display the entry count using a 7-segment cathode display

⚙️ System Architecture

The system is divided into three main blocks:

Password Storage & Verification

Password entered using DIP switches

Stored in CD4043 SR latch

Compared using XOR (7486) and NOR (7402) gates

Security Alert System

Red LED and buzzer activate on wrong password

Detects unauthorized access attempts

Entry Monitoring & Counter

Laser + LDR detect entry

Logic pulse increments counter

Entry count displayed on 7-segment display

🧠 Working Principle

A binary password is set using DIP switches and stored in a CD4043 SR latch.

When the system is enabled, the user re-enters the password.

XOR gates compare each bit of the entered password with the stored password.

If all bits match:

Green LED turns ON

Entry monitoring system is enabled

If any bit mismatches:

Red LED turns ON

Buzzer sounds as a security alert

A laser–LDR pair detects each valid entry and generates a pulse.

Each pulse increments the counter, and the total count is shown on the display.

🧩 Components Used
Integrated Circuits

CD4043 SR Latch

7486 XOR Gate

7402 NOR Gate

Input & Output Devices

DIP switches

Push buttons / tactile switches

Green LED, Red LED

Buzzer

7-segment cathode display

Sensors & Power

Laser module

LDR (Light Dependent Resistor)

5V–12V DC power supply(Booster circuit)

🧪 Simulation

The system was simulated using digital logic simulation software to verify:

Correct password authentication

Alert activation for wrong passwords

Accurate entry counting using laser interruption logic

📸 Simulation Screenshot:
<img width="802" height="341" alt="simulation" src="https://github.com/user-attachments/assets/5ea87a5f-0064-48ee-a3ac-55919f0a2206" />


✅ Advantages

Enhanced security using digital logic

Stable password storage via SR latch

Real-time entry monitoring

Low-cost and easy to implement

Suitable for academic and small-scale security systems

⚠️ Limitations

Limited scalability for multiple entry points

Requires continuous power supply

Laser–LDR accuracy may be affected by environmental conditions

📄 Documentation

📘 LaTeX Lab Report included

📊 Simulation diagrams available

🎥 Presentation video script ready

🚀 Applications

Laboratories

Offices

Secure rooms

Educational demonstrations of digital logic concepts

👨‍💻 Author

Mohammed Mahbub Alam
Department of Electronics and Telecommunication Enginnering
Chittagong University of Engineering and Technology

📜 License

This project is intended for educational purposes.
Feel free to fork, modify, and learn from it.
