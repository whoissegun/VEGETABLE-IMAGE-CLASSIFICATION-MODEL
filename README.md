# VEGETABLE-IMAGE-CLASSIFICATION-MODEL


This repository contains a vegetable image detection model developed using PyTorch and NumPy. The model utilizes the ResNet-50 architecture and has been fine-tuned for accurate classification of vegetable images. With rigorous training, testing, and validation on a dataset comprising 21,000 images, the model achieves an impressive accuracy of 88%.

The model's weights can be found at: https://drive.google.com/file/d/1BkNI9drVsvjKJunQQGYqICoA3tmsHr6g/view?usp=sharing
I couldn't upload them here because of file size restrinctions

Dataset
The dataset used for training and evaluation consists of 21,000 images of various vegetables. These images are categorized into 15 different crop classes, including bean, bitter gourd, bottle gourd, brinjal, broccoli, cabbage, capsicum, carrot, cauliflower, cucumber, papaya, potato, pumpkin, radish and tomato. The dataset provides a comprehensive representation of the diverse vegetable species.
The dataset can be found at: https://www.kaggle.com/datasets/misrakahmed/vegetable-image-dataset

Model Architecture
The model architecture is based on ResNet-50, a widely-used deep learning architecture known for its excellent performance in image classification tasks. By fine-tuning the pre-trained ResNet-50 model, we adapt it to the specific task of vegetable image detection. This allows the model to learn intricate features and patterns specific to vegetable categories, resulting in enhanced classification accuracy.

Training and Validation
The model undergoes a rigorous training process to optimize its parameters using the training dataset. During training, we employ cross-entropy loss as the objective function and utilize the Adam optimizer for efficient parameter updates. The model's performance is regularly evaluated using a validation dataset to monitor its progress and prevent overfitting.

Testing
Once training and validation are complete, the model is tested on a separate test dataset to assess its generalization and real-world performance. The accuracy achieved on the test dataset serves as an unbiased measure of the model's ability to correctly classify vegetable images.

Usage
To use the vegetable image detection model, follow these steps:

Ensure that you have the required dependencies installed, including PyTorch and NumPy.
Prepare your vegetable image dataset in the desired format, following the folder structure specified in the documentation.
Initialize the model using the provided script and load the pre-trained weights.
Provide the path to your test images and run the model for classification.
Evaluate the model's predictions and analyze the results.
Feel free to experiment with different images or extend the model for other vegetable-related tasks based on your requirements.

Conclusion
The vegetable image detection model presented here demonstrates the successful application of deep learning techniques for accurate classification of vegetable images. With an accuracy of 88% on a diverse dataset, the model proves its potential for automated vegetable recognition in various domains, including agriculture, food industry, and research. We hope this repository serves as a valuable resource for those interested in vegetable image classification using deep learning.





