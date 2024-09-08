# Image Inpainting with GAN

This project uses a Generative Adversarial Network (GAN) to perform image inpainting, effectively restoring missing or damaged regions of images. The project was developed and trained on Kaggle Notebook using landscape images, and it leverages advanced deep learning techniques to achieve high-quality restoration.

## Project Overview

Image inpainting is a critical technique in digital image processing for restoring images by filling in missing or damaged parts. In this project, we implemented a GAN with a U-Net generator model for reconstructing the missing portions of the images. 

**Main Features:**
- **Image Masking**: Generate masks to identify the damaged regions.
- **GAN Training**: Train the generator and discriminator to reconstruct the image.
- **Image Restoration**: Achieve realistic restorations by filling the masked regions.

## Dataset

The dataset used for training is available on Kaggle. You can access it via the link below:
[Landscape Image Colorization Dataset](https://www.kaggle.com/datasets/theblackmamba31/landscape-image-colorization)

## Project Structure

- **Data Preprocessing**: Load and preprocess images.
- **GAN Model**: Define U-Net based generator and PatchGAN discriminator.
- **Training**: Train the model over multiple epochs.
- **Evaluation**: Generate and evaluate inpainted images.

## Example Images

Here are some examples of images restored by the model:

### 1. Mask Generation Examples

<img src="https://github.com/user-attachments/assets/b4c4e94e-1ae5-4edd-b6f9-3e568a38037e" alt="Mask Generation" width="600"/>
<img src="https://github.com/user-attachments/assets/a5f41360-d21e-4ab9-9472-7b5cb7aa33d5" alt="Mask Generation" width="600"/>


### 2. Final Predictions

<img src="https://github.com/user-attachments/assets/a04aa786-8361-471c-ae17-5edd06c93700" alt="Mask Generation" width="800"/>
<img src="https://github.com/user-attachments/assets/8957abb0-27d7-4670-b492-d3189bdf019d" alt="Mask Generation" width="800"/>









## How to Run

1. Clone the repository.
2. Download the dataset from Kaggle and add it to the project directory.
3. Run the notebook on Kaggle to train the model and generate results.

## Credits

This project was developed by a team of 4 -Devansh, Yash, Chakshu, and Dishant as part of a course-work Project. Used Kaggle for the computing resources and dataset.
