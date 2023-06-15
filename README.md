# Notebooks

I often use Jupyter notebooks to explore data and to prototype code. This repository contains a collection of notebooks that I have created.

## Development

You can start a new TensorFlow container with GPU support and Jupyter notebook using this command:

```bash
docker run --gpus all -v $(realpath ~/notebooks):/tf/notebooks -p 8888:8888 tensorflow/tensorflow:latest-gpu-jupyter
```
