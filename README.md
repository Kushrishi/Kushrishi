# Kush Rishi

Engineer working across **machine learning, software systems, PNT/GNSS, and intelligent sensing**.

My background is in Geomatics Engineering, navigation, sensing, measurement systems, and software development. I am especially interested in ML systems, model reliability, and software that has to work with imperfect real-world data.

## Current Research

### [Model Regression Forensics](https://github.com/Kushrishi/model-regression-forensics)

I am researching a simple ML debugging question:

> **When a model gets worse after retraining, can we figure out which training change caused it?**

The project compares changes in model behavior with changes made during training. It ranks possible causes, then tests those guesses by reversing individual changes and retraining the model.

That last step matters. I do not want to call something the cause just because it looks suspicious. If reversing that change repairs the model while reversing the others does not, the diagnosis is much stronger.

**Current progress:**

- Early experiments exposed shortcuts that could make a debugging method look better than it really was.
- Later experiments showed that correctly identifying a suspicious change does not necessarily mean it caused the failure.
- Experiments 005–007 exposed problems with how the test regressions themselves were being created.
- **Experiment 008 is active.** Its setup was fixed before training began, the clean reference model scored **96/96**, and the changed models are now being evaluated.

[Read the research page →](https://kushrishi.com/research/model-regression-forensics)

## Selected Engineering Work

### [Autonomy Simulation Lab](https://github.com/Kushrishi/autonomy-simulation-lab)

Interactive autonomy and localization environment combining path planning, dynamic replanning, noisy sensing, nonlinear localization, Kalman filtering, telemetry, evaluation, and automated testing.

### [CareBridge Canada](https://github.com/Kushrishi/carebridge-canada)

Full-stack product prototype exploring source-grounded and safety-aware AI workflows using React, TypeScript, FastAPI, SQL, automated testing, and CI/CD.

## Current Focus

- ML systems and research engineering
- Model evaluation, debugging, and reliability
- Multimodal and intelligent sensing
- PNT/GNSS, estimation, and real-world measurement systems

## Tools

**Languages:** Python, TypeScript, C++, SQL
**ML / Data:** PyTorch, fine-tuning, model evaluation, experiment design, data analysis
**Engineering:** Linux, Git, Docker, APIs, testing, CI/CD
**Domain:** PNT/GNSS, estimation, sensing, spatial measurement

## Links

[Portfolio](https://kushrishi.com) · [LinkedIn](https://www.linkedin.com/in/kushrishi/) · [Research](https://github.com/Kushrishi/model-regression-forensics)
