
![](https://raw.githubusercontent.com/slightech/MYNT-EYE-SDK/master/mynteye.png)

[Google Drive]: https://drive.google.com/drive/folders/1rz7swzOp9zp7Xty-o2cJzLgFYnC71WQZ
[百度网盘]: https://pan.baidu.com/s/1i5REqVz

# MYNT EYE SDK

![](https://img.shields.io/badge/MYNT%20EYE%20SDK-Release%201.7-brightgreen.svg?style=flat)

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

> [User Manual PDF](https://github.com/slightech/MYNT-EYE-SDK/raw/master/doc/mynteye-apidoc-1.7.pdf)

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

Please use "25 fps 500 Hz" firmware that is more suitable for these projects.

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

The introduction of firmwares is [here](https://github.com/slightech/MYNT-EYE-SDK/tree/master/firmware). If run with SLAM, "25 fps 500 Hz" is more suitable.

> All firmwares are stored in `firmware` directory of our online disks: [Google Drive][], [百度网盘][].

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

### Release 1.7

<table>
  <tr>
    <td colspan="3">Platform</td>
    <td>Package Size</td>
    <td>MD5 Checksum</td>
  </tr>
  <tr>
    <td rowspan="4">Linux</td>
    <td rowspan="2">GCC4</td>
    <td>mynteye-1.7-linux-x64-gcc4-opencv-3.2.0.tar.gz</td>
    <td>23.81 MB</td>
    <td>8ef8e2ab53a51627a9bb6cd508c69c5e</td>
  </tr>
  <tr>
    <td>mynteye-1.7-linux-x64-gcc4-opencv-2.4.13.3.tar.gz</td>
    <td>23.81 MB</td>
    <td>1bb9cbdf926db137b0ed3b49ed5ca91a</td>
  </tr>
  <tr>
    <td rowspan="2">GCC5</td>
    <td>mynteye-1.7-linux-x64-gcc5-opencv-3.2.0.tar.gz</td>
    <td>23.93 MB</td>
    <td>6c0693306f55f13e492ff13793f678f0</td>
  </tr>
  <tr>
    <td>mynteye-1.7-linux-x64-gcc5-opencv-2.4.13.3.tar.gz</td>
    <td>23.94 MB</td>
    <td>867eb5a8b04e7c602334df69bbe7c3c5</td>
  </tr>
  <tr>
    <td rowspan="2">macOS</td>
    <td rowspan="2"></td>
    <td>mynteye-1.7-mac-x64-opencv-3.2.0.tar.gz</td>
    <td>18.26 MB</td>
    <td>e647b92d4fcefb4d5659f39b301ad7c5</td>
  </tr>
  <tr>
    <td>mynteye-1.7-mac-x64-opencv-2.4.13.3.tar.gz</td>
    <td>18.24 MB</td>
    <td>e49b433c08be59e604d7b0191984f070</td>
  </tr>
  <tr>
    <td rowspan="2">Windows</td>
    <td rowspan="2">MSVC</td>
    <td>mynteye-1.7-win-x64-opencv-3.2.0.exe</td>
    <td>44.73 MB</td>
    <td>213dc75dd35281fba282181817ae5567</td>
  </tr>
  <tr>
    <td>mynteye-1.7-win-x64-opencv-3.2.0.tar.gz</td>
    <td>44.21 MB</td>
    <td>279ef04dc49bef23c70179ce105ab423</td>
  </tr>
  <tr>
    <td rowspan="2">Tegra</td>
    <td rowspan="2">TX1/TX2</td>
    <td>mynteye-1.7-tegra-aarch64-gcc5-opencv-3.2.0.tar.gz</td>
    <td>2.38 MB</td>
    <td>111b3b6300739c51ab0d3d9d35c8c2e7</td>
  </tr>
  <tr>
    <td>mynteye-1.7-tegra-aarch64-gcc5-opencv-2.4.13.1.tar.gz</td>
    <td>2.38 MB</td>
    <td>2767c79b6f8c4ae84433b5a93cebbe8f</td>
  </tr>
</table>

## Mirrors

国内镜像：[码云](https://gitee.com/mynt/MYNT-EYE-SDK)。
