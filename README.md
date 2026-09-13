# Kush Rishi

GNSS Analyst at Xona and Geomatics Engineering graduate working across **machine learning, software systems, intelligent sensing, and model evaluation**.

My background spans positioning and estimation, sensing, measurement systems, production software, and independent ML research. Much of my work comes back to the same question: **how do we know when a model, estimate, or measurement is wrong?**

## Flagship Research

### [Model Regression Forensics](https://github.com/Kushrishi/model-regression-forensics)

Independent ML research focused on a practical debugging question:

> **When a model regresses after retraining, can we identify which training change caused it?**

The project uses controlled training experiments, behavioral evaluation, candidate ranking, and counterfactual retraining to separate a plausible explanation from one that actually survives intervention.

Experiments 000–008 built a controlled synthetic test series. In Experiment 008, the planted root was localized and restoring it fully recovered the target, but some non-root restorations also produced material recovery. Experiment 009 is now testing the method on a natural-language Banking77 task with paired training trajectories and explicit retraining-variability controls.

[Research page](https://kushrishi.com/research/model-regression-forensics)

## Active Private Research

### TrueMargin

Medical-imaging research asking whether registration uncertainty is actually informative about spatial error at specific locations, rather than only looking reasonable in aggregate.

An audit found that the historical intensity perturbation was likely too small to probe meaningful registration sensitivity. A scale-aware replacement was defined before testing, but none of the frozen settings passed the promotion gate. That negative result was kept. Current work is testing registration convergence before another uncertainty method is chosen.

**Status:** private research; active validation and methodology work. No clinical-use claims.

[Research page](https://kushrishi.com/research/truemargin)

## Selected Engineering Work

### [CareBridge Canada](https://github.com/Kushrishi/carebridge-canada)

Healthcare-continuity prototype with two deliberately separate layers:

- a **public React/TypeScript concept demo** using synthetic data and deterministic logic; and
- a **private FastAPI/SQL retrieval-backed AI prototype** for source-note retrieval, grounded generation, structured validation, audit trails, and runtime safety controls.

The public repository shows the product experience; it does **not** contain the private backend or live AI implementation.

### [Autonomy Simulation Lab](https://github.com/Kushrishi/autonomy-simulation-lab)

Completed v1.0 autonomy/localization environment combining BFS, A*, Dijkstra, weighted planning, dynamic replanning, noisy sensing, nonlinear range least squares, Kalman filtering, telemetry, automated testing, CI, and a deployed browser demo.

## Technical Stack

- **Languages:** Python, TypeScript, C++, SQL
- **ML:** PyTorch, Hugging Face Transformers, PEFT/LoRA, fine-tuning, model evaluation, RAG
- **Engineering:** Linux, Git, Docker, FastAPI, REST APIs, testing, CI/CD, data systems
- **Methods:** experimental design, uncertainty/calibration, estimation, signal processing, reproducible evaluation
- **Domains:** PNT/GNSS, medical imaging, intelligent sensing

## Links

[Portfolio](https://kushrishi.com) · [LinkedIn](https://www.linkedin.com/in/kushrishi/) · [Model Regression Forensics](https://github.com/Kushrishi/model-regression-forensics)
