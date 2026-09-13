# Kush Rishi

Engineer working across **machine learning, research engineering, intelligent sensing, and reliable software systems**.

I am a Geomatics Engineering graduate and GNSS Analyst at Xona. My background spans software engineering, positioning/navigation, estimation, sensing, measurement systems, and independent ML research. I am especially interested in systems where model behavior, uncertainty, evidence, and real-world measurement quality need to be tested rather than assumed.

## Flagship Research

### [Model Regression Forensics](https://github.com/Kushrishi/model-regression-forensics)

Independent ML research focused on a practical debugging question:

> **When a model regresses after retraining, can we identify which training change caused it?**

The project uses controlled training experiments, behavioral evaluation, candidate ranking, counterfactual retraining, and explicit verification to distinguish suspicious training changes from changes that actually recover affected behavior.

Experiments 000–008 built a controlled synthetic test series and exposed an important limitation: the planted root could be localized and its restoration could fully recover the target while non-root restorations also produced material recovery. Experiment 009 is now moving to a natural-language Banking77 setting with prospectively frozen regression gates, paired training trajectories, and explicit stochastic-variability controls.

[Research page](https://kushrishi.com/research/model-regression-forensics)

## Active Private Research

### TrueMargin

Medical-imaging research asking whether registration uncertainty is not only calibrated in aggregate, but actually informative about spatial registration error point-by-point. The project combines public medical imaging, deformable registration, uncertainty estimation, patient-level evaluation, prospective protocols, known-deformation validation, reproducibility tooling, and explicit investigation of failure modes.

A prospectively corrected intensity-perturbation ensemble did not meet its frozen promotion criteria, and that negative result was preserved rather than tuned away. Current work is testing registration convergence before the next uncertainty mechanism is selected prospectively.

**Status:** private research; active validation and methodology work. No clinical-use claims.

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
- uncertainty, calibration, and scientific ML
- evidence-grounded and agentic AI systems
- reproducible experimentation and model lifecycle tooling
- intelligent sensing, estimation, and physical-world measurement

## Technical Stack

- **Languages:** Python, TypeScript, C++, SQL
- **ML / AI:** PyTorch, Hugging Face Transformers, PEFT/LoRA, fine-tuning, model evaluation, RAG, LLM APIs
- **Engineering:** Linux, Git, Docker, FastAPI, REST APIs, testing, CI/CD, SQL/data systems
- **Research:** experimental design, reproducible evaluation, uncertainty/calibration, medical-image registration, signal processing, measurement validation
- **Domain foundations:** PNT/GNSS, estimation, sensing, spatial measurement

## Links

[Portfolio](https://kushrishi.com) · [LinkedIn](https://www.linkedin.com/in/kushrishi/) · [Model Regression Forensics](https://github.com/Kushrishi/model-regression-forensics)
