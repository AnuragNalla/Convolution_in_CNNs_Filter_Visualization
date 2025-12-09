# Convolution_in_CNNs_Filter_Visualization

# Understanding Convolution in CNNs: How Filters Learn Features

This repository contains the complete materials—tutorial report, runnable code, and generated figures—for the Advanced Machine Learning assignment focusing on Convolutional Neural Networks (CNNs) and feature visualization.

The core objective is to demystify the **convolution operation** and empirically demonstrate how a CNN learns **interpretable feature detectors** (filters) in its early layers.

## 🚀 Key Demonstration

The code trains a small CNN on the MNIST dataset and then performs two critical visualizations:

1.  **Learned Filters:** Plots the weights of the filters in the first convolutional layer, showing they specialize into patterns like edges and gradients.
2.  **Feature Maps:** Shows the activation (output) of these filters when a sample image is fed into the network, revealing what the network "sees."

## 📁 Repository Contents

| File/Folder | Description |
| :--- | :--- |
| `CNN_Filter_Visualization.ipynb` | **The primary code submission.** A runnable PyTorch Jupyter Notebook that trains the CNN, extracts the weights, and generates the two visualization figures. |
| `CNN_Tutorial_Report.pdf` | The final tutorial document submitted for the assignment. This includes the conceptual explanations and final interpretations of the figures. |
| `README.md` | This overview file. |
| `LICENSE.md` | Defines the licensing terms for the code and documentation (MIT License). |

## ⚙️ Setup and Execution

### Prerequisites

You need a Python environment with the following libraries installed:

* `torch` (PyTorch)
* `torchvision`
* `numpy`
* `matplotlib`
* `jupyter` (or `jupyterlab`)

You can install the necessary dependencies using `pip`:


pip install torch torchvision numpy matplotlib jupyter

git clone [[Your Repository URL Here](https://github.com/AnuragNalla/Convolution_in_CNNs_Filter_Visualization)]
cd Convolution_in_CNNs_Filter_Visualization

Run All Cells: Execute all cells in the notebook sequentially. The script will automatically download the MNIST dataset, train the CNN, and display the two critical visualization figures.
