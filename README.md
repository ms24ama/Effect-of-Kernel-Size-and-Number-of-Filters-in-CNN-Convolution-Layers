# Effect-of-Kernel-Size-and-Number-of-Filters-in-CNN-Convolution-Layers
Effect of Kernel Size and Number of Filters in CNN Convolution Layers
📌 Project Overview

This project investigates how kernel size and number of filters in convolutional layers affect the performance of Convolutional Neural Networks (CNNs). Using the CIFAR-10 image classification dataset, multiple CNN architectures are trained and compared to analyse learning behaviour, generalisation ability, and overfitting.

🎯 Objectives

To study the impact of different kernel sizes (3×3 and 5×5) on feature extraction
To analyse how varying the number of filters (32 and 64) influences model capacity
To compare training and validation accuracy and loss across CNN configurations
To provide practical guidelines for CNN architecture design

🗂 Dataset
CIFAR-10
60,000 colour images (32×32 pixels)
10 balanced object classes
50,000 training images and 10,000 test images

🧠 Methodology
Four CNN models were implemented using TensorFlow/Keras with controlled experimental settings. Only kernel size and filter count were varied, while other hyperparameters remained fixed. Performance was evaluated using training and validation metrics.

📊 Results
Smaller kernels (3×3) consistently achieved better accuracy than larger kernels (5×5)
Increasing the number of filters improved learning capacity but increased overfitting risk
The 3×3 kernel with 64 filters achieved the best overall performance
Validation loss analysis highlighted the importance of regularisation techniques

📁 Repository Structure
cnn-kernel-filter-analysis/
│
├── notebook.ipynb
├── tutorial.pdf
├── training_accuracy_comparison.png
├── training_loss_comparison.png
├── validation_accuracy_comparison.png
│└── validation_loss_comparison.png
│
├── README.md
├── LICENSE

⚙️ Requirements

Python 3.8+

TensorFlow / Keras

NumPy

Matplotlib

Pandas

▶️ How to Run

Clone this repository

Open the Jupyter Notebook in the notebook/ directory

Run all cells to reproduce results and figures

📚 References

Key references include :
1. LeCun, Y., Bottou, L., Bengio, Y., & Haffner, P. (2002). Gradient-based learning applied 
to document recognition. Proceedings of the IEEE, 86(11), 2278-2324. 
2. Simonyan, K., & Zisserman, A. (2014). Very deep convolutional networks for large
scale image recognition. arXiv preprint arXiv:1409.1556. 
3. Krizhevsky, A., Sutskever, I., & Hinton, G. E. (2012). Imagenet classification with deep 
convolutional neural networks. Advances in neural information processing 
systems, 25. 
4. Goodfellow, I. (2016). Deep learning. 
5. He, K., Zhang, X., Ren, S., & Sun, J. (2016). Deep residual learning for image 
recognition. In Proceedings of the IEEE conference on computer vision and pattern 
recognition (pp. 770-778). 
6. Szegedy, C., Liu, W., Jia, Y., Sermanet, P., Reed, S., Anguelov, D., ... & Rabinovich, A. 
(2015). Going deeper with convolutions. In Proceedings of the IEEE conference on 
computer vision and pattern recognition (pp. 1-9). 

📄 License

This project is released under the MIT License, allowing free use, modification, and distribution with attribution.
