# Machine Learning AlgoTrading

Algorithmic trading relies on computer programs that execute algorithms to automate some or all elements of a trading strategy. Algorithms are a sequence of steps or rules designed to achieve a goal. They can take many forms and facilitate optimization throughout the investment process, from idea generation to asset allocation, trade execution, and risk management.

Machine learning (ML) involves algorithms that learn rules or patterns from data to achieve a goal such as minimizing a prediction error. The examples in this book will illustrate how ML algorithms can extract information from data to support or automate key investment activities. These activities include observing the market and analyzing data to form expectations about the future and decide on placing buy or sell orders, as well as managing the resulting portfolio to produce attractive returns relative to the risk.

Ultimately, the goal of active investment management is to generate alpha, defined as portfolio returns in excess of the benchmark used for evaluation. The fundamental law of active management postulates that the key to generating alpha is having accurate return forecasts combined with the ability to act on these forecasts (Grinold 1989; Grinold and Kahn 2000).

It defines the information ratio (IR) to express the value of active management as the ratio of the return difference between the portfolio and a benchmark to the volatility of those returns. It further approximates the IR as the product of

The information coefficient (IC), which measures the quality of forecast as their rank correlation with the outcomes
The square root of the breadth of a strategy expressed as the number of independent bets on these forecasts
The competition of sophisticated investors in financial markets implies that making precise predictions to generate alpha requires superior information, either through access to better data, a superior ability to process it, or both. This is where ML comes in: applications of ML for trading (ML4T) typically aim to make more efficient use of a rapidly diversifying range of data to produce both better and more actionable forecasts, thus improving the quality of investment decisions and results.

![Machine_Learning_AlgoTrading]()

---

## Python Libraries

Before attempting to execute any Python code in machine_learning_trading_bot.ipynb, it is imperative that your development environment holds the following modules:

- matplotlib [docs](https://github.com/matplotlib/matplotlib)
- numpy [docs](https://github.com/numpy/numpy)
- pandas [docs](https://github.com/pydata/pandas)
- scipy [docs](https://github.com/scipy/scipy)
- scikit-learn [docs](https://scikit-learn.org/stable/user_guide.html)
- TensorFlow [docs](https://www.tensorflow.org/guide)
- PyTorch [docs](https://pytorch.org/docs/stable/index.html)
- Machine Learning Financial Laboratory (mlfinlab) [docs](https://mlfinlab.readthedocs.io/en/latest/)
- seaborn [docs](https://github.com/mwaskom/seaborn)
- statsmodels [docs](https://github.com/statsmodels/statsmodels)

---

## Installation Guide

With your _Python 3.7+_ environment, run the following commands via CLI:

```
from datetime import datetime
import requests
import config
import pandas as pd
import time

---

## Examples

![Example_One]()

![Example_Two]()

---

## Conclusion



---

## Baseline

![Example_Three]()


## Updated Comparison

![Example_Four]()

---

## Usage  NEED EDITING BELOW

1. Clone repository onto your personal machine.

2. Open Jupyter Lab or Jupyter Notebook via Anaconda Navigator and navigate to the directory in which the file machine_learning_trading_bot.ipynb is present. All relevant code for this repository will be executed via Jupyter Notebook and no output will be printed to the command line. Ensure that all relevant dependencies and Python modules are installed (see Technologies and Installation Guide for more details) before attempting to execute code within Jupyter Notebook; otherwise, you will receive multiple interpreter errors!

3. With the notebook open, start at the very first cell reading "Machine Learning Trading Bot" (a cell will be active when a rectangular border is surrounding the area in question). Run each cell in sequential order. It is vital that all cells are ran in sequential order or your notebook will generate compiler errors!

---

## Contributors

New development created by Brandon Chen, David Zou, Santiago Rosas, Tim Kipper. Code from 'Initial commit.' commit originates from ML for AlgoTrading - 2nd Edition.  We do not claim original ownership nor scholarship.

---
### Books

- [Advances in Financial Machine Learning](https://www.wiley.com/en-us/Advances+in+Financial+Machine+Learning-p-9781119482086), Marcos Lopez de Prado, 2018
- [Quantresearch](http://www.quantresearch.info/index.html) by Marcos López de Prado
- [Quantitative Trading](http://epchan.blogspot.com/), Ernest Chan
- [Machine Learning in Finance](https://www.springer.com/gp/book/9783030410674), Dixon, Matthew F., Halperin, Igor, Bilokon, Paul, Springer, 2020

#### Machine Learning

- [Machine Learning](http://www.cs.cmu.edu/~tom/mlbook.html), Tom Mitchell, McGraw Hill, 1997
- [An Introduction to Statistical Learning](http://www-bcf.usc.edu/~gareth/ISL/), Gareth James et al.
    - Excellent reference for essential machine learning concepts, available free online
- [Bayesian Reasoning and Machine Learning](http://web4.cs.ucl.ac.uk/staff/D.Barber/textbook/091117.pdf), Barber, D., Cambridge University Press, 2012 (updated version available on author's website)

---
## License

Software tool available for public use. 
