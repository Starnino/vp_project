# Human CycleGAN
Project repository for the course of Vision and Perception 2020, Sapienza University of Rome. 

## Abstract
Image-to-image translation is a class of vision and graphics problems where the goal is to learn the mapping between an input image and an output image using a training set of aligned image pairs. However, for many tasks, paired training data will not be available. CycleGANs learn to translate an image from a source domain X to a target domain Y in the absence of paired examples. The goal of the project is to propose a solution for image translation task from human faces into different kind of domains using the CycleGAN architecture proposed in the paper “Unpaired Image-to-Image Translation using Cycle-Consistent Adversarial Network”.

## The project
The Python implementation includes:
- Download Datasets from Kaggle
- Image Preprocessing
- CycleGAN architecture
- Training and Testing

### Domains
I tested the algorithm with 3 different domains:
- Animals
- Simpsons
- Bitmoji

### Results
![results](https://github.com/Starnino/vp_project/blob/main/results.jpeg?raw=true)

## [Presentation](https://github.com/Starnino/vp_project/blob/main/CycleGAN_V%26P_Presentation.pdf)
## [Notebook](https://github.com/Starnino/vp_project/blob/main/CycleGAN_V%26P_Project.ipynb)

## References
> Jun-Yan Zhu, Taesung Park, Phillip Isola, Alexei A. Efros. 2017
[https://arxiv.org/abs/1703.10593](https://arxiv.org/pdf/1703.10593.pdf)
