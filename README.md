# S³F — Safety-Critical UAV Navigation

**Real-Time Optimisation-Based Safety-Critical UAV Navigation via a Sliding-Mode Reformulation of Barrier and Lyapunov Constraints**

🌐 **Project page:** https://wlaa41.github.io/s3f-safe-uav-navigation/

## TL;DR

CBF/CLF safe control normally requires solving a constrained QP at every control update.
**S³F** embeds the CLF inequality, HOCBF safety inequalities, and the optimality conditions
into a single nonlinear residual using the Fischer–Burmeister function, interprets its zero
set as an **optimality sliding manifold**, and drives the system onto it with a dedicated
reaching law — recovering the optimal safe control action **without a QP solver**, cutting
online computation time by up to **70%**.

## Highlights

- ✅ Provably safe: HOCBF measures ψ₁, ψ₂ remain non-negative throughout flight
- ⚡ Up to 70% faster than conventional QP-based safe control
- 🏔️ Validated in cluttered 3D environments with heterogeneous obstacles and safety margins
- 🎲 Paired Monte Carlo robustness studies under geometric and dynamic uncertainty
- 🚁 Real-UAV hardware experiments

## Repository contents

This repository currently hosts the **project website** (GitHub Pages).
Code and paper links will be added upon publication.

## Citation

```bibtex
@inproceedings{s3f2026,
  title     = {Real-Time Optimisation-Based Safety-Critical UAV Navigation
               via a Sliding-Mode Reformulation of Barrier and Lyapunov Constraints},
  author    = {Anonymous},
  booktitle = {Under review},
  year      = {2026},
  note      = {Project page: https://wlaa41.github.io/s3f-safe-uav-navigation/}
}
```
