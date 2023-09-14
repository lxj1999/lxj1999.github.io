---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am currently a Master of Science(Robotics) student at the National University of Singapore. During my research assistant period at Xi'an Jiaotong University, I worked with Prof. Liuyang Zhang in the Department of Mechanical Engineering. From 2017 to 2021, I studied at Xi'an Jiaotong University and received a B.Eng. degree in Mechanical Engineering. I was awarded 'Excellent Undergraduate Graduation Project (Top 1%)' to finish my undergraduate study.

My research interest includes medical robots and medical imaging.

# 📖 Educations
- *2023.01 - 2024.01(expected)*, M.Sc., Robotics, National University of Singapore (NUS), Singapore
- *2017.08 - 2021.07*, B.Eng., Mechanical Engineering, Xi'an Jiaotong University (XJTU), China
- *2019.01 - 2019.05*, Visiting International Student Program, University of Wisconsin-Madison (UW-Madison), USA

# 🛠 Skills
- Engineering Software: Abaqus; Ansys APDL; COMSOL; SolidWorks; AutoCAD
- Computer Languages: MATLAB; Python

# 📝 Research Experiences
- *2023.04 - 2023.12*, Semantic Segmentation of Laparoscopic Surgery Videos Based on HGNN, NUS
  - Assisted surgeons in collecting, categorizing and annotating laparoscopic surgery video datasets.
  - Trained video semantic segmentation model baselines using open-source library "MMSegmentation".
- *2021.11 - 2022.08*, Terahertz Detectors Based on Carbon Nanomaterials, XJTU
  - Prepared carbon nanotube (CNT) films by wet methods, specifically, dispersed CNT powder into organic solvents using an ultrasonic crusher, and preparing dry 5-micron-thick CNT films using vacuum filtration equipment.
  - Executed vapor deposition of metal electrodes onto CNT films covered with metal mask using a magnetron sputtering machine or an electron beam evaporation system.
  - Engaged in the thermoelectric response and terahertz attenuation measurement of CNT-based devices using the Terahertz Time-Domain Spectroscopy (THz TDS) and Terahertz Quantum Cascade Lasers (THz QCL) system.
- *2021.08 - 2022.03*, Test Verification of Key Equipment Failure Type Identification and Failure Prediction, XJTU
  - Produced four faulty bearings with different lengths of wear on the inner race, measured the data on a bearing test rig using piezoelectric vibration sensors, and collated them into a corresponding dataset.
  - Produced four solenoid valves with different levels of wear on the outer surface of the spool, and measured the data on a hydraulic test rig using a piezoelectric vibration sensor, and collated into a corresponding dataset.
  - Utilized PyTorch-based ResNet to perform fault diagnosis and prediction on bearings and solenoid valves.

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Excellent Undergraduate Graduation Project</div><img src='images/500x300.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

- *2020.02 - 2021.07*, Geometrical and Vibrational Properties of a Clamped-clamped Beam under Large Deformation, XJTU
  - Simulated the buckling characteristics and vibration modal response of a clamped-clamped beam fixed on a flexible substrate with different levels of pre-strain using ABAQUS and ANSYS APDL.
  - Acquired the formula for the buckling form of the clamped-clamped beam at different two-end compression displacements utilizing the perturbation method.
  - Used polyimide (PI) to cut and simulate the rectangular test strips with matching parameters, carried out buckling experiments by securing both ends on a self-designed tensile-compression test rig, and observed the buckling behaviour under different experiment parameters.
  - Used a shaking table and a piezoelectric chip to detect vibration intensities at various points on the buckling beam.

</div>
</div>


# 📑 Course Projects
- *2023.08 - 2023.12*, Ongoing, Virtual Ping-pong Player Trained by Reinforcement Learning, NUS
- *2023.08 - 2023.12*, Ongoing, Grasp of Blanket, NUS
- *2023.02 - 2023.05*, CV Segmentation and AI Classification of Picture of Chip Index, NUS
  - Utilized Matlab to segment letters and numbers in the picture with self-written functions (worked as regionprops, bwlabel and so on).
  - Utilized Matlab to recognize and classify letters and numbers in the picture with simple CNN.
- *2023.03 - 2023.04*, Comparison of Solvers in Solving SDP (Semi-definite Program) Problems, NUS
  - Utilized SDPT3 solver and SeDuMi solver on CVX interface in Matlab to solve the pure primal form of SDP.
- *2020.02 - 2020.12*, Swarm Intelligence Algorithms in Solving Flexible Job Shop Scheduling Problem (FJSP), XJTU
  - Designed a data generation method for eight workpieces, six machine tools, and six processes for the FJSP problem.
  - Utilized genetic algorithm (GA), ant colony optimization algorithm (ACO) and particle swarm optimization algorithm (PSO) to solve the FJSP problem.
  - Plotted Gantt charts for the FJSP problem.
- *2020.02 - 2020.07*, Roll to Roll (R2R) Machine Measurement System Design, XJTU
  - Utilized SolidWorks to disassemble the given R2R machine model and identified optimal locations for pressure sensors.
  - Conducted a literature review in the field of R2R pressure measurement and elucidated the rationale behind selecting the specific sensor.
- *2020.02 - 2020.07*, “More hot water” Intelligent Water Dispenser Design, XJTU
  - Utilized SolidWorks to model the outer frame of the water dispenser and assembled the whole model.
  - Assembled the Intelligent Water Dispenser with custom materials.
- *2020.02 - 2020.07*, Deep Learning and Signal Processing in Machine Fault Diagnosis, XJTU
  - Utilized Matlab for frequency-domain and time-domain analysis, wavelet analysis, FFT, EMD envelope demodulation, and spectral kurtosis calculation on CWRU bearing dataset.
  - Utilized CNN and RNN on bearing fault diagnosis of CWRU bearing dataset.
- *2019.09 - 2019.12*, Literature Review on Planetary Gearbox Fault Diagnosis, XJTU
  - Conducted a literature review in the field of planetary gearbox fault diagnosis.
- *2019.09 - 2019.12*, Automatic Walkway Ladder Design, XJTU
  - Utilized MATLAB to calculate and do strength checks of all parameters of the speed reducer in the walkway ladder based on real parameters.
  - Utilized SolidWorks to model the worm gear speed reducer and convert the 3D model into standardized 2D drawings using AutoCAD.
- *2019.01 - 2019.05*, Truck Reducer Design, UW-Madison
  - Utilized EES to calculate and do strength checks of all parameters of the reducer in a truck based on given torque and power.
  - Utilized SolidWorks to model the three-stage cylindrical gear reducer.
- *2019.02 - 2019.03*, Injection Molding Design and Simulation, UW-Madison
  - Utilized Moldex3D to design and simulate polymer flow in designated component mould.
 
# 💻 Internships
- *2022.11 - 2023.11*, CD Capital, Department of Medical Device Investment, Investment Analyst Intern
  - Involved in investment analysis on medical devices, mainly ophthalmology surgical robots, endourology surgical robots, and minimally invasive neuromodulation.
- *2021.07 - 2022.08*, Xi'an Jiaotong University, Department of Mechanical Engineering, Research Assistant
  - Involved in 'Terahertz Detectors Based on Carbon Nanomaterials' project.
  - Involved in 'Test Verification of Key Equipment Failure Type Identification and Failure Prediction' project.
- *2019.06 - 2019.07*, GE Healthcare (Wuxi), Department of Anesthesia Machine, Summer Intern
  - Involved in the CAD drawing, acid resistance test, fatigue test, and tightness test for the anaesthetic machine.

# 🎖 Honors and Awards
- *2021.11* Second Prize in the Excellent General Course Paper and Teaching Outcome, Xi’an Jiaotong University
- *2021.07* Excellent Undergraduate Graduation Project (Top 1%), Xi'an Jiaotong University
- *2020.05* School-level Second Scholarship, Xi’an Jiaotong University
- *2019.05* Second Scholarship, SMC Educational Foundation
