# A ROS-O deb repository for check_jsk_recognition-jammy-one

## Github Preview Notice

If you are viewing this page on github.com, please note that the README.md preview on the repository page is incomplete.
Please view [the `README.md` file directly](https://github.com/k-okada/ros-o-overlay/blob/check_jsk_recognition-jammy-one/README.md) to see the full content.

## Install Instructions

```bash
echo "deb [trusted=yes] https://raw.githubusercontent.com/k-okada/ros-o-overlay/check_jsk_recognition-jammy-one/repository/ ./" | sudo tee /etc/apt/sources.list.d/k-okada_ros-o-overlay-check_jsk_recognition-jammy-one.list
sudo apt update
sudo apt install python3-rosdep2
echo "yaml https://raw.githubusercontent.com/k-okada/ros-o-overlay/check_jsk_recognition-jammy-one/repository/local.yaml debian" | sudo tee /etc/ros/rosdep/sources.list.d/1-k-okada_ros-o-overlay-check_jsk_recognition-jammy-one.list
rosdep update

# install required packages, e.g.,
sudo apt install ros-one-desktop-full ros-one-plotjuggler ros-one-navigation [...]
```

## Build

|     |     |
| --- | --- |
| Target Distribution | check_jsk_recognition-jammy |
| Architecture | amd64 |
| Available Packages | 22 |
| Build Date | Mon Jan  6 12:17:56 UTC 2025 |

## Build Status

|   | Logs | Package | Version | Files | Upstream |
| - | ---- | ------- | ------- | ----- | -------- |
| <a id="[audio_to_spectrogram](https://raw.githubusercontent.com/k-okada/ros-o-overlay/check_jsk_recognition-jammy-one/repository/ros-one-audio-to-spectrogram_1.2.17-42-g7816812a-2025.01.06.10.59_amd64.deb)" href="#[audio_to_spectrogram](https://raw.githubusercontent.com/k-okada/ros-o-overlay/check_jsk_recognition-jammy-one/repository/ros-one-audio-to-spectrogram_1.2.17-42-g7816812a-2025.01.06.10.59_amd64.deb)">:green_circle:</a> | [:green_book:](https://raw.githubusercontent.com/k-okada/ros-o-overlay/check_jsk_recognition-jammy-one/repository/audio_to_spectrogram_1.2.17-42-g7816812a-2025.01.06.10.59-bloom_generate.log) [:green_book:](https://raw.githubusercontent.com/k-okada/ros-o-overlay/check_jsk_recognition-jammy-one/repository/ros-one-audio-to-spectrogram_1.2.17-42-g7816812a-2025.01.06.10.59_amd64-2025-01-06T10:59:57Z.build) | [audio_to_spectrogram](https://raw.githubusercontent.com/k-okada/ros-o-overlay/check_jsk_recognition-jammy-one/repository/ros-one-audio-to-spectrogram_1.2.17-42-g7816812a-2025.01.06.10.59_amd64.deb) | 1.2.17-42-g7816812a-2025.01.06.10.59 | [:books:](https://raw.githubusercontent.com/k-okada/ros-o-overlay/check_jsk_recognition-jammy-one/repository/ros-one-audio-to-spectrogram_1.2.17-42-g7816812a-2025.01.06.10.59_amd64.files) | [:link:](https://github.com/ros-o/jsk_recognition/tree/obese-devel) |
| <a id="[checkerboard_detector](https://raw.githubusercontent.com/k-okada/ros-o-overlay/check_jsk_recognition-jammy-one/repository/ros-one-checkerboard-detector_1.2.17-42-g7816812a-2025.01.06.11.07_amd64.deb)" href="#[checkerboard_detector](https://raw.githubusercontent.com/k-okada/ros-o-overlay/check_jsk_recognition-jammy-one/repository/ros-one-checkerboard-detector_1.2.17-42-g7816812a-2025.01.06.11.07_amd64.deb)">:green_circle:</a> | [:green_book:](https://raw.githubusercontent.com/k-okada/ros-o-overlay/check_jsk_recognition-jammy-one/repository/checkerboard_detector_1.2.17-42-g7816812a-2025.01.06.11.07-bloom_generate.log) [:green_book:](https://raw.githubusercontent.com/k-okada/ros-o-overlay/check_jsk_recognition-jammy-one/repository/ros-one-checkerboard-detector_1.2.17-42-g7816812a-2025.01.06.11.07_amd64-2025-01-06T11:07:03Z.build) | [checkerboard_detector](https://raw.githubusercontent.com/k-okada/ros-o-overlay/check_jsk_recognition-jammy-one/repository/ros-one-checkerboard-detector_1.2.17-42-g7816812a-2025.01.06.11.07_amd64.deb) | 1.2.17-42-g7816812a-2025.01.06.11.07 | [:books:](https://raw.githubusercontent.com/k-okada/ros-o-overlay/check_jsk_recognition-jammy-one/repository/ros-one-checkerboard-detector_1.2.17-42-g7816812a-2025.01.06.11.07_amd64.files) | [:link:](https://github.com/ros-o/jsk_recognition/tree/obese-devel) |
| <a id="[imagesift](https://raw.githubusercontent.com/k-okada/ros-o-overlay/check_jsk_recognition-jammy-one/repository/ros-one-imagesift_1.2.17-42-g7816812a-2025.01.06.11.30_amd64.deb)" href="#[imagesift](https://raw.githubusercontent.com/k-okada/ros-o-overlay/check_jsk_recognition-jammy-one/repository/ros-one-imagesift_1.2.17-42-g7816812a-2025.01.06.11.30_amd64.deb)">:green_circle:</a> | [:green_book:](https://raw.githubusercontent.com/k-okada/ros-o-overlay/check_jsk_recognition-jammy-one/repository/imagesift_1.2.17-42-g7816812a-2025.01.06.11.30-bloom_generate.log) [:green_book:](https://raw.githubusercontent.com/k-okada/ros-o-overlay/check_jsk_recognition-jammy-one/repository/ros-one-imagesift_1.2.17-42-g7816812a-2025.01.06.11.30_amd64-2025-01-06T11:30:23Z.build) | [imagesift](https://raw.githubusercontent.com/k-okada/ros-o-overlay/check_jsk_recognition-jammy-one/repository/ros-one-imagesift_1.2.17-42-g7816812a-2025.01.06.11.30_amd64.deb) | 1.2.17-42-g7816812a-2025.01.06.11.30 | [:books:](https://raw.githubusercontent.com/k-okada/ros-o-overlay/check_jsk_recognition-jammy-one/repository/ros-one-imagesift_1.2.17-42-g7816812a-2025.01.06.11.30_amd64.files) | [:link:](https://github.com/ros-o/jsk_recognition/tree/obese-devel) |
| <a id="[jsk_pcl_ros](https://raw.githubusercontent.com/k-okada/ros-o-overlay/check_jsk_recognition-jammy-one/repository/ros-one-jsk-pcl-ros_1.2.17-42-g7816812a-2025.01.06.11.47_amd64.deb)" href="#[jsk_pcl_ros](https://raw.githubusercontent.com/k-okada/ros-o-overlay/check_jsk_recognition-jammy-one/repository/ros-one-jsk-pcl-ros_1.2.17-42-g7816812a-2025.01.06.11.47_amd64.deb)">:green_circle:</a> | [:green_book:](https://raw.githubusercontent.com/k-okada/ros-o-overlay/check_jsk_recognition-jammy-one/repository/jsk_pcl_ros_1.2.17-42-g7816812a-2025.01.06.11.47-bloom_generate.log) [:green_book:](https://raw.githubusercontent.com/k-okada/ros-o-overlay/check_jsk_recognition-jammy-one/repository/ros-one-jsk-pcl-ros_1.2.17-42-g7816812a-2025.01.06.11.47_amd64-2025-01-06T11:48:00Z.build) | [jsk_pcl_ros](https://raw.githubusercontent.com/k-okada/ros-o-overlay/check_jsk_recognition-jammy-one/repository/ros-one-jsk-pcl-ros_1.2.17-42-g7816812a-2025.01.06.11.47_amd64.deb) | 1.2.17-42-g7816812a-2025.01.06.11.47 | [:books:](https://raw.githubusercontent.com/k-okada/ros-o-overlay/check_jsk_recognition-jammy-one/repository/ros-one-jsk-pcl-ros_1.2.17-42-g7816812a-2025.01.06.11.47_amd64.files) | [:link:](https://github.com/ros-o/jsk_recognition/tree/obese-devel) |
| <a id="[jsk_pcl_ros_utils](https://raw.githubusercontent.com/k-okada/ros-o-overlay/check_jsk_recognition-jammy-one/repository/ros-one-jsk-pcl-ros-utils_1.2.17-42-g7816812a-2025.01.06.11.34_amd64.deb)" href="#[jsk_pcl_ros_utils](https://raw.githubusercontent.com/k-okada/ros-o-overlay/check_jsk_recognition-jammy-one/repository/ros-one-jsk-pcl-ros-utils_1.2.17-42-g7816812a-2025.01.06.11.34_amd64.deb)">:green_circle:</a> | [:green_book:](https://raw.githubusercontent.com/k-okada/ros-o-overlay/check_jsk_recognition-jammy-one/repository/jsk_pcl_ros_utils_1.2.17-42-g7816812a-2025.01.06.11.34-bloom_generate.log) [:green_book:](https://raw.githubusercontent.com/k-okada/ros-o-overlay/check_jsk_recognition-jammy-one/repository/ros-one-jsk-pcl-ros-utils_1.2.17-42-g7816812a-2025.01.06.11.34_amd64-2025-01-06T11:34:44Z.build) | [jsk_pcl_ros_utils](https://raw.githubusercontent.com/k-okada/ros-o-overlay/check_jsk_recognition-jammy-one/repository/ros-one-jsk-pcl-ros-utils_1.2.17-42-g7816812a-2025.01.06.11.34_amd64.deb) | 1.2.17-42-g7816812a-2025.01.06.11.34 | [:books:](https://raw.githubusercontent.com/k-okada/ros-o-overlay/check_jsk_recognition-jammy-one/repository/ros-one-jsk-pcl-ros-utils_1.2.17-42-g7816812a-2025.01.06.11.34_amd64.files) | [:link:](https://github.com/ros-o/jsk_recognition/tree/obese-devel) |
| <a id="[jsk_perception](https://raw.githubusercontent.com/k-okada/ros-o-overlay/check_jsk_recognition-jammy-one/repository/ros-one-jsk-perception_1.2.17-42-g7816812a-2025.01.06.11.15_amd64.deb)" href="#[jsk_perception](https://raw.githubusercontent.com/k-okada/ros-o-overlay/check_jsk_recognition-jammy-one/repository/ros-one-jsk-perception_1.2.17-42-g7816812a-2025.01.06.11.15_amd64.deb)">:green_circle:</a> | [:green_book:](https://raw.githubusercontent.com/k-okada/ros-o-overlay/check_jsk_recognition-jammy-one/repository/jsk_perception_1.2.17-42-g7816812a-2025.01.06.11.15-bloom_generate.log) [:green_book:](https://raw.githubusercontent.com/k-okada/ros-o-overlay/check_jsk_recognition-jammy-one/repository/ros-one-jsk-perception_1.2.17-42-g7816812a-2025.01.06.11.15_amd64-2025-01-06T11:15:40Z.build) | [jsk_perception](https://raw.githubusercontent.com/k-okada/ros-o-overlay/check_jsk_recognition-jammy-one/repository/ros-one-jsk-perception_1.2.17-42-g7816812a-2025.01.06.11.15_amd64.deb) | 1.2.17-42-g7816812a-2025.01.06.11.15 | [:books:](https://raw.githubusercontent.com/k-okada/ros-o-overlay/check_jsk_recognition-jammy-one/repository/ros-one-jsk-perception_1.2.17-42-g7816812a-2025.01.06.11.15_amd64.files) | [:link:](https://github.com/ros-o/jsk_recognition/tree/obese-devel) |
| <a id="[jsk_recognition](https://raw.githubusercontent.com/k-okada/ros-o-overlay/check_jsk_recognition-jammy-one/repository/ros-one-jsk-recognition_1.2.17-42-g7816812a-2025.01.06.11.01_amd64.deb)" href="#[jsk_recognition](https://raw.githubusercontent.com/k-okada/ros-o-overlay/check_jsk_recognition-jammy-one/repository/ros-one-jsk-recognition_1.2.17-42-g7816812a-2025.01.06.11.01_amd64.deb)">:green_circle:</a> | [:green_book:](https://raw.githubusercontent.com/k-okada/ros-o-overlay/check_jsk_recognition-jammy-one/repository/jsk_recognition_1.2.17-42-g7816812a-2025.01.06.11.01-bloom_generate.log) [:green_book:](https://raw.githubusercontent.com/k-okada/ros-o-overlay/check_jsk_recognition-jammy-one/repository/ros-one-jsk-recognition_1.2.17-42-g7816812a-2025.01.06.11.01_amd64-2025-01-06T11:01:56Z.build) | [jsk_recognition](https://raw.githubusercontent.com/k-okada/ros-o-overlay/check_jsk_recognition-jammy-one/repository/ros-one-jsk-recognition_1.2.17-42-g7816812a-2025.01.06.11.01_amd64.deb) | 1.2.17-42-g7816812a-2025.01.06.11.01 | [:books:](https://raw.githubusercontent.com/k-okada/ros-o-overlay/check_jsk_recognition-jammy-one/repository/ros-one-jsk-recognition_1.2.17-42-g7816812a-2025.01.06.11.01_amd64.files) | [:link:](https://github.com/ros-o/jsk_recognition/tree/obese-devel) |
| <a id="[jsk_recognition_msgs](https://raw.githubusercontent.com/k-okada/ros-o-overlay/check_jsk_recognition-jammy-one/repository/ros-one-jsk-recognition-msgs_1.2.17-42-g7816812a-2025.01.06.11.02_amd64.deb)" href="#[jsk_recognition_msgs](https://raw.githubusercontent.com/k-okada/ros-o-overlay/check_jsk_recognition-jammy-one/repository/ros-one-jsk-recognition-msgs_1.2.17-42-g7816812a-2025.01.06.11.02_amd64.deb)">:green_circle:</a> | [:green_book:](https://raw.githubusercontent.com/k-okada/ros-o-overlay/check_jsk_recognition-jammy-one/repository/jsk_recognition_msgs_1.2.17-42-g7816812a-2025.01.06.11.02-bloom_generate.log) [:green_book:](https://raw.githubusercontent.com/k-okada/ros-o-overlay/check_jsk_recognition-jammy-one/repository/ros-one-jsk-recognition-msgs_1.2.17-42-g7816812a-2025.01.06.11.02_amd64-2025-01-06T11:02:33Z.build) | [jsk_recognition_msgs](https://raw.githubusercontent.com/k-okada/ros-o-overlay/check_jsk_recognition-jammy-one/repository/ros-one-jsk-recognition-msgs_1.2.17-42-g7816812a-2025.01.06.11.02_amd64.deb) | 1.2.17-42-g7816812a-2025.01.06.11.02 | [:books:](https://raw.githubusercontent.com/k-okada/ros-o-overlay/check_jsk_recognition-jammy-one/repository/ros-one-jsk-recognition-msgs_1.2.17-42-g7816812a-2025.01.06.11.02_amd64.files) | [:link:](https://github.com/ros-o/jsk_recognition/tree/obese-devel) |
| <a id="[jsk_recognition_utils](https://raw.githubusercontent.com/k-okada/ros-o-overlay/check_jsk_recognition-jammy-one/repository/ros-one-jsk-recognition-utils_1.2.17-42-g7816812a-2025.01.06.11.09_amd64.deb)" href="#[jsk_recognition_utils](https://raw.githubusercontent.com/k-okada/ros-o-overlay/check_jsk_recognition-jammy-one/repository/ros-one-jsk-recognition-utils_1.2.17-42-g7816812a-2025.01.06.11.09_amd64.deb)">:green_circle:</a> | [:green_book:](https://raw.githubusercontent.com/k-okada/ros-o-overlay/check_jsk_recognition-jammy-one/repository/jsk_recognition_utils_1.2.17-42-g7816812a-2025.01.06.11.09-bloom_generate.log) [:green_book:](https://raw.githubusercontent.com/k-okada/ros-o-overlay/check_jsk_recognition-jammy-one/repository/ros-one-jsk-recognition-utils_1.2.17-42-g7816812a-2025.01.06.11.09_amd64-2025-01-06T11:09:30Z.build) | [jsk_recognition_utils](https://raw.githubusercontent.com/k-okada/ros-o-overlay/check_jsk_recognition-jammy-one/repository/ros-one-jsk-recognition-utils_1.2.17-42-g7816812a-2025.01.06.11.09_amd64.deb) | 1.2.17-42-g7816812a-2025.01.06.11.09 | [:books:](https://raw.githubusercontent.com/k-okada/ros-o-overlay/check_jsk_recognition-jammy-one/repository/ros-one-jsk-recognition-utils_1.2.17-42-g7816812a-2025.01.06.11.09_amd64.files) | [:link:](https://github.com/ros-o/jsk_recognition/tree/obese-devel) |
| <a id="[jsk_topic_tools](https://raw.githubusercontent.com/k-okada/ros-o-overlay/check_jsk_recognition-jammy-one/repository/ros-one-jsk-topic-tools_2.2.16-1-2025.01.06.11.03_amd64.deb)" href="#[jsk_topic_tools](https://raw.githubusercontent.com/k-okada/ros-o-overlay/check_jsk_recognition-jammy-one/repository/ros-one-jsk-topic-tools_2.2.16-1-2025.01.06.11.03_amd64.deb)">:green_circle:</a> | [:green_book:](https://raw.githubusercontent.com/k-okada/ros-o-overlay/check_jsk_recognition-jammy-one/repository/jsk_topic_tools_2.2.16-1-2025.01.06.11.03-bloom_generate.log) [:green_book:](https://raw.githubusercontent.com/k-okada/ros-o-overlay/check_jsk_recognition-jammy-one/repository/ros-one-jsk-topic-tools_2.2.16-1-2025.01.06.11.03_amd64-2025-01-06T11:04:04Z.build) | [jsk_topic_tools](https://raw.githubusercontent.com/k-okada/ros-o-overlay/check_jsk_recognition-jammy-one/repository/ros-one-jsk-topic-tools_2.2.16-1-2025.01.06.11.03_amd64.deb) | 2.2.16-1-2025.01.06.11.03 | [:books:](https://raw.githubusercontent.com/k-okada/ros-o-overlay/check_jsk_recognition-jammy-one/repository/ros-one-jsk-topic-tools_2.2.16-1-2025.01.06.11.03_amd64.files) | [:link:](https://github.com/tork-a/jsk_common-release/tree/HEAD) |
| <a id="[libsiftfast](https://raw.githubusercontent.com/k-okada/ros-o-overlay/check_jsk_recognition-jammy-one/repository/ros-one-libsiftfast_2.1.29-1-2025.01.06.11.28_amd64.deb)" href="#[libsiftfast](https://raw.githubusercontent.com/k-okada/ros-o-overlay/check_jsk_recognition-jammy-one/repository/ros-one-libsiftfast_2.1.29-1-2025.01.06.11.28_amd64.deb)">:green_circle:</a> | [:green_book:](https://raw.githubusercontent.com/k-okada/ros-o-overlay/check_jsk_recognition-jammy-one/repository/libsiftfast_2.1.29-1-2025.01.06.11.28-bloom_generate.log) [:green_book:](https://raw.githubusercontent.com/k-okada/ros-o-overlay/check_jsk_recognition-jammy-one/repository/ros-one-libsiftfast_2.1.29-1-2025.01.06.11.28_amd64-2025-01-06T11:28:28Z.build) | [libsiftfast](https://raw.githubusercontent.com/k-okada/ros-o-overlay/check_jsk_recognition-jammy-one/repository/ros-one-libsiftfast_2.1.29-1-2025.01.06.11.28_amd64.deb) | 2.1.29-1-2025.01.06.11.28 | [:books:](https://raw.githubusercontent.com/k-okada/ros-o-overlay/check_jsk_recognition-jammy-one/repository/ros-one-libsiftfast_2.1.29-1-2025.01.06.11.28_amd64.files) | [:link:](https://github.com/tork-a/jsk_3rdparty-release/tree/HEAD) |
| <a id="[resized_image_transport](https://raw.githubusercontent.com/k-okada/ros-o-overlay/check_jsk_recognition-jammy-one/repository/ros-one-resized-image-transport_1.2.17-42-g7816812a-2025.01.06.12.12_amd64.deb)" href="#[resized_image_transport](https://raw.githubusercontent.com/k-okada/ros-o-overlay/check_jsk_recognition-jammy-one/repository/ros-one-resized-image-transport_1.2.17-42-g7816812a-2025.01.06.12.12_amd64.deb)">:green_circle:</a> | [:green_book:](https://raw.githubusercontent.com/k-okada/ros-o-overlay/check_jsk_recognition-jammy-one/repository/resized_image_transport_1.2.17-42-g7816812a-2025.01.06.12.12-bloom_generate.log) [:green_book:](https://raw.githubusercontent.com/k-okada/ros-o-overlay/check_jsk_recognition-jammy-one/repository/ros-one-resized-image-transport_1.2.17-42-g7816812a-2025.01.06.12.12_amd64-2025-01-06T12:12:20Z.build) | [resized_image_transport](https://raw.githubusercontent.com/k-okada/ros-o-overlay/check_jsk_recognition-jammy-one/repository/ros-one-resized-image-transport_1.2.17-42-g7816812a-2025.01.06.12.12_amd64.deb) | 1.2.17-42-g7816812a-2025.01.06.12.12 | [:books:](https://raw.githubusercontent.com/k-okada/ros-o-overlay/check_jsk_recognition-jammy-one/repository/ros-one-resized-image-transport_1.2.17-42-g7816812a-2025.01.06.12.12_amd64.files) | [:link:](https://github.com/ros-o/jsk_recognition/tree/obese-devel) |
| <a id="[sound_classification](https://raw.githubusercontent.com/k-okada/ros-o-overlay/check_jsk_recognition-jammy-one/repository/ros-one-sound-classification_1.2.17-42-g7816812a-2025.01.06.12.15_amd64.deb)" href="#[sound_classification](https://raw.githubusercontent.com/k-okada/ros-o-overlay/check_jsk_recognition-jammy-one/repository/ros-one-sound-classification_1.2.17-42-g7816812a-2025.01.06.12.15_amd64.deb)">:green_circle:</a> | [:green_book:](https://raw.githubusercontent.com/k-okada/ros-o-overlay/check_jsk_recognition-jammy-one/repository/sound_classification_1.2.17-42-g7816812a-2025.01.06.12.15-bloom_generate.log) [:green_book:](https://raw.githubusercontent.com/k-okada/ros-o-overlay/check_jsk_recognition-jammy-one/repository/ros-one-sound-classification_1.2.17-42-g7816812a-2025.01.06.12.15_amd64-2025-01-06T12:15:48Z.build) | [sound_classification](https://raw.githubusercontent.com/k-okada/ros-o-overlay/check_jsk_recognition-jammy-one/repository/ros-one-sound-classification_1.2.17-42-g7816812a-2025.01.06.12.15_amd64.deb) | 1.2.17-42-g7816812a-2025.01.06.12.15 | [:books:](https://raw.githubusercontent.com/k-okada/ros-o-overlay/check_jsk_recognition-jammy-one/repository/ros-one-sound-classification_1.2.17-42-g7816812a-2025.01.06.12.15_amd64.files) | [:link:](https://github.com/ros-o/jsk_recognition/tree/obese-devel) |

## Top Offenders (broken packages)

|   | Logs | Package | Version | Files | Upstream |
| - | ---- | ------- | ------- | ----- | -------- |
