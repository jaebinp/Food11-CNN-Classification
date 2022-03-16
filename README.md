# Food11-CNN-Classification
Classifying food images into 11 categories using convolutional neural networks, data augmentation, and transfer learning

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

The files were split into three folders: Training, Validation, Evaluation.
This project mainly used Tensorflow and Keras to carry out the convolutional neural network.
All the training images were augmented using the ImageDataGenerator function, and all three datasets were rescaled (divide by 255).
The images were then generated into data by using the flow_from_directory function to pull straight from the directory.
The transfer learned model used was InceptionResNetV2, which has 1,000,000+ trained images, 164 layers, and 1000 classes.
After pooling and adding few more dense layers, the training model was fitted with EarlyStopping and ModelCheckpoint callbacks.
The model was evaluated with both the validation and test sets to have the following results:

- Val Loss: 0.5879      Val Acc: 0.8167
- Test Loss: 0.5127     Test Acc: 0.8354

After, a confusion matrix as well as a heatmap was plotted to view the accuracy, precision, and recall scores of each class.
Finally, 20 images were printed with it's prediction label as well as actual label beneath it.
