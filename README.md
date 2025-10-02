# Handwritten Digit Classification with PyTorch

## Description

This project is mainly for learning purposes. It starts with a basic implementation of a Convolutional Neural Network (CNN) in PyTorch to recognize handwritten digits from the MNIST dataset.
Later, I plan to extend it by testing the model on digits written by myself, creating a small custom dataset. This way, I can evaluate the model’s performance in different scenarios.


## Use of LLMs for assistance

I acknowledge the major role that LLMs play today in development, both for generating code and improving documentation. I will use them as a support tool in this project—for commands, PyTorch syntax, and general guidance—but always applying critical thinking and making sure I understand what I’m doing. The ultimate goal is to learn to carry out these tasks independently in the future.

*Miguel Robledo Kusz, October 3rd, 2025, 00:41.*

## Environment

### First way (recommended)

#### Create environment from environment.yml

```bash
conda env create -f environment.yml
```

#### Activate the environment

```bash
conda activate pytorch-cnn-mnist
```

### Second way

#### Create the environment

```bash
conda create -n pytorch-cnn-mnist python=3.10 -y
```

#### Activate environment
```bash
conda activate pytorch-cnn-mnist
```

#### Install libraries
```bash
conda install pytorch torchvision torchaudio cpuonly matplotlib -c pytorch
```

