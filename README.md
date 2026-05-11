# 🌸 Flower Classifier — Oxford Flowers 102
 
A deep learning app that identifies **102 flower species** from a photo using a fine-tuned **MobileNetV3** model trained on the Oxford Flowers 102 dataset.

## 🔍 Overview
 
This project fine-tunes a pretrained **MobileNetV3-Small** (trained on ImageNet) to classify 102 flower species. The model is lightweight and suitable for mobile or web deployment.
 
**Key features:**
- 102 flower species classification
- Transfer learning with MobileNetV3-Small
- Top-5 prediction visualization with confidence scores
- GPU support (CUDA) with CPU fallback
---
 
## 🌼 Dataset
 
**Oxford Flowers 102** — built into `torchvision.datasets`
 
| Split | Images |
|-------|--------|
| Train | 1,020  |
| Val   | 1,020  |
| Test  | 6,149  |
