# Cricket Player Image Processing & Amazon Review Analysis with MongoDB

## Overview
This project focuses on two main data processing tasks:
1. **Cricket Player Image Processing**: Prepares a structured database of cricket player images and annotations to assist in IPL auction decision-making.
2. **Amazon Review Analysis**: Processes customer reviews using NLP techniques to extract insights about consumer sentiment and behavior.

All processed data is stored in MongoDB for efficient retrieval and management.

## Features
### **Cricket Player Image Processing**
- Image renaming, resizing, and denoising
- Feature extraction (color, texture, and shape features)
- Image annotation and metadata creation
- Storing processed images and extracted data in MongoDB

### **Amazon Review Analysis**
- Text normalization, tokenization, and vectorization
- Sentiment analysis using TextBlob
- Storing processed text files and metadata in MongoDB

## Technologies Used
- **Python**: Data processing and feature extraction
- **OpenCV & skimage**: Image processing
- **Pandas & NumPy**: Data handling
- **NLTK & TextBlob**: NLP tasks
- **MongoDB**: Database for structured storage
- **Google Colab**: Execution environment

## Data Sources
- **Cricket player images**: Getty Images
- **Amazon product reviews**: Kaggle dataset


## Results & Insights
- Structured IPL player database with images & metadata
- Customer sentiment analysis from Amazon reviews
