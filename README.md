# SciImpact

This repository hosts the project homepage for **SciImpact: A Multi-Dimensional, Multi-Field Benchmark for Scientific Impact Prediction**.

SciImpact studies scientific impact prediction beyond citation counts alone. The benchmark covers **7 impact dimensions**, **19 scientific fields**, and **215,928 contrastive pairs**, enabling systematic evaluation of whether models can identify the more impactful artifact under different definitions of impact.

## Project Overview

SciImpact expands scientific impact prediction to include:

- Citation
- Award
- Patent
- Media
- Code
- Dataset
- Model

Each benchmark instance is constructed as a contrastive pair from the same field, asking a model to predict which artifact has higher impact under a given dimension. This setup makes it possible to compare model behavior across both short-term and long-term impact settings.

## Key Highlights

- **Broad coverage:** 19 fields spanning computer science, medicine, chemistry, physics, and other disciplines.
- **Heterogeneous inputs:** paper titles and abstracts, GitHub README files, Hugging Face dataset cards, and model cards.
- **Strong empirical signal:** supervised fine-tuning substantially improves compact open-weight models, allowing small models such as a 4B backbone to outperform much larger baselines on average.

## Repository Contents

- `index.html`: main homepage entry
- `static/css/index.css`: site styling
- `static/js/index.js`: lightweight client-side interactions
- `static/images/`: figures used on the homepage

## Homepage

GitHub Pages site:

[https://FlyPig23.github.io/sciimpact-homepage/](https://FlyPig23.github.io/sciimpact-homepage/)

## Notes

- This repository is for the **project homepage**, not the full benchmark release.
- The local paper PDF is not included in this repository.
