# Spikformer-like Models for Spiking Neural Networks

Spiking Neural Networks (SNNs) are a type of artificial neural network that closely mimic the way biological neurons communicate. They use spikes, or discrete events, to transmit information, making them more efficient in terms of energy consumption and processing speed.

**This repository provides implementations of Spikformer-like models, which combine the advantages of Transformers and SNNs.** The main purpose of this repository is to help users easily understand the key concepts and ideas behind these models. Therefore, we provide notebook files with detailed explanations and simple implementations using PyTorch and snnTorch. Below is a list of the models included in this repository (or future works):

|Model|Colab|Paper (Year)|Description|
|:---:|:---:|:---:|---|
|[Spikformer](spikformer.ipynb)|[![spikformer.ipynb](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/DevSlem/spikformer-like-models/blob/main/spikformer.ipynb)|[Zhou, Zhaokun, et al. (2022)](https://arxiv.org/abs/2209.15425)|Replaces the softmax function with a simple matrix multiplication of pure spike-form Query, Key, and Value.|
|Spike-driven Transformer|-|[Yao, Man, et al. (2023)](https://arxiv.org/abs/2307.01694)|
|Spiking Token Mixer|-|[Deng, Shikuang, et al. (2024)](https://proceedings.neurips.cc/paper_files/paper/2024/hash/e8c20cafe841cba3e31a17488dc9c3f1-Abstract-Conference.html)|
|One-step Spiking Transformer|-|[Song, Xiaotian, et al. (2024)](https://www.ijcai.org/proceedings/2024/348)|

## Setup

If you use conda, create a new Python 3.11 environment:

```bash
conda create -n spikformer-like-models python=3.11 -y
conda activate spikformer-like-models
```

Install the required packages using `pip`:

```bash
pip install -r requirements.txt
```
