# Fraud Patterns Unmasked: GMM-Based Synthetic Sampling for Imbalanced Credit Card Data

- **Author:** Charukhesh  
- **Roll No:** AE22B028

## 📖 Project Overview

This project investigates advanced resampling strategies for credit card fraud detection, focusing on the use of Gaussian Mixture Model (GMM) based synthetic sampling. The notebook demonstrates how modeling the minority (fraud) class as a mixture of Gaussians enables the generation of realistic synthetic samples, leading to significant improvements in fraud detection performance compared to baseline and traditional resampling methods.

## 📁 Repository Structure

```
DA5401-assignment-4-Charukhesh/
│
├── main.ipynb
├── creditcard_dataset/
│   └── creditcard.csv
└── README.md
```


- **main.ipynb**: The main Jupyter notebook containing all code, analysis, visualizations, and conclusions.  

- **creditcard_dataset/**: Directory containing the dataset used for analysis.
    - **creditcard.csv**: The actual credit card fraud detection dataset.

- **README.md**: Project documentation and instructions.

## Dependencies

- Python 3.7+
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- imbalanced-learn

Install the required libraries using pip:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn
```

## How to Run This Project
1. **Clone the Repository**
    ```bash
    git clone https://github.com/Charukhesh/DA5401-assignment-4-Charukhesh.git
    cd DA5401-assignment-4-Charukhesh
    ```

2. **Dataset**

    Ensure the creditcard.csv file is present in the creditcard_dataset/ folder.

3. **Open and Run the Notebook**
    - Open `main.ipynb` in [Jupyter Notebook](https://jupyter.org/) or [VS Code](https://code.visualstudio.com/).
    - Run all cells sequentially to reproduce the analysis and results.
