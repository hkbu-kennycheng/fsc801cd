# Installation

We will be using the [Anaconda](https://www.anaconda.com/) distribution of Python 3.11. Anaconda is a free and open-source distribution of Python and R programming languages for scientific computing, that aims to simplify package management and deployment. Package versions are managed by the package management system `conda`.

## Installing Anaconda

Anaconda is available for Windows, macOS and Linux. You can download the installer from [here](https://www.anaconda.com/products/individual). Make sure you download the Python 3.11 version.

## Create a virtual environment

A virtual environment is a self-contained directory tree that contains a Python installation for a particular version of Python, plus a number of additional packages. Different virtual environments can have different versions of Python and different sets of installed packages. This allows you to have multiple versions of Python on the same system, and to maintain a stable version of Python for production applications while working with bleeding-edge versions for testing and development.

Please create a virtual environment for this course with Python 3.11.x

## Install packages

Please install the packages using the following command:

```bash
conda install -y -c conda-forge cudatoolkit=11.8 cudnn=8.2.1
conda install -y pytorch torchvision torchaudio pytorch-cuda=11.8 -c pytorch -c nvidia
```

```bash
conda install -y -c conda-forge requests diffusers transformers accelerate jupyter seaborn matplotlib pandas scikit-learn scikit-image scikit-learn-intelex opencv numpy scipy beautifulsoup4 nltk pyppeteer
conda install -y -c conda-forge orange3 orange3-educational orange3-associate orange3-text orange3-imageanalytics orange3-geo orange3-bioinformatics orange3-prototypes
```