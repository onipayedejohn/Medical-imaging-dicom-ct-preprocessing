# Medical Imaging AI: From a Raw DICOM File to a Trained Model

**Bootcamp Week 4 · Medical Imaging Applications**

## Overview

Works with a real CT DICOM file end to end: converts raw pixel data to Hounsfield Units (the physical density scale CT scanners use), applies clinical windowing to make specific tissue types visible, and resizes the result into an ML-ready shape for model input.

## Dataset

Real CT DICOM file

## What this notebook demonstrates

- Reading raw DICOM files with `pydicom`
- Converting pixel data to Hounsfield Units (HU)
- Clinical windowing for tissue-specific visibility
- Resizing imaging data into an ML-ready shape

## Libraries

`pydicom`, `numpy`, `matplotlib`

## Why this project is here

The imaging-preprocessing depth (Hounsfield Units, windowing) that separates a toy image classifier from one built with real clinical imaging-physics understanding, directly useful for imaging-informatics research.

## Files

- `notebook.ipynb` — the full, run notebook (cell outputs, including charts, are saved inline and render directly on GitHub)

---
Part of a chronological AI-in-healthcare / ML portfolio built during a hands-on bootcamp. See the [portfolio index](https://github.com/YOUR-USERNAME/portfolio-index) for the full sequence.
