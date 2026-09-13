 Geoscan Pioneer Quadcopter - TRIK Studio Flight & LED Program

This repository contains an automated flight control program developed in **TRIK Studio** for the **Geoscan Pioneer Kit** quadcopter. The project executes an autonomous flight sequence while using the drone's 4 addressable RGB LEDs as visual status telemetry for each phase of flight.

  Flight & Telemetry Sequence

1. Standby / Pre-flight:
   Flight:  4-second system initialization delay.
   LED Telemetry: Solid Green (`R: 0, G: 255, B: 0`).


2. Takeoff:
   Flight: Autonomous takeoff and climb to an altitude of $1.5\text{ m}$.
   LED Telemetry: Solid Red (`R: 255, G: 0, B: 0`).


3. Waypoint Navigation:
   Flight: Autonomous flight to target coordinates $(X: 1.2, Y: 2.0, Z: 1.5)$.
   LED Telemetry: Solid Blue (`R: 0, G: 0, B: 255`).


4. Landing:
   Flight: Controlled descent, landing, and motor disarm sequence.
   LED Telemetry: Solid Yellow (`R: 255, G: 255, B: 0`).

  Prerequisites

  TRIK Studio (configured with the *Pioneer Kit* palette)
  Geoscan Pioneer quadcopter (or the built-in TRIK Studio 2D Simulator)

  How to Run

1. Open TRIK Studio.
2. Select File > Open and open the `.qrs` project file.
3. Switch to the Robot's Behaviour Diagram tab.
4. Click the green Play button (or press `Ctrl + R`) to launch the 2D simulator or transmit the code to your connected Pioneer quadcopter over Wi-Fi.

   <img width="1221" height="1012" alt="Screenshot 2026-09-13 183547" src="https://github.com/user-attachments/assets/a22ac819-11b8-4d03-9795-4eb839b6a1bd" />

   

