# Multimodal Autoencoder

This repository contains an implementation of a multimodal autoencoder designed for feature compression, denoising, and cross-modal reconstruction tasks. The model is implemented in **PyTorch** and supports dynamic noise injection for robustness evaluation.

---

## Features
- **Feature Compression**: Encodes multimodal data into a compact latent space.
- **Denoising**: Learns to reconstruct clean signals from noisy inputs.
- **Cross-Modal Reconstruction**: Trains the autoencoder to predict one modality from another.
- **Dynamic Noise Injection**: Noise is added during training at the batch level for realistic augmentation.
- **Handling Missing Modality**: Any all-NaN aka missing or flatline channel is masked & replaced with zeros; masks carried through losses.

---

## Requirements
- Python 3.8+
- PyTorch
- NumPy
- Matplotlib
- Jupyter Notebook

Install dependencies via:
```bash
pip install -r requirements.txt
