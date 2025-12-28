# NanoJEPA: Educational I-JEPA Implementation

**NanoJEPA** is a minimalist, educational project designed to demystify the **Joint-Embedding Predictive Architecture (I-JEPA)** by Meta AI.

Our goal is to confirm that you can learn semantic image representations **without labels** using a simple self-supervised architecture, even on a standard laptop CPU.

> **Status:** 🚧 **Work in Progress** - New content released weekly! 🚧

---

## Weekly Release Schedule

We are building this project in public, releasing "atoms" of knowledge every week to take you from **Zero to Hero**.

### Currently Available:
*   [**Prerequisites: PyTorch Foundations**](./prerequisites/README.md)
    *   **Chapter 1:** The Magic of Tensors 
    *   **Chapter 2:** Autograd - The Engine of Learning 
    *   **Chapter 3:** Linear Regression - Your First Model 📉 

### Coming Soon:
*   **Prerequisites: The Zero to Hero Roadmap** (Linear Regression, MLPs, CNNs)
*   **NanoJEPA Series:**
    1.  **Embeddings**: Mapping images to vector spaces.
    2.  **Masking Strategies**: How to hide parts of an image effectively.
    3.  **The Predictor**: Learning to dream in latent space.
    4.  **The Full I-JEPA System**: Putting it all together.

---

## Quick Start

### 1. Installation

```bash
# Clone and enter directory
cd nano_jepa

# Create virtual environment
python3 -m venv venv
source venv/bin/activate 

# Install dependencies
pip install -r requirements.txt
```

### 2. Start Learning

Launch Jupyter to explore the released notebooks:

```bash
jupyter notebook
```

Navigate to the `prerequisites/` folder to begin your journey!

---

## What is I-JEPA? (High Level)

I-JEPA (Image Joint-Embedding Predictive Architecture) is a new way for AI to "understand" images. Instead of predicting missing *pixels* (like many other models), it predicts missing *information* in an abstract representation space.

Think of it like this: If I cover a dog's ear in a photo, you don't imagine every individual hair. You recall the *concept* of a dog ear. I-JEPA tries to do the same.

**Key Technical Features:**
- **Encoders**: Turn images into compact feature vectors.
- **Predictors**: Guess the feature vectors of hidden image regions.
- **Self-Supervision**: Learns without any human labels.

---

## References

- [I-JEPA Paper](https://arxiv.org/abs/2301.08243)
- [Meta AI Blog](https://ai.meta.com/blog/yann-lecun-ai-model-i-jepa/)

---

**Happy Learning!**
