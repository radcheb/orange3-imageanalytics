Orange3 Image Analytics Developer Guide
=======================================

## Create local dev environment

```bash
conda create -n orange python=3.6 orange3 
conda activate orange
```

## Launch Orange

```bash
conda activate orange
orange-canvas &
```

## Install Image analytics module locally

```
conda activate orange
pip install .
```

Restarting Orange is required after installing a new version of Image Analytics Module
