# NBA Stats Projection Model

KNN inspired NBA Stats Fantasy Projection Model in Python with Pandas

## Getting Started

These instructions will get you a copy of the model up and running on your local machine for development and testing purposes. This is for MacOS.

### Prerequisites

Recommend using Homebrew to install python and pyenv. Need to install [xcode](https://itunes.apple.com/us/app/xcode/id497799835?mt=12) first then install [homebrew](https://brew.sh/).

```py
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

### Installation

A step by step guide to get your venv running

### **Install pyenv using homebrew on macOS**

```py
brew install pyenv
```

### **Install python using pyenv**

```py
pyenv install 3.6.8
```

Install at the global level

```py
pyenv global 3.6.6
pyenv shell 3.6.6
```

### **Create a virtual environment**

```py
python -m venv venv
```

Activate the virtual environment

```py
source venv/bin/activate
```

### **Install packages**

```py
pip install -r requirements.txt
```

### CSV Files

As example we'll use a local directory [nba-stats-csv] with CSV files. It won't be uploaded to the repository.

Data pulled from [NBA stats](https://stats.nba.com/) and saved down into CSV files to be imported into dataframes. Filenames may be updated over time.

### Acknowledgments

- While data was previously pulled down via NBA API, I came across an NBA chrome extension that made it super easy to get NBA stats in CSV form. [NBA Data Retriever](https://chrome.google.com/webstore/detail/nba-data-retriever/cibebblabkdibhnidfnipfnjkfbcmeha?hl=en)
- Projection Model was heavily inspired by the [FATS Model from NBA Math](https://nbamath.com/fats-model/)

### Useful Dependencies to visit

- [Pandas](https://pandas.pydata.org/) for data manipulation
- [Numpy](http://www.numpy.org/) for numerical operations
- [Scikit-learn](https://scikit-learn.org/stable/) for machine learning
- [Jupyter Notebook](https://jupyter.org/) for data exploration
- [Matplotlib](https://matplotlib.org/) for data visualization
- [Seaborn](https://seaborn.pydata.org/) for data visualization
