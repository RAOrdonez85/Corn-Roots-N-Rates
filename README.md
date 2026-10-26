# Corn Roots by N Rate

**Dr. Raziel A. Ordóñez**, Plant Scientist and Root Biologist

An interactive teaching model of root development in **conventional tall corn** under three nitrogen rates: **0, 168 and 336 kg N ha⁻¹** (N0, N168, N336). It is built from real root data measured in the field over three seasons (2017, 2018 and 2019): 153 soil cores, three N rates, three replicates per sampling.

> **Simulated from a calibrated model.** Everything shown (plants, roots and values) is simulated by a model calibrated against the field measurements. It reproduces the measured patterns of root growth over the season and with depth. It is not a photograph or a plot of individual samples. The measured field means are shown as points on the root mass chart.

**Open the interactive page:** use the website link in the *About* section of this repository.

## What students can explore

- Whole plants and root systems from planting to day 140: two rows 75 cm apart, soil to 180 cm
- Root length density in each soil layer (0–15, 15–30, 30–60 … 150–180 cm)
- Roots from neighboring rows meeting between rows (predicted day for each N rate)
- Maximum rooting depth: 155 cm (N0), 160 cm (N168), 168 cm (N336)
- Root mass over the season, three seasons combined, with the field means
- Crown and brace roots, laterals with branches, root caps and root hairs
- Plant height (210 cm without N, 230 cm with N), tassel and ear; silking 5 days later without N

## How it is built

| Component | Basis |
|---|---|
| Root mass, root length density by layer, root fineness | Calibrated on 153 field soil cores, 2017–2019 |
| Rooting depth | Root front velocity 0.62 cm d⁻¹ until V5, then 3.12 cm d⁻¹ to the maximum depth |
| Row closure | Topsoil (0–30 cm) root length, 40-day reference |
| Plant height | Measured: 210 cm (N0), 230 cm (N168, N336) to the top collar at R1.5 |
| Silking (R1) | Day 77 with N, day 82 without N |
| Leaf and ear form; N-deficiency look of N0 (paler leaves, V-shaped yellowing, smaller ear) | Illustrative, not measured |

## Files

| File | What it is |
|---|---|
| `index.html` | The interactive page |
| `corn_roots_model.R` | R script: reads the field data, calibrates the model and draws the figures and time-lapse |
| `corn_roots_timelapse.mp4`, `corn_roots_timelapse.gif` | Time-lapse, planting to day 140 |
| `fig/` | Figures at days 20, 40, 65, 89 (R2), 115 and 140, root length density by layer and root mass over the season (PNG and JPG) |
| `LICENSE` | Copyright terms |

## Use on any device

Runs in any modern web browser on computers, tablets and smartphones. No installation or account needed.

## Copyright

© 2026 Dr. Raziel A. Ordóñez. All rights reserved. Provided for students enrolled in the course. Do not copy, modify, or redistribute without the author's written permission. See [LICENSE](LICENSE).
