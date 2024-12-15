# GPT-2 From Scratch

This repository contains my implementation of **GPT-2** (Generative Pre-trained Transformer-2), developed entirely from scratch using **PyTorch**, **TensorFlow**, and **NumPy**. GPT-2 is an autoregressive language model capable of generating coherent and contextually relevant text by predicting the next word in a sequence.

---

## Model Overview

- **Architecture:** 12 Transformer blocks with multi-head self-attention.
- **Parameters:** Approximately **124 million parameters**.
- **Training Strategy:** Initially trained on a custom dataset. Due to overfitting and limitations in computational resources, I integrated **pre-trained weights** released by OpenAI for fine-tuning and text generation tasks.

---

## Table of Contents

1. [Features](#features)  
2. [Technologies Used](#technologies-used)  
3. [Challenges Encountered](#challenges-encountered)  
4. [Usage](#usage)  
5. [Why This Project?](#why-this-project)  
6. [Future Enhancements](#future-enhancements)  

---

## Features

- Custom implementation of the **Transformer architecture**, including:
  - **Multi-head self-attention mechanism**.
  - **Feed-forward neural network layers**.
  - **Positional encoding** for sequence order information.
  - **Layer normalization**.
- **Integration of Pre-trained Weights:** Utilizes OpenAI's released GPT-2 weights for improved predictions.
- **Next-Word Prediction:** Generates text one word at a time in an autoregressive manner.

---

## Technologies Used

- **PyTorch**
- **TensorFlow**
- **NumPy**

---

## Challenges Encountered

- Training from scratch led to **overfitting** due to insufficient training data and computational resources.  
- Integrated OpenAI's **pre-trained weights** to achieve better performance and overcome resource limitations.

---

## Usage

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your_username/GPT-2-from-scratch.git
   cd GPT-2-from-scratch

---

## Why This Project?

This project aims to:  
- Understand the **Transformer architecture** and the working of GPT-2.  
- Explore challenges in training large models from scratch.  
- Build a modular and extensible foundation for future NLP experiments.

---

## Future Enhancements

- [ ] Implement optimization techniques for faster training.  
- [ ] Fine-tune the model on larger and more diverse datasets.
