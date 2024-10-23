# Intro to ML for biological data analysis

This repository contains a Jupyter notebook with two example projects for using ML for analyzing biological imaging data. If you can, please try to install the repository using one of the methods below. If you don't manage, that's ok - there is also the option to run the notebook online via Binder without installing anything (description at the bottom).

## Getting Started

You will need to have to install python 3.9 to make sure all requirements can be installed. 

### Option 1: Install with `requirements.txt` (Using `pip`)

This is probably the easiest option, although option 2 is more reliable.

1. **Clone the repository** Download the repository to your computer by opening a terminal and running:

		git clone https://github.com/jjmetzger/ML-Intro.git
		cd ML-Intro
   
2. **Create and activate a virtual environment**. If you don't have python installed, you will need to do this first.
   
		python3.9 -m venv venv
		source venv/bin/activate

4. **Install the required packages**

		pip install -r requirements.txt

5. **Launch Jupyter Notebook**

		jupyter notebook ML_intro.ipynb
	

### Option 2: Install with pyproject.toml (Using Poetry)
This is the better option, but you will have to install poetry.

1. **Clone the repository**
   
		git clone https://github.com/jjmetzger/ML-Intro.git
		cd ML-Intro

3. **Install poetry if you haven't done so already.**
   
		curl -sSL https://install.python-poetry.org | python3 -

5. **Install the project dependencies using Poetry and run**
In the project folder, run

		poetry install
		poetry shell 
		poetry run jupyter notebook ML_intro.ipynb


## Launch on Binder.
This will launch the notebook online without any need for installing anything. However, it won't be possible to actually run training of any models.

Click the badge below to launch.

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/jjmetzger/ML-Intro/main?labpath=ML_intro.ipynb)
