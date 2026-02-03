# Supplementary Visualizations for Our TAES Paper

This repository hosts **supplementary trajectory visualizations** (GIF/PNG) accompanying our IEEE TAES submission on long-horizon stratospheric airship trajectory planning under forecast-uncertain wind fields.

> **Paper (TODO):** *[Full Paper Title]*, IEEE Transactions on Aerospace and Electronic Systems (TAES), Year.  
> **Method (TODO):** *[e.g., POMDP + Asymmetric Actor–Critic + LSTM]*  
> **Project page / preprint (optional, TODO):** *[arXiv / DOI]*

---

## What’s Inside

- **Trajectory animations (GIF):** qualitative comparisons across methods, lead times, and OOD settings.
- **High-resolution figures (PNG):** publication-ready visuals for the paper appendix/supplement.
- **(Optional) Rendering scripts:** lightweight utilities to convert rollout logs into PNG/GIF.

This repository is intentionally **minimal** and focuses on *visual evidence* rather than full training code.

---

## Repository Structure

A recommended layout (adapt to your actual files):


> If your GIF/PNG files are large, consider using **Git LFS**.

---

## Quick Preview

### Key Trajectory Comparisons

> Replace the filenames below with your actual paths.

**Algorithms**
![Algorithms comparison](assets/traj_vis_algo.png)

**Lead-time sweep (0–48h)**
![Lead-time sweep](assets/traj_vis_lead_time.png)

---

## Naming Conventions (Suggested)

To keep things searchable and consistent:

- `traj_compare_<setting>.png` / `.gif`
- `<setting>` examples:
  - `origin`
  - `temporal_ood_YYYYMM`
  - `spatial_ood_regionA_to_regionB`
  - `altitude_70hPa`
  - `forecast_source_graphcast`
  - `leadtime_0_48h_step6h`

If you have multiple algorithms per figure, encode them in a short tag:
- `..._aac_lstm_vs_baselines.gif`
- `..._pomdp_vs_mdp.gif`

---

## How to View

- GIFs and PNGs are directly viewable on GitHub under `assets/`.
- For local viewing:
  - GIF: any browser
  - PNG: any image viewer

---
