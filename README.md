# Aviation Probation Report – MARVEL Makerspace ✈️

## Overview
This repository documents the work I completed during my **probation period for the Aviation Student Coordinator role** at **MARVEL**, the makerspace of my college.  
Over the span of one month, I explored various aspects of **drone science, stabilization systems, and control architectures**, combining theoretical knowledge with hands-on experimentation.  
The complete details, results, and observations of each task are compiled in the attached **Aviation Task Report (PDF)**.

---

## Projects Undertaken

### 1. Propeller Design and Analysis
- Studied the fundamentals of propeller nomenclature, geometry, and aerodynamic parameters.  
- Designed a **2-blade propeller** aimed to generate a minimum of **8N of thrust**, applying pitch–diameter balancing principles.  
- Explored the efficiency effects of blade count and propeller configuration (CW/CCW).  
- Documented the complete design process and performance insights in the final report.

### 2. 3-Axis Camera Gimbal Development
- Designed and built a **3-axis gimbal** 
- Implemented a **feedback control loop** for active stabilization using real-time IMU sensor fusion.  
- Calibrated motion response to counter drone tilts and vibrations, maintaining camera orientation.  
- Recorded test results and design improvements for inclusion in the report.

### 3. Flight Controller Study and Embedded System Review
- Reviewed and documented key flight controllers including **Pixhawk** and **APM**, focusing on onboard microcontrollers, IMUs, barometers, and magnetometers.  
- Analyzed **STM32**-based architectures and their data processing pipelines.  
- Proposed a **custom lightweight flight computer** concept using ESP32/STM32 to handle automation and onboard sensor processing.  
- Emphasized modular integration for tasks such as stabilization, data fusion, and communication.

### 4. Optical Flow–Based Stabilization
- Implemented **optical flow algorithms** to estimate drone movement relative to the ground using grayscale image comparisons.  
- Used **frame differencing** and **motion vector estimation** to detect drift and simulate stabilization feedback.  
- Conducted experiments with both onboard and external vision systems to study accuracy and computational limits.  
- Documented methodology, results, and challenges in the final report.

### 5. General Drone and Flight Performance Analysis
- Studied drone dynamics including thrust-to-weight ratio, torque balancing, and center of gravity considerations.  
- Performed calculations for **propulsion efficiency**, **power draw**, and **flight endurance** under varying payloads.  
- Analyzed flight data to understand the relationship between propeller parameters, motor response, and stability.  
- Compiled detailed observations, conclusions, and recommendations in the report.

---

## Key Learnings
- Developed strong practical understanding of **drone mechanics, control systems, and flight physics**.  
- Gained hands-on experience in **stabilization algorithms**, **sensor integration**, and **feedback control design**.  
- Improved skills in **technical documentation**, **system analysis**, and **simulation-based validation**.  
- Learned to approach engineering problems with both creativity and structured methodology.

---

## Repository Contents
- `Aviation_Task_Report_Krithik.pdf` – Comprehensive report detailing all projects, methodologies, and results.  
- `images/` – Collection of photos showing the drone setup, gimbal prototype, and experimental tests (to be added).  
- `README.md` – Summary of tasks and learnings.

---

## Author
**Krithik Kumar**  
Department of Electronics and Communication Engineering (ECE-A)  
MARVEL Makerspace, UVCE  
2nd Semester  

---

## License
This project is shared for educational and documentation purposes.  
© 2025 Krithik Kumar. All rights reserved.
