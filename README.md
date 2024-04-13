# Satellite_image_segmentation_using_DL
This project focuses on segmenting satellite images to classify different land features such as water, vegetation, buildings, and more using deep learning. By leveraging a multi-UNet architecture and custom loss functions, the model achieves precise segmentation for a variety of real-world applications.
<br>
# Overview
Satellite image segmentation is essential for applications like urban planning, environmental monitoring, and agriculture management. This project uses a deep learning approach to segment satellite images and classify them into different land features.
<br>
# Dataset
The project utilizes a dataset of satellite images and corresponding masks identifying different land classes. Images are preprocessed by patching them into smaller sections and normalizing pixel values.
You can download the dataset here [https://www.kaggle.com/datasets/humansintheloop/semantic-segmentation-of-aerial-imagery] 
<br>
# Model Architecture
The model is based on a multi-UNet architecture known for its efficiency in handling complex image segmentation tasks. Custom loss functions such as Dice Loss and Categorical Focal Loss are used to enhance model performance.
<br>
# Training and Evaluation
The model is trained using a mix of training and validation data. Key performance metrics such as accuracy and Intersection over Union (IoU) are monitored during the training process to ensure optimal performance.
