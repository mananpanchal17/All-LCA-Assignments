# All LCA Assignments 🐍

A collection of **Python Programming Laboratory** assignments completed using **Jupyter Notebook** as part of my coursework at **MIT World Peace University (MIT-WPU), Pune**.

This repository documents Python fundamentals, data structures, functions, NumPy, Pandas, and data visualization.

## 📚 Assignments

| Assignment | Topic | Notebook |
| --- | --- | --- |
| 01 | Lists, tuples, dictionaries, and add/update/delete operations | [Assignment1.ipynb](Assignment1.ipynb) |
| 02 | Find the largest of three numbers using conditional statements | [Assignment2.ipynb](Assignment2.ipynb) |
| 03 | Check whether a triangle is right-angled using a function | [Assignment3.ipynb](Assignment3.ipynb) |
| 04 | Matrix addition using NumPy | [Assignment4.ipynb](Assignment4.ipynb) |
| 05 | String validation using regular expressions; Iris dataset visualization | [Assignment5.ipynb](Assignment5.ipynb) |
| 06 | Titanic dataset exploration and analysis with Pandas | [Assignment6.ipynb](Assignment6.ipynb) |
| 07 | Titanic data visualization with line, bar, scatter, and correlation heatmap plots | [Assignment7.ipynb](Assignment7.ipynb) |

## 🛠️ Tech Stack

- **Language:** Python 3
- **Notebook environment:** Jupyter Notebook
- **Libraries:** NumPy, Pandas, Matplotlib, Seaborn, scikit-learn
- **Data:** Iris dataset (via scikit-learn) and a local Titanic CSV file

## 🚀 Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/mananpanchal17/All-LCA-Assignments.git
   cd All-LCA-Assignments
   ```

2. Install the packages:

   ```bash
   pip install notebook numpy pandas matplotlib seaborn scikit-learn
   ```

3. Launch Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

4. Open an `Assignment*.ipynb` file and run its cells.

### 📁 Dataset setup for Assignments 6 and 7

Assignments **6** and **7** read a Titanic CSV from a **local Windows path**. That file is **not currently included in this repository**. Download or provide a compatible `Titanic-Dataset.csv` and change the `pd.read_csv(...)` path in the notebook to its location, for example:

```python
df = pd.read_csv("Titanic-Dataset.csv")
```

The example above works if you place the CSV in the same folder as the notebook. The notebooks expect standard Titanic columns such as `PassengerId`, `Survived`, `Pclass`, `Name`, `Age`, and `Fare`.

Assignment 5 uses the Iris dataset provided by scikit-learn, so no separate Iris CSV is needed.

## 🎯 Learning Goals

- Practice Python syntax, user input, and control flow
- Work with lists, tuples, and dictionaries
- Define and use Python functions
- Perform numerical operations with NumPy
- Inspect and analyze tabular data using Pandas
- Visualize datasets and correlations with Matplotlib and Seaborn

## 👨‍💻 Author

**Manan Panchal**  
[GitHub: @mananpanchal17](https://github.com/mananpanchal17)

---

*Created for learning and academic practice.*
