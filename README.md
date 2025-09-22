

# 6T SRAM Cell Design in 65nm CMOS

This project implements a **6T SRAM cell** in **65nm CMOS technology**, focusing on transistor sizing, stability analysis, and functional verification. The design methodology ensures robust operation, reliable data storage, and improved read performance using a custom sense amplifier.

---

## 🔑 Features

* **Transistor Sizing Optimization**

  * Balanced readability and writability through careful tuning of **cell ratio** and **pull-up ratio**.
* **Stability Analysis**

  * Performed **butterfly curve extraction** to evaluate Static Noise Margin (SNM) and assess cell robustness.
* **Functional Verification**

  * Verified **read/write operations** by controlling bitlines and wordlines across typical operating scenarios.
* **High-Speed Sensing**

---

## 🛠️ Technology & Tools

* **Process Technology**: 65nm CMOS
* **Simulation Tools**: (e.g., Cadence Virtuoso, HSPICE, LTSpice — replace with yours)
* **Design Methods**: Circuit-level transistor optimization, SNM evaluation, transient simulations

---

## 📊 Results

* Extracted **butterfly curves** showing improved noise margin.
* Verified correct **read/write cycles** with controlled bitline and wordline operations.
* Achieved faster read speed with integrated **sense amplifier**.

(Add screenshots/plots of simulation waveforms, butterfly curves, or schematics here for better visualization.)

---

## 🚀 Applications

* Embedded memory systems
* High-speed cache design
* Scalable SRAM array architectures

---

## 📂 Repository Structure

```
├── /schematics        # Circuit schematics
├── /simulation        # Simulation testbenches and results
└── README.md          # Project description
```

