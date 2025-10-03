# 📄 Suggested Papers and Repos for EEG Emotion Recognition

## 🧠 Key Papers

| # | Title & Link | Contribution / Why Useful |
|---|--------------|----------------------------|
| 1 | [Deep learning-based EEG emotion recognition: Current trends and challenges](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC) | A survey of deep learning methods in EEG emotion recognition; useful for background and identifying research gaps. |
| 2 | [TSception: Capturing Temporal Dynamics and Spatial Asymmetry from EEG for Emotion Recognition](https://github.com/Inteegrus-Research/EEG-Emotion-Recognition/blob/main/notebooks/TSception) | Multi-scale CNN combining temporal and spatial features; evaluated on DEAP dataset. |
| 3 | [AMDET: Attention based Multiple Dimensions EEG Transformer for Emotion Recognition](https://github.com/Inteegrus-Research/EEG-Emotion-Recognition/blob/main/notebooks/AMDET) | Transformer + attention for spectral, spatial, and temporal EEG info; tested on DEAP, SEED, SEED-IV. |
| 4 | [Hybrid Spatio‑Temporal Attention NN](https://github.com/Inteegrus-Research/EEG-Emotion-Recognition/blob/main/notebooks/Hybrid-Spatio-Temporal-Attention-NN) | Graph smoothing + spatio-temporal attention; strong architecture for benchmarking. |
| 5 | [EEG-RegNet: Regressive Emotion Recognition in Continuous VAD](https://www.mdpi.com/journal) | Predicts continuous emotional scores (valence/arousal) rather than discrete emotion classes. |
| 6 | [Enhancing EEG Signal-Based Emotion Recognition with Synthetic Data: Diffusion Model Approach](https://arxiv.org/abs) | Uses diffusion models for synthetic EEG data augmentation; helps with small dataset issues. |

## 🧪 Key Repositories

| # | Repo & Link | Contribution / Why Useful |
|---|-------------|----------------------------|
| 1 | [TSception (PyTorch)](https://github.com/yi-ding-cs/TSception) | PyTorch implementation of TSception; strong baseline CNN for raw EEG on DEAP. |
| 2 | [EEGain](https://github.com/EmotionLab/EEGain) | Turnkey framework for running EEG emotion experiments across datasets and models. |
| 3 | [EEGNet (PyTorch)](https://github.com/Amir-Hofo/EEGNet) | Lightweight CNN baseline; ideal for low-parameter and hardware-ready models. |
| 4 | [EEG-Transformer](https://github.com/eeyhsong/EEG-Transformer) | Transformer-based EEG model with spatial & temporal attention; aligns with AMDET design. |
| 5 | [Synthetic EEG via Diffusion (Author Repo)](https://github.com/gsiddhad) | Author portfolio for diffusion-based EEG augmentation; useful for small dataset scenarios. |
