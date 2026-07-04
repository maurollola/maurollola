# Hi, I'm Mauro Llorens La Torre 👋

Systems & research engineer focused on decoding human physiological signals through digital signal processing (DSP), contactless biosensing, and Brain-Computer Interfaces (BCI).

---

## 🗺️ Repository Guide

### 📡 [bio_IA](https://github.com/maurollola/bio_IA) — PasiveVital: Contactless mmWave Radar Engine
**Personal project · Built by vocation in my free time**

A 60GHz FMCW MIMO radar processing engine for contactless extraction of Heart Rate (HR) and Respiration Rate (RR). Designed for elderly care and residential monitoring without wearables.

| Metric | Result |
| :--- | :---: |
| **MAE** | 2.82 BPM |
| **RMSE** | 5.37 BPM |
| **Pearson (r)** | 0.922 |
| **Dataset** | 3GHz FMCW · 2 subjects · 48 recordings · 9 spatial positions |

**Key achievements:**
- Achieved clinical-grade accuracy (MAE < 3 BPM) using classical DSP — no deep learning required.
- 100% test coverage with `pytest`, mocking real-time radar hardware bitstreams.
- Clean Architecture (Hexagonal) separating pure DSP math from hardware adapters.

---

### 📊 [PulseMetrics-Showcase](https://github.com/maurollola/PulseMetrics-Showcase) — rPPG Clinical Evaluation
**Biomedical Engineering Internship · Universitat Rovira i Virgili (URV) · IRCV Group · 2026**

Results-only showcase for PulseMetrics: a proprietary rPPG engine that estimates heart rate from a standard webcam or iPhone front camera, validated on the UBFC-rPPG public clinical dataset.

| Metric | Result |
| :--- | :---: |
| **MAE** | 2.68 BPM |
| **RMSE** | 3.17 BPM |
| **Pearson (r)** | 0.978 |
| **Benchmark** | UBFC-rPPG · vs 7 SOTA algorithms including MTTS-CAN (NeurIPS) |

**Key achievements:**
- Outperforms all tested deep learning and classical baselines (POS, CHROM, GREEN, ICA, MTTS-CAN).
- Native iOS application in Swift using Apple Accelerate (vDSP) for real-time processing.
- Full Bland-Altman clinical concordance analysis and per-subject temporal Pearson evaluation.
- Source code is private due to IP protection. This repo contains only figures, benchmark tables, and scientific validation.

> Developed in collaboration with the **IRCV Group (Image Recognition and Computer Vision)** at URV.
> Private repositories: [maurollola/RPPG_Project](https://github.com/maurollola/RPPG_Project) / [ircv-group/rPPG-Mauro](https://github.com/ircv-group/rPPG-Mauro)

---

### 🧠 [SistemaRecomendaciones](https://github.com/maurollola/SistemaRecomendaciones) — Recommendation Engine
**University coursework**

Intelligent recommendation system using collaborative filtering and content-based techniques in Jupyter Notebook.

---

### ⚽ [BaseDatos-LaLiga-](https://github.com/maurollola/BaseDatos-LaLiga-) — LaLiga Database
**University coursework**

Relational database design and SQL query optimization modeling Spanish Football League metrics.

---

## 🛠️ Technical Focus Areas

| Domain | Tools & Techniques |
| :--- | :--- |
| **DSP** | MVDR Beamforming, Burg Spectral Estimation, Wavelet Transforms, Butterworth/Chebyshev filters |
| **BCI** | Common Spatial Patterns (CSP), Riemannian Geometry, ICA artifact removal, Lab Streaming Layer (LSL) |
| **Bio-AI** | EEGNet, 1D CNNs, Temporal Attention, contrastive self-supervised learning |
| **Engineering** | Hexagonal Architecture, SOLID, TDD, Python (NumPy/SciPy), Swift (vDSP), Rust (PyO3) |

---

## 📫 Contact

*   💼 **LinkedIn:** [linkedin.com/in/mauro-llorens-10a67628a](https://www.linkedin.com/in/mauro-llorens-10a67628a/)
*   📍 **Location:** Alicante / Barcelona, Spain
*   ✉️ **Email:** [maurollorensl@gmail.com](mailto:maurollorensl@gmail.com)
