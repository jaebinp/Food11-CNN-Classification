# Food11-CNN-Classification 
Classifying food images into 11 categories using Convolutional Neural Networks

## In-Depth Synopsis
The purpose of this project is to use Convolutional Neural Networks to classify food images that belong into 11 categories. The project utilizes techniques that help with the classification process, such as data augmentation and transfer learning. The transfer learned model used was InceptionResNetV2, which as 1,000,000+ trained images, 164 layers, and 1000 classes. The files were split into three folders: Training, Validation, Evaluation. A path was created for each folder, which is something anyone planning on using this project will need to change accordingly

The dataset contains 16643 images of food in 11 different categories. The categories are as follows:

- Bread
- Dairy Product
- Dessert
- Egg
- Fried Food
- Meat
- Noodles-Pasta
- Rice
- Seafood
- Soup
- Vegetable-Fruit

Dense and pooling layers were added to the learned layers and the training model was fitted with EarlyStopping and ModelCheckpoint callbacks. The model was evaluated with both the validation and test sets. A confusion matrix as well as a heatmap was plotted to view the accuracy, precision, and recall scores of each class. At the end, 20 images were printed with it's prediction label as well as actual label beneath it.

## Getting Started

### Dependencies
* Tensorflow 2.0 or higher, Python 3.0 or higher
* IF USING MAC WITH M1 CHIP: need to download Miniforge to run Tensorflow 2.0 at full capacity with running GPU, as tensorflow 2.0 is not compatible with the new chip on Anaconda and Jupyter Notebooks
* Instructions for installing Miniforge and Tensorflow 2.0: https://www.youtube.com/watch?v=_CO-ND1FTOU

### Download & Installing
* The notebook is open for downloads on this git
* Dataset can be found on kaggle: https://www.kaggle.com/datasets/trolukovich/food11-image-dataset
* After downloading the dataset and notebook, must change filepath on the notebook
<img width="550" alt="Screen Shot 2022-03-25 at 10 27 39 AM" src="https://user-images.githubusercontent.com/33381687/160140736-49416d52-1b68-4346-b842-a7fa5600757a.png">

### Execution
* Make sure all packages and libraries required to run the noteboko are downloaded and installed
* 'pip install ______' any packages that are not installed, or use any other desired method




