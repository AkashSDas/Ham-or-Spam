# Ham or Spam

  

[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)

[![](https://img.shields.io/badge/python-3.8-blue.svg)](https://www.python.org/downloads/release/python-380/)

[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/AkashSDas)

[![Ask Me Anything !](https://img.shields.io/badge/Ask%20me-anything-1abc9c.svg)](https://github.com/AkashSDas)

[![PyPI license](https://img.shields.io/pypi/l/ansicolortags.svg)](LICENSE)

  
  

## Table of contents

  

*  [About](#about)

* [Technologies Used](#technologies-used)

* [Results of the Project](#results-of-the-project)

* [Implementation](#implementation)

*  [Installation](#installation)

*  [License](#license)

  
  

## About

> `Spam` and `Ham` classification is very useful since it save a lot of time of users. The time spend in reading spam emails are saved.


## Technologies Used
  
> [![](https://img.shields.io/badge/python-3.8-blue.svg)](https://www.python.org/downloads/release/python-380/) is used as Programming Language.

>  `Numpy` and `Pandas` are used to work with the data.

> `Matplotlib` is used to visualise the results.

> `Sciki-learn` is used for data preprocessing, creating machine learning model and evaluating it, thus creating a pipeline.

> `Pipenv` is the virtual environment used for the project. `Jupyter Notebook` is used to for the entire data science and machine learning life cycle.

## Results of the Project

####  Metrics Scores

![Metrics Scores](https://github.com/AkashSDas/Ham-or-Spam/blob/master/project-results-images/metrics-scores.png)

#### Confusion Matrix

```python
   precision    recall  f1-score   support

           0       0.99      1.00      0.99      1314
           1       1.00      0.97      0.98       405

    accuracy                           0.99      1719
   macro avg       0.99      0.98      0.99      1719
weighted avg       0.99      0.99      0.99      1719
```

![Confusion Matrix](https://github.com/AkashSDas/Ham-or-Spam/blob/master/project-results-images/confusion-matrix.png)

## Implementation

> The `machine learning model` developed here is `implemented` on `website` build using `Django` framework of `Python` as its backend and using `HTML5`, `CSS3` and `Bootstrap4`.

> The source code is available [here](https://github.com/AkashSDas/HamSpam).

## Installation

  

It is highly **recommended** to use **`virtual environment`** for this project to avoid any issues related to dependencies.

  

Here **`pipenv`** is used for this project.

  

There is a **`requirements.txt`** file in `'Ham-or-Spam'/requirements.txt` which has all the dependencies for this project.

  

- First, start by closing the repository

  

```bash
git clone https://github.com/AkashSDas/Ham-or-Spam
```

  

- Start by installing **`pipenv`** if you don't have it

```bash
pip install pipenv
```

  

- Once installed, access the venv folder inside the project folder

```bash
cd  'Ham-or-Spam'/venv/
```

  

- Create the virtual environment

```bash
pipenv install
```

The **Pipfile** of the project must be for creating replicating project's virtual environment.

  

This will install all the dependencies and create a **Pipfile.lock** (this should not be altered).

  

- Enable the virtual environment

```bash
pipenv shell
```
- dataset, jupyter notebook and model are in `'Ham-or-Spam'/requirements.txt/src` folder.
```bash
cd src/
```

  

- To start/view the jupyter notebook

```bash
jupyter noterbook
```

  

This will open a webpage in the browser from there you can click on notebook.ipynb to view it.
  

## License

  

This project is licensed under the MIT License - see the [MIT LICENSE](LICENSE) file for details.
