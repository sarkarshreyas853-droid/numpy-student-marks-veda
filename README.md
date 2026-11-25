# NumPy Student Marks

Create a NumPy array of student marks and calculate the mean, median, maximum, minimum, and standard deviation.

## Objective

Learn how NumPy can efficiently perform numerical analysis.

## Tools

- Python
- NumPy
- Jupyter Notebook

## Dataset

Manually created marks (out of 100) for 10 students:

```python
marks = np.array([78, 85, 62, 91, 55, 88, 73, 95, 67, 80])
```

## Results

| Statistic | Value | NumPy function |
|---|---|---|
| Mean | 77.40 | `np.mean()` |
| Median | 79.00 | `np.median()` |
| Maximum | 95 | `np.max()` |
| Minimum | 55 | `np.min()` |
| Standard deviation | 12.40 | `np.std()` |

Student 8 scored highest (95) and student 5 scored lowest (55). Six of the ten students scored above the mean.

## Explanation

- The **mean** (77.40) and **median** (79.00) are close, so the marks are not heavily skewed.
- The marks span 40 points, from 55 to 95.
- A **standard deviation** of 12.40 means marks sit about 12 points from the average, a moderate spread.
- NumPy calculates each value with a single function call on the whole array, with no loops.

## Interview questions

**What is NumPy?**
A Python library for numerical computing, built around the fast multi-dimensional `ndarray` and functions for maths, statistics, and linear algebra.

**Why is NumPy useful in machine learning?**
ML works on large arrays of numbers. NumPy runs vectorised operations in optimised C code, much faster than Python loops, and libraries such as pandas, scikit-learn, and TensorFlow build on it.

**What is standard deviation?**
A measure of how spread out values are from the mean. Small means values sit close to the average; large means they are widely spread.

## How to run

```bash
pip install numpy jupyter
jupyter notebook NumPy_Student_Marks.ipynb
```

## Files

- `NumPy_Student_Marks.ipynb`: the notebook with code, outputs, and explanation
- `README.md`: this file
