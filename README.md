**Modified ResNet-18 for Image Classification**

This repository contains modified code for the ResNet-18 architecture to improve its performance on image classification tasks. Specifically, we investigated the impact of changing batch size, activation function, and incorporating dropout in the model. We conducted experiments using the CIFAR-10 dataset and compared the performance of four different models.

Performance Metrics: 
| Model | Train Loss | Train Accuracy | Test Loss | Test Accuracy |
| --- | --- | --- | --- | --- |
| 1 | 0.264 | 91.000% | 0.343 | 88.350% |
| 2 | 0.099 | 96.518% | 0.335 | 90.050% |
| 3 | 0.083 | 97.166% | 0.327 | 90.570% |
| 4 | 0.155 | 94.640% | 0.275 | 91.480% |

Requirements:
To run the code, you will need the following:

- Python 3.6 or later
- PyTorch 1.7.1 or later
- torchvision 0.8.2 or later
- NumPy 1.19.3 or later
