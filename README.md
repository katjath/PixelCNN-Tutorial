# PixelCNN-Tutorial

This repository introduces PixelCNN with theory and a runnable implementation, followed by an application to a spin glass lattice model.

## Quick Start: Run in Google Colab (No Setup Required)

Click the badges below to run the notebooks directly in your browser:

- **01_pixelcnn_intro.ipynb**: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/katjath/PixelCNN-Tutorial/blob/main/01_pixelcnn_intro.ipynb)
- **02_spin_glass_lattice_example.ipynb**: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/katjath/PixelCNN-Tutorial/blob/main/02_spin_glass_lattice_example.ipynb)

## Local Setup (Python 3.11 + venv)

For running locally:

```bash
git clone https://github.com/katjath/PixelCNN-Tutorial.git
cd PixelCNN-Tutorial
python3 -m venv .venv
source .venv/bin/activate  # On Windows: .venv\Scripts\activate
pip install -r requirements.txt
jupyter notebook
```

## Notebooks

- `01_pixelcnn_intro.ipynb`: PixelCNN theory + implementation + sampling
- `02_spin_glass_lattice_example.ipynb`: Spin glass lattice example
