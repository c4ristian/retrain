# Retrain Project

## What is it?
This project uses a neural network to show that retraining can be harder than training from 
scratch in a radically changing environment.

## Main Features
The project provides a [jupyter notebook](_backup/retrain.ipynb) running the experiment.

## Where to get it
The source code is currently hosted on GitHub at:
https://github.com/c4ristian/retrain

## Setup
```sh
conda env create -f environment.yml

conda activate retrain
```

## Jupyter

### Install Kernel 
```sh
python -m ipykernel install --user --name=retrain
```

### Run Notebooks
```sh
jupyter notebook --notebook-dir="."
```

## License
[Apache 2.0](LICENSE.txt)