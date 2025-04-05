# Lung Cancer Classification using Deep Learning

## 🚀 Project Overview
Welcome to the Lung Cancer Classification project using Deep Learning. This repository is dedicated to developing robust deep learning models to classify CT scan images into various types of lung cancer. Utilizing state-of-the-art convolutional neural networks (CNNs), this project aims to improve the accuracy of early lung cancer detection, which is critical for effective treatment and patient outcomes.

## 🧠 Models Utilized
In this project, we explore several advanced CNN architectures known for their efficacy in image classification tasks:
- **VGG19**: Known for its simplicity and depth, which is effective in capturing intricate patterns in image data.
- **ResNet50**: Utilizes residual connections to enable training of deeper neural network architectures without performance degradation.
- **DenseNet201**: Features dense connections between layers to enhance feature propagation and reuse, making it highly efficient.
- **EfficientNetB4**: Balances model scaling across depth, width, and resolution, leading to improved efficiency and accuracy.

## 📊 Data Description
The dataset consists of CT scans labeled into the following categories, which represent different types of lung cancer and normal conditions:
- Normal
- Squamous Cell Carcinoma
- Adenocarcinoma
- Large Cell Carcinoma

The data is preprocessed to align image sizes and augment the dataset to ensure robustness and generalizability of the models.

## 🔍 Main Findings
- **Model Performance**: Each model was rigorously trained and evaluated. Here are the key performance metrics:
  - **VGG19**: Achieved an accuracy of 89.52% on the test set.
  - **ResNet50**: Reached a test accuracy of 72.22%, demonstrating strong generalization.
  - **DenseNet201**: The best-performing model with a test accuracy of 93.33%.
  - **EfficientNetB4**: Performed with an accuracy of 68.75% on the test set.
- **Best Model**: DenseNet201 was finalized as the best model due to its superior accuracy and efficiency in handling complex image classifications.

## 🛠 Technologies Used
This project employs various technologies and libraries, primarily focused on Python for data science and machine learning:
- **TensorFlow** and **Keras**: For designing, training, and evaluating deep learning models.
- **NumPy** and **Pandas**: For efficient data manipulation and analysis.
- **Matplotlib** and **Seaborn**: For visualizing data and model performance metrics.

## 📈 Example Predictions
The notebooks within this repository provide visualization of predictions made by each model, demonstrating their performance and the effectiveness of the applied machine learning techniques.

## 🌟 How to Contribute
We encourage contributions from the community, whether it's adding new features, enhancing existing models, or improving documentation:
1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/YourFeature`).
3. Commit your changes (`git commit -am 'Add some YourFeature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Create a new Pull Request.

## 📝 License
This project is released under the MIT License, which allows for open and reproducible scientific research.

## 📩 Contact
If you have any feedback, questions, or would like to discuss the project further, please reach out through GitHub issues or contact the maintainers directly via email.

---
*Note: This project is intended for educational and research purposes in the field of medical image analysis using deep learning.*
