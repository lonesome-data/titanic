# Rudimentary EDA using Titanic Data

## Description

The sinking of the RMS Titanic is one of the most infamous shipwrecks in history.  On April 15, 1912, during her maiden voyage, the Titanic sank after colliding with an iceberg, killing 1502 out of 2224 passengers and crew. This sensational tragedy shocked the international community and led to better safety regulations for ships.

One of the reasons that the shipwreck led to such loss of life was that there were not enough lifeboats for the passengers and crew. Although there was some element of luck involved in surviving the sinking, some groups of people were more likely to survive than others, such as women, children, and the upper-class.

In this repo, I analyze which passengers were likely to survive. In the next project, I apply the tools of machine learning to predict which passengers survived the tragedy.

## Prerequisites

Familiarization with...

* programming fundamentals of the Python programming language (e.g., variables, for loops);
* Jupyter Notebooks;
* terminal/shell.

## Getting set up computationally

## Git
At the heart of GitHub is an open source version control system (VCS) called [Git](http://product.hubspot.com/blog/git-and-github-tutorial-for-beginners). Git is responsible for everything GitHub-related that happens locally on your computer.  To use Git on the command line, download, install, and configure Git on computer.

### 1.a Download Git (if you (Windows users) haven't already)

If you do not already have [Git](https://git-for-windows.github.io/), download for BASH or GUI access to the premier version control [SCM](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git).

### 1.b Clone the repository

Executing the following in a Git capable terminal:

```
git clone https://github.com/lonesome-data/titanic/
```
Alternatively, download the zip file of the repository at the top of the main page. If you prefer not to use git or don't have experience with it, this a good option.  Just be mindful of where the file is unzipped.

### 2. Download Anaconda (if you haven't already)

If you do not already have the [Anaconda](https://www.anaconda.com/download/) distribution of Python 3, go get it (n.b., you can also do this w/out Anaconda using `pip` to install the required packages, however Anaconda is great for Data Science so you are encouraged to use it).

### 3. Create your conda environment for this session

Navigate to the relevant 'titanic' directory and install required packages in a new conda [environment](https://conda.io/docs/user-guide/tasks/build-packages/environment-variables.html):

```
conda env create -f environment.yml
```

This will create a new environment called titanic_env. To activate the environment on OSX/Linux, execute

```
source activate titanic_env
```
On Windows, execute

```
activate titanic_env
```
### 4. Open your Jupyter notebook

In the terminal, execute 

```
jupyter notebook
```

Then open the notebook `titanic.ipynb` and get coding.

### Code
The code in this repository is released under the [MIT license](LICENSE). Read more at the [Open Source Initiative](https://opensource.org/licenses/MIT). 
