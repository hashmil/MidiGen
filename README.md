# MidiGen

## Overview

MidiGen is a series of three Jupyter notebooks designed to process, train, and generate music using MIDI files. This project employs neural networks to learn from a dataset of MIDI files and subsequently generates new, unique musical pieces. It's an exciting blend of technology and creativity, ideal for those interested in the intersection of machine learning and music.

## Notebooks

### 1. Processing

[Processing Notebook](https://github.com/hashmil/MidiGen/blob/main/MidiGen_PrePorcess.ipynb) - This notebook handles the initial setup and processing of MIDI files. It reads MIDI files, extracts note and chord information, and saves this data for subsequent use in training the model. 

**Note**: The notebook assumes that MIDI files are stored on Google Drive. Paths to the MIDI files and output directories in the code should be updated according to your Google Drive structure.

### 2. Training the Model

[Training Model Notebook](#) - In this notebook, a neural network model is created and trained on the processed data. The model learns to predict musical patterns based on the input MIDI files.

**Note**: This notebook uses Google Drive for storing intermediate data and the trained model. Be sure to check and update the file paths as necessary.

### 3. Generating Music

[Generating Music Notebook](#) - The final notebook uses the trained model to generate new music. It outputs a MIDI file that represents a new piece of music based on the training.

**Note**: This notebook interacts with Google Drive for loading the trained model and saving the generated music. Ensure that the file paths are correct for your setup.

## Usage

To use these notebooks, clone the repository, and open the notebooks in a Jupyter environment that has access to Google Drive (Google Colab is recommended). Make sure to update the file paths to point to your Google Drive where the MIDI files are stored and where you want the output files (processed data, model, generated music) to be saved.

## Dependencies

Ensure you have installed all necessary libraries including `music21`, `keras`, `tensorflow`, and others as needed by the notebooks.
