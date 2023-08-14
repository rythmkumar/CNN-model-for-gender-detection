# CNN-model-for-gender-detection
Step 1: Import all the necessary libraries . I used tensorflow,keras for this<br>
Step 2: Create a CNN model with 4 conv2d layers and 4 maxpool layers<br>
  Activation function used is Relu<br>
    formulae for size of output  = (W-k+2p)/s + 1 <br>
    S is for stride <br>
    p is for padding <br>
    k is the kernel size <br>
    w is the image size <br>
Step 3: Add flatten layer to the model and add Fully connected layer and a sigmoid function for binary classification <br>
Step 4: Compile the model with optimizers adam and binary cross entropy loss <br>
Step 5: Saving the model with name my_model.h5 <br>
Upload the my_model.h5 in kaggle then load the model
