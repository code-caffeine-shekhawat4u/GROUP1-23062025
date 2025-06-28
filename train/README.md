# 🤖 Training Module - College Area Detection System

> Machine learning model training pipeline for college area classification

---

## 📋 Overview

This module handles:

- **📊 Dataset Management** - Organizing and preprocessing image data
- **🧠 Model Training** - CNN architecture training and validation
- **📈 Performance Monitoring** - Training metrics and visualization
- **💾 Model Saving** - Serializing trained models for deployment
- **🔄 Data Augmentation** - Expanding dataset with transformations

---

## 🚀 Quick Start

### Prerequisites

```bash
✅ Python 3.8+
✅ CUDA-compatible GPU (recommended)
✅ Minimum 8GB RAM
✅ 50GB+ storage for datasets
```

### Installation

```bash
# Create virtual environment
python -m venv venv

# Activate virtual environment
# Windows:
venv\Scripts\activate
# Linux/Mac:
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt
```

---

## 📊 College Areas Classification

### Target Classes

| Class ID | Area Name             | Expected Images |
| -------- | --------------------- | --------------- |
| 0        | Classrooms            | 500+            |
| 1        | Laboratories          | 300+            |
| 2        | Library               | 200+            |
| 3        | Cafeteria             | 150+            |
| 4        | Main Entrance         | 100+            |
| 5        | Administrative Office | 100+            |
| 6        | Sports Facilities     | 200+            |
| 7        | Auditorium            | 100+            |
| 8        | Gardens               | 150+            |
| 9        | Parking Area          | 100+            |

### Data Requirements

- **Minimum 100 images per class**
- **Various lighting conditions** (morning, afternoon, evening)
- **Different angles and perspectives**
- **High resolution** (minimum 224x224 pixels)

---

## 👥 Developers

**🤖 Ankit Kumar** - Machine Learning Engineer  
**📊 Chahat Garg** - Data Collection & Preparation Specialist

---

## 📝 Notes

- **GPU Training**: Significantly faster than CPU (10x+ speedup)
- **Data Quality**: Clean, well-labeled data is crucial for good performance
- **Overfitting**: Monitor validation loss to prevent overfitting
- **Checkpoints**: Regular model saving for recovery and comparison
- **Experimentation**: Try different architectures and hyperparameters

---

## 🚨 Troubleshooting

### Common Issues

- **CUDA Out of Memory**: Reduce batch size
- **Low Accuracy**: Check data quality and labeling
- **Slow Training**: Verify GPU utilization
- **Convergence Issues**: Adjust learning rate
