🐾 Cats and Dogs Dataset Exploration

This project focuses on **analyzing and visualizing a dataset of cats and dogs** used for image classification tasks.  
The dataset is divided into **training** and **validation** sets, each containing labeled images of cats (`category = 0`) and dogs (`category = 1`).  

The goal of this stage is to perform **data inspection**, **missing value checks**, and **class distribution visualizations** before training a classification model.
📁 Dataset Structure

The dataset is stored in Google Drive and accessed in Google Colab using the following base path:
/content/drive/MyDrive/CatsAndDogsDataset/

✅ Result: Both train and val datasets contain no missing values.
📊 Category Distribution

Category distributions were analyzed to check for class imbalance.

Training Set:

Dogs (1): 180  
Cats (0): 95


Validation Set:

Dogs (1): 46  
Cats (0): 24


Bar charts were generated using Matplotlib to visualize class proportions.

📈 These charts can be viewed in the GitHub repository under the visuals section.

🖼️ Sample Images Visualization

A random selection of sample images from the training set was displayed to verify image quality and correct labeling:

sample = train.sample(5, random_state=42)


Each image is shown along with its category label (Cat or Dog).

⚙️ Tools and Libraries Used

Python 3

Google Colab

Pandas – for data handling and analysis

Matplotlib – for visualization

Google Drive – for dataset storage and access

🎯 Purpose

This analysis serves as a data exploration and validation stage before building an image classification model.
It ensures the dataset is clean, balanced (or managed), and ready for training with models such as Convolutional Neural Networks (CNNs).

✨ Created by: [Gerta Voka] 📅 Date: 19 October 2025
