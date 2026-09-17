<div align="center">

<img src="https://img.shields.io/badge/SI--LAB-KoreaTech-E57373?style=for-the-badge" alt="SI-LAB KoreaTech" />

# 👋 Hi, we're SI-LAB @ KoreaTech

**Multi-sensor SLAM & Autonomous Perception Research Lab**
Korea University of Technology and Education (KOREATECH)

<br/>

[![Website](https://img.shields.io/badge/Lab-Website-blue?style=flat-square)](#)
[![Location](https://img.shields.io/badge/Location-Cheonan%2C%20Korea-informational?style=flat-square)](#)
[![Members](https://img.shields.io/badge/Members-3-success?style=flat-square)](#)

</div>

---

## 🔬 About

We are a student research group working on **multi-sensor SLAM (Simultaneous Localization and Mapping)**.
Our goal is to build a mobile scanning platform that fuses **LiDAR** and **multiple camera modalities**
(depth, event) to reconstruct 3D maps of indoor/outdoor environments, built on top of established
open-source SLAM frameworks.

- 🎯 **Focus:** LiDAR–camera sensor fusion for real-time 3D mapping
- 🧪 **Approach:** Benchmarking and extending open-source SLAM pipelines across sensor combinations
- 🚗 **Platform:** Ground vehicle-based mobile mapping rig

---

## 🚀 Project — `SLAM_2026`

| | |
|---|---|
| **Goal** | Move through space and generate a 3D map using LiDAR + multi-camera fusion |
| **Dev Environment** | Ubuntu 22.04 · VS Code |
| **Team** | 3 members |

### Repository structure

We split sensor-specific development into dedicated repos, integrated under the `SLAM_2026` umbrella:

| Repository | Sensor / Role |
|---|---|
| [`slam2026_livox`](https://github.com/SI-LAB-KoreaTech/slam2026_livox) | LIVOX MID-360 — LiDAR |
| [`slam2026_realsense`](https://github.com/SI-LAB-KoreaTech/slam2026_realsense) | Intel RealSense D455 — Depth Camera |
| [`slam2026_davis`](https://github.com/SI-LAB-KoreaTech/slam2026_davis) | DAVIS346 MONO — Event Camera |
| [`slam2026_scout`](https://github.com/SI-LAB-KoreaTech/slam2026_scout) | AGILEX SCOUT MINI — UGV Platform |

---

## 🛠️ Hardware

<div align="center">

| LiDAR | Depth Camera | Event Camera | UGV |
|:---:|:---:|:---:|:---:|
| LIVOX MID-360 | Intel RealSense D455 | DAVIS346 MONO | AGILEX SCOUT MINI |

</div>

---

## 🧰 Tech Stack

<div align="center">

![ROS2](https://img.shields.io/badge/ROS2-22314E?style=for-the-badge&logo=ros&logoColor=white)
![Ubuntu](https://img.shields.io/badge/Ubuntu%2022.04-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

</div>

---

> Commit messages, code comments, and documentation are written in **English** to keep the repo accessible to all lab members.

---

<div align="center">

**SI-LAB · KoreaTech**

</div>
