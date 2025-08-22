AR Wave Visualizer

# Overview #

The AR Wave Visualizer is a project that aims to make invisible electromagnetic (EM) signals visible in near real-time through an augmented reality headset.
By combining software-defined radios (SDRs), signal processing, and AR visualization, the system allows users to “see” wireless signals such as WiFi, Bluetooth, and cellular connections as immersive wave patterns.

### Features #

 - Signal Visualization – Render WiFi, cellular, and Bluetooth signals as dynamic waves or vector fields.
 - Signal Mode Switching – Toggle between signal types to reduce clutter and avoid overlapping noise.
 - Adjustable Update Speed – Control how fast the visuals refresh (tradeoff between realism and clarity).
 - Portable Design – Backpack houses SDR hardware, battery, and processing unit.
 - AR Integration – Visualizations aligned with headset tracking for immersive experience.
 - System Architecture

### Headset #

 - Displays EM visualizations.
 - Includes mode-switching buttons.
 - Backpack Unit
 - Contains SDR unit(s).
 - Provides power supply and processing hardware.
 - Python / Unity software.
 - Collects SDR data.
 - Applies FFTs, filtering, and noise reduction.
 - Converts signals into AR-ready waveforms and patterns.

### Current Limitations #

 - Hardware Constraints – SDR sensitivity, antenna quality, and wearable integration.
 - Signal Ambiguity – Overlapping signals (e.g., 2.4 GHz WiFi & Bluetooth) can cause interference.
 - Data Processing – Real-time FFTs and AR rendering demand high computing power.
 - Latency – Visualizations may lag due to hardware/software delays.
 - Portability – Backpack form factor could become bulky.
 - Battery Life – High power draw from continuous SDR + AR rendering.
 - Regulatory Compliance – Must remain passive (non-transmitting) to meet FCC restrictions.

 ### Roadmap #
 
  - Mockups and hardware diagrams.
  - Aquire required hardware. 
  - Basic SDR data capture + offline visualization.
  - Develop prototype AR rendering pipeline.
  - Integrate headset + backpack prototype.
