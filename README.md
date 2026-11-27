# Hey, I'm Ahmed Wafdy 👋

**Embedded Systems Engineer** · Software-Defined Vehicles, embedded Linux and in-vehicle infotainment<br>
📍 Cairo, Egypt

[![Portfolio](https://img.shields.io/badge/Portfolio-222222?logo=githubpages&logoColor=white)](https://ahmedadelwafdy7.github.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://linkedin.com/in/ahmed-wafdy-094567242)
[![X](https://img.shields.io/badge/X-000000?logo=x&logoColor=white)](https://x.com/wafdev)

---

## 🚗 What I work on

- **Software-Defined Vehicles:** Xen on Jetson Orin Nano with separate domains for driving and infotainment, Autoware on Yocto, a QNX safety guest that takes over when Linux fails
- **Embedded Linux:** Yocto/BitBake layers, Flatpak on embedded targets, first-boot services, data partitions, systemd
- **Wayland and graphics:** Flutter embedder and compositor work (ivi-homescreen, ihs_wl_server), Weston capture protocols, GL/Vulkan on the Raspberry Pi 5 (V3D)
- **Vehicle middleware:** ROS 2, Zenoh, DDS, gRPC, MQTT, SOME/IP, CAN, D-Bus

## 🔧 Upstream contributions

| Project | What I did | Merged PRs |
|---|---|---|
| [meta-flatpak-minimal](https://github.com/flatpak-minimal/meta-flatpak-minimal/pulls?q=is%3Apr+author%3AAhmedAdelWafdy7+is%3Amerged) | Flatpak runtime and guest isolation on AGL, first-boot services (Flathub remote, bundle install, rootfs expansion), per-user installs, SDK for flatpak-builder | 13 |
| [xdg-desktop-portal-agl](https://github.com/flatpak-minimal/xdg-desktop-portal-agl/pulls?q=is%3Apr+author%3AAhmedAdelWafdy7+is%3Amerged) | Rust portal backend for AGL: Screenshot and Settings over weston_capture, agl_screenshooter and wlr-screencopy | 4 |
| [flatpak_dart](https://github.com/flatpak-minimal/flatpak_dart/pulls?q=is%3Apr+author%3AAhmedAdelWafdy7+is%3Amerged) | Launch/stop and running state, AppStream metadata, portal permissions | 3 |
| [autoware_universe](https://github.com/autowarefoundation/autoware_universe/pulls?q=is%3Apr+author%3AAhmedAdelWafdy7+is%3Amerged) · [autoware_component_monitor](https://github.com/autowarefoundation/autoware_component_monitor/pulls?q=is%3Apr+author%3AAhmedAdelWafdy7+is%3Amerged) | Build fixes for newer Boost and fmt | 7 |
| [ivi-homescreen](https://github.com/toyota-connected/ivi-homescreen/pulls?q=is%3Apr+author%3AAhmedAdelWafdy7+is%3Amerged) · [ihs_wl_server](https://github.com/toyota-connected/ihs_wl_server/pulls?q=is%3Apr+author%3AAhmedAdelWafdy7+is%3Amerged) · [emb_cli](https://github.com/toyota-connected/emb_cli/pulls?q=is%3Apr+author%3AAhmedAdelWafdy7+is%3Amerged) | GL compositor and platform view fixes on V3D, window reporting to Dart, building a Flatpak from one manifest | 6 |
| [meta-flutter](https://github.com/meta-flutter/meta-flutter/pulls?q=is%3Apr+author%3AAhmedAdelWafdy7+is%3Amerged) · [meta-ros](https://github.com/ros/meta-ros/pulls?q=is%3Apr+author%3AAhmedAdelWafdy7+is%3Amerged) · [AGL sodev-demo-workspace-rpi](https://github.com/automotive-grade-linux/sodev-demo-workspace-rpi/pulls?q=is%3Apr+author%3AAhmedAdelWafdy7+is%3Amerged) | flutter_tools on non-x86-64 hosts, native hook user defines, aarch64 build host for AGL Flutter | 5 |

## 🛠️ Featured projects

- **[Yaquod](https://github.com/Yaquod): robotaxi SDV platform** · Xen · Yocto · Autoware · Zenoh · Jetson Orin
  - Autoware and the Flutter IVI share one Jetson Orin Nano, each in its own Xen domain ([meta-tegra-xen](https://github.com/Yaquod/meta-tegra-xen)). The [autoware-agent](https://github.com/Yaquod/autoware-agent) runs trips, [iv-cloud-gateway](https://github.com/Yaquod/iv-cloud-gateway) links the car to the cloud over gRPC/MQTT, and [flutter-ivi](https://github.com/Yaquod/flutter-ivi) talks to the driving domain over Zenoh.
- **[Autoware QNX Guardian](https://github.com/AhmedAdelWafdy7/autoware-qnx-guardian)** · QNX 8.0 · QNX Hypervisor · ROS 2 Jazzy · Raspberry Pi 5
  - Autoware's safe-stop stack ported to QNX, supervising an Autoware Linux guest ([meta-autoware](https://github.com/AhmedAdelWafdy7/meta-autoware)) on the same SoC, and taking over when Linux fails.
- **AGL App Store** (GSoC 2025) · Flutter · Flatpak · mutual TLS
  - App store for AGL IVI images with sandboxed app installs ([flutter_remote_manager](https://github.com/flatpak-minimal/flutter_remote_manager)), built on the Flatpak work above.
- **[Infotainment System on Raspberry Pi 4](https://github.com/AhmedAdelWafdy7/Infotainment-System)** · C++ · Qt · SOME/IP · CAN · Yocto
  - Qt head unit with CAN and SOME/IP IPC, built with [meta-infotainment](https://github.com/AhmedAdelWafdy7/meta-infotainment).

## 💻 Tech stack

**Languages:** C · C++ · Rust · Dart · Python · Shell · BitBake<br>
**Platforms:** Yocto · AGL · Xen · QNX · Jetson Orin · Raspberry Pi 4/5<br>
**Frameworks and middleware:** Flutter (embedded) · Qt/QML · ROS 2 · Autoware · Zenoh · gRPC · SOME/IP · Flatpak<br>
**Tooling:** CMake · Cargo · Docker · GitHub Actions · Git

---

## 📊 GitHub metrics

![](https://raw.githubusercontent.com/AhmedAdelWafdy7/AhmedAdelWafdy7/main/github-metrics.svg)
