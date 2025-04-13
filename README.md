# Skin Disease Image Reconstruction and Generation

## Overview:

This project aims to utilize the ISIC 2016 dataset for segmenting skin disease contours and generating images using Vector Quantized Variational Autoencoders (VQ-VAE). The workflow involves segmenting skin disease contours from the dataset, using these segmentations to create sketches and labels, and providing them to the VQ-VAE model to generate corresponding realistic skin lesion images. The generated images are then evaluated using a pre-trained model to assess their quality and fidelity.

## Prerequisites:

- Python 3.x
- PyTorch
- OpenCV
- ISIC 2016 dataset
- CUDA (optional, for GPU acceleration)

## Installation:

1. Clone the repository:

git clone https://github.com/karansspk462000/Reconsruction-and-Generation-of-Skin-Lesion-Diseases-using-VQVAE.git


2. Install necessary dependencies.


3. Download the ISIC 2016 dataset and place it in the `data/` directory.

## Usage:

1. **Segmentation:**

- Run the segmentation module with your chosen dataset.

- This will generate contours for the skin diseases present in the dataset.

2. **Image Generation:**

- Provide the generated contours and labels to the VQVAE model for image generation.

3. **Testing:**

- Test the generated images using a pre-trained model.

## Results:

<figure>
<figcaption><em>Segmented Mask</em></figcaption>
  <img src="https://github.com/karansspk462000/Generation-and-Segmentation-of-Skin-Lesion-Disease-Images-ISIC-dataset-for-Medical-Imaging/blob/main/output_yfys.png?raw=true" alt="Output" title="Segmented Mask">
</figure>

<figure>
<figcaption><em>Generated Images</em></figcaption>
  <img src="https://github.com/karansspk462000/Generation-and-Segmentation-of-Skin-Lesion-Disease-Images-ISIC-dataset-for-Medical-Imaging/blob/main/epoch_99_batch_100.png?raw=true" alt="Output" title="Generated Images">
</figure>


## Acknowledgments:

- ISIC 2016 dataset: [International Skin Imaging Collaboration](https://www.isic-archive.com/#!/topWithHeader/wideContentTop/main)
- PyTorch: [PyTorch](https://pytorch.org/)
- OpenCV: [OpenCV](https://opencv.org/)

Feel free to contribute to this project by forking and submitting pull requests. If you encounter any issues or have suggestions for improvement, please open an issue on the repository.
