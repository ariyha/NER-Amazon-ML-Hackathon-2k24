# Named Entity Recognition (NER) from Images

## Overview

This project is an experimental implementation of Named Entity Recognition (NER) from images using the **Phi 3.5 Vision Instruct** model. The system takes an image and extracts meaningful entities directly from it. It was developed as part of a hackathon challenge, and as such, it remains a work in progress. Several features and optimizations are planned but have not yet been completed.

## Project Status

⚠️ **Important:**  
This project was built for a hackathon and is **not a complete, production-ready solution**. The current implementation works in basic scenarios but lacks extensive error handling, performance optimizations, and support for all edge cases.

## Features

- Uses **Phi 3.5 Vision Instruct** model for extracting entities from images.
- Input: An image containing text (e.g., receipts, documents, posters).
- Output: Named entities such as person names, organizations, and dates.
- Limited preprocessing for handling noise in image data.
- Hackathon build — expect incomplete features and limitations.

## Setup

### Prerequisites

- Python 3.8+
- PyTorch (CUDA support recommended for faster processing)
- Required libraries:
  - `transformers`
  - `torchvision`
  - `Pillow`
