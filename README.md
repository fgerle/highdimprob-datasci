# Repository of Python examples 

These examples accompany the lecture "High dimensional probability towards data science" held by Prof. Dr. Anita Winter in the summer term 2021 at the university of Duisburg-Essen, Germany.

## General

This repository provides some examples as interactive Jupyter Notebooks. More about Jupyter Notebooks can be found on the homepage of the [Jupyter Project](https://jupyter.org/). The notebooks are viewed through a web browser but need a running python kernel to run the code. This kernel can be run either locally or remotely via a cloud service like binder. 

### Run Notebooks locally

#### Prerequisits
This guide assumes you have already python3 installed on your system.

In order to run the Notebooks locally I recommend jupyterlab. Installing jupyterlab via pip is very simple, just run 
```
pip install jupyterlab
```
in a terminal. More information is again available on the pages of the [Jypyter Project](https://jupyter.org/install.html).

I also recommend using git ([git installation](https://git-scm.com/downloads)) to download the latest version of the repository. 


#### Get the sources
You can either download the source files directly from this repository or you can clone the whole repository using git:

```
git clone git@gitlab.com:fabian.gerle/high-dimensional-probability.git
```

Once you have cloned the repository you can update the sources at anytime using `git fetch`

```
cd high-dimensional-probability
git fetch origin
git pull
```
Be aware that this overwrites local changes on the source files.

#### Install dependencies
The repository comes with a list of dependencies in `requirements.txt`. To install all dependencies at once run
```
pip install -r requirements.txt
```
from within the projects folder.

#### Run the jupyter kernel
Finally run the jupyter kernel
```
jupyter-lab
```
This starts the kernel and should open jupyter-lab in the system's default browser. If for some reason this does not work, the command outputs a url to copy and paste into a browser of your choice.


### Run Notebooks remotely
Easier but possibly slower is the usage of a cloud service like [binder](https://mybinder.org/). This repository comes with pre-build binder instances for each notebook.

## Erdos-Renyi Examples

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gl/fabian.gerle%2Fhigh-dimensional-probability/HEAD?filepath=Erdos_Renyi.ipynb)
