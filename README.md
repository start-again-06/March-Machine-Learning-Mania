# March Machine Learning Mania  
## Predictive Probability Distribution Visualization

## Overview
This repository contains a Python script for visualizing the distribution of predicted probabilities using **Seaborn** and **Matplotlib**. The visualization helps analyze model confidence and probability calibration in classification tasks.

---

## Features
- Generates a histogram of predicted probabilities using `seaborn.histplot`
- Supports Kernel Density Estimation (KDE) for smooth distribution visualization
- Uses Matplotlib for figure sizing and plot customization
- Clearly labeled axes and descriptive plot titles for interpretability

---

## Prerequisites
Ensure the following Python libraries are installed:
- **Matplotlib** – Plot rendering and customization
- **Seaborn** – Statistical visualization (histograms and KDE)
- **Pandas** – Dataset handling and processing

## Usage
- Ensure your dataset is loaded into a Pandas DataFrame.
- The DataFrame should contain a column with predicted probability values.
- Run the script to generate and display the probability distribution plot.
- Adjust parameters such as bin size, figure dimensions, and KDE settings to refine the visualization.

---

## Applications
- Model confidence analysis
- Probability calibration inspection
- Classification model evaluation
- Kaggle competition analysis and reporting

---

## Contributing
Contributions are welcome. Feel free to open an issue or submit a pull request to improve functionality or visualization options.

---

## License
MIT License. Free to use, modify, and distribute for academic and research purposes.
