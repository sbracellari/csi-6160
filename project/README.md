# CSI 6160 Final Project — Artificial Bee Colony

The main goal of this project was to use an enhanced [[4]](#4) version of the artificial bee colony algorithm [[1]](#1), [[3]](#3) as a means of solving the feature engineering problem [[5]](#5).

We evaluate the problem using the Wine Quality dataset found on Kaggle [[2]](#2).

## Required Packages

To be able to compile and run this project, you will need to have the following installed:

- Python $\geq$ 3.9.x (can be installed [here](https://www.python.org/downloads/))
- `numpy-1.24.3`
- `polars-0.17.7`
- `scikit-learn-1.2.2`
- `matplotlib-3.7.1`
- `seaborn-0.12.2`
- `pandas-2.0.0`

## Quick(er) Visuals

Some of the visuals shown in the `.ipynb` file take a bit of time to generate. For convenience, we've included a `RUN` flag on the top level that, when set to `False`, will skip those computations and simply graph a hardcoded version of our results.

## References

<a id="1">[1]</a>
D. Karaboga, “Artificial Bee Colony algorithm,” Scholarpedia, vol. 5, no. 3, p. 6915, 2010.

<a id="2">[2]</a>
G. Khaled, “Wine_Quality_Data,” Kaggle, 13-Apr-2023. [Online]. Available: https://www.kaggle.com/datasets/ghassenkhaled/wine-quality-data. [Accessed: 23-Apr-2023].

<a id="3">[3]</a>
H. Rao, X. Shi, A. K. Rodrigue, J. Feng, Y. Xia, M. Elhoseny, X. Yuan, and L. Gu, “Feature selection based on artificial bee colony and Gradient Boosting Decision tree,” Applied Soft Computing, vol. 74, pp. 634–642, 2019.

<a id="4">[4]</a>
H. Wang, W. Wang, S. Xiao, Z. Cui, M. Xu, and X. Zhou, “Improving artificial bee colony algorithm using a new neighborhood selection mechanism,” Information Sciences, vol. 527, pp. 227–240, 2020.

<a id="5">[5]</a>
R. S. Sutton and A. Barto, “On-policy Prediction with Approximation,” in Reinforcement learning: An introduction, Cambridge, Massachusetts ; London, England: The MIT Press, 2020, pp. 210–222.
