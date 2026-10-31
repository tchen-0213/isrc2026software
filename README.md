
***

```markdown
# 🤖 ISRC 2026: Humanoid Robotics Project | 2026 国际学生机器人社：人形机器人项目

**Beihang University (BUAA) | 北京航空航天大学**

[![Python](https://img.shields.io/badge/Python-3.10+-blue?logo=python)](https://www.python.org/)
[![ROS2](https://img.shields.io/badge/ROS2-Jazzy/Iron-22314E?logo=ros)](https://docs.ros.org/)
[![Raspberry Pi](https://img.shields.io/badge/Hardware-Raspberry_Pi_5-C51A4A?logo=raspberrypi)](https://www.raspberrypi.com/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

---

## 🇬🇧 English

### 🌟 Introduction
Welcome to the official repository for the **International Students Robotic Club (ISRC) 2026** at Beihang University. This project is dedicated to the research, design, and development of a fully autonomous **Humanoid Robot** powered by the **Raspberry Pi** ecosystem. Our ultimate goal is to compete and excel in the upcoming [Insert Competition Name, e.g., RoboCup 2026 / National University Robotics Competition].

### 🎯 Project Goals
- **Bipedal Locomotion:** Develop stable walking gaits and balance control using IMU and kinematic algorithms.
- **Computer Vision & AI:** Implement real-time object detection, tracking, and spatial mapping using Raspberry Pi AI capabilities.
- **Manipulation:** Design and control robotic arms/hands for precise object grasping and interaction.
- **System Integration:** Seamlessly integrate hardware and software using ROS2 (Robot Operating System 2) on Raspberry Pi.

### 🛠️ Tech Stack
- **Core Compute:** Raspberry Pi 5 / Compute Module 5 (Running Ubuntu 22.04/24.04)
- **Middleware:** ROS2 (Humble/Jazzy)
- **Languages:** Python, C++
- **Vision & AI:** OpenCV, PyTorch, MediaPipe, YOLOv8
- **Hardware Control:** PCA9685 / Custom Servo Drivers, I2C/SPI communication

### 📂 Repository Structure
```text
├── src/                # ROS2 packages (Navigation, Vision, Control)
├── hardware/           # CAD models, schematics, and 3D printing files
├── docs/               # Project documentation and setup guides
├── scripts/            # Utility and calibration scripts
└── README.md           # You are here!
```

### 🚀 Getting Started
1. **Clone the repository:**
   ```bash
   git clone https://github.com/BUAA-ISRC/isrc2026-humanoid.git
   cd isrc2026-humanoid
   ```
2. **Install dependencies:** (Ensure ROS2 and Python environments are set up)
   ```bash
   sudo apt update && sudo apt install -y ros-${ROS_DISTRO}-desktop
   pip3 install -r requirements.txt
   ```
3. **Build the workspace:**
   ```bash
   colcon build
   source install/setup.bash
   ```

---

## 🇨🇳 中文

### 🌟 简介
欢迎来到**北京航空航天大学 2026 国际学生机器人社 (ISRC)** 的官方代码仓库。本项目致力于基于 **树莓派 (Raspberry Pi)** 生态系统，研究、设计和开发一款全自主的 **人形机器人**。我们的最终目标是在即将到来的 [请填入比赛名称，例如：2026 RoboCup / 全国大学生机器人竞赛] 中参赛并取得优异成绩。

### 🎯 项目目标
- **双足运动控制：** 利用 IMU 和运动学算法，开发稳定的步态与平衡控制。
- **计算机视觉与 AI：** 利用树莓派的 AI 算力，实现实时的目标检测、跟踪与空间建图。
- **机械臂与抓取：** 设计并控制机械臂/灵巧手，实现精准的物体抓取与交互。
- **系统集成：** 在树莓派上使用 ROS2（机器人操作系统 2）实现软硬件的无缝集成。

### 🛠️ 技术栈
- **核心计算平台：** 树莓派 5 / Compute Module 5 (运行 Ubuntu 22.04/24.04)
- **中间件：** ROS2 (Humble/Jazzy)
- **编程语言：** Python, C++
- **视觉与 AI：** OpenCV, PyTorch, MediaPipe, YOLOv8
- **硬件控制：** PCA9685 / 自定义舵机驱动, I2C/SPI 通信

### 📂 仓库结构
```text
├── src/                # ROS2 功能包 (导航、视觉、控制)
├── hardware/           # CAD 模型、电路原理图及 3D 打印文件
├── docs/               # 项目文档与环境配置指南
├── scripts/            # 工具与标定脚本
└── README.md           # 您正在阅读的文件！
```

### 🚀 快速开始
1. **克隆仓库：**
   ```bash
   git clone https://github.com/BUAA-ISRC/isrc2026-humanoid.git
   cd isrc2026-humanoid
   ```
2. **安装依赖：** (请确保已配置 ROS2 和 Python 环境)
   ```bash
   sudo apt update && sudo apt install -y ros-${ROS_DISTRO}-desktop
   pip3 install -r requirements.txt
   ```
3. **编译工作空间：**
   ```bash
   colcon build
   source install/setup.bash
   ```

---

## 🤝 Contributing | 参与贡献

**EN:** We welcome contributions from all ISRC members and the open-source community! Please read our [Contributing Guidelines](CONTRIBUTING.md) before submitting a Pull Request.
**CN:** 我们欢迎所有 ISRC 成员及开源社区的开发者的贡献！在提交 Pull Request 之前，请阅读我们的 [贡献指南](CONTRIBUTING.md)。

## 📞 Contact | 联系我们

- **Club:** International Students Robotic Club (ISRC) @ Beihang University | 北京航空航天大学国际学生机器人社
- **Email:** isrc@buaa.edu.cn *(Update with your actual email)*
- **WeChat Official Account:** BUAA_ISRC *(Update with your actual ID)*

## 📜 License | 开源许可

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
本项目基于 MIT 许可证开源。详情请参阅 [LICENSE](LICENSE) 文件。

```

### 💡 Tips for your GitHub Repository:
1. **Update Placeholders:** Make sure to replace `[Insert Competition Name...]` with the actual name of the competition you are preparing for (e.g., *RoboCup 2026*, *CN RoboMaster*, etc.).
2. **Update Contact Info:** Change the email and WeChat ID to your club's actual contact information.
3. **Add Images:** GitHub READMEs look much better with images. I highly recommend adding a banner image at the very top (under the title) showing your CAD design or a photo of the robot. You can do this by adding: `![Robot Banner](docs/images/robot_banner.jpg)` right below the badges.
4. **Create the folders:** Make sure to actually create the `src/`, `hardware/`, `docs/`, and `scripts/` folders in your repo so the structure matches the README.
