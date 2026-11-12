# Hi there, I'm Sai Hardhik Reddy 👋
### AI & Data Science Engineer | SDR & Cyber-Physical Systems | Scientific ML (PINNs) | Robotics

<p align="center">
  <img alt="Focus: AI and Data Science" src="https://img.shields.io/badge/Focus-AI_%26_Data_Science-blue?style=for-the-badge&logo=python" />
  <img alt="Specialization: Software-Defined Radio" src="https://img.shields.io/badge/Specialization-Software_Defined_Radio-green?style=for-the-badge" />
  <img alt="Research: Physics-Informed ML" src="https://img.shields.io/badge/Research-Physics_Informed_ML-purple?style=for-the-badge" />
  <img alt="Robotics: ROS 2" src="https://img.shields.io/badge/Robotics-ROS_2-22314E?style=for-the-badge&logo=ros" />
  <img alt="Location: India" src="https://img.shields.io/badge/Location-India-orange?style=for-the-badge" />
</p>

---

## ⚡ About Me

B.Tech AI & Data Science student at **Amrita Vishwa Vidyapeetham**. I like building complete systems from the maths up: signal chains, physics-informed models, robots and the software that runs them. I care about results I can measure and explain.

- 📡 **Software-Defined Radio**: DSSS covert links, Costas-loop carrier recovery, RF steganography and detectors.
- 🧠 **Scientific ML**: physics-informed neural networks (SIREN PINNs) for inverse problems in structural dynamics.
- 🤖 **Robotics**: ROS 2 perception, inverse kinematics and path planning written from scratch.
- 🛰️ **Networks & Edge AI**: learning-based routing for offline Bluetooth mesh networks.
- ☁️ **AI Infrastructure**: multi-agent MCP servers with policy-as-code (OPA/Rego) guardrails.

---

## 🚀 Featured Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3 align="center">📡 SentinelSpread</h3>
      <p align="center"><b>Spread-Spectrum Covert SDR & Detector Suite</b></p>
      <p>End-to-end DSSS covert link: AES-256-GCM sealing, BPSK/QPSK with RRC pulse shaping, Costas-loop carrier recovery and a GNU Radio flowgraph, benchmarked for BER against theory. The other side is a detector suite (statistical tests, a random forest and a CNN on raw I/Q) and a closed loop that adds frequency hopping and power backoff until the CNN's detection confidence falls below a target.</p>
      <p><b>Stack:</b> Python, GNU Radio, SciPy, PyCryptodome, PyTorch, scikit-learn, Pytest</p>
      <p align="center"><a href="https://github.com/saihardhikreddy/SentinelSpread">👉 View Repository</a></p>
    </td>
    <td width="50%" valign="top">
      <h3 align="center">🤖 Strata Cobot</h3>
      <p align="center"><b>Autonomous Ore Sorting & Haulage in ROS 2</b></p>
      <p>A UR7e arm and a mobile robot sort and haul ore with no human in the loop. RGB-D perception, inverse kinematics, motion planning and path planning are all written from scratch, with no MoveIt 2 or Nav2.</p>
      <p><b>Stack:</b> ROS 2, Python, Gazebo, OpenCV</p>
      <p align="center"><a href="https://github.com/saihardhikreddy/strata-cobot">👉 View Repository</a></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3 align="center">🛰️ Predictive Edge AI Routing</h3>
      <p align="center"><b>Learning Routing for Offline BLE Mesh Networks</b></p>
      <p>A learning, privacy-preserving and self-defending routing layer for BitChat-style Bluetooth meshes. Includes a mesh simulator, DTN baselines, a digital-twin server and an Android app.</p>
      <p><b>Stack:</b> Python, Kotlin, BLE, Simulation</p>
      <p align="center"><a href="https://github.com/saihardhikreddy/predictive-edge-ai-routing">👉 View Repository</a></p>
    </td>
    <td width="50%" valign="top">
      <h3 align="center">🧠 FD-PINN Beam Inverse</h3>
      <p align="center"><b>Frequency-Domain Physics-Informed Neural Network</b></p>
      <p>Recovers the hidden bending stiffness <i>EI</i> of a simply supported, lightly damped Euler-Bernoulli beam under a moving load, from 41 frequency-domain sensor readings. Sine (SIREN-style) activations, heavily weighted boundary penalties and L-BFGS optimisation of the physics loss; the plotting script reports the fit to every sensor reading.</p>
      <p><b>Stack:</b> DeepXDE, TensorFlow, NumPy, Matplotlib</p>
      <p align="center"><a href="https://github.com/saihardhikreddy/FD-PINN-Beam-Inverse">👉 View Repository</a></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3 align="center">☁️ CloudOps OS MCP</h3>
      <p align="center"><b>Autonomous Multi-Agent Terraform Pipeline</b></p>
      <p>Model Context Protocol server for Infrastructure-as-Code governance: cost optimisation and OPA/Rego policy compliance with LLM reasoning, packaged with Docker and CI.</p>
      <p><b>Stack:</b> TypeScript, Node.js, MCP, Terraform, OPA/Rego, Docker</p>
      <p align="center"><a href="https://github.com/saihardhikreddy/cloudops-os-mcp">👉 View Repository</a></p>
    </td>
    <td width="50%" valign="top">
      <h3 align="center">❤️ SeismoPulse</h3>
      <p align="center"><b>₹410 Cuffless Blood-Pressure Trend Monitor</b></p>
      <p>Times each heartbeat from the aortic-valve opening (MPU-6050 seismocardiogram) to the fingertip pulse (PPG) on an Arduino Nano, and converts the transit time into a BP trend with physics-based calibration.</p>
      <p><b>Stack:</b> Arduino C++, Python, Signal Processing</p>
      <p align="center"><a href="https://github.com/saihardhikreddy/SeismoPulse">👉 View Repository</a></p>
    </td>
  </tr>
</table>

<details>
<summary><b>🔍 More Projects</b></summary>

- 🧬 [**UniGenome**](https://github.com/saihardhikreddy/unigenome): Anti-counterfeit supply-chain tracking. Ed25519-signed QR identities, signed and hash-chained scans at every hop, one Merkle-rooted QR per carton or pallet, and portals for manufacturer, warehouse, retailer, buyer and regulator. TypeScript: React + Vite, a Hono API, PostgreSQL (embedded PGlite by default).
- 🔭 [**Issue Scout**](https://github.com/saihardhikreddy/issue-scout): Finds fresh, unclaimed GitHub issues in projects whose AI-contribution policy fits you. Python CLI. [Live demo](https://saihardhikreddy.github.io/issue-scout/).
- 👁️ [**Omni-Track**](https://github.com/saihardhikreddy/omni-track): Real-time crowd topography with SVD Rank-1 anomaly detection, YOLOv8/ByteTrack and SAHI sliced inference.
- ⚛️ [**Lammps-AI**](https://github.com/saihardhikreddy/Lammps-AI): Local LAMMPS research assistant: generates validated scripts for liquids and metals from plain-English requests, runs them in LAMMPS, and parses logs and trajectories (diffusion, Green-Kubo viscosity) in a web UI.
- 🔬 [**Copper-Tensile-Deformation-Informatics**](https://github.com/saihardhikreddy/Copper-Tensile-Deformation-Informatics): LAMMPS + OVITO simulation of FCC copper tensile failure from 300 K to 900 K, with DXA dislocation tracking.
- 🎯 [**Mini-Air-Defence-System-Sky_Forge**](https://github.com/saihardhikreddy/Mini-Air-Defence-System-Sky_Forge): Arduino air-defence turret prototype: a sweeping ultrasonic radar finds close-range targets, verifies them with multi-sample voting, aims and fires a servo launcher, with a Processing radar display.
- 🔐 [**steganography-and-watermarking**](https://github.com/saihardhikreddy/steganography-and-watermarking): Browser suite for LSB steganography, RSA keypairs, digital watermarking and the Web Crypto API.
- 🪞 [**Deferral Twin**](https://github.com/saihardhikreddy/deferral-twin): An honest digital twin that answers in your words, in your cloned voice and with a lip-synced face, and says "I don't know" when retrieval confidence is low. English, Telugu and Hindi, offline on Apple Silicon: FAISS retrieval, Phi-3-mini (MLX), XTTS-v2, Whisper, Wav2Lip.
- 🧳 [**WanderIndia**](https://github.com/saihardhikreddy/WanderIndia): AI travel planner for India with live route scanning. Flask, Llama 3.3 70B (Groq), Geoapify, Google OAuth.
- 🖐️ [**gesture-reactions**](https://github.com/saihardhikreddy/gesture-reactions): macOS-style hand-gesture reactions (hearts, fireworks, confetti...) for any video call on Windows: Zoom, Teams and Meet through a virtual camera, WhatsApp through OBS. MediaPipe, OpenCV, PyVirtualCam.
- 🎨 [**afterlight**](https://github.com/saihardhikreddy/afterlight): A library of 15 agent skills for UI and WebGL work (design systems, scroll stories, three.js scenes, verification workflows), with runnable offline demos, a skill linter and a desktop/phone screenshot checker.

</details>

---

## 🛠️ Languages & Technical Skills

```
Languages        : Python, C++, TypeScript, JavaScript, Kotlin, SQL, MATLAB, Bash
Machine Learning : PyTorch, TensorFlow, Scikit-Learn, PINNs (SIREN), OpenCV, YOLOv8, SAHI
SDR & Telecom    : DSSS, BPSK/QPSK, Costas Loop, RRC Filtering, GNU Radio
Robotics & Embedded : ROS 2, Gazebo, Inverse Kinematics, Path Planning, Arduino, IMU/PPG sensing
Cloud & DevOps   : Terraform, Docker, GitHub Actions, Open Policy Agent (OPA), Node.js
Simulation       : LAMMPS, OVITO (DXA), SciPy Signal / Linear Algebra
```

---

## 📈 GitHub Statistics

<p align="center">
  <img height="160" alt="GitHub stats for saihardhikreddy" src="https://github-readme-stats.vercel.app/api?username=saihardhikreddy&show_icons=true&theme=tokyonight&count_private=true" />
  <img height="160" alt="Most used languages" src="https://github-readme-stats.vercel.app/api/top-langs/?username=saihardhikreddy&layout=compact&theme=tokyonight" />
</p>

---

## 📫 Connect With Me

- ✉️ **Email**: saihardhikreddy@gmail.com
- 🌐 **GitHub**: [@saihardhikreddy](https://github.com/saihardhikreddy)
