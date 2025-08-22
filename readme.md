# Shoebill Leader & Follower

Shoebill Banner

An open source leader-follower robotic arm system with 7 degrees of freedom, made by Vassar Robotics

## Overview

Shoebill Leader & Follower in action

**Build specs:** ~$750 cost | 3-5 days lead time | Intermediate skill level

Shoebill is a leader-follower robotic arm system featuring:

* 🎯 **7-axis articulated movement** with FeeTech servo motors
* 🤖 **Leader/Follower teleoperation** with 1:1 joint mapping
* 💪 **Force feedback capability** via torque position setting
* 🎮 **LeRobot compatibility** for ACT training policy infrastructure
* 🔧 **Open source SDK** with pip-installable Vassar-FeeTech servo SDK

## Build Guide

**Start here:** Prerequisites & Planning

### Complete Build Process

1. 📋 Prerequisites & Planning - Skills, tools, and BOM
2. 🔧 Components & 3D Parts - Technical specs and electrical layout
3. ⚙️ Servo Setup - Configure FeeTech HLS3625 servos
4. 🎯 Leader Arm Assembly - GELLO kinematics, torsion-spring gripper
5. 🏗️ Follower Arm Assembly - UMI-inspired end effector with TPU material
6. 🎮 Teleoperation Setup - Leader-follower mapping and control
7. 🔍 Troubleshooting - Common issues and solutions

### Quick Reference

* **Bill of Materials**: Complete component list with suppliers
* **3D Print Files**: Available in `/3D/` directory (OnShape CAD)
* **Software Control**: Vassar-FeeTech SDK Repository

## Project Status

✅ **Production Ready** - This project is fully developed and available for purchase through Vassar Robotics.

## Key Features

### Leader Arm
* **GELLO Leader Arm Design** - Follows identical kinematics as ARX, Trossen, and I2RT follower arms
* **Custom Torsion-Spring Gripper** - Easy-to-use, normally-open design
* **FeeTech HLS3625 Servos** - Torque position setting capability for force-feedback paradigms

### Follower Arm
* **UMI-Inspired End Effector** - Compliant TPU material for higher dexterity
* **7 Degrees of Freedom** - More closely mimics human joint structure than 6 DoF
* **12V FeeTech Servos** - 3 N·m output torque for robust performance

## Community & Support

### Getting Help

* **Start here**: Troubleshooting Guide for common issues
* **GitHub Issues**: Report bugs or ask questions
* **Documentation**: Comprehensive setup and usage guides

### Contributing

We welcome contributions:

* 🐛 Bug reports and fixes
* 📖 Documentation improvements
* 🔧 Design enhancements
* 🌍 Regional supplier information
* 📸 Build photos and videos

Please check existing issues before creating new ones.

## Technical Specifications

* **Servo Motors**: FeeTech HLS3625 (Leader), 12V FeeTech (Follower)
* **Degrees of Freedom**: 7 DoF (improvement over SO-101 design)
* **Torque Output**: 3 N·m (Follower arm)
* **Compatibility**: LeRobot ACT training policy infrastructure
* **SDK**: Open source Vassar-FeeTech servo SDK (pip installable)

## License

This project is licensed under the GNU General Public License v3.0 - see the LICENSE file for details.

## About

Open-source Leader-Follower Robotic Arm System with 7 Degrees of Freedom

### Resources

* [Vassar Robotics Shop](https://shop.vassarrobotics.com/products/7-dof-leader-follower-pair-assembled)
* [Vassar-FeeTech SDK](https://github.com/vassar-robotics/feetech-servo-sdk)
* [LeRobot Documentation](https://huggingface.co/docs/lerobot/en/installation)

### License

GPL-3.0 license