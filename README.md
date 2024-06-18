# VlG_Image_denoising
This Jupyter notebook showcases the application of a deep convolutional neural network (CNN) autoencoder for image denoising. The model is 
trained to eliminate noise from images, generating cleaner versions as output.

# How to Run the Notebook

* Clone the repository or download the notebook file.
* Install the required libraries as specified in the initial section.
* Load and preprocess the images according to the instructions.
* Divide the dataset into training and testing sets.
* Define the PSNR function and create a custom callback.
* Construct and train the model using the specified architecture.
* Plot the training and testing loss curves.
* Compute the PSNR score for the test data.
* Display the predicted, noisy, and clean images for evaluation.

# Requirements
Python 3.x
Jupyter Notebook
Necessary Python libraries (e.g., TensorFlow, NumPy, Matplotlib)

# Improvements
* Experiment with deeper networks or adding skip connections.
* Use data augmentation to improve robustness.
* Implement advanced loss functions like Structural Similarity Index (SSIM) for better perceptual quality.



