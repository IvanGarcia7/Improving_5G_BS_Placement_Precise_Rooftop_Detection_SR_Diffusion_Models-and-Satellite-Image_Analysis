# Improving 5G Base Station Placement through Precise Rooftop Detection using Super-Resolution Diffusion Models and Satellite Image Analysis

This repository contains the code, data, and experimental results associated with the research project "Improving 5G Base Station Placement through Precise Rooftop Detection using Super-Resolution Diffusion Models and Satellite Image Analysis." This work has been developed as part of state-funded projects to enhance 5G network deployment through improved rooftop detection.

## Overview

The project proposes a novel methodology to accurately detect rooftops from satellite imagery, which in turn improves the placement of 5G base stations in urban areas. Key components of the methodology include:

- **Super-Resolution Diffusion Models:** Enhancing the quality and level of detail in satellite images.
- **Patch Extraction and Recomposition:** Dividing high-resolution images into overlapping patches using a sliding window approach, followed by recomposition of segmentation masks.
- **Weighted Aggregation:** Combining global and local segmentation outputs through a weighted scoring scheme.
- **Thresholding and Contour Extraction:** Refining the segmentation with thresholding and delineating object boundaries via contour extraction.

## Installation

### Prerequisites

- Python 3.8 or higher
- PyTorch (see [pytorch.org](https://pytorch.org/))
- OpenCV
- Additional dependencies are listed in `requirements.txt`

Install the required dependencies using pip:

```bash
pip install -r requirements.txt
```

Upon acceptance of the submitted article to Natural Computing, the complete code associated with this work will be published, ensuring open access and full reproducibility of the presented results.


