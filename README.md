GutCheck

Dual-ultrasonic gutter clog detector with a real-time web dashboard for homeowners.

GutCheck is a low-cost, mountable sensor system that detects gutter clogs before they cause water damage. Two ultrasonic sensors take a differential-pair water-level measurement inside the gutter, and the results are streamed to a web dashboard where homeowners can see at a glance whether their gutters need attention.

Built by Alex Huang, Euvene Kae, Sahej Sachdeva, and Benson Zhang for the Design Thinking and Communication program at Northwestern University's McCormick School of Engineering.


Table of Contents


Overview
Features
How It Works
Tech Stack
Hardware / Bill of Materials
Repository Structure
Getting Started
Design Requirements
Future Development
Team
Acknowledgments
License



Overview

Clogged gutters cost American homeowners hundreds to thousands of dollars a year in water damage, mold, and foundation repair — most of it preventable if the clog is caught early. GutCheck mounts directly onto an existing gutter (replacing two standard gutter hangers, no major retrofit required) and continuously monitors water flow, flagging clogs before they become expensive problems.

Features


🌊 Differential-pair clog detection — two ultrasonic sensors measure water level at two points; the difference between readings indicates a blockage
🛡️ Waterproof enclosure — 3D-printed polycarbonate housing, silicone-sealed, rated for outdoor exposure
📶 Real-time dashboard — color-coded status (green/yellow/amber/red) with expandable graphs of live sensor data
🏠 Multi-house, multi-sensor support — hierarchical data model (user → house → gutter system → sensor), each sensor uniquely identified by its ESP32 MAC address
📉 Noise-resistant readings — a simple moving average (SMA) algorithm filters out momentary spikes from environmental interference
💸 Low cost — full prototype bill of materials is under $100


How It Works


Two IP67 ultrasonic range sensors measure water level at two points along the gutter.
An ESP32 DevKit reads both sensors and sends data packets (tagged with the sensor's MAC address) to the backend.
Supabase (PostgreSQL + Auth) ingests the data, applies a simple moving average to smooth out noise, and computes the differential between the two sensors.
Differences are bucketed into severity levels (clear → minor → moderate → severe clog) based on tested thresholds.
The React.js dashboard displays a live status indicator per sensor, with the option to expand into detailed graphs and raw readings.


Tech Stack

LayerTechnologyMicrocontrollerESP32 DevKitSensorsIP67 UART Ultrasonic Range SensorsPowerAdafruit Waterproof 3×AA Battery HolderBackend / DBSupabase (PostgreSQL, Supabase Auth)FrontendReact.jsEnclosure3D-printed polycarbonate (PC), silicone-sealed

Hardware / Bill of Materials

ItemSpecsQtyCostBattery HolderWaterproof 3×AA2$14.64ESP32 DevKit—2$19.89PC Filament—1 kg$29.99BoltsM2x81 bag$6.89Wire16 AWG1$6.89Silicone Seal Strip2mm x 6m1$6.99Threaded InsertsM2x41 bag$9.99Total$95.28

STL files for the enclosure are available in the repo / linked Google Drive for anyone who wants to 3D print their own.

Repository Structure


⚠️ Update this section to match your actual folder layout — placeholder shown below.



gutcheck/
├── firmware/        # ESP32 sensor firmware
├── dashboard/        # React.js web dashboard
├── enclosure/         # STL files and CAD source for the 3D-printed enclosure
├── docs/              # Final report, diagrams, design docs
└── README.md

Getting Started


⚠️ These are general starting steps — adjust commands/paths to match the actual repo once code is added.



Firmware


Open the firmware/ project in the Arduino IDE or PlatformIO.
Set your Wi-Fi credentials and Supabase endpoint in the config file.
Flash to the ESP32 DevKit.


Dashboard

bashcd dashboard
npm install
npm run dev

Set your Supabase URL and anon key as environment variables before running.

Backend

Create a Supabase project, run the schema migrations (if included in docs/ or a supabase/ folder), and enable Supabase Auth.

Design Requirements

RequirementMetricIdealAllowableDetects clogsDifferential pair measurement>10%±5%WaterproofMock IP ratingIP54IP42Secure when attachedShake testDoesn't breakDoesn't breakLightweightTotal system mass2 lbs3 lbsLoad-bearingTotal system mass + object10 lbs10 lbsNotifies homeowner promptlyClog-to-notification time5 min10 min

Future Development


Adaptable/universal enclosure for 5", 6", and 7" K-style gutters
Move from 3D-printed PC to a more durable metal enclosure
Custom PCB to reduce footprint and improve signal integrity
Additional sensing methods (infrared, capacitive) for better flow detection
More scalable database structure for users with many gutter systems
UI improvements to pinpoint which section of a gutter is clogged


Team


Alex Huang
Euvene Kae
Sahej Sachdeva
Benson Zhang


Acknowledgments

Developed for the Design Thinking and Communication (DTC) program, McCormick School of Engineering and Applied Science, Northwestern University, under Professors Meghan Geigner and Zachary Berent.
