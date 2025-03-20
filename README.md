🐶 Dog Breed Classification (120 Breeds) | MobileNetV2
Who’s a good dog? 🐾 Ever seen a pup and wondered, What breed is that? Well, deep learning can help answer that! This project uses transfer learning with MobileNetV2 to classify 120 different dog breeds from images.

🚀 Overview
This project applies deep learning and computer vision to predict the breed of a dog from an image. Using MobileNetV2 and TensorFlow, the model learns to differentiate between breeds, even with limited training data.

🔹 Approach: Transfer learning with a pre-trained model
🔹 Dataset: 120-class subset of ImageNet (Stanford Dogs Dataset)
🔹 Evaluation Metric: Multi-class Log Loss

🔨 Tools & Libraries
TensorFlow & TensorFlow Hub – Deep learning framework
Scikit-Learn – Data preprocessing & evaluation
NumPy & Pandas – Data handling
Matplotlib & Seaborn – Data visualization
OS – File handling
📌 Steps Involved
1️⃣ Exploratory Data Analysis (EDA)
Loaded and visualized sample images 📸
Checked for class distribution and imbalances
Explored metadata to understand dataset structure
2️⃣ Data Preprocessing
Converted image paths & labels into structured format
Applied one-hot encoding for multi-class classification
Resized & normalized images to match MobileNetV2 input
3️⃣ Model Building
Used MobileNetV2 as a feature extractor
Added custom fully connected layers for classification
Used Softmax activation in the final layer
Implemented early stopping and model checkpoints
4️⃣ Training the Model
Trained on 10,000+ images with an 80-20 train-validation split
Used data augmentation to improve generalization
5️⃣ Saving & Reloading the Model
Stored trained models for later use
Enabled easy reloading for evaluation & inference
6️⃣ Predictions & Testing
Generated breed predictions for test images
Created a CSV submission file for Kaggle format
7️⃣ Custom Image Classification
Uploaded my own dog images 🐕
Got real-time breed predictions using the trained model
