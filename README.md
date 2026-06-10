# spacecraft-pose-estimation
Modified ResNet-50 spacecraft pose estimation framework with multi-stage supervision and weighted Euclidean loss for RGB-based 6DoF pose regression.
Before uploading, I would recommend sharing your actual project folder (or a zip of the code). Then I can tell you exactly which files to commit, which files to remove, generate a professional README.md, requirements.txt, and .gitignore, and prepare the repo in GitHub-ready form. 
# Spacecraft Pose Estimation Using Deep Learning

Implementation of spacecraft pose estimation using
a modified ResNet-50 architecture with a weighted
multi-stage Euclidean loss function.
Deep learning-based spacecraft pose estimation using a modified ResNet-50 architecture with multi-stage supervision and a weighted Euclidean loss function. 

## Features

- ResNet-50 backbone
- Multi-stage supervision
- Custom weighted pose loss
- Position and quaternion regression
- Spacecraft pose estimation from RGB images

## Dataset

Soyuz synthetic spacecraft dataset.

## Installation

pip install -r requirements.txt

## Training

python train.py

## Evaluation

python evaluate.py

## Prediction

python predict.py --image examples/sample.jpg

## Results

Location Error: 2.1 m
Orientation Error: 7.4 deg

## References
This work builds upon the UrsoNet framework proposed by Pedro F. Proença and Yang Gao and extends it through a multi-stage supervision strategy and a customized weighted Euclidean loss formulation for improved spacecraft pose estimation.
UrsoNet repository: https://github.com/pedropro/UrsoNet
Related work:
Pedro F. Proença and Yang Gao (ICRA 2020)
