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

## Usage

To run this project, follow these steps:

1. Download the dataset
2. Run the image scraping script:
 ```
 python scrapeImages.py
 ```
This will scrape images from Airbnb based on the dataset.

3. Open and run the `GenAI_Approach.ipynb` Jupyter notebook. Follow the instructions within the notebook to process the images and extract features.

**Important note:** Ensure you use the same file and directory names as specified in the scripts, or modify the paths in the code to match your directory structure.
