# EE 120 Lab 3: Keypad and OLED Interface

This project uses an STM32 NUCLEO-L476RG to read input from a 4x4 keypad and display the entered characters on a 128x64 OLED screen.

## Hardware

- STM32 NUCLEO-L476RG
- 4x4 keypad
- 128x64 OLED display

## Software

- C
- Keil uVision
- STM32 Cortex-M4
- GPIO keypad scanning
- OLED display control

## Files

- `main.c` — main application and OLED display logic
- `keypad.c` — keypad GPIO setup and scanning functions
- `keypad.h` — keypad function declarations
