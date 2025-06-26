# 🏏 IPL Score Prediction

This project predicts the final score of an IPL innings based on input conditions like team, venue, players, and match progress using a trained machine learning model.

---

## 🔧 Setup Instructions

### 📥 Clone the Repository

```bash
git clone https://github.com/arindal1/IPL-score-pred
cd IPL-score-pred
```

---

## ⚙️ Option A: Using Python Virtual Environment

### ✅ Prerequisite

- Python version **3.10.9** is required.

### 🛠️ Create and Activate Virtual Environment

```bash
python -m venv venv310
```

#### Windows

```bash
venv\Scripts\activate
```

#### Linux/macOS

```bash
source venv/bin/activate
```

---

### 📦 Install Dependencies

```bash
pip install -r requirements.txt
pip install jupyter
pip install ipywidgets==8.0.6
```

---

### 🚀 Launch the Notebook

```bash
jupyter notebook IPLScore-test.ipynb
```

> ⚠️ **Make sure to update the CSV file path in the notebook before running it.**

In Jupyter, go to:

```
Kernel → Restart Kernel and Run All Cells
```

> If errors occur, troubleshoot them manually (e.g., missing packages, incorrect paths).

---

## 🐍 Option B: Using Anaconda (Recommended)

### 1️⃣ Install [Anaconda](https://www.anaconda.com/) for Windows/macOS

---

### 2️⃣ Create a Conda Environment

```bash
conda create -n iplpred python=3.10 -y
conda activate iplpred
```

---

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
pip install ipywidgets==8.0.6
```

---

### 4️⃣ Launch the Notebook

```bash
jupyter notebook IPLScore-test.ipynb
```

> ⚠️ Adjust the CSV file path before running the notebook and use “Restart Kernel and Run All Cells”.

---

## 🧠 Notes

- Ensure your dataset (`.csv`) is placed correctly relative to the notebook path.
- The model uses deep learning with **Keras** and performs better with clean, structured input data.
- If you face widget display issues in Jupyter, try running:

```bash
jupyter nbextension enable --py widgetsnbextension
```

---

Feel free to contribute or suggest improvements to enhance model performance or usability.
