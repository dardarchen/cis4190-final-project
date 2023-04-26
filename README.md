Each set of notebook(s) in this repo corresponds to one of the models. See below for model-specific instructions:

ViT:

Dependencies that need to be installed: 
matplotlib,
numpy,
pandas,
PIL,
sklearn.model_selection: train_test_split,
sklearn.metrics: precision_recall_fscore_support,
tqdm.notebook,
torch,
torchvision,
vit

Running the code:
The notebooks are mostly self-contained since the notebooks were run on Kaggle. To reproduce the results, download the Kaggle dataset and read in the data with the appropriate file path. To modify the model, the parameters such as optimizer, loss, learning rate, and regularization are specified under the VisionTransformer header. Run the fit cell to train and evaluate the model, which will also print out training and validation (which serves as our test) accuracy as well as the other evaluation metrics. 

ResNet50: 
Run all code blocks and collect performance metrics from the "Train and Validate" code block outputs. On my device, the model took about 6:30 min per epoch to train and validate, however this time may vary for you depending on your device and GPU constraints.

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
