<div align="center">

<img src="../assets/neobotics-full-logo-dark.png" alt="Neobotics Foundation Logo" width="420"/>

Empowering the next generation of robotics education

[![Website](https://img.shields.io/badge/Website-1B2036?style=for-the-badge&logo=google-chrome&logoColor=white)](https://neobotics.org)
[![Discord](https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/7Ew7WQ4haj)
[![YouTube](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/@NeoboticsFoundation)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0yMC40NDcgMjAuNDUyaC0zLjU1NHYtNS41NjljMC0xLjMyOC0uMDI3LTMuMDM3LTEuODUyLTMuMDM3LTEuODUzIDAtMi4xMzYgMS40NDUtMi4xMzYgMi45Mzl2NS42NjdIOS4zNTFWOWgzLjQxNHYxLjU2MWguMDQ2Yy40NzctLjkgMS42MzctMS44NSAzLjM3LTEuODUgMy42MDEgMCA0LjI2NyAyLjM3IDQuMjY3IDUuNDU1djYuMjg2ek01LjMzNyA3LjQzM2MtMS4xNDQgMC0yLjA2My0uOTI2LTIuMDYzLTIuMDY1IDAtMS4xMzguOTItMi4wNjMgMi4wNjMtMi4wNjMgMS4xNCAwIDIuMDY0LjkyNSAyLjA2NCAyLjA2MyAwIDEuMTM5LS45MjUgMi4wNjUtMi4wNjQgMi4wNjV6bTEuNzgyIDEzLjAxOUgzLjU1NVY5aDMuNTY0djExLjQ1MnpNMjIuMjI1IDBIMS43NzFDLjc5MiAwIDAgLjc3NCAwIDEuNzI5djIwLjU0MkMwIDIzLjIyNy43OTIgMjQgMS43NzEgMjRoMjAuNDUxQzIzLjIgMjQgMjQgMjMuMjI3IDI0IDIyLjI3MVYxLjcyOUMyNCAuNzc0IDIzLjIgMCAyMi4yMjIgMGguMDAzeiIvPjwvc3ZnPg==&logoColor=white)](https://www.linkedin.com/company/neobotics-foundation-inc/)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/neoboticsorg/)
[![GitHub](https://img.shields.io/github/stars/Neobotics-Foundation-Inc?style=for-the-badge&logo=github&labelColor=333333&color=FFD700)](https://github.com/Neobotics-Foundation-Inc)

<img src="../assets/red-line.svg" alt="" width="760"/>

[![NeoRacer](https://img.shields.io/badge/NeoRacer-1B2036?style=flat-square)](#️-neoracer-v1)
[![Ecosystem](https://img.shields.io/badge/Ecosystem-1B2036?style=flat-square)](#️-ecosystem)
[![How to Use](https://img.shields.io/badge/How%20to%20Use-1B2036?style=flat-square)](#-how-to-use-this-github)
[![Community](https://img.shields.io/badge/Community-1B2036?style=flat-square)](#-community-guidelines)
[![Support](https://img.shields.io/badge/Support-1B2036?style=flat-square)](#️-support-neobotics)
[![Licensing](https://img.shields.io/badge/Licensing-1B2036?style=flat-square)](#-licensing)

</div>

<br>

# Welcome to Neobotics

Welcome! Our GitHub organization is the home to all projects and repositories associated with **Neobotics Foundation Inc.**, along with the broader community discussions and support.

Our goal is to build a **practical, well-documented, and accessible racecar** that is easy to use, easy to contribute to, and an educational tool for students and researchers alike.

Whether you’re here to **use our software**, **learn from it**, or **contribute**, you’re in the right place!

## 🏎️ NeoRacer V1

The **NeoRacer** is designed to be both a benchmark platform for autonomous vehicle research and a flagship system for self-driving education. 

It faithfully replicates real-world road scenarios at scale, enabling students and researchers to understand, test, and validate the full autonomous driving stack, from perception and planning to control and deployment. 

<div align="center">
<img src="../assets/neoracer-line-1.png" alt="NeoRacer" width="600"/>
</div>


<div align="center">

### Specifications

| Category | Specification | Value |
|----------|---------------|-------|
| **Chassis** | Dimensions | 380 x 300 x 220mm |
| | Wheelbase | 280mm |
| | Drive System | Single Motor 4WD shaft drivetrain |
| | Frame | Independent suspension, Ackermann steering |
| | Max Speed | 25 km/hr |
| **Power** | Battery | 11.1V LiPo, 5200mAh |
| | Motor | Custom brushed motor, 11000 RPM |
| | Servo | 20kg waterproof High-Torque |
| **Compute** | Processor | NVIDIA Jetson Orin Nano |
| | OS | JetPack 6.2 pre-installed |
| | Framework | ROS (Robot Operating System) ready |
| **Sensors** | LiDAR | Industrial-grade 30 Hz 2D |
| | Camera | High-resolution for image capture |
| | IMU | 9-axis (accelerometer, magnetometer, gyroscope) |
| | Encoder | Incremental A/B/Z 3-channel |

</div>

By bridging education and experimentation, NeoRacer serves as a practical testbed for investigating and addressing many of the open challenges that continue to define autonomous vehicle research today.

---

## 🗂️ Ecosystem

Explore the repositories that power the NeoRacer platform:

| Repository | Language | License | Issues | Contributors | Activity |
|------------|:--------:|:-------:|:------:|:------------:|:--------:|
| [**neoracer_ros2_driver**](https://github.com/Neobotics-Foundation-Inc/neoracer_ros2_driver)<br>Backend ROS2 driver for neoracer v1 with... | ![Language](https://img.shields.io/github/languages/top/Neobotics-Foundation-Inc/neoracer_ros2_driver?style=flat-square&labelColor=1B2036) | ![License](https://img.shields.io/github/license/Neobotics-Foundation-Inc/neoracer_ros2_driver?style=flat-square&label=) | ![Issues](https://img.shields.io/github/issues/Neobotics-Foundation-Inc/neoracer_ros2_driver?style=flat-square&label=) | ![Contributors](https://img.shields.io/github/contributors/Neobotics-Foundation-Inc/neoracer_ros2_driver?style=flat-square&label=) | ![Last Commit](https://img.shields.io/github/last-commit/Neobotics-Foundation-Inc/neoracer_ros2_driver?style=flat-square&labelColor=1B2036) |
| [**NeoRacer-V2**](https://github.com/Neobotics-Foundation-Inc/NeoRacer-V2)<br>3D-printable open-source chassis for aut... | ![Language](https://img.shields.io/github/languages/top/Neobotics-Foundation-Inc/NeoRacer-V2?style=flat-square&labelColor=1B2036) | ![License](https://img.shields.io/github/license/Neobotics-Foundation-Inc/NeoRacer-V2?style=flat-square&label=) | ![Issues](https://img.shields.io/github/issues/Neobotics-Foundation-Inc/NeoRacer-V2?style=flat-square&label=) | ![Contributors](https://img.shields.io/github/contributors/Neobotics-Foundation-Inc/NeoRacer-V2?style=flat-square&label=) | ![Last Commit](https://img.shields.io/github/last-commit/Neobotics-Foundation-Inc/NeoRacer-V2?style=flat-square&labelColor=1B2036) |
| [**support**](https://github.com/Neobotics-Foundation-Inc/support)<br>Documentation, discussions, extended res... | ![Language](https://img.shields.io/github/languages/top/Neobotics-Foundation-Inc/support?style=flat-square&labelColor=1B2036) | ![License](https://img.shields.io/github/license/Neobotics-Foundation-Inc/support?style=flat-square&label=) | ![Issues](https://img.shields.io/github/issues/Neobotics-Foundation-Inc/support?style=flat-square&label=) | ![Contributors](https://img.shields.io/github/contributors/Neobotics-Foundation-Inc/support?style=flat-square&label=) | ![Last Commit](https://img.shields.io/github/last-commit/Neobotics-Foundation-Inc/support?style=flat-square&labelColor=1B2036) |

---

## 📖 How to Use This Github

### If you just want to use the projects
1. Browse the repositories in this organization
2. Read the `README.md` in each repo for setup and usage instructions
3. Clone or fork the repository as needed
4. Follow the [license terms](#licensing)


### If you want to ask questions or discuss ideas
Use **[GitHub Discussions](https://github.com/orgs/Neobotics-Foundation-Inc/discussions)** for:
- General questions
- Design discussions
- Feature ideas
- Community feedback

Use **GitHub Issues** for:
- Bug reports
- Clearly defined feature requests
- Reproducible technical problems

### If you want to contribute
We welcome contributions of all kinds: code, documentation, examples, tests, or suggestions.

1. Start by reading the `CONTRIBUTING.md` file in the repository if available
2. Familiarize yourself with the repository's issues
3. Fork the repository and create a feature branch
4. Make small, focused changes
5. Open a pull request with a clear explanation of what you changed and why

If you’re unsure where to start, feel free to open a discussion first.

---

## 🌍 Community Guidelines

We aim to keep this space:
- Respectful and welcoming
- Technically constructive
- Focused on learning and collaboration

Please be kind, assume good intent, and help us maintain a positive and productive community.

---

## ♥️ Support Neobotics

There are many ways to help the Neobotics community grow:

- **Star our repositories** — It helps others discover our work and shows your support. Every star makes a difference!
- **Spread the word** — Share our projects with fellow students, educators, and robotics enthusiasts.
- **Donate** — As a nonprofit organization, we rely on community support to continue building accessible robotics education tools. Your contribution helps us develop new platforms, create educational content, and keep our projects open-source.

<p align="center">
<a href="https://neobotics.org/donate"><img src="https://img.shields.io/badge/Donate-Support%20Us-ED1C24?style=for-the-badge&logo=githubsponsors&logoColor=ED1C24&labelColor=1B2036" alt="Donate"/></a>
</p>

---

## 📃 Licensing

All projects in this organization are open-source, but **licenses may vary by repository**.  
Always check the `LICENSE` file in each repository before using or redistributing the work.

In general:
- **Software repositories** are typically licensed under **GNU GENERAL PUBLIC LICENSE Version 3 ([GPLv3](https://www.gnu.org/licenses/gpl-3.0.en.html))**
- **Hardware and open-hardware repositories** are typically licensed under **CERN Open Hardware Licence Version 2 - Strongly Reciprocal ([CERN-OHL-S](https://cern-ohl.web.cern.ch))**

The exact license and its terms are defined in each repository and take precedence over this general guidance.

We’re excited to build this community together, welcome aboard :)
