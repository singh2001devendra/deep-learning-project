# 🧠 Image Classification using CNN

A deep learning project that classifies images using a Convolutional Neural Network (CNN) built with TensorFlow/Keras. This repository demonstrates how to build, train, and evaluate a simple yet effective image classification model.

## 📁 Project Structure


## 🧰 Features

- Image preprocessing (resizing, normalization, augmentation)
- CNN model building using TensorFlow/Keras
- Model training with accuracy and loss tracking
- Evaluation using test data
- Save/load trained models
- Custom predictions on new images

2. Install dependencies
   pip install -r requirements.txt

3. Prepare dataset
   data/
├── train/
│   ├── class1/
│   ├── class2/
│   └── ...
└── test/
    ├── class1/
    ├── class2/
    └── ...
4. Train the model
   python src/train.py
5. Evaluate the model
   python src/evaluate.py

6. Make predictions
You can use a script or notebook to load the model and predict on new images.

🏗 Model Architecture
A simple CNN structure:

Conv2D → ReLU → MaxPooling

Conv2D → ReLU → MaxPooling

Flatten → Dense → Dropout → Output

This can be modified or extended for better performance.

📊 Results
Accuracy: ~97% (on test set)

Accuracy: ~88% (on training set)

Update with your actual results

🧪 Requirements
Python 3.7+

TensorFlow / Keras

NumPy

Matplotlib

Scikit-learn

Install using:
pip install -r requirements.txt
📜 License
This project is licensed under the MIT License.

🤝 Contributing
Contributions, issues, and feature requests are welcome!
Feel free to check issues page if you want to contribute.
