# fashion-recommender-system
# Fashion Recommender System

## Overview

This project is a Content-Based Fashion Recommender System that recommends visually similar fashion products using Computer Vision and similarity matching techniques.

The application allows users to upload a fashion image and receive recommendations for similar products based on extracted image features.

The project demonstrates practical implementation of:

* Computer Vision
* Recommendation Systems
* Transfer Learning
* Image Feature Extraction
* Similarity Search
* Streamlit Deployment

The system is built using Python, TensorFlow, ResNet50, Scikit-learn, and Streamlit.

---

# Problem Statement

Fashion e-commerce platforms contain thousands of products, making it difficult for users to manually search for visually similar items.

This project solves the problem by building a recommendation system that suggests products based on image similarity instead of keyword-based search.

---

# Features

* Upload fashion product images
* Extract image features using ResNet50
* Recommend visually similar fashion products
* Similarity matching using cosine distance
* Interactive Streamlit web application
* Fast recommendation generation

---

# Technologies Used

## Programming Language

* Python

## Libraries & Frameworks

* TensorFlow
* Keras
* Scikit-learn
* NumPy
* OpenCV
* PIL
* Streamlit
* Pickle

---

# Project Workflow

## 1. Image Upload

The user uploads a fashion image through the Streamlit interface.

## 2. Image Preprocessing

The uploaded image is:

* Resized to 224x224
* Converted into array format
* Preprocessed using ResNet50 preprocessing

## 3. Feature Extraction

A pretrained ResNet50 model is used to extract image feature vectors.

The final classification layer is removed and Global Max Pooling is applied to generate compact feature embeddings.

## 4. Similarity Search

The extracted image features are compared with stored embeddings using:

* Nearest Neighbors Algorithm
* Cosine Similarity

## 5. Recommendation Display

The system displays visually similar fashion products to the user.

---

# Model Used

## ResNet50

The project uses a pretrained ResNet50 model for feature extraction.

### Why ResNet50?

* Strong image feature extraction capability
* Pretrained on ImageNet dataset
* Efficient transfer learning model
* Generates meaningful image embeddings
* Widely used in Computer Vision applications

---

# Project Structure

```bash
fashion-recommender-system/
│
├── README.md
├── app.py
├── main.py
├── test.py
├── filenames.pkl
├── sample_images_1.zip
```

---

# File Description

## app.py

Responsible for:

* Extracting image features
* Generating embeddings
* Saving embeddings and filenames using pickle

## main.py

Main Streamlit application responsible for:

* Uploading images
* Extracting features from uploaded images
* Finding similar products
* Displaying recommendations

## test.py

Used for local testing of the recommendation pipeline using OpenCV.

---

# Important Repository Note

Due to GitHub file size limitations:

* The complete fashion image dataset was not uploaded.
* Only sample images are included for demonstration purposes.
* Generated embeddings are stored locally and were not uploaded because of large file size.

The repository is intentionally kept lightweight while still demonstrating the complete recommendation workflow.

---

# Recommendation Technique

This project follows a Content-Based Recommendation approach.

The recommendation system works by comparing visual features extracted from fashion images rather than relying on user ratings or purchase history.

---

# Core Algorithms Used

| Algorithm          | Purpose                   |
| ------------------ | ------------------------- |
| ResNet50           | Image feature extraction  |
| GlobalMaxPooling2D | Feature vector generation |
| Nearest Neighbors  | Similar item retrieval    |
| Cosine Similarity  | Similarity measurement    |

---

# Skills Demonstrated

## Machine Learning & Computer Vision

* Transfer Learning
* Image Feature Extraction
* Recommendation Systems
* Similarity Search
* CNN-based embeddings

## Software Development

* Streamlit application development
* File handling
* Pickle serialization
* Modular project structure

## Data Science Skills

* Image preprocessing
* Embedding generation
* Recommendation pipeline design
* Similarity-based retrieval systems

---

# Challenges Faced

* Handling image embeddings efficiently
* Managing large image datasets
* Implementing fast similarity search
* Working with GitHub storage limitations
* Building an end-to-end recommendation workflow

---

# Future Improvements

Potential future enhancements include:

* Adding a larger fashion dataset
* Improving recommendation accuracy
* Using FAISS for faster similarity search
* Deploying the project on cloud platforms
* Adding category-wise filtering
* Building a responsive frontend UI

---

# Learning Outcomes

Through this project, I gained practical experience in:

* Building recommendation systems
* Working with pretrained CNN models
* Extracting image embeddings
* Deploying applications using Streamlit
* Implementing similarity search algorithms
* Designing end-to-end Computer Vision workflows

---

# Why This Project Matters

This project demonstrates practical understanding of:

* Computer Vision pipelines
* Recommendation systems
* Transfer Learning
* Image similarity search
* End-to-end ML application workflow

It reflects problem-solving and implementation skills relevant for:

* Data Science roles
* Machine Learning Engineer roles
* Computer Vision projects
* AI/ML internship opportunities

---

# Author

## Ankita Agrawal

Aspiring Data Scientist | Machine Learning Enthusiast | Open Source Contributor

---

# License

This project is open-source and available for educational and learning purposes.
