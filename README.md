## What

Small script to water Plants on a schedule with an Relais for a pump. Its nothing else than a glorified timer for an USB pump.

## Overview

The system is designed with reliability in mind:

- All watering schedule settings (times, duration, enabled status) are stored in flash memory and persist through device restarts and power outages
- When the ESP restarts, it immediately loads saved settings from flash and sends them to Home Assistant
- For safety, the pump always starts in the OFF state after any power loss event
- Active watering states do not persist through power loss as a safety feature, preventing unexpected resumption of watering

<img width="750" alt="image" src="https://github.com/user-attachments/assets/95adeb32-332c-4523-83b8-9b6bc461d64d" />


<img width="750" alt="image" src="https://github.com/user-attachments/assets/e31d03e7-25e6-4ba8-a890-ecdef8f3de50" />


<img width="750" alt="image" src="https://github.com/user-attachments/assets/b50eb0ed-a168-4937-b3ae-e3eaa046b3c4" />



