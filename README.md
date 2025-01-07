# A ROS-O deb repository for rqt_joint_trajectory_plot-jammy-one

## Github Preview Notice

If you are viewing this page on github.com, please note that the README.md preview on the repository page is incomplete.
Please view [the `README.md` file directly](https://github.com/k-okada/ros-o-overlay/blob/rqt_joint_trajectory_plot-jammy-one/README.md) to see the full content.

## Install Instructions

```bash
echo "deb [trusted=yes] https://raw.githubusercontent.com/k-okada/ros-o-overlay/rqt_joint_trajectory_plot-jammy-one/repository/ ./" | sudo tee /etc/apt/sources.list.d/k-okada_ros-o-overlay-rqt_joint_trajectory_plot-jammy-one.list
sudo apt update
sudo apt install python3-rosdep2
echo "yaml https://raw.githubusercontent.com/k-okada/ros-o-overlay/rqt_joint_trajectory_plot-jammy-one/repository/local.yaml debian" | sudo tee /etc/ros/rosdep/sources.list.d/1-k-okada_ros-o-overlay-rqt_joint_trajectory_plot-jammy-one.list
rosdep update

# install required packages, e.g.,
sudo apt install ros-one-desktop-full ros-one-plotjuggler ros-one-navigation [...]
```

## Build

|     |     |
| --- | --- |
| Target Distribution | rqt_joint_trajectory_plot-jammy |
| Architecture | amd64 |
| Available Packages | 1 |
| Build Date | Tue Jan  7 13:03:03 UTC 2025 |

## Build Status

|   | Logs | Package | Version | Files | Upstream |
| - | ---- | ------- | ------- | ----- | -------- |
| <a id="[rqt_joint_trajectory_plot](https://raw.githubusercontent.com/k-okada/ros-o-overlay/rqt_joint_trajectory_plot-jammy-one/repository/ros-one-rqt-joint-trajectory-plot_0.0.5-31-g508ce24-2025.01.07.13.01_amd64.deb)" href="#[rqt_joint_trajectory_plot](https://raw.githubusercontent.com/k-okada/ros-o-overlay/rqt_joint_trajectory_plot-jammy-one/repository/ros-one-rqt-joint-trajectory-plot_0.0.5-31-g508ce24-2025.01.07.13.01_amd64.deb)">:green_circle:</a> | [:green_book:](https://raw.githubusercontent.com/k-okada/ros-o-overlay/rqt_joint_trajectory_plot-jammy-one/repository/rqt_joint_trajectory_plot_0.0.5-31-g508ce24-2025.01.07.13.01-bloom_generate.log) [:green_book:](https://raw.githubusercontent.com/k-okada/ros-o-overlay/rqt_joint_trajectory_plot-jammy-one/repository/ros-one-rqt-joint-trajectory-plot_0.0.5-31-g508ce24-2025.01.07.13.01_amd64-2025-01-07T13:01:55Z.build) | [rqt_joint_trajectory_plot](https://raw.githubusercontent.com/k-okada/ros-o-overlay/rqt_joint_trajectory_plot-jammy-one/repository/ros-one-rqt-joint-trajectory-plot_0.0.5-31-g508ce24-2025.01.07.13.01_amd64.deb) | 0.0.5-31-g508ce24-2025.01.07.13.01 | [:books:](https://raw.githubusercontent.com/k-okada/ros-o-overlay/rqt_joint_trajectory_plot-jammy-one/repository/ros-one-rqt-joint-trajectory-plot_0.0.5-31-g508ce24-2025.01.07.13.01_amd64.files) | [:link:](https://github.com/tork-a/rqt_joint_trajectory_plot/tree/master) |

## Top Offenders (broken packages)

|   | Logs | Package | Version | Files | Upstream |
| - | ---- | ------- | ------- | ----- | -------- |
