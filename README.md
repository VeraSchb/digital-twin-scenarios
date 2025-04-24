# Digital Twin Scenarios

This repository contains three digital twin scenarios: **Room Brightness**, **Air Quality**, and **Soil Moisture**. 
Each scenario simulates a virtual representation of a physical environment, split into physical, control, and environmental processes.
 
---
## Repository Structure

Three folders containing all processes of a scenario, including:
- .xml file of physical process
- .xml file(s) of control process(es)
- .xml files of environmental processes

All files are exported from cpee.org.

---

## Scenarios

- **Room Brightness**  
  Simulates lighting conditions inside a room throughout the day and adjusts actuators to manage the light intensity.

- **Air Quality**  
  Models indoor air quality dynamics using CO₂ levels, adjusting ventilation accordingly.

- **Soil Moisture**  
  Manages irrigation based on moisture thresholds calculated in the physical process, influenced in environmental processes.

---

## How to Use

Each scenario folder is self-contained. 
Open the folder of interest and load all files in cpee.org to execute a process. 

All processes interact through a digital twin container where they update a variable. For a process to provide output, it needs to be started in cpee.org.

