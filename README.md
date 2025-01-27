# Flower Classification and Clustering using CNN

## Project Overview
This project focuses on classifying and clustering flower images using Convolutional Neural Networks (CNNs) and K-Means clustering. It involves building a CNN model for multi-class classification and using autoencoders for unsupervised feature extraction followed by clustering.

## Features
- **Image Classification:** Trains a CNN model to classify flower images into 10 categories.
- **Data Augmentation:** Implements techniques like rotation, zoom, shear, and flips to enhance model robustness.
- **Clustering:** Uses autoencoders to extract features and K-Means for clustering similar images.
- **Visualization:** Displays loss, accuracy metrics, and clustering results for better insights.

---

## Getting Started

### Prerequisites
Ensure you have the following installed:
- Python 3.7+
- TensorFlow 2.0+
- NumPy
- Matplotlib
- Scikit-learn
- PIL

### Dataset
Place your flower image dataset in the specified directory structure:
```
/dataset/
    /category1/
        img1.jpg
        img2.jpg
    /category2/
        img1.jpg
        img2.jpg
```
Replace `category1`, `category2`, etc., with the appropriate category names.



---

## Results
- **Training and Validation:**
  - Plots show the loss and accuracy for both training and validation datasets over epochs.
- **Clustering:**
  - Displays clustered images to visualize grouping by similarity.

---

## Technologies Used
- TensorFlow
- Keras
- Scikit-learn
- Python
- Matplotlib
- PIL (Pillow)

---

## License
This project is licensed under the MIT License. See the LICENSE file for details.

---

## Acknowledgments
- TensorFlow and Keras for providing powerful deep learning tools.
- Inspiration from various deep learning research papers and online resources.

---

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

---

## Contact
Created by [Nishant Rodrigues](mailto:your_email@example.com). Feel free to reach out for any questions or feedback!

