| Model | Accuracy | Precision | Recall | F1 Score | Overfitting | Underfitting | Stability | Generalization |
|-------|---------|-----------|--------|----------|-------------|--------------|-----------|----------------|
| Custom_CNN | 0.625 | 0.625 | 1.000 | 0.769 | No | Yes | Poor | Weak |
| VGG16 | 0.832 | 0.908 | 0.813 | 0.858 | Mild | No | Stable | Good |
| VGG19 | 0.763 | 0.856 | 0.746 | 0.797 | Mild | No | Stable | Good |
| ResNet50 | 0.789 | 0.852 | 0.800 | 0.825 | Mild | No | Stable | Good |
| **MobileNetV2** | 0.897 | 0.910 | 0.928 | 0.919 | No | No | Very Stable | Excellent |
| DenseNet121 | 0.856 | 0.912 | 0.851 | 0.881 | Slight | No | Stable | Strong |
| EfficientNetB0 | 0.375 | 0.000 | 0.000 | 0.000 | Failed | Severe | Unstable | Failed |
