# Cat or Not - Image Classification

## Overview
This project classifies images based on whether they contain a cat or not. The classification is performed using categorical features like ear shape, face shape, and whiskers. The model utilizes decision trees and information gain to determine the best classification splits.

## Features
- Uses one-hot encoding for categorical features (Ear Shape, Face Shape, Whiskers)
- Implements decision trees with information gain for classification

## Installation
To run this project locally, follow these steps:

1. Clone the repository:
   ```sh
   git clone https://github.com/Bin-Thabit/cat-or-not.git
   cd cat-or-not
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook:
   ```sh
   jupyter notebook
   ```

## Usage
- Open the `cat or not.ipynb` notebook
- Follow the step-by-step instructions to preprocess data, train the decision tree, and evaluate model performance
- Modify hyperparameters to experiment with classification accuracy

## Dataset
The dataset includes labeled images with categorical attributes:
- **Ear Shape**: Pointy (1) or Floppy (0)
- **Face Shape**: Round (1) or Not Round (0)
- **Whiskers**: Present (1) or Absent (0)

## Model Architecture
The classification model follows a decision tree structure:
- Computes information gain for each feature
- Splits nodes based on the highest information gain
- Continues until stopping criteria are met

## Results
The decision tree model effectively classifies images based on given features, demonstrating high accuracy on the dataset.

## Future Enhancements
- Incorporate additional features for improved classification
- Implement deep learning models for image-based classification
- Optimize decision tree parameters for better performance

## Contributing
Contributions are welcome! Feel free to open issues or submit pull requests to enhance the project.
