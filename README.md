# PixelCNN-Tutorial

This repository introduces **PixelCNN** with a physically and mathematically accurate explanation, plus a runnable implementation and an application to spin glass lattice models.

## 🚀 How to Run

### Option 1: Google Colab (No Setup - Cloud GPU Available)

**Best for**: Quick testing, no local setup needed

Click to open and run directly in your browser:
- [01_pixelcnn_intro.ipynb](https://colab.research.google.com/github/katjath/PixelCNN-Tutorial/blob/main/01_pixelcnn_intro.ipynb)
- [02_spin_glass_lattice_example.ipynb](https://colab.research.google.com/github/katjath/PixelCNN-Tutorial/blob/main/02_spin_glass_lattice_example.ipynb)

### Option 2: Local Setup (Full Control)

**Best for**: Development, reproducibility, local GPU

```bash
git clone https://github.com/katjath/PixelCNN-Tutorial.git
cd PixelCNN-Tutorial
python3 -m venv .venv
source .venv/bin/activate  # On Windows: .venv\Scripts\activate
pip install -r requirements.txt
jupyter notebook
```

**Requirements**: Python 3.11+, PyTorch, NumPy, Matplotlib

## 📓 Notebooks

- **01_pixelcnn_intro.ipynb**: Theory + masked convolutions + implementation + sampling
- **02_spin_glass_lattice_example.ipynb**: PixelCNN applied to physical lattice models
