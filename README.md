# TAWASUL – Multimodal Emotion Recognition App

A team-based graduation project that analyzes user emotions from written text and facial images to support emotional self-awareness.

## Overview

TAWASUL is an innovative multimodal emotion recognition application developed as part of a DEPI (Digital Egypt Pioneers Initiative) team graduation project. The system combines natural language processing and computer vision to provide comprehensive emotional analysis from multiple input modalities.

## Key Features

- **Multimodal Emotion Analysis**:
  - Text-based emotion recognition from written input
  - Facial emotion analysis from images
  - Combined insights from both modalities

- **Real-time Facial Emotion Detection**: Live camera-based emotion prediction

- **Comprehensive Dataset**:
  - 22,508 facial images
  - 8 emotion classes coverage
  - Diverse demographic representation

- **High Accuracy**: Up to 71% classification accuracy on validation data

- **Interactive Testing Tools**: Real-time OpenCV-based evaluation

## Technologies Used

### Computer Vision (Facial Analysis)
- **Face Detection**: MTCNN (Multi-task Cascaded Convolutional Networks)
- **Transfer Learning Architectures**:
  - VGG16/19
  - DenseNet121/169/201
  - ResNet50V2
- **Image Processing**: OpenCV, PIL
- **Deep Learning**: TensorFlow/Keras

### Natural Language Processing (Text Analysis)
- NLP libraries for sentiment extraction
- Text preprocessing and tokenization
- Emotion classification from text

### Framework & Tools
- Python 3.x
- TensorFlow/Keras
- OpenCV
- NumPy, Pandas

## My Role: Computer Vision Engineer

As the Computer Vision Engineer on this team project, I was responsible for:

### Facial Preprocessing Pipeline
- Designed and implemented MTCNN-based face detection and localization
- Developed face cropping and alignment workflow
- Processed 22,508 images with 8 emotion classes

### Model Experimentation & Optimization
- Conducted extensive trial-and-error experimentation with multiple architectures:
  - VGG (baseline model)
  - DenseNet (dense connections for feature reuse)
  - ResNet50V2 (residual learning framework)
- Optimized preprocessing strategies:
  - Image normalization techniques
  - Augmentation strategies
  - Face alignment improvements
- Fine-tuned training parameters to balance accuracy and generalization

### Performance Achievements
- **Achieved 71% classification accuracy** on held-out validation data
- Demonstrated stable generalization (not memorization)
- Prevented overfitting through:
  - Proper train/validation/test splits
  - Dropout and regularization
  - Early stopping mechanisms
  - Data augmentation strategies

### Real-time Testing & Evaluation
- Implemented OpenCV-based real-time facial emotion testing tool
- Enabled live camera input processing
- Created evaluation interface for system testing

## Dataset Information

- **Total Images**: 22,508
- **Emotion Classes**: 8
  - Happy
  - Sad
  - Angry
  - Fearful
  - Surprised
  - Disgusted
  - Neutral
  - (One additional class)
- **Preprocessing**: Standardized to 224×224 pixels for transfer learning models

## Model Performance

| Architecture | Accuracy | Notes |
|---|---|---|
| VGG16 | 68% | Baseline model |
| DenseNet121 | 70% | Better feature reuse |
| ResNet50V2 | **71%** | Best performance |

**Validation Results**: 71% accuracy on held-out validation set with stable generalization

## Key Achievements

✅ Processed 22,508 facial images with comprehensive preprocessing
✅ Achieved 71% accuracy with stable generalization
✅ Evaluated 3 major transfer learning architectures
✅ Implemented real-time emotion detection from live camera
✅ Created complete CV pipeline for facial emotion analysis
✅ Demonstrated successful team collaboration

## Course Information

- **Project Type**: DEPI Team Graduation Project
- **Role**: Computer Vision Engineer
- **Institution**: DEPI Program

## License

MIT License