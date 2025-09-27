# Biomedical Image Segmentation using U-Net 🧬🩺
 ![Python](https://img.shields.io/badge/Python-3.8+-blue.svg?logo=python&logoColor=white) |
 ![TensorFlow](https://img.shields.io/badge/TensorFlow-2.6+-ff6f00.svg?logo=tensorflow&logoColor=white) |
 ![Keras](https://img.shields.io/badge/Keras-2.6+-D00000.svg?logo=keras&logoColor=white) |
 ![NumPy](https://img.shields.io/badge/NumPy-1.x-013243.svg?logo=numpy&logoColor=white) |
 ![Matplotlib](https://img.shields.io/badge/Matplotlib-3.x-013243.svg?logo=plotly&logoColor=white) |
 ![OpenCV](https://img.shields.io/badge/OpenCV-4.x-5C3EE8.svg?logo=opencv&logoColor=white) |


---

This project implements **U-Net**, a convolutional neural network (CNN) architecture, for **semantic segmentation of biomedical images**.  
The model is trained to identify and segment regions of interest (such as **cell structures**) from grayscale biomedical datasets with **pixel-level accuracy**.

---


##  Project Overview
Biomedical image segmentation plays a crucial role in **healthcare and research** by enabling precise identification of cell structures and medical regions of interest.  

In this project, we:  
- Implemented **U-Net**, a popular CNN architecture for segmentation tasks.  
- Trained the model on **biomedical image datasets**.  
- Achieved accurate **pixel-wise segmentation** of cell structures from grayscale images.  
- Visualized **segmentation masks** and model predictions.  

---

##  Features
✔️ U-Net implementation in TensorFlow/Keras  
✔️ Data preprocessing & augmentation with OpenCV  
✔️ End-to-end training and evaluation pipeline  
✔️ Visualization of predicted segmentation masks vs ground truth  
✔️ Runs on Google Colab for easy reproducibility  

---

##  Dataset
- Uses biomedical grayscale images (e.g., cell structure datasets).  
- Images and masks are **preprocessed into fixed input sizes** before training.  
- You can replace the dataset with your own biomedical images for custom segmentation tasks.  

---

##  Model Architecture: U-Net
U-Net is specifically designed for **semantic segmentation** tasks. It consists of

