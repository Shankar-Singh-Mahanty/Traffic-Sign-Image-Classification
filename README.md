# Traffic Sign Image Classification

This repository provides a comprehensive solution for classifying traffic signs using a customized CNN sequential model. The repository includes the dataset and code structured as follows:

1. **Download and Imports**: Download necessary libraries and import required modules.
2. **Functions**: Define helper functions for data processing and model evaluation.
3. **Loading Dataset (Traffic Signs Images)**: Load the traffic signs dataset.
4. **Data Splitting and Conversion**: Split the dataset into training, validation, and test sets and preprocess the images.
5. **Creating and Compiling the Model**: Define and compile the customized CNN model.
6. **Training the Model**: Train the CNN model on the training dataset.
7. **Visualizing the Performance of the Model during Training Phase**: Visualize the training and validation performance.
8. **Loading Test Dataset and Evaluating the Model**: Load the test dataset and evaluate the model's performance.

## Getting Started

### Prerequisites

Ensure you have the following libraries installed:

- TensorFlow
- Keras
- NumPy
- Matplotlib
- Scikit-learn

You can install them using pip:

```
pip install tensorflow keras numpy matplotlib scikit-learn
```

**Usage**
1. Clone the repository
```
git clone https://github.com/Shankar-Singh-Mahanty/traffic-sign-image-classification.git
cd traffic-sign-image-classification
```
2. Run the code:
   ```
   python traffic_sign_classification.ipynb
   ```
###Project Structure
traffic_sign_image_classification.ipynb: Main script containing the entire workflow from data loading to model evaluation.
archieve: Zip file containing the traffic signs dataset.

###Model Architecture
The model is a customized CNN sequential model designed for efficient classification of traffic signs. The architecture includes multiple convolutional layers followed by pooling layers and fully connected dense layers.

###Results
Visualize the training and validation accuracy and loss, and evaluate the model on the test dataset to obtain metrics such as accuracy, precision, recall, and F1-score.

###Contributing
Feel free to submit issues or pull requests if you want to contribute to the project.

###License
This project is licensed under the MIT License - see the LICENSE file for details.

###Acknowledgments
This project is inspired by various research papers and tutorials on traffic sign classification using deep learning.
