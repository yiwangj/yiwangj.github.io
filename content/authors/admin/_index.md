---
# Display name
title: 王熠

# Full name (for SEO)
first_name: YI
last_name: WANG

# Status emoji
status:
  icon: ☕️

# Is this the primary user of the site?
superuser: true

# Role/position/tagline
role: Research Assistant in Robotics

# Organizations/Affiliations to display in Biography blox
organizations:
  - name: Carnegie Mellon University 
    url:  https://www.cmu.edu/
  - name: Johns Hopkins University 
    url:  url: https://www.jhu.edu/
    
# Social network links
# Need to use another icon? Simply download the SVG icon to your `assets/media/icons/` folder.
profiles:
  - icon: at-symbol
    url: 'ywang779@jhu.edu'
    label: E-mail Me


education:
  - area: Master of Science in Engineering, Robotics 
    institution: Johns Hopkins University
    date_start: 2022-08
    date_end: 2024-05
    summary: |
      GPA: 3.85/4.0
    
      Core Courses:
      - Algorithms for Sensor-Based Robotics
      - Computer Integrated Surgery
      - Robot Motion Planning
      - Robot Dynamics Kinematics and Control
      - Haptic Interface Design for Human-Robot Interaction
      - Medical Robotics System Design
      - Computer Vision. 

  - area:Bachelor of Science in Mechatronics i
    institution:  University of Melbourne
    date_start: 2019-02
    date_end: 20201-12
    summary: |
      GPA: 3.97/4.0

work:
  - position: Research Assistant
    company_name:  AMIRo Laboratory, LCSR, Johns Hopkins University 
    company_url: ''
    company_logo: ''
    date_start: 2024-03
    date_end: ''
    summary: |2-
      Responsibilities include:
      - Project : Chicken embryo model for retinal vein - like development
      - Utilized the Eyerobot platform to manually puncture veins and validated success through bubble formation
      - Automated the needle navigation and insertion with deep neural networks (ResNet and Yolov5) on micro 
      and B-mode images, respectively
      - Trained and refined the models using customized dataset collected from manual experiments. The model 
      achieved 86% of success rate and reduce the overall time by 21%
      - In preparation of manuscript for ICRA 2025 (submission deadline September 15)

        
  - position: Research Assistant
    company_name: Surgical Mechatronics Laboratory, Carnegie Mellon University Robotics Institute 
    company_url: ''
    company_logo: ''
    date_start: 2024-06
    date_end: ''
    summary: |
      Responsibilities include:
      -Project 1: C++ Software development for real-time motor control and communication
      - Implemented a two-way communication module for exchanging control commands between Jetson Nano 
      and middleware platform using UDP.
      - Designed and developed a shared memory mechanism to facilitate reliable inter-process access for the 
      control commands such that the motor can be controlled by commands directly acquired from the shared 
      memory. Additionally, this feature allows real-time monitoring and control across all hardware.
      - Implemented logging module between different components of the system.
      - Project 2: HeartLander
      - Recurrent whole pipeline

        
- position: Research Assistant
    company_name: MUSiiC Laboratory , LCSR, Johns Hopkins University
    company_url: ''
    company_logo: ''
    date_start: 2023-05
    date_end: 2024-02
    summary: |
      Responsibilities include:
      - Project 1: Dual-robotic arm prostate ultrasound (US) tomography
      - Designed a calibration pipeline for the Abdominal Probe and TRUS Probe using Bxp and calculating 
      Transformation between Probe Bases using point cloud
      - Generated the probe trajectory in MATLAB using Inverse Kinematics and Virtual Fixture.
      - Result in an archived manuscript (tentatively).
      - Project 2: Motion tracking of moving phantom based on convolutional neural network
      - Defined the movement of the probe as in-plane motion and out-of-plane motion
      - Used K-Wave simulation to synthesize US images with specific speckle patterns for data augmentation
      - Automated the collection of the datasets and trained a CNN model to learn the Out-of-Plane motion from 
      speckle patterns in ultrasound images


- position: Research Assistant
    company_name: BIGSS Lab Laboratory for Computational Sensing and Robotics, LCSR
    company_url: ''
    company_logo: ''
    date_start: 2023-02
    date_end: 2023-06
    summary: |
      Responsibilities include:
      - Project: Virtual Reality (VR) Drilling Simulator for Laminectomy: Implementation and Evaluation
      - Conducted spine CT segmentation and Colored VR platform setup
      - Performed laminectomy user studies; analyzed the data collected with the surgeons


  - position: Research Assistant
    company_name: Yue- Gang-Ao Artificial Intelligence Association 
    company_url: ''
    company_logo: ''
    date_start: 2020-12
    date_end: 2021-03
    summary: |
      Responsibilities include:
      - Collected datasets and optimized the network structure in three ways and further improved the accuracy of 
the model, with the adjusted experimental accuracy rate exceeding 80%
      - Published 2 papers on IEEE conferences

        
# Skills
# Add your own SVG icons to `assets/media/icons/`
skills:
  - name: Technical Skills
    items:
      - name: Python
      - name: C++
      - name: PyTorch
      - name: Matlab
      - name: ROS
        
  - name: Hobbies
    color: '#eeac02'
    color_border: '#f0bf23'
    items:
      - name: Walking
      - name: Piano
      - name: Novel


languages:
  - name: English
    percent: 80
  - name: Chinese
    percent: 100

# Awards.
#   Add/remove as many awards below as you like.
#   Only `title`, `awarder`, and `date` are required.
#   Begin multi-line `summary` with YAML's `|` or `|2-` multi-line prefix and indent 2 spaces below.
awards:
  - title:  scholarship at university of Melbourne in 2021

