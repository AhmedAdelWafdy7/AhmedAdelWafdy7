<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=200&color=0:0f2027,50:203a43,100:2c5364&text=Ahmed%20Wafdy&fontColor=ffffff&fontSize=56&fontAlignY=36&desc=Embedded%20Systems%20Engineer%20%C2%B7%20Cairo%2C%20Egypt&descAlignY=56&descSize=18" width="100%" alt="Ahmed Wafdy" />

<a href="https://github.com/flatpak-minimal/flutter_remote_manager"><img src="https://readme-typing-svg.demolab.com/?font=JetBrains+Mono&weight=600&size=20&duration=3200&pause=900&color=2EA8C6&center=true&vCenter=true&width=620&lines=Maintainer+of+the+AGL+App+Store;Maintainer+of+meta-autoware+for+Yocto;Flatpak+on+embedded+Linux;Xen+%2B+Autoware+on+Jetson+Orin;QNX+safety+guest+for+Autoware" alt="Maintainer of the AGL App Store" /></a>

[![Portfolio](https://img.shields.io/badge/Portfolio-0f2027?style=for-the-badge&logo=githubpages&logoColor=white)](https://ahmedadelwafdy7.github.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/ahmed-wafdy-094567242)
[![X](https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/wafdev)

</div>

## 🏪 AGL App Store

I maintain the **AGL App Store** in [flatpak-minimal](https://github.com/flatpak-minimal). It started as my GSoC 2025 project with Automotive Grade Linux and I've kept building it since. It covers the whole path from a Flatpak remote to an app launched on an AGL IVI screen: the store UI, the Dart API over libflatpak, the desktop portal and the Yocto layer that puts it in the image.

<table>
<tr>
<td width="50%" valign="top">

### [Store app](https://github.com/flatpak-minimal/flutter_remote_manager)
![Owner](https://img.shields.io/badge/owner-2ea8c6?style=flat-square) ![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)

Browse remotes, install and update apps, manage portal permissions. Runs under the AGL homescreen.

</td>
<td width="50%" valign="top">

### [Desktop portal for AGL](https://github.com/flatpak-minimal/xdg-desktop-portal-agl)
![Author](https://img.shields.io/badge/author-2ea8c6?style=flat-square) ![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)

Rust portal backend. Screenshot and Settings over `weston_capture_v1`, `agl_screenshooter` and wlr-screencopy.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [Flatpak API for Dart](https://github.com/flatpak-minimal/flatpak_dart)
![Maintainer](https://img.shields.io/badge/maintainer-2ea8c6?style=flat-square) ![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white) ![C++23](https://img.shields.io/badge/C%2B%2B23-00599C?style=flat-square&logo=cplusplus&logoColor=white)

Typed Dart API over libflatpak through a C++23 FFI bridge. I added launch/stop, running state, AppStream metadata and portal permissions.

</td>
<td width="50%" valign="top">

### [Yocto integration](https://github.com/flatpak-minimal/meta-flatpak-minimal)
![Maintainer](https://img.shields.io/badge/maintainer-2ea8c6?style=flat-square) ![Yocto](https://img.shields.io/badge/Yocto-0f2027?style=flat-square&logo=linux&logoColor=white)

The layer that ships it all into the image. Flatpak isolation on AGL, first-boot Flathub setup, per-user installs, data partition handling.

</td>
</tr>
</table>

Store work regularly needs fixes in the projects underneath it, so I send them upstream:

[![Toyota Connected](https://img.shields.io/badge/Toyota_Connected-embedded_Flutter_on_Wayland-203a43?style=flat-square)](https://github.com/search?q=author%3AAhmedAdelWafdy7+is%3Apr+is%3Amerged+org%3Atoyota-connected&type=pullrequests)
[![Flutter on Yocto](https://img.shields.io/badge/Flutter-on_Yocto-203a43?style=flat-square)](https://github.com/meta-flutter/meta-flutter/pulls?q=is%3Apr+author%3AAhmedAdelWafdy7+is%3Amerged)
[![AGL](https://img.shields.io/badge/AGL-Flutter_demo_workspace-203a43?style=flat-square)](https://github.com/automotive-grade-linux/sodev-demo-workspace-rpi/pulls?q=is%3Apr+author%3AAhmedAdelWafdy7+is%3Amerged)

## 🚗 Software-Defined Vehicles

<table>
<tr>
<td width="50%" valign="top">

### [Yaquod](https://github.com/Yaquod)
![Xen](https://img.shields.io/badge/Xen-2c5364?style=flat-square) ![Jetson Orin](https://img.shields.io/badge/Jetson_Orin-76B900?style=flat-square&logo=nvidia&logoColor=white) ![Zenoh](https://img.shields.io/badge/Zenoh-2c5364?style=flat-square)

Robotaxi platform. Autoware and a Flutter IVI share one Jetson Orin Nano, each in its own Xen domain, with a trip agent, a cloud gateway over gRPC/MQTT and Zenoh between domains.

</td>
<td width="50%" valign="top">

### [Autoware QNX Guardian](https://github.com/AhmedAdelWafdy7/autoware-qnx-guardian)
![QNX 8.0](https://img.shields.io/badge/QNX_8.0-2c5364?style=flat-square) ![ROS 2 Jazzy](https://img.shields.io/badge/ROS_2_Jazzy-22314E?style=flat-square&logo=ros&logoColor=white) ![Raspberry Pi 5](https://img.shields.io/badge/Raspberry_Pi_5-C51A4A?style=flat-square&logo=raspberrypi&logoColor=white)

Autoware's safe-stop stack on QNX, supervising an Autoware Linux guest on the same SoC, so the car can still stop safely if Linux crashes.

</td>
</tr>
<tr>
<td colspan="2" valign="top">

### [meta-autoware](https://layers.openembedded.org/layerindex/branch/master/layer/meta-autoware/)
![Maintainer](https://img.shields.io/badge/maintainer-2ea8c6?style=flat-square) ![OpenEmbedded Layer Index](https://img.shields.io/badge/OpenEmbedded_Layer_Index-listed-203a43?style=flat-square) ![Yocto](https://img.shields.io/badge/Yocto-0f2027?style=flat-square&logo=linux&logoColor=white) ![ROS 2](https://img.shields.io/badge/ROS_2-22314E?style=flat-square&logo=ros&logoColor=white)

The Yocto layer that builds the Autoware autonomous driving stack on ROS 2, listed in the OpenEmbedded Layer Index. It also builds the Linux guest that the QNX Guardian supervises.

</td>
</tr>
</table>

Also upstream in [Autoware](https://github.com/autowarefoundation/autoware_universe/pulls?q=is%3Apr+author%3AAhmedAdelWafdy7+is%3Amerged) and [ROS on Yocto](https://github.com/ros/meta-ros/pulls?q=is%3Apr+author%3AAhmedAdelWafdy7+is%3Amerged). Earlier work: an [infotainment system on Raspberry Pi 4](https://github.com/AhmedAdelWafdy7/Infotainment-System) with Qt, CAN and SOME/IP.

## 🧰 Tech stack

<div align="center">

<img src="https://skillicons.dev/icons?i=c,cpp,rust,dart,python,bash,flutter,qt,linux,raspberrypi,ros,cmake,docker,githubactions,git&perline=15" alt="C, C++, Rust, Dart, Python, Bash, Flutter, Qt, Linux, Raspberry Pi, ROS, CMake, Docker, GitHub Actions, Git" />

![Yocto](https://img.shields.io/badge/Yocto-0f2027?style=for-the-badge&logo=linux&logoColor=white)
![AGL](https://img.shields.io/badge/AGL-203a43?style=for-the-badge)
![Flatpak](https://img.shields.io/badge/Flatpak-4A90D9?style=for-the-badge&logo=flatpak&logoColor=white)
![Wayland](https://img.shields.io/badge/Wayland-FFBC00?style=for-the-badge&logo=wayland&logoColor=black)
![Xen](https://img.shields.io/badge/Xen-2c5364?style=for-the-badge)
![QNX](https://img.shields.io/badge/QNX-2c5364?style=for-the-badge&logo=blackberry&logoColor=white)
![Autoware](https://img.shields.io/badge/Autoware-203a43?style=for-the-badge)
![Zenoh](https://img.shields.io/badge/Zenoh-0f2027?style=for-the-badge)
![SOME/IP](https://img.shields.io/badge/SOME%2FIP-203a43?style=for-the-badge)

</div>

<details>
<summary>📊 GitHub metrics</summary>
<br>

![GitHub metrics](https://raw.githubusercontent.com/AhmedAdelWafdy7/AhmedAdelWafdy7/main/github-metrics.svg)

</details>

<img src="https://capsule-render.vercel.app/api?type=waving&height=100&color=0:2c5364,50:203a43,100:0f2027&section=footer" width="100%" alt="" />
