<h1 align="center">David Iosifescu</h1>

<p align="center">
  <strong>MSc Systems, Control & Robotics · Embedded Robotics · Autonomous Systems</strong><br/>
  KTH Royal Institute of Technology, Stockholm
</p>

<p align="center">
  Robotics engineer and MSc student at KTH, currently working as an
  <strong>Assistant Research Engineer at the Robotics, Perception and Learning Lab (RPL)</strong>.
  <br/><br/>
  My work spans embedded robotic systems, underwater communication and ranging,
  distributed autonomy, state estimation, robot perception, and learning-based
  manipulation, with a particular interest in systems that must operate reliably
  under real-world sensing, timing, computation, and communication constraints.
</p>

---

<h3>Research Interests</h3>

<p>
  <img src="https://img.shields.io/badge/Embedded_Robotics-2C3E50?style=flat"/>
  <img src="https://img.shields.io/badge/Autonomous_Robotic_Systems-34495E?style=flat"/>
  <img src="https://img.shields.io/badge/Distributed_Autonomy-5D6D7E?style=flat"/>
  <img src="https://img.shields.io/badge/State_Estimation_%26_Sensor_Fusion-1F618D?style=flat"/>
  <img src="https://img.shields.io/badge/Robot_Perception-1ABC9C?style=flat"/>
  <img src="https://img.shields.io/badge/Robot_Learning-8E44AD?style=flat"/>
  <img src="https://img.shields.io/badge/Communication_%26_Ranging-239B56?style=flat"/>
  <img src="https://img.shields.io/badge/Real--Time_Systems-2874A6?style=flat"/>
</p>

---

<h3>Background</h3>

<ul>
  <li>
    MSc in <strong>Systems, Control and Robotics</strong>,
    KTH Royal Institute of Technology, 2025–2027
  </li>
  <li>
    BSc in <strong>Electronics, Electrical Energy and Automation</strong>,
    Sorbonne University
  </li>
  <li>
    Graduated <strong>Valedictorian</strong> with a GPA of 17.32 / 20
  </li>
</ul>

---

<h3>Current Research</h3>

<ul>
  <li>
    <strong>Assistant Research Engineer — KTH RPL / SMaRC</strong><br/>
    Developing embedded communication, synchronization, and acoustic ranging
    systems for autonomous underwater robotic platforms.
  </li>

  <li>
    <strong>One-Way Travel Time Acoustic Ranging</strong><br/>
    Developing and experimentally validating GNSS/PPS-synchronized
    <strong>OWTT acoustic ranging</strong> for SMaRC underwater robots,
    building on synchronization and ranging work investigated in connection
    with <strong>OCEANS 2026</strong>.
    The system combines GNSS-disciplined timing, embedded timestamping,
    acoustic modems, and distributed ROS 2 / micro-ROS nodes.
  </li>

  <li>
    <strong>Clock Synchronization & Holdover</strong><br/>
    Characterizing clock drift and timing uncertainty for underwater ranging,
    including PPS calibration, holdover behavior, TCXO / OCXO evaluation,
    oscillator aging, and compensation of clock-frequency error when GNSS
    synchronization becomes unavailable underwater.
  </li>

  <li>
    <strong>Embedded Multi-Robot Infrastructure</strong><br/>
    Integrating Raspberry Pi 5, Teensy 4.1, GNSS receivers, acoustic modems,
    serial interfaces, custom PCBs, and micro-ROS into deployment-ready
    distributed robotic systems.
  </li>
</ul>

---

<h3>Selected Robotics & Research Projects</h3>

<ul>
  <li>
    <strong>OWTT Acoustic Ranging for Autonomous Underwater Vehicles</strong><br/>
    Implemented an embedded timing and communication pipeline for one-way
    acoustic ranging between SMaRC robotic platforms. Work includes GNSS/PPS
    synchronization, modem timestamping, clock-drift estimation, serial
    communication, micro-ROS integration, and field validation against
    RTK-GNSS.
    <br/><br/>
    Kilometer-scale experiments achieved approximately <strong>84% OWTT
    availability</strong> compared with <strong>56% for conventional
    two-way ranging</strong>, with roughly <strong>1.1 m RMSE</strong>
    against RTK-GNSS in the evaluated trials.
  </li>

  <li>
    <strong>Policy Mobilization for the Rainbow Robotics RB-Y1</strong><br/>
    Developing a mobile-manipulation pipeline for reusing fixed-base
    manipulation policies from different robot base poses.
    The project combines <strong>RoboCasa, robosuite, MuJoCo, Diffusion Policy,
    Whole-Body Inverse Kinematics, and Mobi-π</strong>, with ongoing work toward
    RGB-D and learning-based humanoid manipulation.
  </li>

  <li>
    <strong>Cartesian Diffusion Policy for RB-Y1 Manipulation</strong><br/>
    Building a fixed-base manipulation baseline in which a visual Diffusion
    Policy predicts base-relative Cartesian end-effector trajectories that are
    executed through the RB-Y1 Whole-Body IK controller, separating learned
    manipulation from the robot's internal whole-body action representation.
  </li>

  <li>
    <strong>RGB-D Perception & Mapless Robotics</strong><br/>
    Worked with RGB-D observations, point clouds, learned visual
    representations, odometry, IMU data, and robotic perception pipelines for
    navigation and environment understanding.
  </li>

  <li>
    <strong>Room-Transition Detection & Topological Scene Understanding</strong><br/>
    Exploring temporal visual models for detecting transitions between rooms
    from robot camera streams, with applications to mapless navigation,
    topological scene graphs, and visual loop closure.
  </li>

  <li>
    <strong>Underwater Communication Systems</strong><br/>
    Developed ROS 2 / micro-ROS components for acoustic modem communication,
    timestamping, retries, modem identification, message transport, and
    ranging between autonomous underwater platforms.
  </li>
</ul>

---

<h3>Earlier Engineering Work</h3>

<ul>
  <li>
    <strong>ARM-Based Autonomous Mobile Robot</strong><br/>
    Worked on embedded control, sensing, and actuator integration for a mobile
    robot using low-level microcontroller programming, timers, PWM, UART,
    and real-time control logic.
  </li>

  <li>
    <strong>Reliable UDP Communication</strong><br/>
    Implemented a sender–receiver communication system using
    <strong>Selective Repeat</strong> to provide reliable packet delivery over
    UDP.
  </li>

  <li>
    <strong>Portable PCR Thermocycler</strong><br/>
    Developed a low-cost portable PCR prototype combining temperature sensing,
    closed-loop thermal control, embedded electronics, and microcontroller
    programming for biomedical applications.
  </li>

  <li>
    <strong>Biomedical Software & Data Visualization</strong><br/>
    Developed analysis and visualization tools using <strong>R Shiny</strong>
    for biomedical and experimental datasets.
  </li>

  <li>
    <strong>Embedded Electronics</strong><br/>
    Worked on sensor acquisition, analog and digital electronics,
    communication interfaces, real-time microcontroller programming, and
    custom hardware prototypes.
  </li>
</ul>

---

<h3>Programming & Software</h3>

<p>
  <img src="https://img.shields.io/badge/C-00599C?style=flat&logo=c&logoColor=white"/>
  <img src="https://img.shields.io/badge/C++-00599C?style=flat&logo=c%2B%2B&logoColor=white"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/MATLAB-0076A8?style=flat&logo=mathworks&logoColor=white"/>
  <img src="https://img.shields.io/badge/R-276DC3?style=flat&logo=r&logoColor=white"/>
</p>

---

<h3>Robotics & Embedded Systems</h3>

<p>
  <img src="https://img.shields.io/badge/ROS_2-22314E?style=flat&logo=ros&logoColor=white"/>
  <img src="https://img.shields.io/badge/micro--ROS-1B4F72?style=flat"/>
  <img src="https://img.shields.io/badge/MuJoCo-566573?style=flat"/>
  <img src="https://img.shields.io/badge/RoboCasa-34495E?style=flat"/>
  <img src="https://img.shields.io/badge/robosuite-2E4053?style=flat"/>
  <img src="https://img.shields.io/badge/Teensy_4.1-566573?style=flat"/>
  <img src="https://img.shields.io/badge/Raspberry_Pi_5-C51A4A?style=flat&logo=raspberrypi&logoColor=white"/>
  <img src="https://img.shields.io/badge/STM32-03234B?style=flat&logo=stmicroelectronics&logoColor=white"/>
  <img src="https://img.shields.io/badge/FreeRTOS-00979D?style=flat"/>
  <img src="https://img.shields.io/badge/Bare--Metal-000000?style=flat"/>
</p>

---

<h3>Control, Estimation & Robot Learning</h3>

<p>
  <img src="https://img.shields.io/badge/Control_Theory-8E44AD?style=flat"/>
  <img src="https://img.shields.io/badge/State_Estimation-7D3C98?style=flat"/>
  <img src="https://img.shields.io/badge/Sensor_Fusion-5B2C6F?style=flat"/>
  <img src="https://img.shields.io/badge/Computer_Vision-884EA0?style=flat"/>
  <img src="https://img.shields.io/badge/Machine_Learning-CA6F1E?style=flat"/>
  <img src="https://img.shields.io/badge/Diffusion_Policy-A04000?style=flat"/>
  <img src="https://img.shields.io/badge/Inverse_Kinematics-1F618D?style=flat"/>
</p>

---

<h3>Communication, Timing & Estimation</h3>

<p>
  <img src="https://img.shields.io/badge/Acoustic_Ranging-117864?style=flat"/>
  <img src="https://img.shields.io/badge/GNSS_%2F_PPS-148F77?style=flat"/>
  <img src="https://img.shields.io/badge/Clock_Synchronization-0E6655?style=flat"/>
  <img src="https://img.shields.io/badge/Serial_Communication-1A5276?style=flat"/>
  <img src="https://img.shields.io/badge/UDP-21618C?style=flat"/>
</p>

---

<h3>Tools & Environment</h3>

<p>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white"/>
  <img src="https://img.shields.io/badge/Slurm-34495E?style=flat"/>
  <img src="https://img.shields.io/badge/VS_Code-007ACC?style=flat&logo=visual-studio-code&logoColor=white"/>
  <img src="https://img.shields.io/badge/EAGLE-34495E?style=flat"/>
  <img src="https://img.shields.io/badge/OrCAD-2E4053?style=flat"/>
</p>

---

<p align="center">
  <em>
    Interested in research and engineering at the intersection of embedded
    systems, communication, estimation, perception, and learning-based
    autonomous robotic behavior.
  </em>
</p>
