# Morphix

An interactive face generation and manipulation project using StyleGAN2-ADA with Gradio interfaces.

## Demo
Check out the demo video of the Gradio interface in action: [Demo Video](https://drive.google.com/drive/folders/1Qb57lrzGOZ-UycXSRPz7SiY-OkpD_yBx)

## Overview
This project provides a suite of tools for generating, editing, and manipulating realistic human faces using NVIDIA's StyleGAN2-ADA. Features include:
- Face generation with latent space manipulation
- Interactive attribute editing (smile, age, gender)
- Style mixing between different faces
- Undo/redo functionality
- Batch generation and export

## Project Structure
- `Morphix_1.ipynb`: Initial face generation and latent vector creation
- `Morphix_2.ipynb`: Basic real-time face editing interface
- `Morphix_3.ipynb`: Advanced editing with style mixing and history
- `assign1_npx/`: Pre-computed latent vectors

## Requirements
- Python
- PyTorch (1.13.1)
- torchvision (0.14.1)
- Gradio
- CUDA support
- Additional dependencies: click, requests, tqdm, pyspng, ninja, imageio-ffmpeg

## Quick Start

1. **Generate Faces** (Morphix_1.ipynb):
   - Creates and saves face images with their latent vectors

2. **Basic Editing** (Morphix_2.ipynb):
   - Real-time face attribute manipulation
   - Simple interface for exploring generated faces

3. **Advanced Editing** (Morphix_3.ipynb):
   - Style mixing between faces
   - Attribute manipulation with undo/redo
   - Enhanced interface with performance metrics