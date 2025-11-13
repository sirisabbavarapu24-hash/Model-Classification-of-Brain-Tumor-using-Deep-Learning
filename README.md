# Model-Classification-of-Brain-Tumor-using-Deep-Learning
This project leverages using Convolutional Neural Network (CNN) to automatically detects and classify the tumor through using MRI scans.It aims to assists the radiologists and medical professionals by providing fast, realiable,and interpretable diagnosistss tool.

🔍 Objective
To develop a deep learning model that can classify brain MRI images into tumor types (e.g., glioma, meningioma, pituitary and no tumor) or detect the presence/absence of tumors with high accuracy.

🧪 Dataset
- Source: Publicly available brain MRI datasets (e.g., Kaggle, Figshare)
- Classes: Glioma, Meningioma, Pituitary, No Tumor
- Format: Preprocessed grayscale images, resized and normalized for model input

🧠 Model Architecture
- Base Model: CNN (custom or transfer learning with VGG16, ResNet50, etc.)
- Layers: Convolutional + MaxPooling + Dense + Dropout
- Activation: ReLU, Softmax
- Loss Function: Categorical Crossentropy
- Optimizer: Adam

📊 Performance
- Accuracy: ~95% on validation set
- Evaluation Metrics: Confusion matrix, ROC curve, precision, recall, F1-score

🧾 Features
- Image preprocessing pipeline
- Model training and evaluation scripts
- Visualization of predictions and activation maps (Grad-CAM)
- Explainable AI integration for interpretability

🚀 Future Work
- Integration with clinical workflows
- Real-time inference using web or mobile interface
- Expansion to 3D MRI volumes and segmentation tasks
