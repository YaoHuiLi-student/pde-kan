# PDE-KAN

Official implementation of:

"PDE-KAN: Physics-Informed Medical Image Segmentation via PDE-Guided Feature Evolution and Kolmogorov-Arnold Networks"

## Environment

```bash
conda create -n pdekan python=3.10
conda activate pdekan

pip install -r requirements.txt

Training

python train.py

Testing

python test.py

Datasets
Synapse
ACDC
ISIC2017
ISIC2018
PH2

Please download datasets from the official sources.
