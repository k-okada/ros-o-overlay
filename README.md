# A ROS-O deb repository for check_catkin_tools-jammy-one

## Github Preview Notice

If you are viewing this page on github.com, please note that the README.md preview on the repository page is incomplete.
Please view [the `README.md` file directly](https://github.com/k-okada/ros-o-overlay/blob/check_catkin_tools-jammy-one/README.md) to see the full content.

## Install Instructions

```bash
echo "deb [trusted=yes] https://raw.githubusercontent.com/k-okada/ros-o-overlay/check_catkin_tools-jammy-one/repository/ ./" | sudo tee /etc/apt/sources.list.d/k-okada_ros-o-overlay-check_catkin_tools-jammy-one.list
sudo apt update
sudo apt install python3-rosdep2
echo "yaml https://raw.githubusercontent.com/k-okada/ros-o-overlay/check_catkin_tools-jammy-one/repository/local.yaml debian" | sudo tee /etc/ros/rosdep/sources.list.d/1-k-okada_ros-o-overlay-check_catkin_tools-jammy-one.list
rosdep update

# install required packages, e.g.,
sudo apt install ros-one-desktop-full ros-one-plotjuggler ros-one-navigation [...]
```

## Build

|     |     |
| --- | --- |
| Target Distribution | check_catkin_tools-jammy |
| Architecture | amd64 |
| Available Packages | 2 |
| Build Date | Thu Jan  2 08:47:31 UTC 2025 |

## Build Status

|   | Logs | Package | Version | Files | Upstream |
| - | ---- | ------- | ------- | ----- | -------- |
| <a id="[collada_urdf_jsk_patch](https://raw.githubusercontent.com/k-okada/ros-o-overlay/check_catkin_tools-jammy-one/repository/ros-one-collada-urdf-jsk-patch_2.1.28-1-2025.01.02.08.45_amd64.deb)" href="#[collada_urdf_jsk_patch](https://raw.githubusercontent.com/k-okada/ros-o-overlay/check_catkin_tools-jammy-one/repository/ros-one-collada-urdf-jsk-patch_2.1.28-1-2025.01.02.08.45_amd64.deb)">:green_circle:</a> | [:green_book:](https://raw.githubusercontent.com/k-okada/ros-o-overlay/check_catkin_tools-jammy-one/repository/collada_urdf_jsk_patch_2.1.28-1-2025.01.02.08.45-bloom_generate.log) [:green_book:](https://raw.githubusercontent.com/k-okada/ros-o-overlay/check_catkin_tools-jammy-one/repository/ros-one-collada-urdf-jsk-patch_2.1.28-1-2025.01.02.08.45_amd64-2025-01-02T08:45:21Z.build) | [collada_urdf_jsk_patch](https://raw.githubusercontent.com/k-okada/ros-o-overlay/check_catkin_tools-jammy-one/repository/ros-one-collada-urdf-jsk-patch_2.1.28-1-2025.01.02.08.45_amd64.deb) | 2.1.28-1-2025.01.02.08.45 | [:books:](https://raw.githubusercontent.com/k-okada/ros-o-overlay/check_catkin_tools-jammy-one/repository/ros-one-collada-urdf-jsk-patch_2.1.28-1-2025.01.02.08.45_amd64.files) | [:link:](https://github.com/tork-a/jsk_3rdparty-release/tree/HEAD) |

## Top Offenders (broken packages)

|   | Logs | Package | Version | Files | Upstream |
| - | ---- | ------- | ------- | ----- | -------- |
