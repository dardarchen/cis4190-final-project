Each notebook in this repo corresponds to one of the models. See below for model-specific instructions:

ViT:

ResNet50:

EfficientNet:

Dependencies that need to be installed:
fmix,
opendatasets,
glob,
sklearn,
cv2,
skimage, 
torch,
torchvision,
pandas,
numpy, 
tqdm, 
matplotlib,
timm,
joblib,
pydicom,
scipy,
catalyst,
albumentations

Running the code:
First, download the Kaggle dataset using opendatasets. This will require a Kaggle username and key, which you can obtain on the Kaggle website. Each header indicates the purpose of the section of code that follows it. Modify CFG and run the main loop to train when testing simple changes such as adjusting the learning rate or regularization parameter. Run the code under the 'Train accuracy and other statistics' header to get the performance metrics after training. For the other changes, run the code under the corresponding header, and use the same code to get performance metrics unless otherwise specified.
