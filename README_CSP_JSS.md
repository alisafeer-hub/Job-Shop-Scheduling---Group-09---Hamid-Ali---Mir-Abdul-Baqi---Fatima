# 🧠 AI Optimization and Prediction using Local Search, Tabu Search, and Random Forest

## 📄 Project Overview
This project explores both **metaheuristic optimization** and **machine learning** techniques to model and analyze scheduling or resource allocation problems (e.g., Job Shop Scheduling).  
It implements:
- **Local Search (Hill Climbing)**
- **Tabu Search**
- **Random Forest Regressor** for performance prediction

The notebook demonstrates how different optimization strategies perform on synthetic data and how machine learning can complement heuristic optimization for better results.

---

## ⚙️ Features
- Data parsing and preprocessing of a custom text dataset (`1000shopjob.txt`)
- Implementation of **Local Search Algorithm**
- Implementation of **Tabu Search Algorithm**
- Comparative analysis between Local Search and Tabu Search
- Random Forest training for performance prediction
- Model evaluation using **Mean Squared Error (MSE)** and **R² Score**
- Visualization of performance metrics and results

---

## 📊 Workflow Summary

1. **Import Required Libraries**
   - NumPy, Pandas, Matplotlib, scikit-learn

2. **Dataset Loading**
   - Reads data from `1000shopjob.txt`
   - Parses the text into structured numeric format using a custom parser

3. **Data Preprocessing**
   - Handling missing values, duplicates, and formatting
   - Feature encoding and splitting for ML model training

4. **Local Search (Hill Climbing)**
   - Starts from a random solution
   - Iteratively improves the solution by exploring local neighborhoods
   - Stops when no better solution is found or after a fixed number of iterations

5. **Tabu Search**
   - Enhances Local Search by maintaining a **tabu list** of recent moves
   - Avoids cycles and local optima
   - Compares performance metrics vs. basic local search

6. **Machine Learning Model**
   - **Random Forest Regressor** trained on generated or parsed data
   - Evaluates model accuracy (R² Score, MSE)
   - Optionally expands dataset with synthetic examples

7. **Results Visualization**
   - Plots of algorithm performance, accuracy, and comparison between methods

---

## 🧩 Technologies Used
| Category | Libraries/Tools |
|-----------|----------------|
| **Programming Language** | Python 3.x |
| **Data Processing** | Pandas, NumPy |
| **Machine Learning** | scikit-learn |
| **Visualization** | Matplotlib |
| **Optimization Algorithms** | Local Search, Tabu Search |

---

## 🚀 How to Run
1. Clone or download this repository.
2. Place the dataset file `1000shopjob.txt` in the same directory as the notebook.
3. Open the notebook:
   ```bash
   jupyter notebook c2d22c4d-28e0-475c-8da5-c249b02c01df.ipynb
   ```
4. Run all cells sequentially.
5. View printed outputs and generated plots for performance comparison.

---

## 📈 Example Outputs
- Local Search runtime and best score
- Tabu Search convergence curve
- Random Forest model accuracy (`R² Score`)
- Comparison of predicted vs actual results

---

## 🧠 Insights
- **Local Search** performs efficiently for small search spaces but can get stuck in local minima.
- **Tabu Search** outperforms Local Search by escaping local minima using memory-based search.
- **Random Forest Regressor** can be used to approximate complex objective functions, reducing optimization runtime.

---

## 🧑‍💻 Author
Developed by **Hamid Ali** as part of an **AI optimization and predictive modeling** project.

---

## 🗂️ File Structure
```
├── c2d22c4d-28e0-475c-8da5-c249b02c01df.ipynb   # Main notebook
├── 1000shopjob.txt                              # Dataset file (job shop or synthetic data)
└── README.md                                    # Project documentation
```
