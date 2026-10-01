# Kush Rishi

GNSS Analyst at Xona and Geomatics Engineering graduate working on **reliable machine learning and sensing systems under uncertainty**.

My foundation is in PNT/GNSS, sensing, estimation, and measurement systems. My independent research extends the same discipline into machine learning and medical image computing: define the failure precisely, separate signal from variability, test interventions prospectively, and keep claims inside the evidence.

## Flagship Research

### [TrueMargin](https://github.com/Kushrishi/truemargin)

Medical-image-computing research on whether local uncertainty from deformable image registration contains useful information about true local spatial error.

The source-pinned M4 known-ground-truth study completed across **30 synthetic cases and 10 held-out anatomies**. All **10 / 10** anatomy-level associations were positive, with median anatomy-level Spearman **0.6841** and a 95% anatomy-bootstrap interval of **[0.3048, 0.8284]**.

M5 is now complete and preserves the failure structure behind that aggregate result: **39 / 1,500** sampled locations met the frozen high-error/low-sigma blind-spot rule, and **6 / 30** deformation-specific case rankings were negative. The result remains deliberately bounded: the promoted uncertainty signal outperformed residual and Jacobian-deviation comparators on the paired rank statistic in this study, but **did not establish superiority over inverse-consistency error**. M6 is prospective calibration protocol design; numerical calibration remains unestablished.

[Research page](https://kushrishi.com/research/truemargin)

### [Model Regression Forensics](https://github.com/Kushrishi/model-regression-forensics)

Independent ML research asking what evidence is sufficient to identify the training change responsible for a model regression rather than a merely correlated one.

Experiment 009 uses Banking77, paired retraining trajectories, explicit stochastic controls, and counterfactual restoration. The development pilot produced consistent root-vs-nuisance restoration separation, then exposed a structural mismatch between root and nuisance candidates.

**M3 is now complete:** a prospectively constructed structurally matched benchmark contains two five-candidate worlds in which every candidate uses the same 66-slot label-only change structure. **M4 is active** and will test competitive localization baselines before any later causal-certification claim. Successful localization and causal specificity on the new matched benchmark remain unestablished.

[Research page](https://kushrishi.com/research/model-regression-forensics)

## Selected Engineering

### [Autonomy Simulation Lab](https://github.com/Kushrishi/autonomy-simulation-lab)

Completed v1.0 autonomy and localization environment combining weighted planning, dynamic replanning, noisy sensing, nonlinear range least-squares localization, Kalman filtering, telemetry, automated testing, CI, and a deployed browser demo.

### [CareBridge Canada](https://github.com/Kushrishi/carebridge-canada)

Healthcare-continuity prototype exploring source-grounded workflows, structured validation, auditability, and bounded AI behavior using synthetic data. The public React/TypeScript demo is intentionally separated from a private full-stack experimentation environment.

## Technical Focus

- **Reliable ML & evaluation:** behavioral testing, model regressions, counterfactual verification, uncertainty, reproducible experimentation
- **Sensing, estimation & localization:** PNT/GNSS, state estimation, sensor fusion, localization, physical-world measurement
- **Scientific & medical systems:** medical image registration, uncertainty analysis, controlled validation
- **Research engineering:** Python, PyTorch, Linux, Git, CI, data pipelines, experiment tooling; growing C++ systems depth

## Links

[Portfolio](https://kushrishi.com) · [LinkedIn](https://www.linkedin.com/in/kushrishi/) · [TrueMargin](https://github.com/Kushrishi/truemargin) · [Model Regression Forensics](https://github.com/Kushrishi/model-regression-forensics)
