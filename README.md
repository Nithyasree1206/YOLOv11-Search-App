## 🏷️ Computer Vision-Based Image Search & Object Detection using YOLOv11
📌 Overview

This project presents a real-time object detection and visual image search system powered by YOLOv11. It enables users to upload an image, detect objects within it, and retrieve visually similar images using feature-based similarity matching.

The system is designed with a scalable architecture, supporting both CPU and GPU execution, and is deployed using an interactive Streamlit web interface.

## 🎯 Key Features

⚡ Real-time object detection using YOLOv11

🔍 Visual similarity search using feature embeddings

🖼️ Multi-image format support (JPG, PNG, etc.)

🌐 Interactive UI built with Streamlit

🚀 GPU acceleration support (CUDA-enabled systems)

🛠️ Modular and scalable project structure

📊 Efficient inference with optimized performance

## 📂 Dataset & Model Details
## 📊 Dataset: COCO 2017

118,000 training images

5,000 validation images

80 object categories

Common classes: person, car, dog, laptop, bottle, etc.

## 🤖 Model: YOLOv11

Model Used: yolo11m.pt

Pretrained on COCO dataset

Supports real-time object detection

High speed and accuracy

## ⚙️ System Architecture

Input Image Upload

YOLOv11 Object Detection

Feature Extraction (Embeddings)

Similarity Matching

## Results Visualization (Bounding Boxes + Similar Images)

🛠️ Environment Setup
Step 1: Create Conda Environment
```
conda create -n yolosearch python=3.10 -y
conda activate yolosearch
```
Step 2: Install Dependencies
```
pip install ultralytics streamlit opencv-python numpy pillow
```
Step 3: Install PyTorch
🔹 GPU (Recommended)
```
pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu118
```
🔹 CPU
```
pip install torch torchvision torchaudio
```
💻 Running the Project
▶️ Run YOLO Inference
```
python src/inference.py
```
🌐 Launch Streamlit App
```
streamlit run app.py
```
## 🖥️ Development Setup (VS Code)

Select Python Interpreter → yolosearch environment

Use integrated terminal

Ensure required extensions (Python, Jupyter) are installed

## 📸 Output Screenshots

Add the following images inside your repository (/assets or /images folder)

<img width="887" height="275" alt="DLPIC1" src="https://github.com/user-attachments/assets/df014768-ac48-4f44-b0a2-ad04a9f61be7" />
<img width="898" height="316" alt="DLPIC2" src="https://github.com/user-attachments/assets/b5e6a951-6113-4efc-8a59-2a775b7796d7" />
<img width="867" height="412" alt="DLPIC4" src="https://github.com/user-attachments/assets/c0d1eba9-463b-4331-a0be-775633cd9642" />
<img width="851" height="405" alt="DLPIC5" src="https://github.com/user-attachments/assets/7113c6ec-b8db-4a3d-b639-2a082b7ade4e" />
<img width="878" height="338" alt="DLPIC3" src="https://github.com/user-attachments/assets/419d2b52-94fa-4493-8df3-73bb2eed310a" />



Streamlit UI Interface

Detection Output with Bounding Boxes

Terminal Logs (YOLO Inference)

Similarity Search Results

## 🚀 Enhancements & Innovations

🔍 Implemented visual similarity search using embedding vectors

⚡ Integrated GPU-accelerated YOLO inference

🌐 Developed a user-friendly Streamlit interface

🔎 Enabled search-by-object-name functionality

🧾 Added logging and exception handling

📁 Supports multiple image input formats

## 📊 Results

Metric	Performance
Detection Accuracy	High
Inference Speed	~20–40 ms (GPU)
Supported Classes	80 (COCO)
Deployment	Streamlit Web App

## ✅ Conclusion

This project demonstrates an efficient and scalable computer vision pipeline combining real-time object detection and content-based image retrieval.

With support for both CPU and GPU environments, along with a deployable web interface, the system is suitable for practical applications such as:

Smart surveillance

E-commerce image search

Content-based media retrieval

AI-powered recommendation systems

📌 Future Scope

🔥 Integration with cloud deployment (AWS / Azure)

📱 Mobile-friendly UI

🧠 Advanced deep learning embeddings (CLIP, ResNet)

📦 API-based service deployment

## 👩‍💻 Author

## NITHYASREE S
