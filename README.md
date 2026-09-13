# Kush Rishi

Engineer working across **machine learning, software systems, PNT/GNSS, and intelligent sensing**.

I am a Geomatics Engineering graduate and GNSS Analyst at Xona. My background spans positioning, navigation, sensing, estimation, measurement systems, and software development. I am particularly interested in ML systems, intelligent sensing, and engineering problems where reliability, evaluation, and real-world data matter.

## Current Research

### [Model Regression Forensics](https://github.com/Kushrishi/model-regression-forensics)

Model Regression Forensics is an independent ML research project focused on a practical debugging question:

> **When a model regresses after retraining, can we identify which training change caused it?**

The project compares model behavior across training runs, records the training changes that could explain a regression, ranks plausible causes, and then tests those diagnoses by reversing individual changes and retraining the model.

This distinction between ranking and verification is central to the project. A training change is not treated as the cause simply because it appears suspicious. The stronger test is whether reversing that change actually restores the affected behavior.

**Current progress:**

- Experiments 000 through 008 are complete.
- Earlier experiments exposed misleading lexical shortcuts, invalid clean baselines, and cases where correct localization did not produce recovery.
- Experiment 008 produced target-localized regressions in both frozen worlds and the task-aware diagnostic uniquely ranked the planted root first in both.
- Restoring the planted root fully repaired the target with no protected-behavior degradation in both worlds, but some non-root restorations also produced material recovery, so unique causal certification failed.
- The next phase moves to a more realistic natural-language regression setting with repeated, paired retraining and explicit variability controls.

[Research page](https://kushrishi.com/research/model-regression-forensics)

### Restoration Interface Sensing

Independent research into longitudinal optical sensing around existing dental restorations.

The project investigates whether repeated optical measurements can distinguish meaningful physical change from positioning, hydration, and other measurement variability.

The work is being approached as a measurement problem first: establish repeatable acquisition, then determine whether biologically meaningful change can be separated from nuisance variation.

**Current progress:**

- Public SWIR and micro-CT dental datasets have been validated and paired into a clean technical cohort.
- Cross-wavelength registration and micro-CT decoding pipelines have been validated.
- The experimental protocol was frozen before physical testing.
- Single-channel bench repeatability testing is the next stage.

**Status:** Early technical validation. No clinical diagnostic claims are being made.

## Selected Engineering Work

### [Autonomy Simulation Lab](https://github.com/Kushrishi/autonomy-simulation-lab)

Interactive autonomy and localization environment combining path planning, dynamic replanning, noisy sensing, nonlinear localization, Kalman filtering, telemetry, quantitative evaluation, and automated testing.

### [CareBridge Canada](https://github.com/Kushrishi/carebridge-canada)

Full-stack product prototype exploring source-grounded and safety-aware AI workflows using React, TypeScript, FastAPI, SQL, automated testing, and CI/CD.

## Current Focus

- ML systems and research engineering
- Model evaluation, debugging, and reliability
- Multimodal learning and intelligent sensing
- Biomedical and optical sensing
- PNT/GNSS, estimation, and real-world measurement systems

## Technical Stack

- **Languages:** Python, TypeScript, C++, SQL
- **ML:** PyTorch, Hugging Face Transformers, PEFT/LoRA, fine-tuning, model evaluation
- **Engineering:** Linux, Git, Docker, APIs, testing, CI/CD
- **Research:** experimental design, reproducible evaluation, signal processing, measurement validation
- **Domain:** PNT/GNSS, estimation, sensing, spatial measurement

## Links

[Portfolio](https://kushrishi.com) · [LinkedIn](https://www.linkedin.com/in/kushrishi/) · [Model Regression Forensics](https://github.com/Kushrishi/model-regression-forensics)
