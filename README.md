# AhaRobot Hardware Design Resources

<div align="center">
  <img src="assets/logo.png" alt="AhaRobot Logo" width="200"/>
</div>

<div align="center">
  <a href="https://aha-robot.github.io/" target="_blank">Project Website</a> • 
  <a href="https://arxiv.org/abs/2503.10070" target="_blank">Paper</a> • 
  <a href="https://www.notion.so/1b433900bc8780c4a503e3490ce3e718?pvs=21" target="_blank">Documentation</a> • 
  <a href="https://github.com/hilookas/astra_ws" target="_blank">ROS Code</a> •
  <a href="https://github.com/hilookas/AstraFirmwares" target="_blank">Firmware Code</a> •
  <a href="https://github.com/hilookas/Astra_Hardwares" target="_blank">Hardware Code</a> •
  <a href="https://huggingface.co/lookas" target="_blank">Dataset</a>
</div>

## Repository Contents

This repository contains hardware design resources for AhaRobot, organized into the following structure:

### Main Components

- **Astra**: Main robot hardware design files
  - **STL/**: 3D printable STL model files
  - **Aluminum_Profiles_STEP/**: Aluminum profile STEP files
  - **Astra.STEP**: Complete robot model
  - **Other files**: STEP models for motors, transmission components, and other parts

- **Astra_Teleop**: Robopilot teleoperation control device design
  - **Ass.STL/Ass.3mf**: 3D printable models for remote control handle

- **astra_description**: Robot description files for ROS2
  - **urdf/**: Unified Robot Description Format files
  - **meshes/**: Mesh models for visualization
  - **launch/**: ROS2 launch files
  - **config/**: Configuration files

## How-to-use

For detailed documentation, please refer to the following resources:

- [Getting Started Guide](docs/getting_started.md)
  - Get Your AhaRobot Parts
  - Bill of Materials
  - 3D Printing Guide
- [Hardware Assembly Guide](docs/assembly.md)
  - Build Base
  - Installing Two Sliding Rail (Body)
  - Building Your Aha Arm
  - Building Grippers and Heads
  - Wiring

## License

This project is licensed under the [GNU General Public License v3.0 (GPL-3.0)](https://www.gnu.org/licenses/gpl-3.0.en.html) with additional restrictions.

This means:
- ✅ You are free to use, modify and distribute the source code
- ✅ You must make your modifications available under the same license
- ✅ You must state changes made to the code
- ✅ You must include the original copyright notice
- ❌ You may not use the material for commercial purposes
- ❌ Modifications must also prohibit commercial use

IMPORTANT: This project explicitly prohibits ANY commercial use, including but not limited to selling products based on this project.

See the [LICENSE](LICENSE) file for the full license text.
