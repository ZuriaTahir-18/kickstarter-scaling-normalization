
# Kickstarter Scaling and Normalization

This repository contains a Jupyter Notebook for practicing data preprocessing techniques—specifically scaling and normalization—on Kickstarter campaign data.

## Objective

* Apply **min-max scaling** to campaign goal values.
* Apply **normalization** (e.g., Box-Cox or similar) to pledged amounts to stabilize variance and approach a normal distribution.
* Visualize the effect of these transformations.

## Tools & Libraries

* Python
* pandas
* numpy
* seaborn
* matplotlib
* mlxtend (installed in the notebook)

## Files

* `kickstarter_scaling_normalization.ipynb`: Main assignment notebook performing scaling and normalization.

## Dataset Source

Kickstarter Projects dataset sourced from Kaggle:
[https://www.kaggle.com/datasets/kemical/kickstarter-projects](https://www.kaggle.com/datasets/kemical/kickstarter-projects)

## Dataset

* `kickstarters_2017.csv`: Kickstarter campaign data including fields like goal, pledged amount, etc.

## Key Concepts Practiced

* Min-Max Scaling
* Data Normalization (e.g., Box-Cox transform)
* Distribution visualization before and after transformation

## How to Run the Project

1. **Clone the repository**

   ```bash
   git clone https://github.com/your-username/kickstarter-scaling-normalization.git
   cd kickstarter-scaling-normalization
   ```

2. **Install required libraries**
   Ensure Python (3.7+) is installed, then install dependencies:

   ```bash
   pip install pandas numpy seaborn matplotlib mlxtend
   ```

3. **Download the dataset**

   * Visit the [dataset page](https://www.kaggle.com/datasets/kemical/kickstarter-projects).
   * Download and extract the dataset.
   * Place `kickstarters_2017.csv` in the same directory as the notebook, or update the path in the code.

4. **Run the notebook**
   Open the notebook in Jupyter or a supported IDE:

   ```bash
   jupyter notebook kickstarter_scaling_normalization.ipynb
