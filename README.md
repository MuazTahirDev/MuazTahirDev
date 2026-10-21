<h1 align="center">Muhammad Muaz Tahir</h1>

<p align="center">
  <b>Robotics &amp; UAV Autonomy Engineer</b><br/>
  Multirotor autonomy · GPS-denied navigation · Drone swarms · Perception
</p>

<p align="center">
  <img src="https://img.shields.io/badge/ArduPilot-007BC0?style=flat-square&logo=data:image/svg+xml;base64,&logoColor=white" alt="ArduPilot"/>
  <img src="https://img.shields.io/badge/ROS%201%20%2F%202-22314E?style=flat-square&logo=ros&logoColor=white" alt="ROS"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/MATLAB-E16737?style=flat-square&logo=mathworks&logoColor=white" alt="MATLAB"/>
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white" alt="OpenCV"/>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch"/>
  <img src="https://img.shields.io/badge/NVIDIA%20Jetson-76B900?style=flat-square&logo=nvidia&logoColor=white" alt="Jetson"/>
</p>

---

I build autonomous multirotors — from the airframe and flight-controller tuning
up through companion-computer perception and multi-vehicle coordination.
Most of my work lives where the control stack meets real hardware: sensor
calibration, EKF behaviour, flight testing and the unglamorous business of
finding out why an aircraft did something unexpected.

**Currently working on** GPS-denied navigation — optical flow and visual
odometry as a fallback when GNSS degrades or disappears.

---

## Featured Work

| Project | What it is |
|---|---|
| 🔥 **[FireHawk Mk1](https://github.com/MuazTahir750/firehawk-wildfire-drone)** | Autonomous wildfire-spotting quadcopter, built from scratch in Webots — custom PID stabilisation, lawnmower search, colour-based fire detection, ground-plane GPS projection |
| 📡 **[Drone RF Detection](https://github.com/MuazTahir750/drone-rf-detection)** | Passive radar using a WiFi hotspot as illuminator of opportunity — detects a drone that isn't transmitting, via propeller micro-Doppler |
| 🎯 **[UAV Precision Landing](https://github.com/MuazTahir750/uav-precision-landing)** | ArUco-guided descent to centimetre repeatability, including the committed final phase once the marker leaves the camera's view |
| 🛡️ **[UAV Obstacle Avoidance](https://github.com/MuazTahir750/uav-obstacle-avoidance)** | Reactive LiDAR + ToF avoidance layered underneath GPS waypoint navigation |
| 🗺️ **[Indoor GPS-Denied Navigation](https://github.com/MuazTahir750/indoor-nav-rtabmap)** | RTAB-Map visual SLAM feeding ArduPilot's EKF as an external nav source |
| 👥 **[Human-Aware Navigation](https://github.com/MuazTahir750/cohan-tiago-human-aware-nav)** | CoHAN social navigation on a PAL Tiago — planning around people, not just around obstacles |
| 👁️ **[OAK-D Perception](https://github.com/MuazTahir750/oakd-ros-perception)** | OAK-D depth + on-camera inference paired with VINS-Fusion visual-inertial odometry |

Also: a **25-drone swarm system** flown simultaneously in field tests, with a
**LoRa ground control station** operating the whole fleet over a ~300 B/s link.

---

## Technical Focus

**Flight stack**
ArduPilot firmware and parameter configuration · EKF source selection and
failsafe behaviour · sensor and ESC calibration · compass/magnetic interference
diagnosis · dataflash log analysis · bench and flight testing

**Autonomy**
GPS-denied navigation · optical flow and visual-inertial odometry · visual SLAM
(RTAB-Map, VINS-Fusion) · obstacle avoidance · precision landing · multi-vehicle
coordination

**Perception**
OpenCV · PyTorch / TensorFlow · semantic segmentation · multi-object tracking ·
on-device inference (Jetson, OAK-D VPU)

**Platforms & protocols**
Quadcopters 3–17 inch, hexacopters, heavy-lift, FPV · Raspberry Pi 4/5 ·
NVIDIA Jetson Nano / Orin Nano · MAVLink, pymavlink, MAVROS, DDS · LoRa

**Languages & tools**
Python · MATLAB / Simulink · ROS 1 & ROS 2 · Gazebo · Webots · LaTeX

---

## Background

**MSc — Electrical Engineering, AI &amp; Autonomous Systems**
*Mobile Robotics · Advanced Robotics · Computer Vision · Machine Learning*

**BSc — Electrical Engineering**

**Achievements** — 2nd place, Swarm Competition (AI Hackathon, Islamabad) ·
TEKNOFEST 2026, Rocket Category

---

<p align="center">
  <a href="https://www.linkedin.com/in/muaz-tahir-55718519a">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="mailto:muaztahir750@gmail.com">
    <img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email"/>
  </a>
</p>
