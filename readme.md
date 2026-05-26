AI-Based Deepfake Detection System
Overview

This project is an AI-powered Deepfake Detection System developed using Deep Learning and Computer Vision techniques. The system analyzes uploaded videos/images and predicts whether the content is Real or Fake.

The project uses:

PyTorch
ResNet34
OpenCV
MediaPipe
FastAPI
Librosa
Features
Deepfake video/image detection
Face extraction using MediaPipe
CNN-based prediction using ResNet34
FastAPI backend server
Real/Fake classification
Modular AI pipeline
Tech Stack
Technology	Purpose
Python	Core Programming
FastAPI	Backend API
PyTorch	Deep Learning
OpenCV	Video Processing
MediaPipe	Face Detection
Torchvision	Pretrained Models
Librosa	Audio Processing
Uvicorn	API Server

Project Architecture



User Upload
    ↓
FastAPI Backend
    ↓
Frame Extraction (OpenCV)
    ↓
Face Detection (MediaPipe)
    ↓
Preprocessing
    ↓
ResNet34 Deep Learning Model
    ↓
Prediction Layer
    ↓
Real / Fake Result