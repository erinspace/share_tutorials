**These tutorials are compatible with SHARE v2 and use Python 3. For the old, SHARE v1-compatible notebooks, see the [share_v1](https://github.com/erinspace/share_tutorials/tree/share_v1) branch.**

------

# SHARE API v2 Tutorials

Some simple Jupyter Notebooks for accessing, querying, and exporting data from SHARE, API V2!


Use Binder to run the notebooks online! Click here: [![Binder](http://mybinder.org/badge.svg)](http://mybinder.org/repo/erinspace/share_tutorials)

pre-requisites:
- Python 3.5
- [pip for installing python packages](https://pypi.python.org/pypi/pip) 
OR
- [Miniconda](http://conda.pydata.org/miniconda.html) for python package and environment handling


## Setup
- Clone this repository to your local machine
    - [Here's a guide to cloning from github](https://help.github.com/articles/cloning-a-repository/)
    - [Fork the repository first](https://help.github.com/articles/fork-a-repo/) to have your own copy and make changes on github!
    - feel free to [create a pull request](https://help.github.com/articles/creating-a-pull-request/) with improvements and suggestions!

### Option 1: With ``conda`` (recommended)

Prerequisite: Must have Anaconda or [miniconda](http://conda.pydata.org/miniconda.html) installed.

**Linux and OSX**:

```
conda env create -f environment.yml --name share_tutorials
source activate share_tutorials
```

**Windows**:

```
conda env create -f environment_win.yml --name share_tutorials
activate share_tutorials
```

### Option 2: With `virtualenv` and `pip`
- Install requirements from ```requirements.txt``` inside a virtualenv with:

```
# After activating your virtualenv
pip install -r requirements.txt
```


## Run the notebooks

- Run the jupyter notebook in  a terminal with the command: ```jupyter notebook```
- Click on the notebook you'd like to run
- Run cells individually with the `shift+return`
