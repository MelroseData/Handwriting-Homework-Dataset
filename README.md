# Pupil Handwriting & Homework Dataset

## Overview
This dataset consists of handwritten Chinese, Mathematics, and English homework collected from pupils. The dataset is structured to allow alignment across different subjects for each student, enabling tasks like OCR processing, memory learning, and transformer-based models.

## Dataset Structure
We provide three different versions of the dataset, each designed for different research and machine learning applications:

### Hard Start (Binary Processed & Normalized)
- Pre-processed for OCR applications
- Binarized, resized, and normalized for model compatibility
- Optimized for qualitative OCR tasks

### Smooth Procedure (Grayscale, Minimal Processing)
- Maintains original handwriting characteristics
- Grayscale images without binarization
- Suitable for models that require raw stroke details

### Raw Intel (Unprocessed Data)
- Provides original, untouched scans
- Ideal for custom preprocessing and analysis

## Key Features
- **Student-Aligned Data**: Each student has a consistent index across all subjects, allowing for long-term and short-term memory modeling.
- **Memory Learning Applications**: The dataset structure enables models to analyze a student’s progression over time.
- **Transformer Compatibility**: Designed with transformer-based models in mind for handwriting recognition, sequence learning, and pattern analysis.

## Usage & Access
The dataset is available for free download on GitHub, Kaggle, and Hugging Face. Researchers and developers can utilize it for OCR, handwriting recognition, and educational AI applications.
The offical website is http://handwriting-ocr.org/


