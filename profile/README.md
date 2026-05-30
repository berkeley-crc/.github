<div align="center"><img src="https://raw.githubusercontent.com/berkeley-crc/.github/main/profile/assets/robot_eye_logo.png" width="190"/></div>

<h1 align="center">Berkeley CRC</h1>

<p align="center">
  Clinical Research Center, UC Berkeley &nbsp;&middot;&nbsp; AI for meibography and meibomian-gland morphology
</p>

---

## About

We build AI methods for the ocular surface, focused on meibomian-gland morphology and its role in meibomian gland dysfunction (MGD) and dry eye. Our work turns raw meibography images into quantitative, reproducible morphology measurements — so that gland health can be characterized consistently rather than estimated by eye.

Our mascot, a friendly robot inspecting an eye through a lens, is a fair summary of the work: careful, close-up measurement.

## Ongoing Research

A unified meibomian-gland **instance-segmentation** pipeline built on Cellpose-SAM, producing per-gland morphology metrics — visible gland count, length, width, contrast, and tortuosity — together with **atrophy** and **density**. A two-model *tarsal-plate &rarr; atrophy* chain constrains an atrophy segmenter to the tarsal plate, and gland masks are likewise restricted to the plate to remove skin and eyelash false positives. Everything runs as an interactive Gradio demo with automatic upper/lower eyelid detection.

## Selected Work

- **Quantifying Meibomian Gland Morphology Using Artificial Intelligence** — [gland-segmentation-release](https://github.com/danielchyeh/gland-segmentation-release)
- **Meibography phenotyping and classification from unsupervised discriminative feature learning** (TVST 2021) — [meibo-ML](https://github.com/danielchyeh/meibo-ML)
- **MGD-AI** — [MGD-AI](https://github.com/danielchyeh/MGD-AI)

## Pipeline Tooling

We also maintain supporting tooling for the meibography workflow, including raw-image enhancement / de-reflection and device file-renaming utilities.

---

<p align="center">
  Maintained by <a href="https://github.com/danielchyeh">Chun-Hsiao (Daniel) Yeh</a> &nbsp;&middot;&nbsp; <a href="https://github.com/danielchyeh">@danielchyeh</a>
</p>
