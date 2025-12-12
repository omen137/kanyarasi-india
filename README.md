# kanyarasi-india
for smart india hackathon
# Hybrid Tactical Communication & Navigation System

A lightweight hybrid communication and tracking device that integrates real-time GPS navigation with dual-mode communication (LoRa + GSM). The system ensures uninterrupted connectivity, autonomous decision-making, and multi-day battery endurance for field operations.

---

## 1. What This Project Does

- Combines communication and GPS tracking into a single compact device.
- Provides continuous location updates using integrated GPS.
- Automatically switches between LoRa (short-range) and GSM (long-range) communication.
- Uses LED indicators to alert the user of communication mode changes.
- Delivers high precision location transmission (up to four decimal places).
- Offers extended battery operation of 3–4 days on a full charge.
- Remains lightweight (150–250 g) and field-ready.
- Runs on on-board intelligence for autonomous decisions and power optimization.

---

## 2. Problem Statement & Solution

### Problem Statement
Border and field personnel rely on separate devices for communication and GPS tracking. This results in:
- Extra weight and cost.
- Higher power consumption.
- Lower operational efficiency.
- Delays in situational awareness.
- Unreliable communication in difficult terrains.

### Solution
A unified hybrid device that integrates:
- Short-range, low-power communication for team-level operations.
- Long-range GSM communication when outside LoRa range.
- Real-time GPS tracking for movement visibility.
- Automatic communication switching to prevent connectivity loss.
- On-board intelligence for autonomous behavior and decision-making.

This reduces load, improves reliability, and increases operational efficiency.

---

## 3. Features

- Hybrid LoRa + GSM communication.
- Automatic switching based on LoRa range thresholds.
- LED indication for communication mode changes.
- Real-time GPS tracking with high precision.
- Battery life of 3–4 days on full charge.
- Lightweight design (150–250 g).
- Switching latency less than 400 ms.
- Works consistently in obstructed and remote terrains.
- Scalable architecture with software upgrades (₹5k–₹6k).
- On-board intelligence for power optimization and decision-making.

---

## 4. Technologies Used

- **ESP32** – System controller and logic manager  
- **LoRa Module** – Low-power short to mid-range communication  
- **SIM800L GSM Module** – Long-range cellular communication  
- **NEO-6M GPS Module** – Real-time geolocation tracking  
- **Arduino / Embedded C** – Firmware development  
- **AT Commands & Serial Communication** – Communication handling  
- **On-board Algorithms** – Intelligent switching and power management  

---

## 5. Steps to Install / Set Up

### Hardware Setup
1. Connect ESP32 with LoRa module via SPI.
2. Connect SIM800L with proper voltage regulation.
3. Connect NEO-6M GPS via UART.
4. Attach LED for communication switch indication.
5. Assemble components into a lightweight enclosure (150–250 g).
6. Ensure a battery capable of supporting 3–4 days of operation.

### Software Setup
1. Install Arduino IDE or PlatformIO.
2. Install ESP32 board support.
3. Install required libraries:
   - LoRa library  
   - TinyGSM  
   - GPS/UBlox parser  
4. Clone the repository:
   ```bash
   git clone <your-repo-link>
   cd <project-folder>
