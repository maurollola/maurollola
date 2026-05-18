# Hi, I'm Mauro Llorens La Torre 👋
### Neuroengineer, DSP Architect & Bio-AI Pioneer

I am a systems and research engineer dedicated to decoding human physiological signals. I build clinical-grade algorithms, real-time spatial decoders, and digital signal processing (DSP) pipelines that bridge the gap between human biology and advanced computing. My ultimate mission is to design state-of-the-art contact and contactless biosensing systems that redefine non-invasive clinical care and Brain-Computer Interfaces (BCI).

---

## 🧬 Core Bio-Sensing Engines (Scientific Highlights)

### 🩺 **PasiveVital: Contactless mmWave Radar Vital Engine**
*An advanced 60GHz FMCW MIMO radar processing suite for real-time, contactless extraction of ECG-grade Heart Rate (HR) and Respiration Rate (RR).*
*   **Clinical Benchmark:** Validated against a medical 3-lead gold-standard reference ECG over a **110-subject clinical trial dataset** (Zenodo ID: 18599983), achieving a **Mean Absolute Error (MAE) of 2.62 BPM** (exceeding clinical acceptability standards of < 3 BPM).
*   **Mathematical Core:** Adaptive MVDR (Minimum Variance Distortionless Response) spatial beamforming, time-domain adaptive Notch harmonic supressor (1x to 8x respiratory harmonics), Complex Phase Unwrapping, and Burg's Maximum Entropy Spectral Estimation.
*   **Software Quality:** 100% test coverage with Python (`pytest`) mocking real-time hardware bitstreams and multi-channel LVDS desinterleaving.
*   **Repository:** [maurollola/bio_IA](https://github.com/maurollola/bio_IA) (Public Portfolio Showcase)

### 📲 **PulseMetrics: Medical-Grade rPPG iOS Engine**
*A proprietary, hardware-accelerated vital sensing engine utilizing standard mobile front camera feeds to extract cardiac metrics.*
*   **Clinical Benchmark (UBFC-rPPG Public Dataset):**
    *   **RMSE:** `3.17 BPM` 📉
    *   **MAE:** `2.68 BPM` 📉
    *   **Pearson Correlation (r):** `0.978` 📈 *(Outperforms deep learning SOTA like MTTS-CAN NeurIPS [8.87 RMSE] and POS/CHROM baselines).*
*   **Core Tech:** Kalman-adaptive chrominance signal extraction, Apple vDSP hardware acceleration, and dynamic ambient illumination filtering.
*   *Note: Due to Intellectual Property (IP) and commercial protection, the source code of the PulseMetrics native iOS application and mathematical core remains in a private repository.*

---

## 🛠️ Technical Arsenal & Engineering Architecture

```
                    ┌──────────────────────────────────────────────┐
                    │          MAURO LLORENS LA TORRE              │
                    └──────────────────────┬───────────────────────┘
                                           │
         ┌─────────────────────────────────┼────────────────────────────────┐
         ▼                                 ▼                                ▼
 ┌───────────────┐                 ┌───────────────┐                ┌───────────────┐
 │   DSP CORE    │                 │ BCI & DECODING│                │    BIO-AI     │
 └───────┬───────┘                 └───────┬───────┘                 └───────┬───────┘
         │                                 │                                │
         ├─ MVDR Spatial Beamforming       ├─ CSP (Common Spatial Patterns) ├─ EEGNet / ShallowFBCNet
         ├─ Burg Spectral Estimation       ├─ Riemannian Geometry Manifolds ├─ 1D CNNs & Temporal Attention
         ├─ Wavelet Transform (CWT/VMD)    ├─ LSL Real-Time Synchronization ├─ Contrastive Learning (SSL)
         └─ Adaptive Clutter Removal       └─ ICA & ASR Artifact Cleaning   └─ Synthetic Data (GANs/Diff)
```

### 🛰️ Digital Signal Processing (DSP)
*   **Spatial Array Processing:** MVDR Spatial Beamforming, Delay-and-Sum beam steering, multi-antenna MIMO radar array phase calibration.
*   **Spectral Estimation & Filtering:** Burg's Maximum Entropy Method, Welch Periodogram, MUSIC (Multiple Signal Classification), Variational Mode Decomposition (VMD), Chebyshev/Butterworth filters.
*   **Time-Frequency Analysis:** Continuous & Discrete Wavelet Transforms (CWT / DWT) for non-stationary biological signal analysis.

### 🧠 Brain-Computer Interfaces (BCI) & Neuro-Decoding
*   **Manifold & Geometry Learning:** SOTA Riemannian Geometry classification of spatial covariance matrices directly on the Riemannian manifold (invariance to hardware drift).
*   **Feature Extraction:** Common Spatial Patterns (CSP), Filter Bank Common Spatial Patterns (FBCSP), Autoregressive modeling of EEG/EMG.
*   **Signal De-noising:** Independent Component Analysis (ICA) for ocular artifact removal, Artifact Subspace Reconstruction (ASR) for high-amplitude movement rejection.
*   **Real-time Streaming:** Lab Streaming Layer (LSL) integration for microsecond-precise hardware-software multi-modal sensor synchronization.

### 🤖 Bio-AI & Deep Learning for 1D Signals
*   **Neural Networks:** 1D Convolutions, Temporal Attention Mechanism, EEGNet, ResNet-1D architectures.
*   **Self-Supervised Learning (SSL):** Unsupervised pre-training using contrastive learning models optimized for raw physiological time-series data.
*   **Generative AI:** Synthetic EEG/ECG signal augmentation via GANs and 1D Diffusion models.

### 💻 Systems Engineering & Software Quality
*   **Architecture:** Hexagonal/Clean Architecture, SOLID Principles, clean separation between domain logic (pure DSP math) and adapters (radar/sensor serial acquisitions).
*   **Performance:** Python (NumPy, SciPy), Rust-to-Python bindings (`PyO3`), hardware-accelerated processing via Apple Accelerate framework (vDSP).
*   **Methodology:** Test-Driven Development (TDD) for mission-critical medical code, Git/GitHub CI/CD pipelines.

---

## 📈 Current Focus & Research Interests
*   **Low-cost EEG integration:** Decoding motor imagery and visual evoked potentials (SSVEP) using dry electrodes.
*   **Hybrid Sensing:** Combining radar RF micro-movements and rPPG visual signals to build a redundant, highly-resilient clinical patient monitor.
*   **Regulatory Compliance:** Designing software following IEC 62304 (Medical Device Software Life Cycle) and ISO 13485 (Medical Quality Management Systems).

---

## 📫 Connect with me

*   💼 **LinkedIn:** [linkedin.com/in/mauro-llorens-10a67628a](https://www.linkedin.com/in/mauro-llorens-10a67628a/)
*   📍 **Location:** Alicante / Barcelona, Spain
*   ✉️ **Email:** [maurollorensl@gmail.com](mailto:maurollorensl@gmail.com)
