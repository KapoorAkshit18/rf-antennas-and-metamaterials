
# Antenna Design Projects — CST Studio Suite

This repository contains **RF and antenna design projects** developed using **CST Studio Suite**, focusing on modern compact antennas and metamaterial-inspired structures for wireless communication applications.

---

## 🛰️ Tools & Software Used

- CST Studio Suite (Time Domain / Frequency Domain Solver)
- 3D EM Simulation & Optimization
- S-Parameter and Radiation Pattern Analysis

---

## 📂 Projects Included

### 1. Split Ring Resonator (SRR) Antenna

The **Split Ring Resonator (SRR)** antenna is a metamaterial-inspired structure used to achieve compact size and resonance control.

**Key Features:**

- Compact geometry
- High-Q resonance behavior
- Used for band-stop / band-pass / filtering antenna structures

**Analysis Performed:**

- Return Loss (S11)
- Surface Current Distribution
- Resonant Frequency Analysis
- Parametric Sweep

📁 Folder:

srr_antenna/

---

### 2. Fractal Antenna

This project implements a **Fractal Antenna**, designed to achieve multi-band or wideband performance using self-similar geometrical patterns.

**Key Features:**

- Space-filling geometry
- Multi-band behavior
- Miniaturization of antenna size

**Analysis Performed:**

- Frequency vs Return Loss
- Gain and Radiation Pattern
- Bandwidth Evaluation

📁 Folder:

fractal_antenna/

---

### 3. Microstrip Patch Antenna

A **Rectangular Microstrip Patch Antenna** designed for standard wireless applications.

**Key Features:**

- Lightweight and low-profile structure
- Easy fabrication
- Suitable for WLAN / ISM band applications

**Analysis Performed:**

- S11 (Return Loss)
- VSWR
- Far-field radiation pattern
- Directivity and Gain

📁 Folder:

patch_antenna/

---

## 📁 Repository Structure

antenna-design-cst/ │── README.md │ ├── srr_antenna/ │   ├── cst_files/ │   ├── screenshots/ │   └── results/ │ ├── fractal_antenna/ │   ├── cst_files/ │   ├── screenshots/ │   └── results/ │ ├── patch_antenna/ │   ├── cst_files/ │   ├── screenshots/ │   └── results/ │ └── docs/

---

## 📊 Simulation Parameters

Typical simulation parameters used across projects:

- Frequency Range: 1 GHz – 10 GHz
- Substrate: FR4 / Rogers (variable across designs)
- Boundary Conditions: Open (add space)
- Excitation Type: Discrete / Waveguide Port

---

## 🧪 Results & Validation

Each project contains:

- S-parameter plots (S11)
- VSWR plots
- Radiation pattern plots
- 3D field distributions

You can find them inside each project’s `results/` or `screenshots/` folder.

---

## 📷 Example Image Usage

To display results/screenshots in README:

```markdown
![S11 Plot](patch_antenna/results/s11_plot.png)
![Radiation Pattern](fractal_antenna/results/radiation_pattern.png)


---

🎯 Learning Outcomes

This repository demonstrates practical experience in:

RF and microwave antenna design

Electromagnetic simulation

Metamaterial-inspired antenna structures

Compact and multi-band antenna engineering



---

📄 License

This project is intended for educational and research purposes.


---

🤝 Contributions

Suggestions, improvements, and collaborations are welcome.

---  

Acknowledgements   

Kumud Sir and Arashdeep Sir.
