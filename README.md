
# DogVision: Dog Breed Identification with Deep Learning

## Overview

DogVision is a deep learning project designed to identify dog breeds from images. The project utilizes TensorFlow and TensorFlow Hub to develop and train the model, and includes comprehensive data visualization to understand the dataset distribution.

## Features

- Data extraction and preparation from a ZIP file and CSV labels.
- Data visualization using matplotlib and seaborn.
- Deep learning model development with TensorFlow and TensorFlow Hub.
- GPU support for accelerated training.

## Project Structure

```
DogVision/
├── DogVision.ipynb  # Jupyter notebook with the entire project code
├── dog-breed-identification.zip  # Dataset (From Kaggle.com)
└── labels.csv  # CSV file with image labels (From kaggle.com)
```

## Installation

1. Clone the repository and navigate to the project directory:

   ```sh
   git clone <repository_url>
   cd DogVision
   ```

2. Install the required dependencies:

   ```sh
   pip install -r requirements.txt
   ```

3. Ensure you have the dataset files in the correct location (as specified in the notebook).

## Usage

1. Open the Jupyter notebook:

   ```sh
   jupyter notebook DogVision.ipynb
   ```

2. Run the cells in the notebook to execute the project code. The notebook includes steps for data extraction, visualization, and model training.

## Data Visualization

The notebook provides several visualizations to help understand the dataset distribution, including:

- Bar charts for the number of images per breed.
- Histograms for detailed data distribution.

## Model Development

The model is built using TensorFlow and TensorFlow Hub, leveraging pre-trained models for transfer learning. The notebook includes steps to:

- Load and preprocess the data.
- Build and compile the model.
- Train the model with GPU support (if available).

## Contributing

Contributions are welcome! Please feel free to open an issue or submit a pull request.

