# NeRF-based 3D Reconstruction with PyTorch

This repository provides a minimal and educational implementation of Neural Radiance Fields (NeRF) using PyTorch. The goal is to demonstrate how 3D scenes can be reconstructed from a sparse set of 2D images using neural rendering techniques.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Requirements](#requirements)
- [Example Output](#example-output)


## Overview

NeRF (Neural Radiance Fields) is a novel approach to synthesizing novel views of complex 3D scenes by optimizing a continuous volumetric scene function using a sparse set of input views. This project implements a simplified version of NeRF to help researchers and students understand its core concepts.

## Features

- Lightweight implementation of NeRF using PyTorch
- Ray generation and volumetric rendering pipeline
- Camera pose sampling from spherical coordinates
- Rendering of novel viewpoints after training

## Requirements

Python 3.8+
PyTorch
NumPy
Matplotlib
tqdm

##  Example Output
You can see the outputs and improvements of the trained model on this link. 
https://embed.deepnote.com/f183d8a3-efd7-45b6-9449-c4006a7cfab3/635c57d453b8459fa0ee8556673554b5/9bc4197c8e014a45b937a872019f8131?height=14512.3251953125

https://github.com/user-attachments/assets/1606bab1-3c14-498b-9c77-baf32a427e7f

## Google Colab
You can access the .ipynb file from my Google Colab link and access the codes and all outputs.
https://colab.research.google.com/drive/1goc5YVrApHEZrXMt5HS_9F7omN7yZZu5?usp=sharing


