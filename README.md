# A ROS-O deb repository for robot_self_filter-jammy-one

## Github Preview Notice

If you are viewing this page on github.com, please note that the README.md preview on the repository page is incomplete.
Please view [the  file directly](https://github.com/v4hn/ros-o-overlay/blob/robot_self_filter-jammy-one/README.md) to see the full content.

## Install Instructions

```bash
echo "deb [trusted=yes] https://raw.githubusercontent.com/v4hn/ros-o-overlay/robot_self_filter-jammy-one/repository/ ./" | sudo tee /etc/apt/sources.list.d/v4hn_ros-o-overlay-robot_self_filter-jammy-one.list
sudo apt update
sudo apt install python3-rosdep2
echo "yaml https://raw.githubusercontent.com/v4hn/ros-o-overlay/robot_self_filter-jammy-one/repository/local.yaml debian" | sudo tee /etc/ros/rosdep/sources.list.d/1-v4hn_ros-o-overlay-robot_self_filter-jammy-one.list
rosdep update

# install required packages, e.g.,
sudo apt install ros-one-desktop-full ros-one-plotjuggler ros-one-navigation [...]
```

## Build

|     |     |
| --- | --- |
| Target Distribution | robot_self_filter-jammy |
| Architecture | amd64 |
| Available Packages | 2 |
| Build Date | Thu Oct 10 14:04:48 UTC 2024 |

## Build Status

|   | Logs | Package | Version | Files | Upstream |
| - | ---- | ------- | ------- | ----- | -------- |
| <a id="[robot_self_filter](https://raw.githubusercontent.com/v4hn/ros-o-overlay/robot_self_filter-jammy-one/repository/ros-one-robot-self-filter_0.1.32-2-ga8d2e49-2024.10.10.14.02_amd64.deb)" href="#[robot_self_filter](https://raw.githubusercontent.com/v4hn/ros-o-overlay/robot_self_filter-jammy-one/repository/ros-one-robot-self-filter_0.1.32-2-ga8d2e49-2024.10.10.14.02_amd64.deb)">:green_circle:</a> | [:green_book:](https://raw.githubusercontent.com/v4hn/ros-o-overlay/robot_self_filter-jammy-one/repository/robot_self_filter_0.1.32-2-ga8d2e49-2024.10.10.14.02-bloom_generate.log) [:green_book:](https://raw.githubusercontent.com/v4hn/ros-o-overlay/robot_self_filter-jammy-one/repository/ros-one-robot-self-filter_0.1.32-2-ga8d2e49-2024.10.10.14.02_amd64-2024-10-10T14:02:05Z.build) | [robot_self_filter](https://raw.githubusercontent.com/v4hn/ros-o-overlay/robot_self_filter-jammy-one/repository/ros-one-robot-self-filter_0.1.32-2-ga8d2e49-2024.10.10.14.02_amd64.deb) | 0.1.32-2-ga8d2e49-2024.10.10.14.02 | [:books:](https://raw.githubusercontent.com/v4hn/ros-o-overlay/robot_self_filter-jammy-one/repository/ros-one-robot-self-filter_0.1.32-2-ga8d2e49-2024.10.10.14.02_amd64.files) | [:link:](https://github.com/PR2/robot_self_filter/tree/indigo-devel) |

## Top Offenders (broken packages)

|   | Logs | Package | Version | Files | Upstream |
| - | ---- | ------- | ------- | ----- | -------- |
