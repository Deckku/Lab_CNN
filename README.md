# Lab_CNN
# Convolutional Neural Networks (CNNs) in Action: From Fundamentals to Classification

This notebook serves as an introductory exploration into the fascinating world of Convolutional Neural Networks (CNNs), a cornerstone of modern computer vision. We delve into the fundamental concepts of CNNs, starting with a hands-on look at 2D image convolution, understanding how filters transform raw pixel data into meaningful feature maps. The notebook also illustrates the role of MaxPooling layers in downsampling feature maps and reducing computational complexity.

Building upon these foundational elements, we apply our understanding to practical image classification problems. Specifically, we train and evaluate CNN models on two widely-used datasets: the **Fashion-MNIST** dataset, which consists of grayscale images of fashion products, and the **EMNIST Digits** dataset, focusing on handwritten digit recognition. Through these examples, we demonstrate the power and effectiveness of CNNs in extracting hierarchical features for robust image classification.

*   **Comparative Conclusion**:
    *   **Dataset Complexity**: EMNIST Digits (handwritten digits) is significantly less complex than Fashion-MNIST (fashion items), leading to much higher performance and stability on EMNIST.
    *   **Generalization**: The same CNN architecture generalized much better on EMNIST Digits.
    *   **Overfitting**: Fashion-MNIST showed signs of overfitting with a respectable ~89% validation accuracy, while EMNIST Digits achieved near-optimal 99.57% accuracy with no apparent overfitting.

### Insights or Next Steps

*   The significant difference in model performance and overfitting behavior between Fashion-MNIST and EMNIST Digits underscores the critical role of dataset complexity in model training and generalization. Simple CNN architectures can excel on less complex, distinct datasets, but more challenging datasets require robust regularization and potentially more sophisticated architectures to prevent overfitting.
*   For the Fashion-MNIST task, future steps should focus on enhancing regularization techniques (e.g., increased dropout, L2 regularization, data augmentation) and potentially refining the CNN architecture or hyperparameters (e.g., learning rate scheduling) to improve generalization and mitigate overfitting, aiming to bridge the gap between training and validation performance.

## 6. Credits * Author: Azami Hassani Adnane. * Supervisor: Prof. Masrour Tawfik.
