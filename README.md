# Get up and running

- Choose a competition from this repository to work on
- in the following text replace \<competition> by the chosen competition

## Clone the repository for the competition
```
git clone git@github.com:alexgawrilow/kaggle.git
```

## Install the requirements using poetry
- Make sure [poetry](https://python-poetry.org/docs/#installation) is installed on your system
```
cd kaggle/<competition>
poetry install
```

## Create a jupyter kernel for the competition
```
source .venv/bin/activate
ipython kernel install --user --name=<competition>
jupyter notebook
```
When creating a new jupyter notebook, choose the created kernel

## Download challenge data

## Submit sollution
