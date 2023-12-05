# Introduction
Welcome to the ROS2 Beginner's Guide repository! This guide is designed to help you get started with ROS2, the Robot Operating System, and provide you with the essential knowledge to work effectively within the ROS2 ecosystem. I will be updating this repository as I learn new concepts in ros2-humble.
This tutorial assumes you have a linux machine (Ubuntu) or have a virtual environment installed.

Our first step would be to check the installation of python in the linux machine.

```console
python3 --version
```
which should output

```console
python 3.XX.X
```
Next go to Ubuntu Software and install VS Code (simplifies file handling). To verify your installation, open your terminal and enter the following:
```console
code .
```
which should open up VS Code, with a plethora of files in your "home" directory.

# Ros2 installation
Note: This tutorial provides an abridged version of the original ROS 2 Documentation. It assumes a fresh Ubuntu Desktop 22.04 LTS x64 installation with superuser access.
Warning: Follow commands precisely; deviations may cause unspecified problems.
```console
sudo apt update && sudo apt upgrade -y
```


