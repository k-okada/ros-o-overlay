# A ROS-O deb repository for check_catkin_virtualenv-jammy-one

## Github Preview Notice

If you are viewing this page on github.com, please note that the README.md preview on the repository page is incomplete.
Please view [the `README.md` file directly](https://github.com/k-okada/ros-o-overlay/blob/check_catkin_virtualenv-jammy-one/README.md) to see the full content.

## Install Instructions

```bash
echo "deb [trusted=yes] https://raw.githubusercontent.com/k-okada/ros-o-overlay/check_catkin_virtualenv-jammy-one/repository/ ./" | sudo tee /etc/apt/sources.list.d/k-okada_ros-o-overlay-check_catkin_virtualenv-jammy-one.list
sudo apt update
sudo apt install python3-rosdep2
echo "yaml https://raw.githubusercontent.com/k-okada/ros-o-overlay/check_catkin_virtualenv-jammy-one/repository/local.yaml debian" | sudo tee /etc/ros/rosdep/sources.list.d/1-k-okada_ros-o-overlay-check_catkin_virtualenv-jammy-one.list
rosdep update

# install required packages, e.g.,
sudo apt install ros-one-desktop-full ros-one-plotjuggler ros-one-navigation [...]
```

## Build

|     |     |
| --- | --- |
| Target Distribution | check_catkin_virtualenv-jammy |
| Architecture | amd64 |
| Available Packages | 2 |
| Build Date | Tue Dec 31 09:01:25 UTC 2024 |

## Build Status

|   | Logs | Package | Version | Files | Upstream |
| - | ---- | ------- | ------- | ----- | -------- |
| <a id="[jsk_rosbag_tools](https://raw.githubusercontent.com/k-okada/ros-o-overlay/check_catkin_virtualenv-jammy-one/repository/ros-one-jsk-rosbag-tools_2.2.15-4-2024.12.31.08.58_amd64.deb)" href="#[jsk_rosbag_tools](https://raw.githubusercontent.com/k-okada/ros-o-overlay/check_catkin_virtualenv-jammy-one/repository/ros-one-jsk-rosbag-tools_2.2.15-4-2024.12.31.08.58_amd64.deb)">:green_circle:</a> | [:green_book:](https://raw.githubusercontent.com/k-okada/ros-o-overlay/check_catkin_virtualenv-jammy-one/repository/jsk_rosbag_tools_2.2.15-4-2024.12.31.08.58-bloom_generate.log) [:green_book:](https://raw.githubusercontent.com/k-okada/ros-o-overlay/check_catkin_virtualenv-jammy-one/repository/ros-one-jsk-rosbag-tools_2.2.15-4-2024.12.31.08.58_amd64-2024-12-31T08:58:19Z.build) | [jsk_rosbag_tools](https://raw.githubusercontent.com/k-okada/ros-o-overlay/check_catkin_virtualenv-jammy-one/repository/ros-one-jsk-rosbag-tools_2.2.15-4-2024.12.31.08.58_amd64.deb) | 2.2.15-4-2024.12.31.08.58 | [:books:](https://raw.githubusercontent.com/k-okada/ros-o-overlay/check_catkin_virtualenv-jammy-one/repository/ros-one-jsk-rosbag-tools_2.2.15-4-2024.12.31.08.58_amd64.files) | [:link:](https://github.com/tork-a/jsk_common-release/tree/HEAD) |

## Top Offenders (broken packages)

|   | Logs | Package | Version | Files | Upstream |
| - | ---- | ------- | ------- | ----- | -------- |
