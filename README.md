
---

# ECG Classification Using Deep Learning Models

## Overview

This repository contains the implementation of a deep learning project aimed at classifying ECG signals into four categories: **Abnormal Heartbeat**, **History of Myocardial Infarction (MI)**, **MI Patients**, and **Normal Cases**. We utilize multiple models, including **MobileNetV2**, a **Custom Convolutional Neural Network (CNN)**, and **VGG16**, and also implement a **fused model** to enhance classification accuracy.

## Contents

- **Source Code:**
  - `Preprocessing.ipynb`: Steps for preprocessing the ECG images, including resizing, normalization, and augmentation.
  - `CNN & MobileNet.ipynb`: Implementation of the custom CNN and MobileNetV2 models for ECG classification.
  - `VGG.ipynb`: Implementation of the VGG16 model for ECG classification.
  - `Fused Model.ipynb`: Code for creating and training the fused model combining the outputs of CNN, MobileNetV2, and VGG16.
  - `Saliency_map.ipynb`: Generating saliency maps to visualize which parts of the ECG images contribute most to the model's predictions.


## Getting Started

To run the code in this repository, follow these steps:

1. **Clone the Repository:**  
   Clone the repository to your local machine:
   ```bash
   git clone https://github.com/yourusername/yourrepository.git
   ```

2. **Navigate to the Directory:**  
   Change into the repository directory:
   ```bash
   cd yourrepository
   ```

3. **Install Required Libraries:**  
   Install the required libraries. You can use the following command:
   ```bash
   pip install -r requirements.txt
   ```

4. **Download ECG Images:**  
   Download the ECG images from the following Google Drive link:  
   [ECG Image Dataset](https://drive.google.com/drive/folders/1EpqWLLR2a-R-iZg1qlGfe5SzV2fAjC1R?usp=drive_link)

5. **Preprocess the ECG Images:**  
   Run the `Preprocessing.ipynb` notebook to preprocess the downloaded ECG images. The preprocessing step will generate preprocessed images, which you can also download from:  
   [Preprocessed Images](https://drive.google.com/drive/folders/1odqh54B3BjiF0ZncOmSPaw5ErQyjXnh1?usp=drive_link)

6. **Train Individual Models:**  
   Use the preprocessed images obtained in the previous step to train the individual models. Run the following notebooks:
   - **CNN & MobileNet Training:** Execute `CNN & MobileNet.ipynb` to train both CNN and MobileNetV2 models.
   - **VGG Training:** Execute `VGG.ipynb` to train the VGG16 model.

7. **Create the Fused Model:**  
   Once the individual models are trained, run the `Fused Model.ipynb` notebook to create the fused model that combines the outputs of CNN, MobileNetV2, and VGG16.

8. **Generate Saliency Maps:**  
   Finally, run the `Saliency_map.ipynb` notebook to generate saliency maps that visualize the important features used by the models during classification.


## Data Access

Due to file size limitations on GitHub, the ECG dataset, preprocessed images, and model weights are hosted on Google Drive. You can access them using the following links:

- **ECG Image Dataset:** [Access Here](https://drive.google.com/drive/folders/1EpqWLLR2a-R-iZg1qlGfe5SzV2fAjC1R?usp=drive_link)
- **Preprocessed Images:** [Access Here](https://drive.google.com/drive/folders/1odqh54B3BjiF0ZncOmSPaw5ErQyjXnh1?usp=drive_link)
- **Model Weights:**
  - **CNN Model:** [Download Here](https://drive.google.com/file/d/1BWe5mrjOYL3T-nDvKPBQam-jYvpFOgyI/view?usp=drive_link)
  - **VGG16 Model:** [Download Here](https://drive.google.com/file/d/1NVVONRuhT-AjP2aSEpNxGTNXo2kyfMU3/view?usp=drive_link)
  - **MobileNetV2 Model:** [Download Here](https://drive.google.com/file/d/1m4mSlghEaA9AyTviiRHRmlZW4Zk2Iy5k/view?usp=drive_link)
  - **Fused Model:** [Download Here](https://drive.google.com/file/d/1fc3oaXM-Lfcy0N54t2FudGFz6uDIyF1z/view?usp=drive_link)


## Acknowledgments

This project was supported by the SERB grant (File No. SUR/2022/004714) under the SERB SURE project and the NGNLab, Anna University, Chennai, India. We express our gratitude for their assistance and resources that have contributed to the success of this work. Additionally, we would like to thank all the contributors and resources that have shaped this project
## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
