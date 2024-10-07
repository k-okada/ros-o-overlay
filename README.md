# A ROS-O deb repository for main-jammy-one

## Github Preview Notice

If you are viewing this page on github.com, please note that the README.md preview on the repository page is incomplete.
Please view [the  file directly](https://github.com/v4hn/ros-o-overlay/blob/main-jammy-one/README.md) to see the full content.

## Install Instructions

```bash
echo "deb [trusted=yes] https://raw.githubusercontent.com/v4hn/ros-o-overlay/main-jammy-one/repository// ./" | sudo tee /etc/apt/sources.list.d/v4hn_ros-o-overlay-main-jammy-one.list
sudo apt update
sudo apt install python3-rosdep2
echo "yaml https://raw.githubusercontent.com/v4hn/ros-o-overlay/main-jammy-one/repository//local.yaml debian" | sudo tee /etc/ros/rosdep/sources.list.d/1-v4hn_ros-o-overlay-main-jammy-one.list
rosdep update

# install required packages, e.g.,
sudo apt install ros-one-desktop-full ros-one-plotjuggler ros-one-navigation [...]
```

## Build

|     |     |
| --- | --- |
| Target Distribution | main-jammy |
| Architecture | amd64 |
| Available Packages | 3 |
| Build Date | Mon Oct  7 15:40:08 UTC 2024 |

## Build Status

|   | Logs | Package | Version | Files | Upstream |
| - | ---- | ------- | ------- | ----- | -------- |
| <a id="[hpp-fcl](https://raw.githubusercontent.com/v4hn/ros-o-overlay/main-jammy-one/repository//ros-one-hpp-fcl_2.4.5-788-g6b9f9c8e-2024.10.07.15.08_amd64.deb)" href="#[hpp-fcl](https://raw.githubusercontent.com/v4hn/ros-o-overlay/main-jammy-one/repository//ros-one-hpp-fcl_2.4.5-788-g6b9f9c8e-2024.10.07.15.08_amd64.deb)">:green_circle:</a> | [:green_book:](https://raw.githubusercontent.com/v4hn/ros-o-overlay/main-jammy-one/repository//hpp-fcl_2.4.5-788-g6b9f9c8e-2024.10.07.15.08-bloom_generate.log) [:green_book:](https://raw.githubusercontent.com/v4hn/ros-o-overlay/main-jammy-one/repository//ros-one-hpp-fcl_2.4.5-788-g6b9f9c8e-2024.10.07.15.08_amd64-2024-10-07T15:08:05Z.build) | [hpp-fcl](https://raw.githubusercontent.com/v4hn/ros-o-overlay/main-jammy-one/repository//ros-one-hpp-fcl_2.4.5-788-g6b9f9c8e-2024.10.07.15.08_amd64.deb) | 2.4.5-788-g6b9f9c8e-2024.10.07.15.08 | [:books:](https://raw.githubusercontent.com/v4hn/ros-o-overlay/main-jammy-one/repository//ros-one-hpp-fcl_2.4.5-788-g6b9f9c8e-2024.10.07.15.08_amd64.files) | [:link:](https://github.com/humanoid-path-planner/hpp-fcl/tree/devel) |
| <a id="[pinocchio](https://raw.githubusercontent.com/v4hn/ros-o-overlay/main-jammy-one/repository//ros-one-pinocchio_3.2.0-2024.10.07.15.15_amd64.deb)" href="#[pinocchio](https://raw.githubusercontent.com/v4hn/ros-o-overlay/main-jammy-one/repository//ros-one-pinocchio_3.2.0-2024.10.07.15.15_amd64.deb)">:green_circle:</a> | [:green_book:](https://raw.githubusercontent.com/v4hn/ros-o-overlay/main-jammy-one/repository//pinocchio_3.2.0-2024.10.07.15.15-bloom_generate.log) [:green_book:](https://raw.githubusercontent.com/v4hn/ros-o-overlay/main-jammy-one/repository//ros-one-pinocchio_3.2.0-2024.10.07.15.15_amd64-2024-10-07T15:16:16Z.build) | [pinocchio](https://raw.githubusercontent.com/v4hn/ros-o-overlay/main-jammy-one/repository//ros-one-pinocchio_3.2.0-2024.10.07.15.15_amd64.deb) | 3.2.0-2024.10.07.15.15 | [:books:](https://raw.githubusercontent.com/v4hn/ros-o-overlay/main-jammy-one/repository//ros-one-pinocchio_3.2.0-2024.10.07.15.15_amd64.files) | [:link:](https://github.com/stack-of-tasks/pinocchio/tree/master) |

## Top Offenders (broken packages)

|   | Logs | Package | Version | Files | Upstream |
| - | ---- | ------- | ------- | ----- | -------- |
