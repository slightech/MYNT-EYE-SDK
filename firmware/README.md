
[Google Drive]: https://drive.google.com/drive/folders/1rz7swzOp9zp7Xty-o2cJzLgFYnC71WQZ
[百度网盘]: https://pan.baidu.com/s/1i5REqVz

# Firmwares

> All firmwares are stored in `firmware` directory of our online disks: [Google Drive][], [百度网盘][].

About how to upgrade firmware, please see [Tutorials](https://slightech.github.io/MYNT-EYE-SDK/tutorials.html). Here are the firmwares:

<table>
  <tr>
    <td>Name</td>
    <td>Version</td>
    <td>Size</td>
    <td>MD5</td>
  </tr>
  <tr>
    <td>mynteye_0105_1711181427.img</td>
    <td>0105</td>
    <td>137.82 KB</td>
    <td>9b48050e8599493c261ff6b0645c3eb8</td>
  </tr>
  <tr>
    <td>mynteye_0104_1711031837.img</td>
    <td>0104</td>
    <td>136.48 KB</td>
    <td>837675c714ab6cf1109b5c17ad34b1c6</td>
  </tr>
  <tr>
    <td>mynteye_0102_1708101513.img</td>
    <td>0102</td>
    <td>131.59 KB</td>
    <td>86ef4069eee6b96bf5325cae8809b904</td>
  </tr>
  <tr>
    <td>mynteye_0101_1706151738.img</td>
    <td>0101</td>
    <td>132.53 KB</td>
    <td>49041624e6dca608e0c6610a5ba16a21</td>
  </tr>
  <tr>
    <th colspan="4">Special Builds</th>
  </tr>
  <tr>
    <td>mynteye_0103_for_slam.img</td>
    <td>0103<br />25 fps, 500 Hz</td>
    <td>129.21 KB</td>
    <td>85158ef5b55f618e8f0ea674be8bc3b1</td>
  </tr>
</table>

`setup.exe` is a application used for upgrading firmware, available on Windows 7, 8 and 10.

<table>
  <tr>
    <td>Name</td>
    <td>Version</td>
    <td>Size</td>
    <td>MD5</td>
  </tr>
  <tr>
    <td>setup.exe</td>
    <td></td>
    <td>58.45 MB</td>
    <td>6f704fd1bbd6d44808f2d989cf78fbe2</td>
  </tr>
</table>

## Release Notes

### 0105

* Add camera control features.
    - Control max-gain, max-brightness and desired-brightness when auto-exposure is enabled.

### 0104

* Add camera control features.
    - Control framerate & IMU frequency: 50 fps 500 Hz, 25 fps 500 Hz, 10 fps 200 Hz.
    - Control gain, brightness, contrast and auto-exposure.
    - Request zero drift calibration.

### 0103 for SLAM

* A test version specially built for SLAM, such as VINS etc.
    - The frame rate is 25 fps, and the IMU frequency is 500 Hz.

### 0102

* Add the adaptability to ambient light, such as indoor and outdoor.
    - The camera will dynamic balance the brightness according to the brightness of ambient light.

**Known Situations**

* If the camera faces to a flicker light, the images may flicker too.
* If the camera focuses on a strong light indoor, the images will be dark in whole.
* For synchronizing brightness of left and right images, the right camera is the main one to detect ambient light, whose dynamic balance will influence the left one.

### 0101

* Initial release.
