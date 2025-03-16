# Dental Image Segmentation and Classification

This project implements an advanced dental image analysis system that combines the power of SAM (Segment Anything Model) for tooth segmentation with a custom classification model for dental condition assessment.

## Project Overview

The project addresses the challenge of automated dental image analysis through two main components:

1. **Tooth Segmentation**: Utilizes the SAM (Segment Anything Model) to accurately isolate individual teeth from radiological images
2. **Tooth Classification**: Implements a classification system that categorizes each segmented tooth into one of 5 predefined classes

## Features

- Automated tooth segmentation using state-of-the-art SAM model
- Multi-class tooth classification
- Support for radiological dental images
- Integration with CSV-based ground truth data
- Comprehensive evaluation metrics

## Requirements

- Python 3.x
- PyTorch
- Segment Anything Model (SAM)
- Other dependencies as specified in requirements.txt

## Dataset

The project works with a dataset of dental radiological images, where:
- Input: Radiological images of teeth
- Ground Truth: CSV file containing classification labels for each tooth
- Classes: 5 distinct categories for tooth classification

## Usage

1. **Data Preparation**:
   - Place your dental radiological images in the designated directory
   - Ensure your CSV file with ground truth labels is properly formatted

2. **Segmentation**:
   - The SAM model will process each image to identify and segment individual teeth
   - Segmented results are saved for further processing

3. **Classification**:
   - Each segmented tooth is processed through the classification model
   - Results are compared against the ground truth data

## License

This project is licensed under the GNU General Public License v3.0 - see the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## Acknowledgments

- SAM (Segment Anything Model) team for their groundbreaking work
- Contributors to the dental image dataset
- Research community in dental image analysis
