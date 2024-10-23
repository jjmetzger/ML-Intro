# Intro to ML for biological data analysis

This repository contains a Jupyter notebook with two example projects for using ML for analyzing biological imaging data.

## Getting Started

### Option 1: Install with `requirements.txt` (Using `pip`)

This is the easiest option if you're not familiar with Python package managers like Poetry.

1. **Clone the repository** Download the repository to your computer by opening a terminal and running:

   git clone https://github.com/jjmetzger/ML-Intro.git
   cd ML-Intro
   
2. **Create and activate a virtual environment**. If you don't have python installed, you will need to do this first.
	python3 -m venv venv
	source venv/bin/activate

3. **Install the required packages**
	pip install -r requirements.txt

4. **Launch Jupyter Notebook**
	jupyter notebook ML_intro.ipynb
	

### Option 2: Install with pyproject.toml (Using Poetry)
This option is ideal if you're comfortable with using the Poetry package manager.

1. **Clone the repository**
	git clone https://github.com/jjmetzger/ML-Intro.git
	cd ML-Intro

2. **Install poetry if you haven't done so already.**	
	curl -sSL https://install.python-poetry.org | python3 -

3. **Install the project dependencies using Poetry and run**
In the project folder, run
	poetry install
	poetry shell 
	poetry run jupyter notebook ML_intro.ipynb


## Launch on Binder.
This will launch the notebook online without any need for installing anything. However, it won't be possible to actually run training of any models.

Click the badge below to launch.

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/jjmetzger/ML-Intro/main?labpath=ML_intro.ipynb)
