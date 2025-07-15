# Physics Equation ML Solver

**Physics Equation ML Solver** is a machine learning project that generates and models data derived from fundamental physics laws. The goal is to discover, verify, and interpret known physical relationships using symbolic regression and traditional ML techniques.

---

## 🧠 Project Objective

To apply machine learning — particularly regression and symbolic modeling — to datasets generated from core physics equations, such as:

- Newton’s Second Law of Motion
- Kinematic Equations
- Pendulum Period
- Ohm’s Law
- Hooke’s Law
- Gravitational Force

The project seeks to:
- Reconstruct physical formulas from synthetic data
- Validate the use of symbolic ML in scientific equation discovery
- Serve as a benchmark project for physics-based ML pipelines

---

## 🚀 Features

- Data generation using physics formulas
- Modular pipeline: data cleaning, EDA, modeling, evaluation
- Symbolic regression to rediscover laws
- Jupyter-based exploratory notebooks
- Reusable Python scripts for automation
- Output: learned equations, performance metrics, visualizations

---

## ⚙️ Technologies Used

- Python 3.10+
- NumPy, Pandas
- Scikit-learn
- SymPy / PySR / gplearn (for symbolic regression)
- Matplotlib, Seaborn
- Jupyter Notebook
- Git for version control

---

## 📦 Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/jobet1130/physics_equation_ml_solver.git
   cd physics_equation_ml_solver
   ```

2. Create a virtual environment and activate it:
   ```bash
   python -m venv .venv
   .venv\Scripts\activate  # Windows
   source .venv/bin/activate  # macOS/Linux
   ```

3. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Launch the notebooks:
   ```bash
   jupyter notebook
   ```

---

## 📁 Datasets

All datasets are synthetically generated from the ground truth equations and stored under the `data/raw/` directory. Processed/cleaned versions are saved in `data/processed/`.

---

## 📊 Results

Each physics equation undergoes full regression and symbolic modeling. Results are saved in:

- `models/` – Trained model artifacts
- `results/formulas/` – Symbolic equation outputs
- `results/figures/` – Visualizations and plots

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

---

## 👨‍🔬 Contributors

- Jobet Casquejo 

---

## 🙌 Acknowledgements

This project is inspired by applications of symbolic regression in scientific discovery and aims to contribute tools and educational insight to that domain.
