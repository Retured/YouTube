# 📚 Retured YouTube Code Vault  

Welcome to the **Retured YouTube Code Vault**—the central hub for every script, notebook, and dataset featured on our videos. Clone the repo, follow along at your own pace, and replicate the results you see on-screen.

[![Subscribe on YouTube](https://img.shields.io/badge/Subscribe-YouTube-red)](https://youtube.com/@Retured) 


---

## ✨ What you’ll find here

| Folder | Corresponding Video | Brief | Level |
| ------ | ------------------- | ----- | ----- |
| `Optimization` | *What Is Optimization* | Basic Python scripting  | Beginner |
| `Optimization` | *What Is Loss Function?* | Python script to plot and visualize loss functions  | Beginner |
| … | … | … | … |

Each folder contains:

* **Jupyter notebook** (`.ipynb`) with step-by-step code  
* **`requirements.txt`** listing pinned package versions  if required
* **Sample data** (when redistribution is allowed)  
* A short **`README.md`** outlining the run order  if required



---

## 🚀 Quick start

```bash
# 1. Clone
git clone https://github.com/retured/YouTube.git
cd your-repo

# 2. Create & activate a virtual env (recommended)
python -m venv .venv
source .venv/bin/activate   # On Windows: .venv\Scripts\activate

# 3. Install core dependencies
pip install -r requirements.txt

# 4. Pick a folder and run the notebook
jupyter lab optimization/what-is-optimization.ipynb
