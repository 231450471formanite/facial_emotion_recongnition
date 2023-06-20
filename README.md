# Facial Emotion Recognition

## Dataset

The dataset used for this project was sourced from Kaggle's "Challenges in Representation Learning: Facial Expression Recognition Challenge" (FER2013). The dataset consists of 48x48-pixel grayscale images of faces labeled with seven emotion categories.

The dataset can be accessed from the following link: [FER2013 Dataset](https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge/data)

Please make sure to comply with the dataset's licensing terms and usage restrictions specified by Kaggle.

## Project Structure

|-- data/
| |-- FER2013.csv
|-- models/
| |-- emotion_recognition_model.h5
|-- src/
| |-- main.py
|-- README.md


- `data/`: Directory containing the dataset file `FER2013.csv`.
- `models/`: Directory to store the trained model weights.
- `src/`: Directory containing the source code for the Facial Emotion Recognition system.
- `README.md`: This file, providing an overview of the project.

## Usage

1. Download the FER2013 dataset from the provided Kaggle link and place the `FER2013.csv` file in the `data/` directory.
2. Set up the required dependencies by installing the necessary libraries mentioned in the `requirements.txt` file.
3. Run the `main.py` script to preprocess the data, train the model, and evaluate its performance.
4. The trained model weights will be saved in the `models/` directory.
5. Once the model is trained, you can use it for facial emotion recognition tasks by loading the model weights and making predictions on new images.

## Dependencies

The project requires the following dependencies:

- Python 3.7+
- TensorFlow
- OpenCV
- Pandas
- Numpy

Please refer to the `requirements.txt` file for the specific versions of the libraries used in this project.

## Acknowledgments

- Kaggle for providing the FER2013 dataset.
- Open-source libraries and frameworks used in the development of this project.
