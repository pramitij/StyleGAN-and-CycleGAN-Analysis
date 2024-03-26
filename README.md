# Exploring Generative Models: StyleGAN and CycleGAN Analysis
>This project started from my interest in deep learning and wanting to know more about the technical details of generative adversarial networks (GANs). The goal was to investigate StyleGAN and CycleGAN, two advanced GAN models. I aimed to understand and demonstrate their unique capabilities in generating and transforming images.

## Key Highlights

- **StyleGAN Exploration:** I implemented StyleGAN to understand its progressive training approach, adaptive instance normalization (AdaIN), noise injection, and equalized learning rates. This exploration was useful in generating high-quality images with controlled style variations, showcasing the model's prowess in creating detailed and varied outputs.

- **CycleGAN Transformation:** With CycleGAN, I focused on image-to-image translation without paired examples. By experimenting with CycleGAN, I successfully transformed images across domains (e.g., horses to zebras), which was visualized after 25 epochs. These transformations provided a clear demonstration of CycleGAN's effectiveness in capturing and translating the essence of one domain to another.

- **Comparative Analysis:** This comparative study highlighted the distinct advantages and use cases of each model, from generating photorealistic faces with StyleGAN to performing astonishing domain transfers with CycleGAN.

## Project Structure

- `stylegan-pre-trained-model.ipynb`: Contains the implementation and experimentation with StyleGAN, including model training and image generation processes.

- `cycle-gan.ipynb`: Details the CycleGAN implementation for image-to-image translation, with a focus on the architecture and transformation results.

- `Presentation.pptx`: A comprehensive presentation of my analysis, results, and insights from working with StyleGAN and CycleGAN.
