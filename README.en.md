# 🚁 AeroForge | Quadrotor Structural Designs

[🌐 Homepage](https://mioulo.github.io/)

[简体中文](README.md) | [English](README.en.md)

Structural designs and example builds for quadrotors. Component placement illustrates one possible assembly arrangement.

> ⚠️ Carbon-fiber plates differ between onboard-computer layouts. Use the plates matching the chosen aircraft.

<p align="center"><img src="assets/2p5-compact/display.png" alt="2.5-inch Compact" width="19%"> <img src="assets/3p5-rear-d455/display.png" alt="3.5-inch Rear Computer / D455" width="19%"> <img src="assets/3p5-rear-forward/display.png" alt="3.5-inch Rear Computer / Forward Camera" width="19%"> <img src="assets/3p5-center-depth/display.jpg" alt="3.5-inch Center Computer / Omnidirectional Depth" width="19%"> <img src="assets/3p5-center-fisheye/display.png" alt="3.5-inch Center Computer / Panoramic Fisheye" width="19%"></p>

📦 Assembly models, carbon-fiber plates, and printed parts are packaged by aircraft in this repository’s [Releases](https://github.com/Mioulo/AeroForge/releases).

## 🪶 2.5-inch Compact

<p align="center"><img src="assets/2p5-compact/design.png" alt="CAD assembly" height="200"> &nbsp; <img src="assets/2p5-compact/display.png" alt="Real aircraft" height="200"></p>

<table align="center">
  <tr><th align="left">Camera</th><td width="360">Intel RealSense D435 depth camera</td></tr>
  <tr><th align="left">Onboard computer</th><td width="360">LubanCat Zero W (RK3566)</td></tr>
  <tr><th align="left">Flight controller</th><td width="360">Micoair H743V2 AIO 45A</td></tr>
  <tr><th align="left">ESC</th><td width="360">Micoair H743V2 AIO 45A</td></tr>
  <tr><th align="left">Motors</th><td width="360">OddityRC 1205 5500KV</td></tr>
  <tr><th align="left">Battery</th><td width="360">Gens ace 4S 850 mAh 120C</td></tr>
</table>

## 📷 3.5-inch · Rear Computer / Depth Camera

<p align="center"><img src="assets/3p5-rear-d455/design.png" alt="CAD assembly" height="200"> &nbsp; <img src="assets/3p5-rear-d455/display.png" alt="Real aircraft" height="200"></p>

<table align="center">
  <tr><th align="left">Camera</th><td width="360">Intel RealSense D455 depth camera</td></tr>
  <tr><th align="left">Onboard computer</th><td width="360">AMOVLAB NVIDIA Orin NX 16 GB</td></tr>
  <tr><th align="left">Flight controller</th><td width="360">Micoair NxtPX4V2</td></tr>
  <tr><th align="left">ESC</th><td width="360">HobbyWing 45A</td></tr>
  <tr><th align="left">Motors</th><td width="360">OddityRC 2006 2150KV</td></tr>
  <tr><th align="left">Battery</th><td width="360">Gens ace 6S 1300 mAh 95C</td></tr>
</table>

## 👁️ 3.5-inch · Rear Computer / Forward Monocular Camera

<p align="center"><img src="assets/3p5-rear-forward/design.png" alt="CAD assembly" height="200"> &nbsp; <img src="assets/3p5-rear-forward/display.png" alt="Real aircraft" height="200"></p>

<table align="center">
  <tr><th align="left">Camera</th><td width="360">DCXG20030 (杰瑞微通), 1.4 mm, 210° FOV</td></tr>
  <tr><th align="left">Onboard computer</th><td width="360">AMOVLAB NVIDIA Orin NX 16 GB</td></tr>
  <tr><th align="left">Flight controller</th><td width="360">Micoair NxtPX4V2</td></tr>
  <tr><th align="left">ESC</th><td width="360">HobbyWing 45A</td></tr>
  <tr><th align="left">Motors</th><td width="360">OddityRC 2006 2150KV</td></tr>
  <tr><th align="left">Battery</th><td width="360">Gens ace 6S 1300 mAh 95C</td></tr>
</table>

> 💡 The camera configuration is provided for reference. Choose a pinhole or fisheye camera and an appropriate field of view (FOV) to suit your application.

## 🧭 3.5-inch · Center Computer / Omnidirectional Depth

<p align="center"><img src="assets/3p5-center-depth/design.png" alt="CAD assembly" height="200"> &nbsp; <img src="assets/3p5-center-depth/display.jpg" alt="Real aircraft" height="200"></p>

<table align="center">
  <tr><th align="left">Camera</th><td width="360">Seeker omni-d (视元)</td></tr>
  <tr><th align="left">Onboard computer</th><td width="360">AMOVLAB NVIDIA Orin NX 16 GB</td></tr>
  <tr><th align="left">Flight controller</th><td width="360">Micoair NxtPX4V2</td></tr>
  <tr><th align="left">ESC</th><td width="360">HobbyWing 45A</td></tr>
  <tr><th align="left">Motors</th><td width="360">OddityRC 2006 2150KV</td></tr>
  <tr><th align="left">Battery</th><td width="360">Gens ace 6S 1300 mAh 95C</td></tr>
</table>

## 🌐 3.5-inch · Center Computer / Panoramic Fisheye

<p align="center"><img src="assets/3p5-center-fisheye/design.png" alt="CAD assembly" height="200"> &nbsp; <img src="assets/3p5-center-fisheye/display.png" alt="Real aircraft" height="200"></p>

<table align="center">
  <tr><th align="left">Camera</th><td width="360">DCXG20030 (杰瑞微通), 1.4 mm, 210° FOV</td></tr>
  <tr><th align="left">Onboard computer</th><td width="360">AMOVLAB NVIDIA Orin NX 16 GB</td></tr>
  <tr><th align="left">Flight controller</th><td width="360">Micoair NxtPX4V2</td></tr>
  <tr><th align="left">ESC</th><td width="360">HobbyWing 45A</td></tr>
  <tr><th align="left">Motors</th><td width="360">OddityRC 2006 2150KV</td></tr>
  <tr><th align="left">Battery</th><td width="360">Gens ace 6S 1300 mAh 95C</td></tr>
</table>

> 💡 The camera configuration is provided for reference. Choose a pinhole or fisheye camera and an appropriate field of view (FOV) to suit your application.

## 🧠 Algorithm Applications

These aircraft platforms support real-world research and validation of the following algorithms:

- [GeoMonoPlan](https://github.com/TJU-Aerial-Robotics/GeoMonoPlan)
- [YOPO](https://github.com/TJU-Aerial-Robotics/YOPO)
- [YOPOv2-Tracker](https://github.com/TJU-Aerial-Robotics/YOPO-Tracker)

## 📄 License

Original design files, images, and documentation are released under the [MIT License](LICENSE). Third-party content retains its respective rights and licenses.
