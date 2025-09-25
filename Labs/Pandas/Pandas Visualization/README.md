# W01 lecture 01
## Goals
- Introduce course
  - anaconda python, git, github, Jupyter notebooks
  - Two textbooks
  - Quizzes on D2L
  - Assignments for ENSF 410, assignments + project for ENSF 611 using github.
- Intrduce machine learning
  - AI->Machine learning->Deep learning
  - Machine learning: Supervised, unsupervised and reinforcement learning.
  - In this course: traditional/statistical methods of supervised and unsupervised learning, no neural networks.
  - A thought: Machines do not learn, we optimize model parameters to fit a mathematical function to data.
- Train our first model `w01-1.ipynb`
- Highlight that feature matrix $X$ has $N$ rows with measurements, and $M$ columns with features. In other words, `X.shape` is `(n_samples, n_features)`.
- Highlight that the target vector $y$ has $N$ elements with lables for each of the measurements. In other words, `y.shape` is `(n_samples, )`.

As post-reading, might be good to read _Data Science Handbook_ Chapter 5 *Machine Learning* to *Introducing Scikit-Learn* p.331-342.


# W01 lecture 02
## Goals
- Review numpy-pandas-matplotlib/seaborn in preparation of ml-lab0.
- Show how to download datasets from UCI
- Adapt `w01-pandas.ipynb` and `w01-visualization.ipynb` using the wine dataset:
https://archive.ics.uci.edu/ml/datasets/wine
- In the wine dataset, `class` column can be used as a grouping varibale. Maybe `alcholol` and `color_intensity` as other interesting variables.
- For correlations, use: `['alcohol', 'color_intensity', 'hue', 'magnesium']`.

**Note:** Pandas and visualization notebooks are also in `ml-lab0`. Doing `ml-lab0` is the next step.
