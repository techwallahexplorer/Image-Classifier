# Image Classifier with Convolutional Neural Networks

## Overview
This project involves training and testing a Convolutional Neural Network (CNN) model for classifying images of cats and dogs. The project is divided into two main sections: training the CNN model and testing its performance.

## Training the CNN Model

### Dependencies
- <span style="color:blue">**os**: for interacting with the operating system.</span>
- <span style="color:blue">**cv2**: OpenCV library for image processing.</span>
- <span style="color:blue">**numpy**: for numerical computations.</span>
- <span style="color:blue">**tensorflow** and **keras**: for building and training the CNN model.</span>
- <span style="color:blue">**sys**: for configuring standard output and error streams.</span>
- <span style="color:blue">**matplotlib.pyplot**: for plotting graphs.</span>

### Instructions
1. The training data directory is specified (`train_data_dir`).
2. Data preprocessing functions are defined, including loading and preprocessing the training data.
3. A CNN model is constructed using Keras Sequential API.
4. The model is compiled with an Adam optimizer, binary cross-entropy loss function, and accuracy metric.
5. Training is performed using the fit method.
6. Model performance on the training data is evaluated.

## Testing the Model

### Dependencies
- Same dependencies as for training, with additional libraries:
  - <span style="color:blue">**tabulate**: for tabulating prediction results.</span>
  - <span style="color:blue">**colorama**: for colored output.</span>
  - <span style="color:blue">**keras.models.load_model**: for loading the saved CNN model.</span>
  - <span style="color:blue">**keras.preprocessing.image**: for preprocessing test images.</span>

### Instructions
1. Test data directory is specified (test_dir).
2. The saved CNN model is loaded.
3. Test images are preprocessed.
4. Predictions are made on test images using the loaded model.
5. Predictions are tabulated and printed with colored output.
6. Model performance on the test data is evaluated.
7. Predictions are visualized using various plots:
   - First 5 images with predicted output.
   - Bar plot showing the distribution of predicted classes.
   - Pie chart showing the distribution of predicted classes.
   - Histogram showing the distribution of predicted classes.

### Note
- Make sure to adjust directory paths according to your system configuration.
- Ensure all dependencies are installed before running the script.

![Cat and Dog Image Classifier](path/to/your/image.jpg)

Feel free to replace "path/to/your/image.jpg" with an image relevant to your project.

For more information, visit [GitHub](https://github.com/techwallahexplorer).
