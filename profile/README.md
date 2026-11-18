# Noether Labs

**Adaptive optics for satellite-to-ground laser links.**

We develop differentiable optical models, calibration methods, and predictive
and learned controllers for optical receivers. Our first application is helping
ground stations maintain useful received light as turbulence, pointing and
instrument response change.

### Research

| Project | Work |
| --- | --- |
| [Noether AO](https://github.com/noetherlabs/noether-ao) | Differentiable wave propagation, sensor validation, predictive and learned controller comparisons, recovery experiments. |
| [Noether Twin](https://github.com/noetherlabs/noether-twin) | Optical-model calibration, registration and prediction of held-out measurements. |
| [ProbeBench](https://github.com/noetherlabs/probebench) | Sequential calibration and measurement selection under photon and exposure budgets. |
| [Noether Replay](https://github.com/noetherlabs/noether-replay) | Offline telemetry reconstruction; timing, calibration and applied-command evidence. |
| [Noether Link Audit](https://github.com/noetherlabs/noether-link-audit) | Spatial fiber overlap, model-conditional loss analysis and a receiver evaluation protocol. |

### Start with the evidence

[**Prediction Boundary**](https://www.noether.one/research/prediction-boundary)
reports 600 held-out simulated trials. Prediction improved wavefront error
against a tuned integrator in five of twelve conditions; seven comparisons
remained uncertain. The learned mixture did not outperform both reference
controllers. The paper includes complete paired comparisons and a reproduction
notebook.

Our [**receiver pilot protocol**](https://github.com/noetherlabs/noether-link-audit/blob/main/docs/receiver-pilot.md)
connects these components: qualify a recording, identify the receiver response,
compare controllers in shadow mode, then measure outcomes in a controlled bench
experiment. It specifies the data, baselines and acceptance decisions needed
before a receiver-specific study can begin.

Reports retain assumptions, provenance and negative results. Public evidence
currently covers simulation, numerical model checks and offline telemetry.
It does not establish improved satellite-link throughput, hardware reliability
or safe autonomous operation. A prospective pilot is not a deployed system.

[Research](https://www.noether.one/research) · [Contact](mailto:founders@noether.one)
