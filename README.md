 
# Chest X-Ray Report Generation using Vision-Language Models

## Overview

This project investigates automatic medical report generation from chest X-ray images using multiple vision-language architectures. The goal is to generate clinically meaningful radiology reports directly from chest X-ray images.

The project compares several approaches, including handcrafted visual features, convolutional neural networks, Vision Transformers (ViT), multimodal fusion techniques, and parameter-efficient fine-tuning using LoRA.

---

## Models Evaluated

1. Handcrafted Features Baseline
2. DenseNet121 + GPT-2
3. Vision Transformer (ViT) + GPT-2
4. DenseNet121 + Handcrafted Features
5. ViT + Handcrafted Features
6. Full Fusion Model
7. ViT + GPT-2 with LoRA Fine-Tuning

---

## Technologies Used

* Python
* PyTorch
* Hugging Face Transformers
* GPT-2
* Vision Transformer (ViT)
* DenseNet121
* LoRA (Low-Rank Adaptation)
* NumPy
* Pandas
* Scikit-learn

---

## Evaluation Metrics

The models were evaluated using:

* BLEU
* ROUGE-L
* BERTScore

---

## Repository Structure

```text
01_handcrafted_baseline.ipynb
02_densenet121_gpt2.ipynb
03_vit_gpt2.ipynb
04_densenet_handcrafted.ipynb
05_vit_handcrafted.ipynb
06_full_fusion.ipynb
07_vit_gpt2_lora.ipynb
```

---

## Project Report

The full project report is included in this repository as:

```text
proj_final_first_version.pdf
```

---

## Author

Mariam Shehada

M.Sc. Student in Artificial Intelligence
