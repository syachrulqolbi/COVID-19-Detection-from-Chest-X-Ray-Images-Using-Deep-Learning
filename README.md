# COVID-19 Detection from Chest X-Ray Images Using Deep Learning

#### <span style="color: green; font-weight: bold;">Project Status: In Progress</span>

## Project Intro/Objective

The purpose of this project is to develop a system for detecting COVID-19 from chest X-ray images using deep learning techniques. This project utilizes a publicly available dataset and aims to build models capable of classifying images into COVID-19 Positive/Negative and Normal/Pneumonia/COVID categories. The results from this project have potential applications in medical diagnostics and health monitoring systems.

## Methods Used
- Image Classification
- Deep Learning (Convolutional Neural Networks)
- Data Augmentation
- Model Evaluation

## Technologies
- Python
- TensorFlow
- Numpy
- Matplotlib
- Pandas
- Kaggle API
- Patool

## Project Description

This project involves processing chest X-ray images from the **COVID-19 Radiography Database**. The following steps are implemented:

1. **Dataset Preparation**: Fetching and organizing the COVID-19 Radiography Database using the Kaggle API.
2. **Preprocessing**: Performing data augmentation and ensuring data readiness for model training.
3. **Model Training**: Building and training deep learning models to classify images.
4. **Evaluation**: Assessing the model's performance through accuracy and validation accuracy metrics.
5. **Results Visualization**: Presenting the results of model performance.

## Dataset
The dataset used in this project is the **COVID-19 Radiography Database**, which can be accessed at [Kaggle](https://www.kaggle.com/tawsifurrahman/covid19-radiography-database).

## Directory Structure
```
├── model.ipynb        <- Jupyter Notebook containing the code for dataset generation, model training, and evaluation.
├── README.md          <- Project documentation and instructions.
```

## Quick Links
- [COVID-19 Radiography Database](https://www.kaggle.com/tawsifurrahman/covid19-radiography-database)
- [Google Colab Notebook](https://colab.research.google.com/drive/18e1Ou3PJxSbzcnGdvakvvoP0LxQ29b8u?usp=sharing)

## Requirements

The following packages and versions are required to run the project:

### Core Requirements
- Python 3.7.10
- TensorFlow 2.5.0
- Numpy 1.19.5
- Matplotlib 3.2.2

### Additional Requirements for Dataset Preparation
- Kaggle
- Shutil
- Pandas 1.1.5
- Patoolib 1.12

### Setup Instructions
1. Install the required Python packages:
   ```bash
   pip install tensorflow==2.5.0 numpy==1.19.5 matplotlib==3.2.2 pandas==1.1.5 kaggle patool
   ```
2. Follow the instructions in the [model.ipynb](model.ipynb) notebook to prepare the dataset and train the models.

## Results

### Covid Model (Positive/Negative)
| Metric       | Value |
|--------------|-------|
| Accuracy     | -     |
| Val_Accuracy | -     |

### Covid Model (Normal/Pneumonia/COVID)
| Metric       | Value |
|--------------|-------|
| Accuracy     | -     |
| Val_Accuracy | -     |

## Contributing Members

**Team Members**
- Syachrul Qolbi Nur Septi
- Raihan Badrahaadipura
- Julio Fachrel

---
For more details, refer to the code and notebook provided in the repository. Contributions and suggestions are welcome!
