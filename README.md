# Image Denoising Using Autoencoders  

## **Overview**  
This project implements an **Image Denoising Autoencoder** using **Convolutional Neural Networks (CNNs)**. The model removes noise from images by learning to reconstruct the original, clean image from noisy input.  


## **How It Works**  
1. **Dataset**: Uses the **MNIST dataset** (handwritten digits).  
2. **Adding Noise**: Artificial noise is added to simulate real-world noise.  
3. **Autoencoder Model**:
   - Uses **Convolutional Layers** for feature extraction.  
   - **Downsamples (Encoder)** to extract key features.  
   - **Upsamples (Decoder)** to reconstruct the image.  
4. **Training**:
   - The model learns to **map noisy images to clean images**.  
5. **Results**:
   - Displays **Original, Noisy, and Denoised images** side by side.  

