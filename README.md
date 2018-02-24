
![](https://raw.githubusercontent.com/slightech/MYNT-EYE-SDK/master/mynteye.png)

[Google Drive]: https://drive.google.com/drive/folders/1rz7swzOp9zp7Xty-o2cJzLgFYnC71WQZ
[百度网盘]: https://pan.baidu.com/s/1i5REqVz

# MYNT EYE SDK

![](https://img.shields.io/badge/MYNT%20EYE%20SDK-Release%201.8-brightgreen.svg?style=flat)

## [Documentation](https://slightech.github.io/MYNT-EYE-SDK)

* [SDK Introduction](https://slightech.github.io/MYNT-EYE-SDK/index.html)
* [Getting Started](https://slightech.github.io/MYNT-EYE-SDK/getting_started.html)
* [Tutorials](https://slightech.github.io/MYNT-EYE-SDK/tutorials.html)
    - [How to calibrate camera with OpenCV](https://slightech.github.io/MYNT-EYE-SDK/calibrate_with_opencv.html)
    - [How to calibrate camera and IMU with Kalibr](https://slightech.github.io/MYNT-EYE-SDK/calibrate_with_kalibr.html)
    - [How to upgrade firmware](https://slightech.github.io/MYNT-EYE-SDK/upgrade_firmware.html)
* [API Documentation](https://slightech.github.io/MYNT-EYE-SDK/annotated.html)
* [FAQ & Issues](https://slightech.github.io/MYNT-EYE-SDK/faq.html)
* [Release Notes](https://slightech.github.io/MYNT-EYE-SDK/release_notes.html)
* [Appendix: Build Platforms](https://slightech.github.io/MYNT-EYE-SDK/appendix_build_platforms.html)
* [Appendix: Test Results](https://slightech.github.io/MYNT-EYE-SDK/appendix_test_results.html)

> [User Manual PDF](https://github.com/slightech/MYNT-EYE-SDK/raw/master/doc/mynteye-apidoc-1.8.pdf)

Download the latest SDK from our online disks: [Google Drive][], [百度网盘][].

> About the SDK packages, please see "[Archives](https://github.com/slightech/MYNT-EYE-SDK#archives)" section.

Then extract the SDK and follow the "README" in the folder to setup it, or follow these online docs:

* [Getting Started on Linux](https://slightech.github.io/MYNT-EYE-SDK/getting_started_linux.html)
* [Getting Started on macOS](https://slightech.github.io/MYNT-EYE-SDK/getting_started_mac.html)
* [Getting Started on Windows (MSVC)](https://slightech.github.io/MYNT-EYE-SDK/getting_started_win.html)
* [Getting Started on Tegra (TX1, TX2)](https://slightech.github.io/MYNT-EYE-SDK/getting_started_tegra.html)

## Samples

Samples about how to use MYNT EYE camera in some popular projects.

* [MYNT-EYE-OKVIS-Sample](https://github.com/slightech/MYNT-EYE-OKVIS-Sample)
* [MYNT-EYE-ORB-SLAM2-Sample](https://github.com/slightech/MYNT-EYE-ORB-SLAM2-Sample)
* [MYNT-EYE-VINS-Sample](https://github.com/slightech/MYNT-EYE-VINS-Sample)
* [MYNT-EYE-VIORB-Sample](https://github.com/slightech/MYNT-EYE-VIORB-Sample)

Please use "25 fps 500 Hz" settings which is more suitable for these projects.

### Videos

<a href="https://www.youtube.com/embed/MB3Fxkj32a8" target="_blank"><img src="http://img.youtube.com/vi/MB3Fxkj32a8/0.jpg"
alt="mynt-eye-okvis-sample" width="240" height="180" border="10" /></a>
<a href="https://www.youtube.com/embed/Z9K0L5jiVYY" target="_blank"><img src="http://img.youtube.com/vi/Z9K0L5jiVYY/0.jpg"
alt="mynt-eye-orbslam2-sample" width="240" height="180" border="10" /></a>
<a href="https://www.youtube.com/embed/yLm2m2P6-a4" target="_blank"><img src="http://img.youtube.com/vi/yLm2m2P6-a4/0.jpg"
alt="mynt-eye-vins-sample" width="240" height="180" border="10" /></a>

> Video links for mainland China: [Video1](https://v.qq.com/x/page/z0555rye6zq.html) [Video2](https://v.qq.com/x/page/z0555wwlot3.html) [Video3](https://v.qq.com/x/page/g05558aekb1.html).

## Integrations

Integrations let you use the MYNT EYE camera in some different environments.

* [MYNT-EYE-ROS-Wrapper](https://github.com/slightech/MYNT-EYE-ROS-Wrapper)

## [Firmwares](https://github.com/slightech/MYNT-EYE-SDK/tree/master/firmware)

The introduction of firmwares is [here](https://github.com/slightech/MYNT-EYE-SDK/tree/master/firmware). Please keep updating the latest version firmware for the best result.

> All firmwares are stored in `firmware` directory of our online disks: [Google Drive][], [百度网盘][].

## 3D Models

* Product Case for 3D Printing
    - mynt_eye_s_no_ir_case_v1.stp.stl

> All 3D models are stored in `3dmodel` directory of our online disks: [Google Drive][], [百度网盘][].

## Archives

This section lists archived and obsolete versions of the MYNT EYE SDK.

> All packages of SDK are stored in our online disks: [Google Drive][], [百度网盘][].

On Linux, please download the SDK with the consistent version of GCC, because GCC 5 uses a new ABI by default (see [here](https://gcc.gnu.org/gcc-5/changes.html#libstdcxx)). You can run `gcc --version` to see your GCC version.

Here are missing things on some platforms, marked with `N/A`.

<table>
  <tr>
    <td rowspan="2" colspan="2">Platform</td>
    <td rowspan="2">Apps</td>
    <td colspan="2">Features</td>
  </tr>
  <tr>
    <td>CPU</td>
    <td>CUDA</td>
  </tr>
  <tr>
    <td>Tegra</td>
    <td>TX1/TX2</td>
    <td>N/A</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>Linux</td>
    <td>AArch64</td>
    <td>N/A</td>
    <td></td>
    <td>N/A</td>
  </tr>
</table>

### Release 1.8

<table>
  <tr>
    <td colspan="3">Platform</td>
    <td>Package Size</td>
    <td>MD5 Checksum</td>
  </tr>
  <tr>
    <td rowspan="5">Linux</td>
    <td rowspan="2">GCC4</td>
    <td>mynteye-1.8-linux-x64-gcc4-opencv-3.4.0.tar.gz</td>
    <td>24.1 MB</td>
    <td>7ee313d8ad9ae93a248c9e98a4a491c9</td>
  </tr>
  <tr>
    <td>mynteye-1.8-linux-x64-gcc4-opencv-2.4.13.5.tar.gz</td>
    <td>24.11 MB</td>
    <td>baf046f6f0119d801de515c8654445d6</td>
  </tr>
  <tr>
    <td rowspan="3">GCC5</td>
    <td>mynteye-1.8-linux-x64-gcc5-opencv-3.4.0.tar.gz</td>
    <td>24.22 MB</td>
    <td>a2e62563faa5928efba4e4e89bfaac5c</td>
  </tr>
  <tr>
    <td>mynteye-1.8-linux-x64-gcc5-opencv-2.4.13.5.tar.gz</td>
    <td>24.23 MB</td>
    <td>26a951206efd67f53e642ccda464b881</td>
  </tr>
  <tr>
    <td>mynteye-1.8-linux-x64-gcc5-opencv-3.3.1-ros-kinetic.tar.gz</td>
    <td>2.9 MB</td>
    <td>5065f625bff207651f07ce9c0e708b72</td>
  </tr>
  <tr>
    <td rowspan="2">macOS</td>
    <td rowspan="2"></td>
    <td>mynteye-1.8-mac-x64-opencv-3.4.0.tar.gz</td>
    <td>18.29 MB</td>
    <td>8658180bfcdd664403886776b06058ec</td>
  </tr>
  <tr>
    <td>mynteye-1.8-mac-x64-opencv-2.4.13.5.tar.gz</td>
    <td>18.28 MB</td>
    <td>eeec67da3dbc9af460fb63defbf934ed</td>
  </tr>
  <tr>
    <td rowspan="2">Windows</td>
    <td rowspan="2">MSVC</td>
    <td>mynteye-1.8-win-x64-opencv-3.4.0.exe</td>
    <td>54.77 MB</td>
    <td>bf2a7c31848642163440a3230e8e8749</td>
  </tr>
  <tr>
    <td>mynteye-1.8-win-x64-opencv-3.4.0.tar.gz</td>
    <td>54.27 MB</td>
    <td>ec3230cf99bc562a78f0524e271a8838</td>
  </tr>
  <tr>
    <td rowspan="3">Tegra</td>
    <td rowspan="3">TX1/TX2</td>
    <td>mynteye-1.8-tegra-aarch64-gcc5-opencv-3.4.0.tar.gz</td>
    <td>2.67 MB</td>
    <td>1ca9e0ab562747d3ae259f36b9c9a932</td>
  </tr>
  <tr>
    <td>mynteye-1.8-tegra-aarch64-gcc5-opencv-2.4.13.1.tar.gz</td>
    <td>2.68 MB</td>
    <td>51e58103fd3d003a3c713e897906d344</td>
  </tr>
  <tr>
    <td>mynteye-1.8-tegra-aarch64-gcc5-opencv-3.3.1-ros-kinetic.tar.gz</td>
    <td>2.67 MB</td>
    <td>1c96f964fa575b55d2d253bc73014395</td>
  </tr>
</table>

## Mirrors

国内镜像：[码云](https://gitee.com/mynt/MYNT-EYE-SDK)。
