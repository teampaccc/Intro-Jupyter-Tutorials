# **Introductory Python for Climate Model Analysis Tutorials**

This repository contains Jupyter Notebook tutorials that demonstrates how to work with NetCDF files using Python. 

## 🚀 Quick Start

### 1. Clone the repository

From your directory on Svante, run:

```bash
git clone https://github.com/teampaccc/Intro-Jupyter-Tutorials.git
cd Intro-Jupyter-Tutorials
```
### 2. Set up your environment

The only packages required for this tutorial are:
`xarray`, `numpy`, `netcdf4`, and `cartopy`

Let's set up a new Python [environment](https://svante.mit.edu/use_python.html#using-conda-w-package-manager-to-create-virtual-environments) using Anaconda on Svante. From the command line, run:
1. Load `conda`
```bash
module add anaconda3/2023.07
```
2. create and activate your environment
```bash
conda create -n «environment name»
source activate «environment name»
```
3. install necessary packages
```bash
conda install jupyterlab
conda install xarray numpy netcdf4 cartopy
```

### 3. Launch Svante Open OnDemand (OOD)

Visit the [OOD webpage](https://svante-ood.mit.edu), and follow the process described [here](https://svante.mit.edu/use_python.html#running-jupyter-notebooks-using-svante-open-ondemand).

Choose the Jupyter notebook option under either the Compute Node Interactive Apps or the Fileserver Interactive Apps section.

Make sure to:

-  ✅ Check box if using custom Anaconda environment
-  Type the correct name of the environment you defined in step **2** in the box labeled: Name of Custom Conda Environment

Then, click **Launch**.

----

From here, you should be able to navigate to your directory, and begin the tutorial!

