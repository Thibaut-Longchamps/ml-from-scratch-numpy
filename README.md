# 🧠 ml-from-scratch-numpy
Machine Learning algorithms and full pipeline from scratch with NumPy. Step-by-step notebooks cover gradient descent, cost functions, regularization, encoding, normalization, metrics, train/test split, and outlier handling.  

Current models: **Linear Regression** and **Logistic Regression**.  
Focus on **maths + code**, not shortcuts — see under the hood of ML.  
More models coming soon.

---

## 📂 Project Structure

- `notebook/lin_reg_scratch.ipynb` — Main notebook with full explanations, math, and code.  
- `data/dataset_rent.csv` — Synthetic dataset used for rent prediction examples.  
- `image/Gradient_descent_image.webp` — Illustration of gradient descent used in the notebook.  
- `requirements.txt` — Minimal dependencies to reproduce the notebook.  
- `.gitignore` — Ignore unnecessary files and checkpoints.  
- `README.md` — Project overview and usage instructions.

---

## ▶️ How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/Thibaut-Longchamps/ml-from-scratch-numpy.git
   cd ml-from-scratch-numpy

2. **Create and activate a virtual environment**
`python -m venv venv`

Activate the environment:
- On Windows:
`venv\Scripts\activate`
- On macOS/Linux:
`source venv/bin/activate`

3. **Update pip**
`python -m pip install --upgrade pip`

4. **Install the recquired packages**
`pip install -r requirements.txt`

5. **Open the notebook**

6. **Update the dataset path and image path if needed**

7. **Run the notebook cell by cell**


**Packages**

numpy : Linear algebra and matrix operations
pandas : CSV loading and data manipulation
matplotlib : Graphs and visualizations
Pillow : Image handling (e.g., .webp)
ipykernel : Notebook runtime support
