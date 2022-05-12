# Interpretable-Machine-Learning-for-Image-Classification

-> import all import libraries
-> initialize InceptionV3
-> Read and pre-process image
-> Predict class of input image

Step 1: Create perturbations of image
Step 2: Use ML classifier to predict classes of new generated images
Step 3: Compute distances between the original image and each of the perturbed images and compute weights (importance) of each perturbed image
Step 4: Use perturbations, predictions and weights to fit an explainable (linear) model
