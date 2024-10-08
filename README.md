# Photo-Classifier

## Introduction
The objective of this project is to develop an efficient photo classifier system using AI Vision models. The system processes a dataset of images, allowing users to provide textual prompts to retrieve relevant images. 

## Objective
The goal of this prototype was to achieve a balance between accuracy and speed by modifying the original CLIP model, which was applied to a dataset containing  images.

## Methodology
Several modifications were made to enhance the original CLIP model's performance:

1. **Image Fetching Optimization**: Improved the process of retrieving images based on textual prompts to increase efficiency.
2. **Enhanced Embedding Creation**: Adjusted the method for creating and using text embeddings from images to better match user prompts.
3. **Top-5 Image Selection**: Implemented a feature to select the top 5 images that best matched the user's prompt, ensuring both relevance and speed.

These modifications were designed to maintain the core strengths of the CLIP model while addressing its limitations in real-time applications.

## Results
- **Accuracy**: The modified CLIP model demonstrated high accuracy, consistently delivering improved classification results.
- **Speed**: The model's processing time was significantly reduced, with results being generated in seconds or a few minutes, making it highly efficient for real-world use.
- **Outcome**: The modified CLIP model emerged as the most optimal solution among the prototypes tested, offering a balanced combination of speed and accuracy.

## Example Outputs
- **Prompt**: `"Pictures of Animals"`  
  **Result**: Retrieved the most relevant animal images from the dataset.
  
- **Prompt**: `"Yellow flower in the garden"`  
  **Result**: Quickly displayed images of yellow flowers in a garden setting.

- **Prompt**: `"Flowers kept in flower vase"`  
  **Result**: Delivered a set of images featuring flowers arranged in a vase.

- **Prompt**: `"Sunset at the beach"`  
  **Result**: Provided images that accurately depicted a sunset at the beach.

## Conclusion
The modified CLIP model successfully met the project's objectives by providing a fast and accurate photo classification system. Its ability to process large datasets and retrieve relevant images based on textual prompts in near real-time makes it a viable solution for practical applications.
