# I-GUIDE GeoAI Education

GeoAI educational materials for the [I-GUIDE](https://i-guide.io) platform. This repository contains Jupyter notebook tutorials covering geospatial artificial intelligence workflows, from data acquisition through advanced deep learning tasks.

## Notebooks

| # | Topic | Description |
|---|-------|-------------|
| 01 | [Downloading Remote Sensing Data](notebooks/01-download-data.md) | Search and download satellite imagery using STAC APIs and the Planetary Computer |
| 02 | [Interactive Mapping & Visualization](notebooks/02-visualization.md) | Create interactive maps with leafmap for data inspection and result evaluation |
| 03 | [Creating Training Data](notebooks/03-training-data.md) | Generate image chips and training datasets from satellite imagery and vector annotations |
| 04 | [Image Recognition](notebooks/04-image-recognition.md) | Train image classifiers on satellite imagery using ResNet, EfficientNet, and other architectures |
| 05 | [Object Detection](notebooks/05-object-detection.md) | Detect and localize objects in remote sensing imagery with Faster R-CNN |
| 06 | [Semantic Segmentation](notebooks/06-semantic-segmentation.md) | Pixel-level classification for land cover mapping, building detection, and water body extraction |
| 07 | [Instance Segmentation](notebooks/07-instance-segmentation.md) | Delineate individual objects (e.g., agricultural fields) with Mask R-CNN |
| 08 | [Image Translation](notebooks/08-image-translation.md) | Enhance Sentinel-2 imagery resolution using latent diffusion super-resolution |
| 09 | [Change Detection](notebooks/09-change-detection.md) | Detect building changes between multi-temporal NAIP imagery with ChangeStar |
| 10 | [Pixel-Level Regression](notebooks/10-pixel-regression.md) | Predict continuous values (e.g., NDVI, canopy height) for every pixel |
| 11 | [Segment Anything for Geospatial](notebooks/11-sam-geospatial.md) | Zero-shot segmentation with SAM 3 for geospatial applications |
| 12 | [Vision-Language Models](notebooks/12-vision-language-models.md) | Image captioning, visual question answering, and object detection with VLMs |
| 13 | [Satellite Embeddings](notebooks/13-foundation-models.md) | Work with satellite foundation model embeddings from Clay, TESSERA, and AlphaEarth |

## Installation

All notebooks use the [geoai](https://opengeoai.org) Python package. Install it with:

```bash
pip install geoai-py
```

## License

This project is licensed under the [MIT License](LICENSE).
