# boston-housing-price-analysis


## Introduction

The Boston Housing dataset contains information collected by the U.S Census Service concerning housing in the area of Boston, Massachusetts.
This dataset is widely used for beginner to intermediate machine learning tasks and offers a mix of categorical and numerical features. The aim is to predict the median value of owner-occupied homes.

## Problem Statement:

Develop a machine learning model to predict the median value of owner-occupied homes in Boston based on various predictor variables (features). This will help real estate agents, homeowners,
and potential buyers to get a better understanding of the housing market in Boston and assist in making informed decisions.
## Table of Contents

- [Installation and Setup](#installation-and-setup)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)
- [Acknowledgments](#acknowledgments)

## Installation and Setup

### Prerequisites

- Python (version 3.6 or later)
- pip (Python package installer, version 19.0 or later)

You can download and install Python from [the official Python website](https://www.python.org/). pip is included automatically when Python is installed.

### Virtual Environment (Optional)

It is recommended to create a virtual environment to manage the dependencies for your project.

```bash
python -m venv venv
```

Activate the virtual environment:

- On Windows:
  
  ```bash
  .\venv\Scripts\activate
  ```

- On macOS and Linux:
  
  ```bash
  source venv/bin/activate
  ```

### Installation

Install the required packages using pip:

```bash
pip install pandas numpy scipy matplotlib seaborn sklearn
```

### Running the Application

After installing the dependencies, you can run your Python script. Make sure your virtual environment is activated.

If you encounter any import errors, ensure that all packages are installed and your virtual environment is active.

## Usage

Include examples of how to use your project. Include code snippets, screenshots, or any other relevant information.

```python
import pandas as pd
import numpy as np
from scipy import stats
import matplotlib.pyplot as plt
import pylab as pl
from scipy.stats import shapiro
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
from sklearn.tree import DecisionTreeRegressor
from sklearn.ensemble import RandomForestRegressor
from sklearn.metrics import mean_squared_error, mean_absolute_error, r2_score
from sklearn.model_selection import cross_val_score
from math import sqrt
import seaborn as sns
from sklearn.cluster import KMeans
from sklearn.preprocessing import PolynomialFeatures, StandardScaler
from sklearn.feature_selection import RFE
import warnings
warnings.filterwarnings('ignore')
```
Although I have uploaded the actual dataset on the repository, I used its link in the portfolio


## Contributing

I would happy to have anyone's contribution.


## Contact

ali.freestyle2014@gmail.com


## Acknowledgments

- [GitHub Emoji Cheat Sheet](https://www.webpagefx.com/tools/emoji-cheat-sheet)
- [Img Shields](https://shields.io)
- [GitHub Pages](https://pages.github.com)
- [Animate.css](https://daneden.github.io/animate.css)
- [Loaders.css](https://connoratherton.com/loaders)
- [Slick Carousel](https://kenwheeler.github.io/slick)
- [Smooth Scroll](https://github.com/cferdinandi/smooth-scroll)
- [Sticky Kit](http://leafo.net/sticky-kit)
- [JVectorMap](http://jvectormap.com)
- [Font Awesome](https://fontawesome.com)
