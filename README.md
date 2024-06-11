# Image Classifier with Python and TensorFlow

This Jupyter notebook demonstrates how to build an image classifier using Python and TensorFlow. The classifier distinguishes between two classes of images: Happy and Sad.

## Steps Involved

1. **Downloading Images**
   - Used a Google extension to download images of two classes: Happy and Sad.

2. **Building a Data Pipeline**
   - Constructed a data pipeline using TensorFlow dependencies to manage the flow of image data.

3. **Preprocessing Images**
   - Preprocessed the images by deleting those less than 10KB in size.
   - Filtered to keep only images with the following extensions: .jpg, .jpeg, .png, .bmp.

4. **Creating a Deep Neural Network Classifier**
   - Used the Sequential library from Keras to build a deep neural network (DNN) classifier.

5. **Evaluating Model Performance**
   - Assessed the model's performance using standard evaluation metrics.

6. **Saving the Model for Deployment**
   - Saved the trained model to a file for future deployment.

## Dependencies and Libraries Used

- **TensorFlow**: For building and training the neural network.
- **OpenCV**: For image processing tasks.
- **Matplotlib**: For plotting and visualisation.
- **Keras**: Specifically the Sequential API for constructing the neural network.
- **OS**: For file and directory operations.

## Installation

To run this project, you need to install the following libraries:

```bash
pip install tensorflow opencv-python matplotlib keras
