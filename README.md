# Kush Rishi

Engineer working across **machine learning, research engineering, intelligent sensing, and reliable software systems**.

I am a Geomatics Engineering graduate and GNSS Analyst at Xona. My background spans software engineering, positioning/navigation, estimation, sensing, measurement systems, and independent ML research. I am especially interested in systems where model behavior, uncertainty, evidence, and real-world measurement quality need to be tested rather than assumed.

## Flagship Research

### [Model Regression Forensics](https://github.com/Kushrishi/model-regression-forensics)

Independent ML research focused on a practical debugging question:

> **When a model regresses after retraining, can we identify which training change caused it?**

The project uses controlled fine-tuning experiments, behavioral evaluation, candidate ranking, retraining interventions, and explicit verification to distinguish suspicious training changes from changes that actually recover affected behavior.

The work has progressed through multiple experiment generations, including cases where localization succeeded but unique causal certification did not. Current work is moving toward more realistic natural-language regression settings with explicit variability controls.

[Research page](https://kushrishi.com/research/model-regression-forensics)

## Selected Private Research

### TrueMargin

Medical-imaging research on whether registration uncertainty is actually calibrated and informative about spatial error. The project combines public medical imaging, deformable registration, uncertainty estimation, patient-level evaluation, conformal methods, known-ground-truth validation, reproducibility tooling, and explicit investigation of failure modes.

**Status:** private research; validation and methodology work ongoing. No clinical-use claims.

### Restoration Interface Sensing

Research into longitudinal optical sensing around existing dental restorations. The project asks whether repeated SWIR measurements can separate meaningful physical change from positioning, hydration, illumination, and other measurement variability.

Public-data validation, cross-wavelength registration, and a held-out nuisance-robustness study have been completed. Physical bench repeatability is the next scientific gate.

**Status:** early private research. No diagnostic or clinical-use claims.

## Selected Engineering Work

### [CareBridge Canada](https://github.com/Kushrishi/carebridge-canada)

Healthcare-continuity product ecosystem with two deliberately separate layers:

- a **public React/TypeScript concept demo** using synthetic data and deterministic logic; and
- a **private FastAPI/SQL/RAG systems prototype** exploring source-note chunking, retrieval-backed generation, OpenAI Responses integration, provider controls, validation, auditability, and safety-aware workflows.

The public repository demonstrates the product experience; it does **not** contain the private backend or live AI implementation.

### [Autonomy Simulation Lab](https://github.com/Kushrishi/autonomy-simulation-lab)

Completed v1.0 autonomy/localization environment combining BFS, A*, Dijkstra, weighted planning, dynamic replanning, noisy sensing, nonlinear range least squares, Kalman filtering, telemetry, automated testing, CI, and a deployed browser demo.

## Current Focus

- ML systems and research engineering
- model evaluation, debugging, and reliability
- uncertainty and calibration
- evidence-grounded AI systems
- multimodal and intelligent sensing
- reproducible experimentation with real-world data

## Technical Stack

- **Languages:** Python, TypeScript, C++, SQL
- **ML / AI:** PyTorch, Hugging Face Transformers, PEFT/LoRA, fine-tuning, model evaluation, RAG, LLM APIs
- **Engineering:** Linux, Git, Docker, FastAPI, REST APIs, testing, CI/CD, SQL/data systems
- **Research:** experimental design, reproducible evaluation, uncertainty/calibration, signal processing, measurement validation
- **Domain foundations:** PNT/GNSS, estimation, sensing, spatial measurement

## Links

[Portfolio](https://kushrishi.com) · [LinkedIn](https://www.linkedin.com/in/kushrishi/) · [Model Regression Forensics](https://github.com/Kushrishi/model-regression-forensics)
