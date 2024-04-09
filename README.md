# Nano_Models

<p align="center">
  <img src="images/cat_image.jpg" alt="alt" width="512"/>
</p>


Welcome to the Nano_Models repository, where our mission is to demystify complex model architectures presented in research papers, making it easier for everyone to grasp the core concepts and enhance reproducibility. Through detailed Jupyter notebooks, we break down these architectures step by step, blending theoretical insights with practical code snippets to illuminate the path from paper to implementation.

## Philosophy

In the pursuit of advancing machine learning and deep learning fields, understanding the essence of research papers is paramount. However, the leap from theory to practice often presents a significant challenge. The  repository aims to bridge this gap by offering a detailed, code-augmented exploration of model architectures. By dissecting these models in an approachable manner, we not only aim to enhance understanding but also to spark innovation and encourage the development of new ideas and improvements.

## Repository Structure

- **Notebooks/**: Contains Jupyter notebooks that walk you through the model architectures. Each notebook is dedicated to a specific paper/model, starting with a brief overview of the paper, followed by a detailed explanation of the model's architecture, and concluding with a touch of code to see the model in action.
- **Modules/**: Houses the actual code implementations of the models discussed in the notebooks. This code is extracted directly from the implementations for reference and educational purposes.

## Getting Started

```
# create the conda environments
conda create -n nano_models python=3.9
# activate the environment
conda activate nano_models
# install the package in editable mode
pip install -e .
```

## Models 
### vit implementation 
Notebook : [vit notebook](notebooks/swin_transformers.ipynb) <br>
Code : [vit code](modules/vit.py)<br>
Inspired from : https://github.com/lucidrains/vit-pytorch

### Swin Implementation
Notebook : [swin notebook](notebooks/swin_transformers.ipynb) <br>
Code : [swinv1 code](modules/swin_easy.py)   [swinv2 code](modules/swin_v2.py)  <br>
Inspired from : https://github.com/microsoft/Swin-Transformer/tree/main/models https://github.com/berniwal/swin-transformer-pytorch

## License
nano_models has a mit type license as found in [license](LICENSE) file