# Workshop: Linear Algebra for Data Programmers

This is the first workshop in the **Math & Coding** series, designed for programmers and analysts with basic to intermediate Python skills. We explore key mathematical ideas such as vectors, matrices, determinants, eigenvalues, and eigenvectors — not just in theory, but through a **real-world application**: **Principal Component Analysis (PCA)**, a widely used method in Data Science and Machine Learning.

### 🔍 Why PCA?

PCA serves as a hands-on example to:
- Understand how linear algebra operates inside real code
- Improve our ability to read and interpret PCA outputs
- Connect abstract math to practical machine learning workflows

The goal is not only to learn linear algebra — but to **understand the mathematics behind the tools** we use in data analysis.

No prior knowledge of advanced math is required. Just curiosity, Python, and a laptop 😉

## 🔧 How to Run This Project

You have two options to run the notebooks from this workshop:

### ▶️ Option 1: Run online with Binder (Recommended)

No installation needed — just click the button below and start working directly in your browser.

https://mybinder.org/v2/gh/Jessica-go/lin_alg_1/main?urlpath=%2Fdoc%2Ftree%2F01_intro_lin_alg_part1.ipynb

> You can open and run all notebooks using the Jupyter file browser on the left.

---

### 🖥️ Option 2: Run locally on your computer

#### Step 1: Clone the repository

```bash
git clone https://github.com/jessica-gonzalez/lin_alg_1.git
cd lin_alg_1
```
#### Step 2: Install required packages
pip install numpy matplotlib scikit-learn pandas

If you are using conda: 
```bash 
conda create -n lin_env python=3.10
conda activate lin_env
conda install numpy matplotlib scikit-learn pandas
```
#### Step 3: Launch Jupyter Notebook
```bash 
jupyter notebook
```

## 📦 Environment requirements

All required packages are defined in the `environment.yml` file, including:

- numpy  
- pandas  
- matplotlib  
- scikit-learn  
- torch  
- jupyterlab  

---

Feel free to explore, run, and adapt the notebooks to your own data projects. This workshop is meant to build intuition and bridge math concepts with real Python code.
