# ⚽ ViT Football Player Classifier

This project fine-tunes a **Vision Transformer (ViT)** model for classifying football players using the [Golden Foot Dataset](https://huggingface.co/datasets/aaronqg/golden-foot-football-players).

---

## 🚀 Project Overview
- Base model: [`google/vit-base-patch16-224`](https://huggingface.co/google/vit-base-patch16-224)
- Frameworks: PyTorch, Hugging Face Transformers, Torchvision
- Dataset: Golden Foot (22 football players)
- Training environment: Kaggle Notebook

---

## 📊 Results
- Fine-tuned for 100 epochs
- Final **Validation Accuracy: ~78%**
- Loss decreased steadily during training

---

## 📂 Repository Contents
- `notebook.ipynb` → Full training pipeline (data loading, preprocessing, training, evaluation)
- Code is ready to rerun on Kaggle or locally

---

## 🔄 How to Reproduce
1. Clone the repository:
   ```bash
   git clone https://github.com/USERNAME/vit-football-classifier.git
