
![](https://raw.githubusercontent.com/slightech/MYNT-EYE-SDK/master/mynteye.png)

[Google Drive]: https://drive.google.com/drive/folders/1rz7swzOp9zp7Xty-o2cJzLgFYnC71WQZ
[百度网盘]: https://pan.baidu.com/s/1i5REqVz

# MYNT EYE SDK

![](https://img.shields.io/badge/MYNT%20EYE%20SDK-Release%201.7-brightgreen.svg?style=flat)

## [Getting Started](https://slightech.github.io/MYNT-EYE-SDK/getting_started.html)

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

> [PDF](https://github.com/slightech/MYNT-EYE-SDK/raw/master/doc/mynteye-apidoc-1.7.pdf)

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

### Release 1.6

<table>
  <tr>
    <td colspan="3">Platform</td>
    <td>Package Size</td>
    <td>MD5 Checksum</td>
  </tr>
  <tr>
    <td rowspan="4">Linux</td>
    <td rowspan="2">GCC4</td>
    <td>mynteye-1.6-linux-x64-gcc4-opencv-3.2.0.tar.gz</td>
    <td>23.79 MB</td>
    <td>0a5dc74c903719899f5db977d2e5d075</td>
  </tr>
  <tr>
    <td>mynteye-1.6-linux-x64-gcc4-opencv-2.4.13.3.tar.gz</td>
    <td>23.8 MB</td>
    <td>73f38465e82c4711d6f95c9992f41e7b</td>
  </tr>
  <tr>
    <td rowspan="2">GCC5</td>
    <td>mynteye-1.6-linux-x64-gcc5-opencv-3.2.0.tar.gz</td>
    <td>23.92 MB</td>
    <td>39cec10adf2a74ebefa76f72fe069c6d</td>
  </tr>
  <tr>
    <td>mynteye-1.6-linux-x64-gcc5-opencv-2.4.13.3.tar.gz</td>
    <td>23.92 MB</td>
    <td>a5e99cac5979179a3cde8ff68a91b01e</td>
  </tr>
  <tr>
    <td rowspan="2">macOS</td>
    <td rowspan="2"></td>
    <td>mynteye-1.6-mac-x64-opencv-3.2.0.tar.gz</td>
    <td>18.25 MB</td>
    <td>5aa640b2abe8aa1e2a3fc24a70b6a5db</td>
  </tr>
  <tr>
    <td>mynteye-1.6-mac-x64-opencv-2.4.13.3.tar.gz</td>
    <td>18.24 MB</td>
    <td>fbb1cc7a4fc67e1506988aa9293166b7</td>
  </tr>
  <tr>
    <td rowspan="2">Windows</td>
    <td rowspan="2">MSVC</td>
    <td>mynteye-1.6-win-x64-opencv-3.2.0.exe</td>
    <td>44.73 MB</td>
    <td>9d96115e6786bb5da34426629121b2fe</td>
  </tr>
  <tr>
    <td>mynteye-1.6-win-x64-opencv-3.2.0.tar.gz</td>
    <td>44.22 MB</td>
    <td>2e082ea8b93802ac2b1ab0ce878db466</td>
  </tr>
  <tr>
    <td rowspan="2">Tegra</td>
    <td rowspan="2">TX1/TX2</td>
    <td>mynteye-1.6-tegra-aarch64-gcc5-opencv-3.2.0.tar.gz</td>
    <td>2.37 MB</td>
    <td>c494cd29f354d32fa0e7f2a014cc8942</td>
  </tr>
  <tr>
    <td>mynteye-1.6-tegra-aarch64-gcc5-opencv-2.4.13.1.tar.gz</td>
    <td>2.37 MB</td>
    <td>6ce9c22a20d290266941a67e352f4666</td>
  </tr>
</table>

### Release 1.5

<table>
  <tr>
    <td colspan="3">Platform</td>
    <td>Package Size</td>
    <td>MD5 Checksum</td>
  </tr>
  <tr>
    <td rowspan="4">Linux</td>
    <td rowspan="2">GCC4</td>
    <td>mynteye-1.5-linux-x64-gcc4-opencv-3.2.0.tar.gz</td>
    <td>27.93 MB</td>
    <td>d50b0f0becc8fb9291aa6944092aac64</td>
  </tr>
  <tr>
    <td>mynteye-1.5-linux-x64-gcc4-opencv-2.4.13.3.tar.gz</td>
    <td>27.94 MB</td>
    <td>5a3c31c7c586fe1b7568f87a49321b8c</td>
  </tr>
  <tr>
    <td rowspan="2">GCC5</td>
    <td>mynteye-1.5-linux-x64-gcc5-opencv-3.2.0.tar.gz</td>
    <td>27.97 MB</td>
    <td>af4f36d8a6d7c02aa04654f918eeef1c</td>
  </tr>
  <tr>
    <td>mynteye-1.5-linux-x64-gcc5-opencv-2.4.13.3.tar.gz</td>
    <td>27.97 MB</td>
    <td>29d719034cfae5cd971901ad1cb9eb18</td>
  </tr>
  <tr>
    <td rowspan="2">macOS</td>
    <td rowspan="2"></td>
    <td>mynteye-1.5-mac-x64-opencv-3.2.0.tar.gz</td>
    <td>17.49 MB</td>
    <td>4f148b1def28377e5366ebbd1ea7c42e</td>
  </tr>
  <tr>
    <td>mynteye-1.5-mac-x64-opencv-2.4.13.3.tar.gz</td>
    <td>17.47 MB</td>
    <td>29c32ea7367b57136037d6a5fb14c785</td>
  </tr>
  <tr>
    <td rowspan="2">Windows</td>
    <td rowspan="2">MSVC</td>
    <td>mynteye-1.5-win-x64-opencv-3.2.0.exe</td>
    <td>43.99 MB</td>
    <td>8b4c6d13d66a56f6effb9b8c6e9ca8b2</td>
  </tr>
  <tr>
    <td>mynteye-1.5-win-x64-opencv-3.2.0.tar.gz</td>
    <td>43.48 MB</td>
    <td>d03d91a004a8e091e8a09b6b7157cad7</td>
  </tr>
  <tr>
    <td rowspan="2">Tegra</td>
    <td rowspan="2">TX1/TX2</td>
    <td>mynteye-1.5-tegra-aarch64-gcc5-opencv-3.2.0.tar.gz</td>
    <td>5.98 MB</td>
    <td>e6be07ea9a61d2cc2481dbf6ad300733</td>
  </tr>
  <tr>
    <td>mynteye-1.5-tegra-aarch64-gcc5-opencv-2.4.13.1.tar.gz</td>
    <td>5.98 MB</td>
    <td>a4e6d108ff826b4e605b6d1adefc3b21</td>
  </tr>
</table>

### Release 1.4

<table>
  <tr>
    <td colspan="3">Platform</td>
    <td>Package Size</td>
    <td>MD5 Checksum</td>
  </tr>
  <tr>
    <td rowspan="4">Linux</td>
    <td rowspan="2">GCC4</td>
    <td>mynteye-1.4-linux-x64-gcc4-opencv-3.2.0.tar.gz</td>
    <td>27.37 MB</td>
    <td>3fd956808f2de50b1e88a6dc168acaec</td>
  </tr>
  <tr>
    <td>mynteye-1.4-linux-x64-gcc4-opencv-2.4.13.3.tar.gz</td>
    <td>27.37 MB</td>
    <td>00f61690fbb1a2eed4b3a0681c723b66</td>
  </tr>
  <tr>
    <td rowspan="2">GCC5</td>
    <td>mynteye-1.4-linux-x64-gcc5-opencv-3.2.0.tar.gz</td>
    <td>27.4 MB</td>
    <td>4b3afeb551fbed0983f9f1b06eb87ff6</td>
  </tr>
  <tr>
    <td>mynteye-1.4-linux-x64-gcc5-opencv-2.4.13.3.tar.gz</td>
    <td>27.4 MB</td>
    <td>6e1db5b30280f7162a86a066e219f6a1</td>
  </tr>
  <tr>
    <td rowspan="2">macOS</td>
    <td rowspan="2"></td>
    <td>mynteye-1.4-mac-x64-opencv-3.2.0.tar.gz</td>
    <td>16.92 MB</td>
    <td>7a491ca23e66f56c4130de7993e49881</td>
  </tr>
  <tr>
    <td>mynteye-1.4-mac-x64-opencv-2.4.13.3.tar.gz</td>
    <td>16.91 MB</td>
    <td>7c8a4cfd1dd1622c37419cd3797d3da9</td>
  </tr>
  <tr>
    <td rowspan="2">Windows</td>
    <td rowspan="2">MSVC</td>
    <td>mynteye-1.4-win-x64-opencv-3.2.0.exe</td>
    <td>43.33 MB</td>
    <td>50c32be46b7c8129c974fb6fe4dbae3d</td>
  </tr>
  <tr>
    <td>mynteye-1.4-win-x64-opencv-3.2.0.tar.gz</td>
    <td>42.81 MB</td>
    <td>cc7380e8ead643c5f01d21ddd87e35c1</td>
  </tr>
  <tr>
    <td rowspan="2">Tegra</td>
    <td rowspan="2">TX1/TX2</td>
    <td>mynteye-1.4-tegra-aarch64-gcc5-opencv-3.2.0.tar.gz</td>
    <td>5.41 MB</td>
    <td>bb8b8be6f941cf7c0b310e562a7f4f54</td>
  </tr>
  <tr>
    <td>mynteye-1.4-tegra-aarch64-gcc5-opencv-2.4.13.1.tar.gz</td>
    <td>5.42 MB</td>
    <td>e56ff71b93da527f18e7423d5ed4db1b</td>
  </tr>
</table>

### Release 1.3

<table>
  <tr>
    <td colspan="3">Platform</td>
    <td>Package Size</td>
    <td>MD5 Checksum</td>
  </tr>
  <tr>
    <td rowspan="2">Linux</td>
    <td>GCC4</td>
    <td>mynteye-1.3-linux-x64-gcc4.tar.gz</td>
    <td>27.31 MB</td>
    <td>dad4dc41a206e31a35f382af87f0c2f9</td>
  </tr>
  <tr>
    <td>GCC5</td>
    <td>mynteye-1.3-linux-x64-gcc5.tar.gz</td>
    <td>27.34 MB</td>
    <td>51ef7e0027a9d8ea789bd46f5e39a83c</td>
  </tr>
  <tr>
    <td>macOS</td>
    <td></td>
    <td>mynteye-1.3-mac-x64.tar.gz</td>
    <td>16.86 MB</td>
    <td>64a761df96b923115f3bc2d3bbd39b86</td>
  </tr>
  <tr>
    <td>Windows</td>
    <td>MSVC</td>
    <td>mynteye-1.3-win-x64.tar.gz</td>
    <td>42.83 MB</td>
    <td>38608f0749eb63be562590236ed445ea</td>
  </tr>
  <tr>
    <td>Tegra</td>
    <td>TX1/TX2</td>
    <td>mynteye-1.3-tegra-aarch64-gcc5.tar.gz</td>
    <td>5.34 MB</td>
    <td>de9449fa3debf23e764e8367706b47cc</td>
  </tr>
</table>

### Release 1.2

<table>
  <tr>
    <td colspan="3">Platform</td>
    <td>Package Size</td>
    <td>MD5 Checksum</td>
  </tr>
  <tr>
    <td rowspan="2">Linux</td>
    <td>GCC4</td>
    <td>mynteye-1.2-linux-x64-gcc4.tar.gz</td>
    <td>27.3 MB</td>
    <td>6802f5ef5b3fb8215a6cbad8489cb058</td>
  </tr>
  <tr>
    <td>GCC5</td>
    <td>mynteye-1.2-linux-x64-gcc5.tar.gz</td>
    <td>27.33 MB</td>
    <td>b38195ea9ead0295b996dffe81009066</td>
  </tr>
  <tr>
    <td>macOS</td>
    <td></td>
    <td>mynteye-1.2-mac-x64.tar.gz</td>
    <td>16.84 MB</td>
    <td>825e0de83fa8c05920394827b2699b9e</td>
  </tr>
  <tr>
    <td>Windows</td>
    <td>MSVC</td>
    <td>mynteye-1.2-win-x64.tar.gz</td>
    <td>42.81 MB</td>
    <td>be132fdcd9d0645389f0ba3a35445588</td>
  </tr>
  <tr>
    <td>Tegra</td>
    <td>TX1/TX2</td>
    <td>mynteye-1.2-tegra-aarch64-gcc5.tar.gz</td>
    <td>5.33 MB</td>
    <td>a65850988a9e7ce7ddcc2a7ec7160a6d</td>
  </tr>
  <tr>
    <td>Linux</td>
    <td>AArch64<br/>GCC5</td>
    <td>mynteye-1.2-linux-aarch64-gcc5.tar.gz</td>
    <td>5.27 MB</td>
    <td>b07dccd6b45e9eaddf00993d3fa205cd</td>
  </tr>
</table>

### Release 1.1

<table>
  <tr>
    <td colspan="3">Platform</td>
    <td>Package Size</td>
    <td>MD5 Checksum</td>
  </tr>
  <tr>
    <td rowspan="2">Linux</td>
    <td>GCC4</td>
    <td>mynteye-1.1-linux-x64-gcc4.tar.gz</td>
    <td>27.28 MB</td>
    <td>2733b307330fc49b4b26ae75a6abbadd</td>
  </tr>
  <tr>
    <td>GCC5</td>
    <td>mynteye-1.1-linux-x64-gcc5.tar.gz</td>
    <td>27.32 MB</td>
    <td>e6f6cc0e223bc99ecf2ef82e83c12edf</td>
  </tr>
  <tr>
    <td>macOS</td>
    <td></td>
    <td>mynteye-1.1-mac-x64.tar.gz</td>
    <td>16.83 MB</td>
    <td>e2e7971d918b430545b5b73bf65c02ce</td>
  </tr>
  <tr>
    <td>Windows</td>
    <td>MSVC</td>
    <td>mynteye-1.1-win-x64.tar.gz</td>
    <td>42.81 MB</td>
    <td>a96cba813670c9ea31ae1723113ad444</td>
  </tr>
</table>

### Release 1.0

<table>
  <tr>
    <td colspan="3">Platform</td>
    <td>Package Size</td>
    <td>MD5 Checksum</td>
  </tr>
  <tr>
    <td rowspan="2">Linux</td>
    <td>GCC4</td>
    <td>mynteye-1.0-linux-x64-gcc4.tar.gz</td>
    <td>27.26 MB</td>
    <td>84184f75f5ca8970ed446abc6287bdbe</td>
  </tr>
  <tr>
    <td>GCC5</td>
    <td>mynteye-1.0-linux-x64-gcc5.tar.gz</td>
    <td>27.22 MB</td>
    <td>efe3f9bd1e8fb9054933399d42971ce6</td>
  </tr>
  <tr>
    <td>macOS</td>
    <td></td>
    <td>mynteye-1.0-mac-x64.tar.gz</td>
    <td>16.82 MB</td>
    <td>e43a0b429681236134515e5add1e7702</td>
  </tr>
</table>

## Mirrors

国内镜像：[码云](https://gitee.com/mynt/MYNT-EYE-SDK)。
