# SDN Defense Framework

This project is a framework for detecting and defending against attacks in Software-Defined Networking (SDN) environments using machine learning. The project involves preprocessing data, training a model, and performing inference to simulate a proof of concept.

## Project Structure

The project consists of several files and directories, each serving a specific purpose:

- `input/`: Directory containing the dataset used for training and testing.
  - `CICIDS2017.csv`: The dataset used for training and testing the model.
- `1_Preprocessing_File.ipynb`: Jupyter notebook for data preprocessing.
- `2_Training_File.ipynb`: Jupyter notebook for training the machine learning model.
- `3_Inference_File.ipynb`: Jupyter notebook for performing inference and simulating the proof of concept.
- `user_input/`: Directory containing input data for inference. Contains 5 DDoS requests, Contains 5 legitimate requests.

## Setup

### Prerequisites

Make sure you have the following installed:

- Python 3.x
- Jupyter Notebook
- Necessary Python libraries (pandas, numpy, scikit-learn, etc.)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/V-Poovarasan-Github/SDN-Defense-Framework.git
   cd SDN-Defense-Framework
