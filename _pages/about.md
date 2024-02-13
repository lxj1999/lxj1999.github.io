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

I have graduated from the National University of Singapore and received a M.Sc. degree in Robotics. From 2017 to 2021, I studied at Xi'an Jiaotong University and received a B.Eng. degree in Mechanical Engineering. I was awarded the 'Excellent Undergraduate Graduation Project (Top 1%)' to finish my undergraduate study.

My research interest includes medical device (surgical robots) and medical imaging.

# 📖 Educations
- *2023.01 - 2024.01*, M.Sc., Robotics, National University of Singapore (NUS), Singapore
- *2017.08 - 2021.07*, B.Eng., Mechanical Engineering, Xi'an Jiaotong University (XJTU), China
- *2019.01 - 2019.05*, Visiting International Student Program (VISP), University of Wisconsin-Madison (UW-Madison), United States

# 📚 Standardized Scores
- GPA: NUS: 4.75/5.0; XJTU: 86.94/100 (WES: 3.72/4.0); UW-Madison: 3.7/4.0.
- IELTS: Overall: 8.0 (L:9.0, R:8.5, W:7.0, S:6.5), expired on 29/Oct/2025.
- GRE: Overal: 319+3.0 (V:149, Q:170), expired on 28/Aug/2025.

# 🛠 Skills
- FEA Software: Abaqus; Ansys APDL
- Engineering Drawing Software: SolidWorks; AutoCAD(2D)
- Computer Languages: MATLAB; Python

# 📝 Research Experiences
- *2023.04 - 2023.10*, Semantic Segmentation of Gastric Cancer Laparoscopic Surgery Videos, NUS
  - Constructed a self-collected gastric cancer laparoscopic surgery video dataset (4 videos, 500 key frames), which is specially annotated for recognizing safe zone (where laparoscopic surgical instruments can safely cut and go deep) and critical organs.
  - Collected, standardized, categorized, filtered and annotated laparoscopic surgery videos under surgeons’ supervision.
  - Trained laparoscopic surgery video semantic segmentation baseline models on repaired CholecSeg8k dataset using UNet, UNet++, DeepLabv3 and DeepLabV3+ models. 
- *2021.11 - 2022.08*, Preparation and Performance Test of Carbon-nanotube Terahertz Detectors, XJTU
  - Prepared carbon nanotube (CNT) films by wet methods, specifically, dispersed CNT powder into organic solvents using an ultrasonic crusher, and preparing 5-micron-thick CNT films using vacuum filtration. 
  - Executed vapor deposition of metal electrodes (Au and Al) onto CNT films covered with metal mask to produce thermoelectric terahertz detectors using magnetron sputtering machine and electron beam evaporation system respectively. 
  - Engaged in the terahertz response measurement of CNT-based detectors using Terahertz Time-Domain Spectroscopy (THz TDS) system and thermoelectric response measurement using Terahertz Quantum Cascade Lasers (THz QCL) system and a lock-in amplifier.
- *2021.08 - 2022.03*, Hydraulic Equipment Failure Type Identification and Failure Prediction, XJTU
  - Produced four faulty bearings with different lengths of wear on the inner race and four faulty solenoid valves with different levels of wear on the outer surface of the spool.
  - Measured the vibration data on a hydraulic test rig with faulty bearings and faulty solenoid valves respectively using piezoelectric vibration sensors, and collated into two corresponding datasets.
  - Utilized ResNet50 to perform fault diagnosis and life prediction on bearings and solenoid valves.

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Excellent Undergraduate Graduation Project</div><img src='images/500x300.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

- *2020.02 - 2021.07*, Geometrical and Vibrational Properties of a Clamped-clamped Beam under Large Deformation, XJTU
  - Simulated the buckling characteristics and vibration modal response of a clamped-clamped beam fixed on a flexible substrate with different levels of pre-strain using ABAQUS (3D) and ANSYS APDL (2D).
  - Acquired the formula for the buckling form of the clamped-clamped beam at different two-end compression displacements utilizing the perturbation method.
  - Used polyimide (PI) to produce and simulate the rectangular test strips with matching parameters in FEA, carried out buckling experiments by securing both ends on a self-designed tensile-compression test rig, and observed the buckling behaviour under different parameters. 
  - Used flexible piezoelectric sensors to detect vibration intensity changes at different points on the buckled beam under 0 to 500Hz vibration produced by a shaking table.

</div></div>


# 📑 Course Projects
- *2023.08 - 2023.12*, Robot Grasp of Randomly-placed Blanket on Object, NUS
  - Collected RGB images and corresponding depth information of randomly-placed color-labelled blankets via a RGBD camera into a dataset.
  - Trained semantic segmentation models for randomly-placed color-labelled blankets to recognize their corners and edges using UNet and DeepLabV3+. 
  - Controlled the Franka Emika robot arm to grasp the blanket at specified edge with a specified angle based on semantic segmentation results and point cloud reconstruction. 
- *2023.08 - 2023.12*, Reinforecement Learning on Self-written 'Fetch'-like Gym Enviroment, NUS
  - Utilized Kuka-iiwa robot arm in gym environment for 3 Fetch tasks, 'Reach', 'Push' and 'Slide', by Pybullet.
  - Trained RL model based on posiiton control and joint angle control.
- *2023.02 - 2023.05*, CV Segmentation and AI Classification of Picture of Chip Index, NUS
  - Utilized Matlab to segment letters and numbers in the picture with self-written functions (worked as regionprops, bwlabel and so on).
  - Utilized Matlab to recognize and classify letters and numbers in the picture with simple CNN.
- *2023.03 - 2023.04*, Comparison of Solvers in Solving SDP (Semi-definite Program) Problems, NUS
  - Utilized SDPT3 solver and SeDuMi solver on CVX interface in Matlab to solve the pure primal form of SDP.
- *2020.02 - 2020.12*, Swarm Intelligence Algorithms in Solving Flexible Job Shop Scheduling Problem (FJSP), XJTU
  - Designed an FJSP data generation method with eight workpieces, six machines, and six jobs. 
  - Utilized genetic algorithm, ant colony optimization algorithm and particle swarm optimization algorithm respectively to solve the FJSP problem with randomly-generated datasets. 
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
  - Investigated the demand for the walkway ladder in the elderly community and measured real parameters.
  - Utilized MATLAB to calculate and do strength checks of all parameters of the speed reducer in the walkway ladder based on real parameters.
  - Utilized SolidWorks to model the worm gear speed reducer and convert the 3D model into standardized 2D drawings using AutoCAD.
- *2019.01 - 2019.05*, Truck Reducer Design, UW-Madison
  - Utilized EES to calculate and do strength checks of all parameters of the reducer in a truck based on given torque and power.
  - Utilized SolidWorks to model the three-stage cylindrical gear reducer.
- *2019.02 - 2019.03*, Injection Molding Design and Simulation, UW-Madison
  - Utilized Moldex3D to design and simulate polymer flow in the designated component mould.
 
# 💻 Internships
- *2022.11 - 2023.11*, CD Capital, Department of Medical Device Investment, Investment Analyst Intern
  - Involved in investment analysis on medical devices, mainly ophthalmology surgical robots, endourology surgical robots, and minimally invasive neuromodulation devices.
- *2021.07 - 2022.08*, Xi'an Jiaotong University, School of Mechanical Engineering, Research Assistant
  - Involved in the 'Preparation and Performance Test of Carbon-nanotube Terahertz Detectors' project.
  - Involved in the 'Hydraulic Equipment Failure Type Identification and Failure Prediction' project.
- *2019.06 - 2019.07*, GE Healthcare (Wuxi), Department of Anesthesia Machine, Summer Intern
  - Involved in the CAD drawing, acid resistance test, fatigue test, and tightness test for the anesthetic machine.

# 🎖 Honors and Awards
- *2021.11* Second Prize in the Excellent General Course Paper and Teaching Outcome, Xi’an Jiaotong University, China
- *2021.07* Excellent Undergraduate Graduation Project (Top 1%), Xi'an Jiaotong University, China
- *2020.05* School-level Second Scholarship, Xi’an Jiaotong University, China
- *2019.05* Second Scholarship, Beijing SMC Educational Foundation, China
