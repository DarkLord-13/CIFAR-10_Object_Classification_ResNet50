# CIFAR-10 Object Recognition with Deep Learning

This project aims to classify images from the CIFAR-10 dataset using deep learning techniques. The CIFAR-10 dataset consists of 60,000 32x32 color images in 10 different classes. The classes include airplanes, cars, birds, cats, deer, dogs, frogs, horses, ships, and trucks.

## Project Overview

The project follows these main steps:
1. **Data Preparation**:
    - Install necessary packages.
    - Download the CIFAR-10 dataset from Kaggle.
    - Extract and preprocess the dataset.
2. **Labels Processing**:
    - Load and process the labels for the dataset.
    - Encode the labels into numerical values.
3. **Image Processing**:
    - Convert the images to numpy arrays for training.
4. **Train-Test Split**:
    - Split the dataset into training and testing sets.
5. **Data Scaling**:
    - Scale the image data to values between 0 and 1.
6. **Building the Neural Network**:
    - Use TensorFlow and Keras to build and train the neural network model.

## Dependencies

The project requires the following dependencies:
- Python 3.x
- Jupyter Notebook
- Kaggle API
- TensorFlow
- OpenCV
- NumPy
- Pandas
- Matplotlib
- py7zr (for extracting .7z files)

## Installation

1. Clone this repository:
    ```sh
    git clone https://github.com/DarkLord-13/Machine-Learning-01.git
    ```

2. Navigate to the project directory:
    ```sh
    cd Machine-Learning-01
    ```

3. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

4. Download the CIFAR-10 dataset from Kaggle:
    - Place your `kaggle.json` file in the project directory.
    - Run the following commands to set up the Kaggle API:
    ```sh
    mkdir -p ~/.kaggle
    cp kaggle.json ~/.kaggle/
    chmod 600 ~/.kaggle/kaggle.json
    kaggle competitions download -c cifar-10
    ```

5. Extract the dataset:
    ```sh
    unzip cifar-10.zip
    ```

## Usage

Open the Jupyter Notebook `CIFAR-10 ObjectRecognitionDL.ipynb` and run the cells to execute the project steps.

```sh
jupyter notebook CIFAR-10\ ObjectRecognitionDL.ipynb
