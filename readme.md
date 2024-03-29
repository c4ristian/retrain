# Retrain Project

## What is it?
This project uses an artificial neural network to show why retraining can be harder than training from 
scratch in a changing environment.

## Main Features
The experiment is run using a [jupyter notebook](retrain_phones.ipynb).

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
