# Image Style Transfer using CNN

## Overview
This project applies Neural Style Transfer using a pretrained VGG19 model to combine the content of one image with the artistic style of another image.

## Problem Statement
Traditional image processing methods cannot separate image content and style. 
This project uses deep learning to transfer artistic styles while preserving the original image structure.

## Objectives
- Implement Neural Style Transfer
- Understand CNN feature extraction
- Generate stylized images

## Input
- Content Image
- Style Image

## Methodology
1. Load content and style images
2. Use pretrained VGG19
3. Extract content and style features
4. Compute losses
5. Optimize generated image

## Model
Pretrained VGG19 Convolutional Neural Network

## Results
The model generates an image that preserves the content while applying the artistic style.

## Workflow
Content Image → CNN → Feature Extraction  
Style Image → CNN → Style Representation  
Generated Image → Optimization → Stylized Image
