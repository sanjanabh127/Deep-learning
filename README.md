**Biomedical Image Segmentation using U-Net 🧬🩺**

A deep learning project that implements U-Net, a convolutional neural network architecture, for semantic segmentation of biomedical images. The model is trained to identify and segment regions of interest (such as cell structures) from grayscale biomedical datasets with pixel-level accuracy.

**Tech Stack**

Python

TensorFlow / Keras

NumPy

Matplotlib

OpenCV

Google Colab

 **Project Overview**

Biomedical image segmentation plays a crucial role in healthcare and research by enabling precise identification of cell structures and medical regions of interest.

In this project, we:

Implemented U-Net, a widely used CNN architecture for segmentation tasks.

Trained the model on biomedical image datasets.

Achieved accurate pixel-wise segmentation of cell structures from grayscale images.

Visualized segmentation masks and model predictions.

 **Features**

✔️ U-Net implementation in TensorFlow/Keras
✔️ Data preprocessing & augmentation with OpenCV
✔️ End-to-end training and evaluation pipeline
✔️ Visualization of predicted segmentation masks vs ground truth
✔️ Runs on Google Colab for easy reproducibility

 **Dataset**

The project uses biomedical grayscale images (e.g., cell structure datasets).

Images and masks are preprocessed into fixed input sizes before training.

You can replace the dataset with your own biomedical images for custom segmentation tasks.

**🧩 Model Architecture: U-Net**

U-Net is designed for semantic segmentation with:

Encoder (Contracting Path): Captures context with convolution & pooling.

Decoder (Expanding Path): Enables precise localization with upsampling & skip connections.
