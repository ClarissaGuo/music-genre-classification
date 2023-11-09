# Music Genre Classification

## Project Description
This project aims to classify music tracks into various genres using a deep learning model. The model processes audio files, extracts relevant features, and uses a Convolutional Neural Network (CNN) to predict the genre.

## How to Run
To run this project, follow these steps:

1. Clone the repository to your local machine.
2. Navigate to the project directory.
3. Install the required dependencies using the command: `pip install -r requirements.txt`.
4. Execute the main script (for example, `python music_genre_classification.py`).

## Dependencies
This project requires the following libraries:

- librosa
- numpy
- matplotlib
- seaborn
- sklearn
- keras

You can install all dependencies at once using the `requirements.txt` file.

## Usage
To use this project, you will need to provide an audio file in WAV format. The script will process the file, extract features, and output the predicted genre.

## Data
The dataset used in this project consists of audio tracks from different music genres. Each track is processed to extract Mel Spectrogram, MFCC, and Chroma features.

## Model
The CNN model used for classification includes convolutional layers, max pooling, dropout for regularization, and dense layers for output.

## Training
The model is trained using a split of training, validation, and test sets. The training process includes callbacks for early stopping and model checkpointing.

## Evaluation
The model's performance is evaluated using accuracy, loss metrics, and a confusion matrix to understand its classification behavior.

## Author
Clarissa GUO
