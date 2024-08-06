# Transfer Learning and Fine-Tuning for Car Classification 🚗

This project demonstrates the application of transfer learning and fine-tuning techniques to classify images of cars. The notebook walks through data preprocessing, model creation, and fine-tuning using pre-trained networks. The Cars dataset contains various types of cars. The dataset is organized into 2 folders (train, test) and contains subfolders for each car category. There are 4,165 images (JPG) and 7
classes of cars(Audi, Hyundai Creta, Mahindra Scorpio, Rolls Royce, Swift, Tata Safari, Toyota Innova). 
This dataset was taken from Kaggle(https://www.kaggle.com/datasets/kshitij192/cars-image-dataset)
## Dataset Overview

The dataset used in this project consists of images of various car models. The goal is to build a model that can accurately classify these car images.

## Project Steps

1. **DataFrame Creation:** Load and structure the dataset into a usable format.
2. **Data Preprocessing:** Prepare the data by resizing images, normalizing pixel values, and splitting into training and validation sets.
3. **Model Creation (Without Fine-Tuning):** Build a base model using a pre-trained network without additional fine-tuning.
4. **Fine-Tuning:** Enhance the model's performance by fine-tuning the pre-trained network with the car images.
5. **Model Evaluation:** Assess the performance of the fine-tuned model and compare it to the base model.

## Key Components

- **Transfer Learning:** Leveraging pre-trained models such as VGG16, ResNet50, or InceptionV3 to jumpstart the learning process.
- **Fine-Tuning:** Adjusting the weights of the pre-trained network to better fit the car classification task.
- **Evaluation:** Using metrics like accuracy, precision, recall, and F1-score to evaluate the model's performance.


