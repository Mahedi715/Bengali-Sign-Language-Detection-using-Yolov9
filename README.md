This project demonstrates how to train the **YOLOv9** object detection model on a custom dataset using a Kaggle notebook. In this project, I have used the latest Yolov9 model to predict Bangla Sign Language from images. I have trained the Yolov9 model with around 9000 images of different Bengali Sign language and classified them into 49 distinct classes. Below is a summary of the key steps involved. 

## 🛠️ YOLOv9 Model with Custom Dataset Training

This project demonstrates how to train the **YOLOv9** object detection model on a custom dataset using a Kaggle notebook. Here's a brief overview of the main steps:

1. **📂 Cloning the YOLOv9 Repo**:
   - The official YOLOv9 repository is cloned from GitHub, bringing in all the necessary files to set up the model.

2. **📥 Downloading the Custom Dataset**:
   - Using **gdown**, a large dataset ZIP file is downloaded from Google Drive directly to the Kaggle environment.

3. **🗂️ Unzipping the Dataset**:
   - The dataset is extracted into the YOLOv9 directory for training, and the ZIP file is removed to save space.

4. **⚙️ Downloading the Dataset Configuration**:
   - A custom `.yaml` file is downloaded, containing dataset paths and configuration parameters for training.

5. **📦 Installing Dependencies**:
   - Required libraries like **ultralytics** and other dependencies are installed to set up the environment.

6. **🚀 Training the Model**:
   - The YOLOv9 model is trained and evaluated on the custom dataset, ready for use in object detection tasks.
