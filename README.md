


🫁 Pneumonia Detection Using Deep Learning

A deep learning–based medical imaging project that detects pneumonia from chest X-ray images using multiple convolutional neural network (CNN) architectures. The project evaluates and compares classical CNNs and transfer-learning models to assess their effectiveness in automated pneumonia diagnosis.

⸻

📌 Project Overview

Pneumonia is a potentially life-threatening respiratory disease that requires early and accurate diagnosis. Traditional diagnosis relies on manual interpretation of chest X-rays by radiologists, which can be time-consuming and subjective.

This project explores the use of deep learning models to automatically classify chest X-ray images as Pneumonia or Normal, aiming to improve diagnostic efficiency and consistency.

⸻

🎯 Objectives
	•	Build and evaluate deep learning models for pneumonia detection
	•	Compare performance across multiple CNN architectures
	•	Apply transfer learning to improve accuracy with limited data
	•	Analyze results using standard classification metrics

⸻

🛠️ Tech Stack
	•	Programming Language: Python
	•	Deep Learning Framework: TensorFlow, Keras
	•	Libraries: NumPy, Pandas, OpenCV, Scikit-learn
	•	Visualization: Matplotlib, Seaborn
	•	Hardware (Training): GPU-accelerated environment (where available)

⸻

📊 Dataset
	•	Source: Public Chest X-Ray Dataset (Kaggle – Guangzhou Women and Children’s Medical Center)
	•	Total Samples: ~5,800 images
	•	Classes:
	•	Pneumonia
	•	Normal
	•	Image Size: 300 × 300 × 3
	•	Splits:
	•	Training
	•	Validation
	•	Testing

Images were screened for quality and labeled by medical experts prior to training.

⸻

🧠 Models Implemented

1️⃣ Custom Convolutional Neural Network (CNN)
	•	Conv2D + ReLU
	•	Batch Normalization
	•	Dropout for regularization
	•	Max Pooling layers

2️⃣ AlexNet
	•	Deep convolutional layers
	•	Multiple filter sizes (3×3, 11×11)
	•	Combination of SAME and VALID padding

3️⃣ ResNet-50 (Transfer Learning)
	•	Residual blocks to prevent vanishing gradients
	•	Pre-trained on ImageNet
	•	Fine-tuned for pneumonia classification

4️⃣ VGG-16 (Transfer Learning)
	•	Pre-trained VGG-16 backbone
	•	Frozen convolution layers
	•	Global Average Pooling + Dense layers

⸻

⚙️ Implementation Highlights
	•	Applied data preprocessing and normalization
	•	Used data augmentation to reduce class imbalance
	•	Compared architectures using:
	•	Accuracy
	•	Precision
	•	Recall (Sensitivity)
	•	Specificity
	•	F1-Score
	•	Trained models using Adam optimizer with learning-rate scheduling

⸻

📈 Results Summary
	•	ResNet-50, AlexNet, and custom CNN achieved high classification accuracy
	•	Transfer learning models demonstrated improved generalization
	•	Results confirm the effectiveness of deep learning for pneumonia detection from X-ray images

⸻

⚠️ Limitations
	•	Model does not consider patient history or clinical metadata
	•	Uses only frontal chest X-ray images
	•	Not intended to replace professional medical diagnosis

⸻

🔮 Future Enhancements
	•	Multi-class classification (bacterial vs viral pneumonia)
	•	Integration with segmentation models (U-Net, YOLO)
	•	Larger and more diverse datasets
	•	Deployment as a clinical decision-support tool

⸻

👨‍💻 Contributors
	•	Hrishikesh Prahalad
	•	A Sai Kalyan
	•	H Srujan Kumar
	•	Hemanth Pai

⸻

📄 Academic Context

This project was completed as part of the Deep Learning (20IS6PEDLG) course
at BMS College of Engineering, Bengaluru (2022–2023).
