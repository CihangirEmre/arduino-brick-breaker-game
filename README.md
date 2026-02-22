# Arduino-Based Brick Breaker Game

## Overview

This project was developed for Programming Laboratory II at Kocaeli University.

The objective was to design and implement a microcontroller-based Brick Breaker game using Arduino and external hardware components.

The player controls a paddle using a potentiometer and attempts to break bricks displayed on an OLED screen.

## Hardware Components

- Arduino UNO
- OLED Display (SSD1306)
- Potentiometer (Paddle Control)
- 7-Segment Display (Score)
- 74HC595 Shift Register
- LEDs (Life Indicator)
- Light Sensor
- Push Buttons

## Game Mechanics

- Paddle controlled via potentiometer
- Ball reflects according to physical collision rules
- Score increases when bricks are destroyed
- Score displayed on 7-segment display
- 3 lives indicated by LEDs
- Falling bonus objects (+1 life, 10% chance)
- Speed increases by 20% after each level
- Score does not reset between levels
- Game returns to menu after losing all lives

## Menu System

- Start
- Quit

Navigation via up/down buttons.

## Algorithm Design

- Collision detection for:
  - Paddle
  - Walls
  - Bricks
- Dynamic ball velocity adjustment
- Random brick generation
- Bonus object drop logic
- Level progression system

## OOP / Embedded Concepts

- State management
- Real-time input handling
- Interrupt-style logic
- Hardware-software interaction
- Memory-efficient design

## Technologies Used

- Arduino IDE
- C/C++
- Proteus Simulation
- OLED Graphics Libraries:
  - Wire
  - Adafruit_GFX
  - Adafruit_SSD1306

## Project Report

Detailed IEEE-format report available, name is:
Report.pdf

