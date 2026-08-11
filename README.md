### Tinkercad Design
[View Tinkercad Design](https://www.tinkercad.com/things/fEZveUSepxy/editel?returnTo=%2Fdashboard&sharecode=2P4pS1wOQ3gjbPLnBok5PI03b4pKhleGlmkXA2n1fZ4)
# Humanoid Robot - Servo Motor Control

## Task Description

This task implements the control of four servo motors for the Humanoid Robot using Arduino.

The four servo motors perform a sweep movement for approximately two seconds and then move to and hold the 90-degree position.

## Components

- Arduino Uno R3
- 4 × Micro Servo Motors

## Servo Connections

| Servo | Signal Pin | Power | Ground |
|---|---:|---|---|
| Servo 1 | 3 | 5V | GND |
| Servo 2 | 5 | 5V | GND |
| Servo 3 | 6 | 5V | GND |
| Servo 4 | 9 | 5V | GND |

## Program

The program controls all four servo motors simultaneously. The motors sweep from 0° to 180°, return to 0°, and then move to 90° where they remain stationary.

## Tinkercad

Tinkercad simulation link:

[PASTE TINKERCAD LINK HERE]

## Result

The four servo motors successfully perform the required sweep movement and stop at 90°.

## Notes

The circuit was simulated using Tinkercad Circuits and programmed using Arduino C++.
