
Please follow steps mentioned below to run the code:

1. Upload raw_data folder on Google drive.
2. Mount your drive on colab.
3. Change directory locations in code accordingly.
4. Run "Creating Dataset" section only for the first time while running the code. It will create Training and Test dataset.


The overall code consists of 5 sections:
1. Importing libraries -> This part imports all the necessary libraries required to run the code. 
2. Mounting Drive -> This section mounts your drive on colab session.
3. Creating Dataset -> This code is used to load the data and performs train testing split to give training data as input to the model for training and inference.
4. Image Pre-Processing -> It containes data augmentation code and creates DataLoader using Tensorflow libraries.
5. CNN Model -> This section contains the implementation of our model using Convolutional Neural Network architecture. The implementation details are given in the project presentation.
4. Training and Validating the Model -> This section is used to train and validate the model and also used for inference.
5. Model testing -> This section is used to analyse the model on unseen dataset and to visualize the output of the model.

Official data Source: http://faculty.neu.edu.cn/yunhyan/NEU_surface_defect_database.html
Model dataset Link: https://drive.google.com/drive/folders/1VPfy6Tja91dKNxzXZpoeHXw0U31l4OHD?usp=sharing