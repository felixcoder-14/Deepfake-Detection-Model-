# 🕵️‍♂️ Deepfake Detection Model
Classify real vs. fake (AI-generated) faces using Deep Learning

This repository contains an end-to-end deepfake detection pipeline that performs:

✅ Face extraction
✅ Pre-processing
✅ Deep learning classification
✅ Interactive UI via Gradio

Built using MTCNN for face detection and MobileNetV2 (Transfer Learning) for classification.

🚀 Features

- Detects whether an image is real or deepfake
- Uses MTCNN to locate & crop facial regions
- Transfer Learning with MobileNetV2
- Data augmentation for improved training
- Lightweight & fast inference
- Easy-to-use Gradio web app
- Modular & extensible code

🧠 Tech Stack
- Component	Library
- Face Detection	MTCNN
- Frame Extraction	OpenCV
- Model	TensorFlow / Keras (MobileNetV2)
- App UI	Gradio
- Data Handling	NumPy / Pandas
- Dataset	FaceForensics / Kaggle
