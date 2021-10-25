---
layout: single 

classes: wide

title:  "Research Works" 

permalink: /researches/
---

Here is a list of research works I've participated in during my undergraduate graduate study and graduate study.

[TOC]

## 3D Through-wall Imaging With Unmanned Aerial Vehicles Using WIFI

- **Project Type**: Undergraduate research program of Mechanical Engineering in SJTU.

- **Goal**: Trying to verify and reproduce the result of [a research paper from IEEE](https://dl.acm.org/doi/10.1145/3055031.3055084).

- **Supervisor**: *[Prof. Weiwei Cai](https://scholar.google.com/citations?user=4mYjOrsAAAAJ&hl=en)*, Associate professor in Institute of Turbomachinery of SJTU.

- **Main Tools**: Raspberry Pi 3 Model B, Arduino, Python.

- **Responsibility**: 

  - Buying components and build two simplest UAV.
  - Create simple modes of motion and tune the parameters so that the distance for each move step is fixed.
  - Organize the flight path and control the  two UAV flying through the desired path at the same time while sampling the WIFI signal strength automatically.
  - Help using the signal strength data to rebuild 3D model.

- **Some photo records**:

  - Different models used to test the algorithms

  <p align ="middle">
      <img src="../assets/images/Model_1.jpg" alt="image" width="200" />
      <img src="../assets/images/Model_2.jpg" alt="image" width="225" />
  </p>

  

  - Pre-designed flight path for each UAV

    <center><img src="../assets/images/Test_path.PNG" alt="image" width="520" /><center>

- **Results**

  - Due to lack of sensors, no position feedback algorithms were used. The positions of UAV could only be automated controlled by open-loop systems. Manually controlling the UAVs was required to ensure the two UAVs arrive at the correctly corresponding positions.
  - Using the data collected by controlling the UAVs manually, two 2D images which are close to the projections are created successfully.
  - Due to time limitation of the research project, no digital 3D models were built.

