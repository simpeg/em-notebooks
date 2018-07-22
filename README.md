**[overview](#overview) | [launching the notebooks](#launching-the-notebooks) | [running the notebooks](#running-the-notebooks) | [issues](#issues) | [contributing](#for-contributors)**

# em-notebooks

[![binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/simpeg/em-notebooks/master?filepath=index.ipynb)
[![azure](https://notebooks.azure.com/launch.png)](https://notebooks.azure.com/import/gh/simpeg/em-notebooks)
[![travis](https://travis-ci.org/simpeg/em-notebooks.svg?branch=master)](https://travis-ci.org/simpeg/em-notebooks)
[![SimPEG](https://img.shields.io/badge/powered%20by-SimPEG-blue.svg)](http://simpeg.xyz)

## Overview

This is a repo of notebooks and interactive examples for http://em.geosci.xyz. They are tutorials on the use
of SimPEG for forward modelling and inversion of DC, frequency domain EM, and time domain EM.

The notebooks are available on
- [Binder](https://mybinder.org/v2/gh/simpeg/em-notebooks/master?filepath=index.ipynb)
- [Azure Notebooks](https://notebooks.azure.com/import/gh/simpeg/em-notebooks)

<img src="https://em.geosci.xyz/_images/FDEM_sounding_over_sphere.png" width=60% align="center">

## Launching the notebooks

The notebooks can be run online through [Binder](#Binder) or [Azure notebooks](#Azure), or [downloaded and run locally](#Locally).

### Binder

[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/simpeg/em-notebooks/master?filepath=index.ipynb)

1. Launch the binder by clicking on the badge above or going to: https://mybinder.org/v2/gh/simpeg/em-notebooks/master?filepath=index.ipynb.
   This can sometimes take a couple minutes, so be patient...

2. Select the notebook of interest from the contents

3. [Run the Jupyter notebook](#Running-the-notebooks)

![Binder-steps](https://em.geosci.xyz/_images/binder-steps.png)

### Azure

[![Azure](https://notebooks.azure.com/launch.png)](https://notebooks.azure.com/import/gh/simpeg/em-notebooks)

1. Navigate to Azure notebooks by clicking on the badge above or going to: https://notebooks.azure.com/import/gh/simpeg/em-notebooks,
   and select `Import` to import the library

2. Sign in to your microsoft account (or `Create One` if you do not already have an account)

3. Create the new library: Select Import

4. Select `index.ipynb` to view the notebook contents

5. Select the notebook of interest from the contents

6. [Run the Jupyter notebook](#Running-the-notebooks)

![Azure-steps](https://em.geosci.xyz/_images/azure-steps.png)

### Locally

To run them locally, you will need to have python installed, preferably through [anaconda](https://www.anaconda.com/download/).

You can then clone this reposiroty. From a command line, run

```
git clone https://github.com/simpeg/em-notebooks.git
```

Then `cd` into `em-notebooks`

```
cd em-notebooks
```

To setup your software environment, we recommend you use the provided conda environment

```
conda env create -f environment.yml
source activate em-notebooks-environment
```

alternatively, you can install dependencies through pypi
```
pip install -r requirements.txt
```

You can then launch Jupyter
```
jupyter notebook
```

Jupyter will then launch in your web-browser.

## Running the notebooks

Each cell of code can be run with `shift + enter` or you can run the entire notebook by selecting `cell`, `Run All` in the toolbar.

![cell-run-all](https://em.geosci.xyz/_images/run_all_cells.png)

For more information on running Jupyter notebooks, see the [Jupyter Documentation](https://jupyter.readthedocs.io/en/latest/)

## Issues

If you run into problems or bugs, please let us know by [creating an issue](https://github.com/simpeg/em-notebooks/issues/new) in this repository.

