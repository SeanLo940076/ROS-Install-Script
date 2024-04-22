# ROS-Install-Script

## Introduction
This repository provides automated scripts to install ROS Melodic and ROS Noetic on Ubuntu. These scripts are designed to simplify the setup of ROS environments for development purposes.

## Installation Scripts

### ROS Noetic Installation
To install ROS Noetic, run the following command in your terminal:
```
sudo sh ros_noetic_install.sh
```

### ROS Melodic Installation
To install ROS Melodic, run the following command in your terminal:
```
sudo sh ros_melodic_install.sh
```

## Script Details
The scripts handle the addition of ROS repositories, installation of ROS desktop full packages, and setting up the necessary environment variables. They also install essential Python tools and initialize rosdep to manage system dependencies.

## Usage
1. Clone this repository or download the scripts.
2. Make the scripts executable:
   ```
   chmod +x ros_noetic_install.sh ros_melodic_install.sh
   ```
3. Execute the script for your desired ROS version as shown above.

## Note
Ensure that you have `curl` and `sudo` privileges on your system to run these scripts effectively.