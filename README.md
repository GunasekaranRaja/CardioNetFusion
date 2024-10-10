
# ECG Classification Using Deep Learning Models

## Overview

This repository contains the implementation of a deep learning project aimed at classifying ECG signals into four categories: **Abnormal Heartbeat**, **History of Myocardial Infarction (MI)**, **MI Patients**, and **Normal Cases**. We utilize multiple models, including **MobileNetV2**, a **Custom Convolutional Neural Network (CNN)**, and **VGG16**, and also implement a **fused model** to enhance classification accuracy. 

## Contents

- **Source Code:**
  - `CNN & MobileNet.ipynb`: Implementation of the custom CNN and MobileNetV2 models for ECG classification.
  - `Fused Model.ipynb`: Code for creating and training the fused model combining the outputs of CNN, MobileNetV2, and VGG16.
  - `Preprocessing.ipynb`: Steps for preprocessing the ECG images, including resizing, normalization, and augmentation.
  - `Saliency_map.ipynb`: Generating saliency maps to visualize which parts of the ECG images contribute most to the model's predictions.
  - `VGG.ipynb`: Implementation of the VGG16 model for ECG classification.

## Data Access

Due to file size limitations on GitHub, the ECG dataset, preprocessed images, and model weights are hosted on Google Drive. You can access them using the following links:

- **ECG Image Dataset:** [Access Here](https://drive.google.com/drive/folders/1EpqWLLR2a-R-iZg1qlGfe5SzV2fAjC1R?usp=drive_link)
- **Preprocessed Images:** [Access Here](https://drive.google.com/drive/folders/1odqh54B3BjiF0ZncOmSPaw5ErQyjXnh1?usp=drive_link)
- **Model Weights:**
  - **CNN Model:** [Download Here](https://drive.google.com/file/d/1BWe5mrjOYL3T-nDvKPBQam-jYvpFOgyI/view?usp=drive_link)
  - **VGG16 Model:** [Download Here](https://drive.google.com/file/d/1NVVONRuhT-AjP2aSEpNxGTNXo2kyfMU3/view?usp=drive_link)
  - **MobileNetV2 Model:** [Download Here](https://drive.google.com/file/d/1m4mSlghEaA9AyTviiRHRmlZW4Zk2Iy5k/view?usp=drive_link)
  - **Fused Model:** [Download Here](https://drive.google.com/file/d/1fc3oaXM-Lfcy0N54t2FudGFz6uDIyF1z/view?usp=drive_link)

## Getting Started

To run the code in this repository, follow these steps:

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/yourusername/yourrepository.git
   ```

2. Navigate to the directory:
   ```bash
   cd yourrepository
   ```

3. Install the required libraries. You can use the following command:
   ```bash
   pip install -r requirements.txt
   ```

4. Download the datasets and models using the provided Google Drive links and place them in the appropriate directories as needed.

5. **Load Preprocessed Images:**
   Open the `Preprocessing.ipynb` notebook to load and prepare the preprocessed images for training.

6. **Run Model Training:**
   - Execute the `VGG.ipynb` notebook to train the VGG16 model and save the weights.
   - Next, run the `CNN & MobileNet.ipynb` notebook to train both the CNN and MobileNetV2 models, saving their respective weights.

7. **Fused Model Implementation:**
   After obtaining the individual models, open and run the `Fused Model.ipynb` notebook to create and train the fused model, which combines the outputs of the CNN, MobileNetV2, and VGG16.

8. **Saliency Map Generation:**
   Finally, run the `Saliency_map.ipynb` notebook to generate saliency maps that visualize the areas of the ECG images contributing most to the model's predictions.

## Acknowledgments

This project was inspired by various research works in the field of ECG signal processing and deep learning. Special thanks to the contributors and resources that have shaped this project.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
