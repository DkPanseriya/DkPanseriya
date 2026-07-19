# Darshak Panseriya

**Perception engineer — radar and vision ML that runs on real hardware.**

Most perception engineers come from pure ML. I came through vehicles: suspension kinematics, load cases, and Formula Student first, then ML on top. That combination is the point — I design models against the constraints they actually ship under: a latency budget, a memory ceiling, a false-positive rate someone has to sign off on.

Currently: at **Robert Bosch GmbH** on UWB-radar gesture detection — owned end to end, from data campaign and labeling infrastructure through model design to real-time ARM Cortex deployment and vehicle validation. M.Eng in **Automated Driving and Vehicle Safety**, TH Ingolstadt.

📍 Stuttgart, Germany · German C1 / English C1 · Open to perception, sensor-fusion, and ADAS roles

---

## What I work on

**Radar-first 3D perception.** Camera perception has tens of thousands of practitioners; radar perception has a few hundred. 4D imaging radar is the cheap all-weather sensor every OEM is betting on, and almost nobody works the full stack from raw ADC through detection to a deployed, validated function. That's the gap I'm building into.

Three things I keep coming back to:

- **Hybrid intelligence** — ML alone is not trustworthy in ambiguous motion. Deterministic physics and temporal logic wrapped around a model beats either half alone.
- **The deployment constraint is the design constraint** — a model that misses the latency budget is not a model, it's a research artifact.
- **False positives are a product risk, not a metric** — how a function fails decides whether it ships.

---

## 🚧 Building: RadarStack

An open-source radar-first 3D perception stack — 4D-radar detection, multi-object tracking, camera-radar BEV fusion, INT8 edge deployment, closed-loop validation, and a documented SOTIF safety case. Trained on public benchmarks (nuScenes, View-of-Delft, K-Radar), validated on a self-built sensor rig.

Shipping in versioned releases, one write-up per release. *Public at v0.1 — watch this space.*

---

## Selected work

| Project | What it does | Stack |
|---|---|---|
| **[Sensor-Data-Fusion](https://github.com/DkPanseriya/Sensor-Data-Fusion)** | Camera-radar fusion for traffic perception: radar point-cloud clustering with a from-scratch range-adaptive DBSCAN, YOLO detection, coordinate transforms, and cluster-to-box association visualized on image and ground planes. | Python, PyTorch, Ultralytics, OpenCV |
| **[Cone-Detection](https://github.com/DkPanseriya/Cone-Detection)** | YOLOv2 cone detector for Formula Student Driverless — labeling through training to real-time video validation. Solution to MathWorks Challenge #248. | MATLAB, Simulink, Computer Vision Toolbox |

---

## Experience

**Robert Bosch GmbH** — Master Thesis, ML-based Kick Detection with UWB Radar · *Oct 2025 – present*
End-to-end ownership: data acquisition, labeling pipelines, model and algorithm design, integration, vehicle validation. Radar spatio-temporal features (CIR preprocessing, range gating, Doppler, STFT). Compact architectures under embedded constraints. Hybrid physics + ML post-processing cutting **>90% of raw ML false positives** in real-world scenarios, at **<100 ms latency on ARM Cortex**.

**Robert Bosch GmbH** — UWB Radar Engineering Intern · *Feb – Sep 2025*
Real-time CIR analysis tool (Python/PyQt). Radar evaluations for child-presence-detection, kick, and intrusion functions. CANoe/CAPL measurement automation, ingestion pipeline for 100k+ measurement files, and an automated + human-in-the-loop labeling framework that cut manual cleanup **>80%**.

**Schanzer Racing Electric** — Perception System Engineer · *Oct 2024 – Apr 2025*
Real-time perception pipeline for autonomous racing. Automated YOLOv8-pose validation (AP/IoU, keypoint RMSE) saving **~100 hours of manual labeling**; class-wise confusion analysis surfacing 25–35% recall losses.

**Fraunhofer IVI** — Sensor Data Fusion · *Mar – Jun 2024*
Camera-radar fusion for traffic perception. YOLOv8 training with dataset balancing; detection and association validation metrics.

**Stealth Startup (Micromobility)** — Vehicle Platform Design Engineer · *Aug 2022 – Aug 2024*
Sole platform engineer: architecture, suspension, brakes, steering, drivetrain. Kinematics and dynamics analysis, FEA, production drawings and BOMs — concept through prototype-ready release.

**GTU Motorsports** — Vehicle Dynamics Engineer · *Apr 2019 – Mar 2021*
Suspension and vehicle-dynamics design, kinematics models, tire-data analysis. Formula Bharat: **3rd place 2020, 5th place 2021**.

---

## Stack

**Perception & ML** — PyTorch · TensorFlow / Keras · Ultralytics YOLO · OpenCV · scikit-learn
**Sensors & signal** — UWB radar · CIR / STFT / Doppler · range gating · CANoe · CAPL · MATLAB / Simulink
**Deployment** — quantization · latency profiling · ARM Cortex · ONNX · Docker
**Data** — NumPy · Pandas · labeling automation · PyQt · Plotly
**Vehicle engineering** — SolidWorks · ANSYS · Adams · vehicle kinematics & dynamics · FEA

---

## Reach me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://linkedin.com/in/dkpanseriya)
[![Email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white)](mailto:dkpanseriya99@gmail.com)

Open to conversations about perception, sensor fusion, radar, and anything that has to work outside a benchmark.
