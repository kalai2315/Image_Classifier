# Image_Classifier

**Model:**  https://drive.google.com/file/d/1qvcSnESFsPEcx19ZUqpD8BViJBczL3Yg/view?usp=sharing

**Objectives:**

**Utilize VGG16 for Feature Extraction:**

● Employ the VGG16 model, excluding its top layers, to serve as a feature
extractor for cat and dog images.

● Ensure the input images are of the correct size (150x150) and preprocessed
appropriately to match VGG16’s requirements.

**Data Preprocessing and Augmentation:**

Implement image data generators for real-time data augmentation, ensuring a
robust and varied dataset for training the classification layers.

**Build and Train the Classification Model:**

● Add custom fully connected layers on top of the VGG16 model for the
classification task.

● Freeze the convolutional layers of VGG16 to retain the pre-trained features
and only train the added classification layers.

**Model Compilation and Training:**

● Compile the model using stochastic gradient descent, categorical
cross-entropy as the loss function, and accuracy as the evaluation metric.

● Train the model using the training data, and validate its performance using
a validation set.

**Evaluate and Test the Model:**

Assess the model’s performance based on its accuracy in classifying
images into cat or dog categories.

Implement a prediction function to classify new images, providing the
predicted category and the associated confidence level.


![image](https://github.com/user-attachments/assets/0bbf2e07-d831-4345-bc27-3189c53fb2fc)



![Screenshot 2024-11-26 175538](https://github.com/user-attachments/assets/f49f4596-dd5f-4e7f-992a-1bc7735e8826)


![Screenshot 2024-11-26 175553](https://github.com/user-attachments/assets/4878d33a-6bfb-4d57-8a1f-5dcf602a797b)



![Screenshot 2024-11-26 175606](https://github.com/user-attachments/assets/3db3da94-6200-4415-a443-039292e3d6a5)
