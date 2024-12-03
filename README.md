# Plot and Fit RF Graph Application

## Overview
This Python application provides a graphical interface for visualizing, analyzing, and fitting RF data. It is built using PyQt5 and Matplotlib, featuring options to customize plots, edit fit parameters, and save graphs and fit results.

## Features
- **Load and Edit Data**: Import CSV files and specify voltage, counts, and other parameters.
- **Graph Customization**: Adjust graph appearance, including labels, limits, title, and aspect ratio.
- **Fit Data**: Perform single or double Lorentzian fitting and annotate graphs with fit parameters.
- **Save Results**: Save graphs as PNG/JPEG/TIFF or export fit results as a text file.

## Requirements
- Python 3.7+
- Required packages:
  - PyQt5
  - Matplotlib
  - Numpy
  - Pandas
  - Lmfit
  - Scipy

Install dependencies using:
```bash
pip install PyQt5 matplotlib numpy pandas lmfit scipy
