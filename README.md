# PIC16F877A Ultrasonic Sensor

An embedded system project built with a PIC16F877A microcontroller that, through four ultrasonic sensors, simultaneously measure distances in centimeters. It features real-time data visualization on a 16x2 LCD screen, an audible buzzer, and a distance-based LED progress indicator.


>**Proximity Alerts are as follows:**

  0 - 20 cm: Rapid beeps + Full LEDs

  20 - 40 cm: Moderate beeps + 3 LEDs

  40 - 60 cm: Slow beeps + 2 LEDs

  60 - 80 cm: Minimal beeps + 1 LED

  +80 cm: Standby / Off


>**Requirements & Dependencies**

  Microcontroller: Microchip PIC16F877A

  Compiler: XC8 C Compiler (MPLAB X IDE)

  Oscillator: 4 MHz external crystal (_XTAL_FREQ 4000000)


>**Peripherals:**

  4x Ultrasonic Distance Sensors (e.g., HC-SR04)

  16x2 LCD Display

  Buzzer & LEDs



>**Quick Setup**
  1. Clone or download this repository into MPLAB X IDE.

  2. Ensure your config.h matches your 4 MHz crystal configurations.

  3. Compile and flash the hex file onto your PIC16F877A microcontroller.

