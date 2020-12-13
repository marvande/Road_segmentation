# ML_Project_2: Project Road Segmentation
Project 2 of the Fall 2020 Machine Learning course. For this choice of project task, they provided a set of satellite images acquired 
from GoogleMaps. They also provided ground-truth images where each pixel is labeled as road or background. Our task was to train a classifier to segment roads in these images, i.e. assigns a label `road=1, background=0` to each pixel.

## Team Members
- Marijn VAN DER MEER
- Léo MEYNENT
- Vincent TOURNIER

## Structure of the repository: 
**complete**

## Instructions to run:

The dataset is available from the 
[here](281e7599-7024-4d7e-a95d-e1af53d3e8c0_test_set_images.zip).

Python modules requirements: ?

Predictions will be saved in `data/predictions/` and in `submit.csv`. To reproduce our best score with logistic regression that we submitted on [AIcrowd](https://www.aicrowd.com):
```
python run.py
```
To see plots of the evolution of losses during training, run `colab.ipynb`. 
