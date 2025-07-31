
This project demonstrates how to build, train, and evaluate a Convolutional Neural Network (CNN) for binary image classification using TensorFlow and Keras.

---

## 📌 **Project Overview**

- 📦 **Data**:  
  - A ZIP archive containing training and test images.
  - Images are organized in subfolders by class inside `train` and `test` directories.

- ⚙️ **Key Steps**:
  1. **Extract Dataset**: Unzips the dataset to the working directory.
  2. **Create Data Generators**: Loads images in batches.
  3. **Normalize Images**: Scales pixel values to [0, 1].
  4. **Build CNN Model**: Uses Conv2D, Batch Normalization, MaxPooling, Dropout, and Dense layers.
  5. **Train the Model**: Trains for 10 epochs with validation.
  6. **Visualize Performance**: Plots accuracy and loss graphs.
  7. **Predict Single Image**: Tests the model on a new image.
  
