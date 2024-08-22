# Image-Feature-Extraction-Using-GenAI

This project implements an advanced generative AI pipeline for extracting and rating features from images. It combines the power of Florence-2, a state-of-the-art vision-language model, with a fine-tuned version of Mistral-v3, a cutting-edge large language model.


## Key Features

- Utilizes Florence-2 to generate detailed image descriptions
- Employs a custom fine-tuned Mistral-v3 model for feature extraction and scoring
- Outputs results in JSON format for easy integration with other applications

### Image Description Generation
- Model: Florence-2
- Input: Raw image data
- Output: Comprehensive text description of the image

### Feature Extraction and Rating
- Model: Fine-tuned Mistral-v3
- Input: Text description from Florence-2
- Output: JSON object containing extracted features and their scores
