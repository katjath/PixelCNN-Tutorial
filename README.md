# PixelCNN-Tutorial
This repository introduces PixelCNN with theory and a runnable implementation, followed by an application to a spin glass lattice model.

## Setup (Python 3.11 + venv)
Create and activate a virtual environment, then install dependencies:

```bash
python3.11 -m venv .venv
. .venv/bin/activate
python -m pip install --upgrade pip
python -m pip install -r requirements.txt
```

## Notebooks
- `01_pixelcnn_intro.ipynb`: PixelCNN theory + implementation + sampling
- `02_spin_glass_lattice_example.ipynb`: Spin glass lattice example
