# Showcase Deep Learning
This showcase consists of two simple showcases to utilize deep learning models.
The first showcase is for a pretty good DL framework called fastai.
The second one shows the usage of a LSTM to classify sequences.

## Setup for jupyter lab

Setup the conda python environment.
```shell
conda env create --prefix /path/to/environment --file environment.yml
```

Activate the conda environment.
```shell
conda activate /path/to/environment
```

Setup fastai
```shell
pip install fastai
```

Install new env as an jupyter kernel
```shell
python -m ipykernel install --user --name /path/to/environment --display-name "DL Showcase"
```


