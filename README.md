# Ironhack-week1-labs
My Labs for IronHack Week 1

# Week 1 Labs

This repository contains all the labs for Week 1 of the Ironhack Python course.

## Lab 1: HomeGuard Security System

The HomeGuard Security System is a simulator that monitors various sensors in a home. It generates readings, checks for abnormal conditions, and triggers alerts depending on the system mode (HOME, AWAY, SLEEP).

### Files in Lab 1

- `homeguard_system.ipynb` → Jupyter Notebook with the full code and simulation
- `simulation_output.txt` → Sample output from running the simulation
- `screenshots/` → Folder containing screenshots showing the program running

### How to Run

1. Open the Jupyter Notebook (`homeguard_system.ipynb`) in VS Code or Jupyter Lab
2. Run the cells in order to simulate the HomeGuard system
3. Check `simulation_output.txt` for a sample of the console output

### System Modes

- **HOME** → Comfort mode: alerts are minimal, only critical events trigger notifications
- **AWAY** → Security mode: motion and door alerts are critical
- **SLEEP** → Night mode: temperature and smoke alerts are active, motion alerts are lower priority
