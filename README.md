# Kush Rishi

Engineer working across **machine learning, software systems, PNT/GNSS, and intelligent sensing**.

My background is in Geomatics Engineering, positioning and navigation, measurement systems, and software development. I am building deeper ML and research-engineering experience through independent work on model evaluation, post-training behavior, regression diagnosis, and reproducible ML experimentation.

## Current Research

### [Model Regression Forensics](https://github.com/Kushrishi/model-regression-forensics)

Research project investigating whether behavioral regressions between model checkpoints can be traced through training lineage to plausible causes and then verified through controlled counterfactual intervention.

The project uses controlled LoRA fine-tuning experiments, prospectively frozen benchmark construction, truth-isolated diagnostic ranking, held-out evaluation, runtime provenance, and selective restoration.

**Progress so far:**
- Experiment 001 exposed a lexical shortcut that could make diagnosis appear stronger than it was.
- Experiment 002 neutralized that shortcut; changed-record analysis still localized the hidden cause, and selective restoration recovered the target behavior with recorded spillover.
- Experiment 003 deliberately stopped when its clean baseline failed; follow-up capability tests isolated the failure boundary and explicit-policy role binding reached **96/96 held-out accuracy**.
- Experiment 004 showed that correct localization is not enough: the intended shard was ranked correctly, but restoring it produced no target recovery.
- Experiments 005 and 006 showed that aggregate and semantic balancing still do not guarantee a valid localized regression.
- Experiment 007 produced material target regressions during calibration, but locality failed, so causal certification did not proceed.
- **Experiment 008 is active:** its two-world protocol was frozen before model training, the clean baseline scored **96/96**, and frozen candidate evaluation is underway.

[Research page →](https://kushrishi.com/research/model-regression-forensics)

## Selected Engineering Work

### [Autonomy Simulation Lab](https://github.com/Kushrishi/autonomy-simulation-lab)

Interactive autonomy and localization environment combining path planning, dynamic replanning, noisy sensing, nonlinear range-based localization, Kalman filtering, telemetry, quantitative evaluation, and automated testing.

### [CareBridge Canada](https://github.com/Kushrishi/carebridge-canada)

Full-stack product prototype exploring source-grounded and safety-aware AI workflows using React, TypeScript, FastAPI, SQL, automated testing, and CI/CD.

### [kushrishi.com](https://kushrishi.com)

Personal research and engineering portfolio covering machine learning, software systems, PNT/GNSS, intelligent sensing, and reliable models under uncertainty.

## Current Focus

- Model evaluation, regression analysis, and reliable ML
- ML systems and research engineering
- Multimodal and intelligent sensing
- PNT/GNSS, estimation, and real-world measurement systems

## Tools

**Languages:** Python, TypeScript, C++, SQL  
**ML / Data:** PyTorch, model evaluation, fine-tuning, experiment design, data analysis  
**Engineering:** Linux, Git, Docker, APIs, testing, CI/CD  
**Domain:** PNT/GNSS, estimation, sensing, spatial measurement

## Links

[Portfolio](https://kushrishi.com) · [LinkedIn](https://www.linkedin.com/in/kushrishi/) · [Model Regression Forensics](https://github.com/Kushrishi/model-regression-forensics)
