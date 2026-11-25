# Vehicle Detection YOLO Pipeline

Work in progress. An end-to-end vehicle detection project: data collection and annotation, YOLO training, evaluation, and a tracking and counting pipeline served through an API.

## Status

- [x] Repo skeleton
- [ ] Data collection and annotation
- [ ] Training and evaluation
- [ ] Inference, tracking and counting
- [ ] API, Docker, CI

## Setup

```powershell
conda create -n vehicle-det python=3.11
conda activate vehicle-det
pip install torch torchvision --index-url https://download.pytorch.org/whl/cpu
pip install -r requirements.txt
```
