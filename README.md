# A ROS-O deb repository for mavros-jammy-one

## Github Preview Notice

If you are viewing this page on github.com, please note that the README.md preview on the repository page is incomplete.
Please view [the `README.md` file directly](https://github.com/v4hn/ros-o-overlay/blob/mavros-jammy-one/README.md) to see the full content.

## Install Instructions

```bash
echo "deb [trusted=yes] https://raw.githubusercontent.com/v4hn/ros-o-overlay/mavros-jammy-one/repository/ ./" | sudo tee /etc/apt/sources.list.d/v4hn_ros-o-overlay-mavros-jammy-one.list
sudo apt update
sudo apt install python3-rosdep2
echo "yaml https://raw.githubusercontent.com/v4hn/ros-o-overlay/mavros-jammy-one/repository/local.yaml debian" | sudo tee /etc/ros/rosdep/sources.list.d/1-v4hn_ros-o-overlay-mavros-jammy-one.list
rosdep update

# install required packages, e.g.,
sudo apt install ros-one-desktop-full ros-one-plotjuggler ros-one-navigation [...]
```

## Build

|     |     |
| --- | --- |
| Target Distribution | mavros-jammy |
| Architecture | amd64 |
| Available Packages | 10 |
| Build Date | Tue Dec 24 16:55:45 UTC 2024 |

## Build Status

|   | Logs | Package | Version | Files | Upstream |
| - | ---- | ------- | ------- | ----- | -------- |
| <a id="[libmavconn](https://raw.githubusercontent.com/v4hn/ros-o-overlay/mavros-jammy-one/repository/ros-one-libmavconn_1.20.0-1-g08142be7-2024.12.24.16.44_amd64.deb)" href="#[libmavconn](https://raw.githubusercontent.com/v4hn/ros-o-overlay/mavros-jammy-one/repository/ros-one-libmavconn_1.20.0-1-g08142be7-2024.12.24.16.44_amd64.deb)">:green_circle:</a> | [:green_book:](https://raw.githubusercontent.com/v4hn/ros-o-overlay/mavros-jammy-one/repository/libmavconn_1.20.0-1-g08142be7-2024.12.24.16.44-bloom_generate.log) [:green_book:](https://raw.githubusercontent.com/v4hn/ros-o-overlay/mavros-jammy-one/repository/ros-one-libmavconn_1.20.0-1-g08142be7-2024.12.24.16.44_amd64-2024-12-24T16:44:26Z.build) | [libmavconn](https://raw.githubusercontent.com/v4hn/ros-o-overlay/mavros-jammy-one/repository/ros-one-libmavconn_1.20.0-1-g08142be7-2024.12.24.16.44_amd64.deb) | 1.20.0-1-g08142be7-2024.12.24.16.44 | [:books:](https://raw.githubusercontent.com/v4hn/ros-o-overlay/mavros-jammy-one/repository/ros-one-libmavconn_1.20.0-1-g08142be7-2024.12.24.16.44_amd64.files) | [:link:](https://github.com/ros-o/mavros/tree/obese-devel) |
| <a id="[mavlink](https://raw.githubusercontent.com/v4hn/ros-o-overlay/mavros-jammy-one/repository/ros-one-mavlink_2024.10.10-1-2024.12.24.16.43_amd64.deb)" href="#[mavlink](https://raw.githubusercontent.com/v4hn/ros-o-overlay/mavros-jammy-one/repository/ros-one-mavlink_2024.10.10-1-2024.12.24.16.43_amd64.deb)">:green_circle:</a> | [:green_book:](https://raw.githubusercontent.com/v4hn/ros-o-overlay/mavros-jammy-one/repository/mavlink_2024.10.10-1-2024.12.24.16.43-bloom_generate.log) [:green_book:](https://raw.githubusercontent.com/v4hn/ros-o-overlay/mavros-jammy-one/repository/ros-one-mavlink_2024.10.10-1-2024.12.24.16.43_amd64-2024-12-24T16:43:33Z.build) | [mavlink](https://raw.githubusercontent.com/v4hn/ros-o-overlay/mavros-jammy-one/repository/ros-one-mavlink_2024.10.10-1-2024.12.24.16.43_amd64.deb) | 2024.10.10-1-2024.12.24.16.43 | [:books:](https://raw.githubusercontent.com/v4hn/ros-o-overlay/mavros-jammy-one/repository/ros-one-mavlink_2024.10.10-1-2024.12.24.16.43_amd64.files) | [:link:](https://github.com/mavlink/mavlink-gbp-release/tree/release/noetic/mavlink) |
| <a id="[mavros](https://raw.githubusercontent.com/v4hn/ros-o-overlay/mavros-jammy-one/repository/ros-one-mavros_1.20.0-1-g08142be7-2024.12.24.16.46_amd64.deb)" href="#[mavros](https://raw.githubusercontent.com/v4hn/ros-o-overlay/mavros-jammy-one/repository/ros-one-mavros_1.20.0-1-g08142be7-2024.12.24.16.46_amd64.deb)">:green_circle:</a> | [:green_book:](https://raw.githubusercontent.com/v4hn/ros-o-overlay/mavros-jammy-one/repository/mavros_1.20.0-1-g08142be7-2024.12.24.16.46-bloom_generate.log) [:green_book:](https://raw.githubusercontent.com/v4hn/ros-o-overlay/mavros-jammy-one/repository/ros-one-mavros_1.20.0-1-g08142be7-2024.12.24.16.46_amd64-2024-12-24T16:46:49Z.build) | [mavros](https://raw.githubusercontent.com/v4hn/ros-o-overlay/mavros-jammy-one/repository/ros-one-mavros_1.20.0-1-g08142be7-2024.12.24.16.46_amd64.deb) | 1.20.0-1-g08142be7-2024.12.24.16.46 | [:books:](https://raw.githubusercontent.com/v4hn/ros-o-overlay/mavros-jammy-one/repository/ros-one-mavros_1.20.0-1-g08142be7-2024.12.24.16.46_amd64.files) | [:link:](https://github.com/ros-o/mavros/tree/obese-devel) |
| <a id="[mavros_extras](https://raw.githubusercontent.com/v4hn/ros-o-overlay/mavros-jammy-one/repository/ros-one-mavros-extras_1.20.0-1-g08142be7-2024.12.24.16.50_amd64.deb)" href="#[mavros_extras](https://raw.githubusercontent.com/v4hn/ros-o-overlay/mavros-jammy-one/repository/ros-one-mavros-extras_1.20.0-1-g08142be7-2024.12.24.16.50_amd64.deb)">:green_circle:</a> | [:green_book:](https://raw.githubusercontent.com/v4hn/ros-o-overlay/mavros-jammy-one/repository/mavros_extras_1.20.0-1-g08142be7-2024.12.24.16.50-bloom_generate.log) [:green_book:](https://raw.githubusercontent.com/v4hn/ros-o-overlay/mavros-jammy-one/repository/ros-one-mavros-extras_1.20.0-1-g08142be7-2024.12.24.16.50_amd64-2024-12-24T16:50:57Z.build) | [mavros_extras](https://raw.githubusercontent.com/v4hn/ros-o-overlay/mavros-jammy-one/repository/ros-one-mavros-extras_1.20.0-1-g08142be7-2024.12.24.16.50_amd64.deb) | 1.20.0-1-g08142be7-2024.12.24.16.50 | [:books:](https://raw.githubusercontent.com/v4hn/ros-o-overlay/mavros-jammy-one/repository/ros-one-mavros-extras_1.20.0-1-g08142be7-2024.12.24.16.50_amd64.files) | [:link:](https://github.com/ros-o/mavros/tree/obese-devel) |
| <a id="[mavros_msgs](https://raw.githubusercontent.com/v4hn/ros-o-overlay/mavros-jammy-one/repository/ros-one-mavros-msgs_1.20.0-1-g08142be7-2024.12.24.16.45_amd64.deb)" href="#[mavros_msgs](https://raw.githubusercontent.com/v4hn/ros-o-overlay/mavros-jammy-one/repository/ros-one-mavros-msgs_1.20.0-1-g08142be7-2024.12.24.16.45_amd64.deb)">:green_circle:</a> | [:green_book:](https://raw.githubusercontent.com/v4hn/ros-o-overlay/mavros-jammy-one/repository/mavros_msgs_1.20.0-1-g08142be7-2024.12.24.16.45-bloom_generate.log) [:green_book:](https://raw.githubusercontent.com/v4hn/ros-o-overlay/mavros-jammy-one/repository/ros-one-mavros-msgs_1.20.0-1-g08142be7-2024.12.24.16.45_amd64-2024-12-24T16:45:37Z.build) | [mavros_msgs](https://raw.githubusercontent.com/v4hn/ros-o-overlay/mavros-jammy-one/repository/ros-one-mavros-msgs_1.20.0-1-g08142be7-2024.12.24.16.45_amd64.deb) | 1.20.0-1-g08142be7-2024.12.24.16.45 | [:books:](https://raw.githubusercontent.com/v4hn/ros-o-overlay/mavros-jammy-one/repository/ros-one-mavros-msgs_1.20.0-1-g08142be7-2024.12.24.16.45_amd64.files) | [:link:](https://github.com/ros-o/mavros/tree/obese-devel) |
| <a id="[test_mavros](https://raw.githubusercontent.com/v4hn/ros-o-overlay/mavros-jammy-one/repository/ros-one-test-mavros_1.20.0-1-g08142be7-2024.12.24.16.54_amd64.deb)" href="#[test_mavros](https://raw.githubusercontent.com/v4hn/ros-o-overlay/mavros-jammy-one/repository/ros-one-test-mavros_1.20.0-1-g08142be7-2024.12.24.16.54_amd64.deb)">:green_circle:</a> | [:green_book:](https://raw.githubusercontent.com/v4hn/ros-o-overlay/mavros-jammy-one/repository/test_mavros_1.20.0-1-g08142be7-2024.12.24.16.54-bloom_generate.log) [:green_book:](https://raw.githubusercontent.com/v4hn/ros-o-overlay/mavros-jammy-one/repository/ros-one-test-mavros_1.20.0-1-g08142be7-2024.12.24.16.54_amd64-2024-12-24T16:54:23Z.build) | [test_mavros](https://raw.githubusercontent.com/v4hn/ros-o-overlay/mavros-jammy-one/repository/ros-one-test-mavros_1.20.0-1-g08142be7-2024.12.24.16.54_amd64.deb) | 1.20.0-1-g08142be7-2024.12.24.16.54 | [:books:](https://raw.githubusercontent.com/v4hn/ros-o-overlay/mavros-jammy-one/repository/ros-one-test-mavros_1.20.0-1-g08142be7-2024.12.24.16.54_amd64.files) | [:link:](https://github.com/ros-o/mavros/tree/obese-devel) |

## Top Offenders (broken packages)

|   | Logs | Package | Version | Files | Upstream |
| - | ---- | ------- | ------- | ----- | -------- |
