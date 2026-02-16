# Part 1 Results

| Model | Epochs | Params | Test Accuracy(%) | Training Time(s) |
|-------|--------|--------|-------------|------------------|
| LeNeT-5 | 25 | 83,126 | 64.84 | 51.87 |
| AlexNet | 30 | 36,926,730 | 75.21 | 457.28 |
| VGGNet | 20 | 14,848,586 | 20.71 | 3726.67 |
| ResNet50 | 10 | 24,114,826 | 24.67 | 1335.38 |
| ResNet101 | 10 | 43,185,290 | 31.70 | 2010.38 |
| EfficientNet | 10 | 4,385,197 | 10.53 | 847.83 |
| InceptionNet | 10 | 22,329,898 | 83.93 | 859.23 |
| MobileNet | 10 | 2,423,242 | 82.37 | 546.81 |

# Part 2 Results

| Model | Optimizer | Epochs | Loss Function | Train Accuracy | Test Accuracy |
|-------|-----------|--------|---------------|----------------|---------------|
| VGG | Adam | 10 | BCE | 97.27 | 73.02 |
| AlexNet | SGD | 20 | Focal Loss | 10.56 | 11.00 |
| ResNet | Adam | 15 | ArcFace | 69.33 | 66.72 |