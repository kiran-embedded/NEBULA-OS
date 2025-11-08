Nebula OS  
Smart. Resilient. Alive.  
An adaptive embedded firmware for Arduino UNO — combining intelligence, aesthetics, and precision.

Nebula OS is a next-generation adaptive firmware designed for intelligent power management and precision control. Built for the Arduino UNO (ATmega328P), it merges reliability, cinematic display animation, and self-learning thermal behavior into a unified embedded operating core.

The system features a watchdog-protected scheduler, persistent outage memory using the .noinit section, and a fully adaptive fan engine that learns from temperature patterns. Even with a basic 12 V non-PWM fan, it delivers smooth jet-like transitions and dynamic control curves.

KEY FEATURES:
- Adaptive Thermal Control – Auto-learns and adjusts fan speed from 45°C to 70°C with smooth transitions.
- Persistent State Memory – Uses .noinit RAM to retain outage logs even after watchdog resets.
- Cinematic LCD Interface – Type-in, slide, and fade-in text animations on 16x2 I2C LCD.
- Dual Daily Alarms – Built-in real-time clock synchronization and alert scheduling.
- Self-Test Mode – Automatic diagnostic for sensors, LEDs, and communication modules at boot.
- Fan Ramp Test – Visually animated fan test sequence during startup.
- Low-Power Sleep Mode – Efficient idle sleep with watchdog protection.
- Immersive Boot Animation – Dynamic startup sequence with “NEBULA OS V1.3.1 — IMMERSIVE MODE ON”.

HARDWARE COMPATIBILITY:
- Arduino UNO / ATmega328P
- 16x2 I2C LCD Display (0x27)
- DS1307 RTC Module
- 12 V DC Fan (non-PWM compatible)
- LiFePO4 4S Battery Pack
- NTC Temperature Sensor (10 kΩ)

HOW IT WORKS:
Nebula OS continuously monitors power input, battery health, and temperature.
Its adaptive fan curve learns from long-term averages, shifting ramp points dynamically.
The system stores outage timestamps persistently, even through watchdog resets, and animates every page transition for a cinematic, modern experience.
