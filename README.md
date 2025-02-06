# FLO-SR: Deep learning-based urban flood super-resolution model

This repository accompanies the paper [**FLO-SR: Deep learning-based urban flood super-resolution model**] (in review) (Hyeonjin Choi, Hyuna Woo, Minyoung Kim, Hyungon Ryu, Jun-Hak Lee, Seungsoo Lee, and Seong Jin Noh)

<img src="images/flo-sr-architecture.png" alt="FLO-SR Model" width="600">

We, **Hydrology and Water Resources Lab (Noh Lab, https://cyber-hydrology.github.io/)** (Hyeonjin Choi, Hyuna Woo, Minyoung Kim, and Seong Jin Noh) of Kumoh National Institute of Technology

It is built upon the code from https://github.com/LimBee/NTIRE2017.

In this repository, we provide
* Demo & Training code (code)
* Datasets we used (data)

## Setup to run the code locally

Download this repository either as zip-file or clone it to your local file system by running

```
https://github.com/cyber-hydrology/FLO-SR-flood-super-resolution-model.git
```

### Setting up the Python environment
This model must be performed in TensorFlow version 2.15.0 and simply run ipynb code in juputer notebook.
Get the required library by running the first code fragment in ipynb code.

If you have a CUDA-capable NVIDIA GPU. This is recommended if you want to train/evaluate the FLO-SR on your machine, but not strictly necessary.

## Data

### Required Downloads
First, you need the flood data set to run the model. This dataset can be downloaded at the data folder
and set a location in ipynb file.


