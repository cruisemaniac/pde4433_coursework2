# Terrain Classification for Robotics Navigation using Machine Learning

## Project Overview
This project implements a Convolutional Neural Network (CNN) for classifying terrain types using machine learning. The model can identify four terrain categories: Forest, Plains, Mountain, and Desert based on the dataset provided in the [`Terrains`](Terrains) folder.

## Prerequisites
- Python 3.11+
- Git
- pip (Python package manager)

## Installation Steps

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/pde4433_coursework2.git
cd pde4433_coursework2
```

### 2. Create a Virtual Environment
```bash
python3 -m venv venv
source venv/bin/activate  # On macOS/Linux
# On Windows, use: venv\Scripts\activate
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

## Dataset Preparation
1. Ensure you have a `Terrains` folder in the project directory
2. The folder should contain subfolders for each terrain type:
   - Forest
   - Plains
   - Mountain
   - Desert
3. Each subfolder should contain image files of that terrain type

The dataset is downloaded from [here](https://www.kaggle.com/code/dogukantabak/terrain-types-classification-resnet50/input).

## Running the Notebook
```bash
jupyter notebook coursework2.ipynb
```

## Model Training and Evaluation
The Jupyter notebook will:
- Load and preprocess images
- Split data into training and testing sets
- Train a CNN model
- Evaluate model performance
- Generate predictions and visualizations

## Key Dependencies
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Scikit-learn
- Seaborn

## Demo Video
The explanation and demonstration of the coursework, dataset, model training, and prediction is uploaded to Youtube [here](https://youtu.be/Ko6-Kw0IRCE).

## Contact
Ashwin Murali Thanalapati

MISIS ID: M01037932

