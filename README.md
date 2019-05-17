# CNN_Keras
## Implementation of a CNN in Keras.
### Dataset:boats-types-recognition

### First model: boat. 
Use the 9 class of the dataset with 2 convolutional layers (3,3), 2 max pooling layers (2,2), 2 dropout and 2 dense layers.

Optimization function:Adadelta; 
Learning rate:default; 
Batch_size:20; 
Epochs:50; 
Steps_per_epochs:50; 
Validation_steps:13; 
Max acc:0.8428; 
Max val_acc:0.6618;

### Second model: boat_reduced. 
Use 4 class of the dataset with 3 convolutional layers (one with 5,5 and the others with 3,3), 2 max pooling layers (2,2), 2 droput and 2 dense layers.

Optimization function:Adam; 
Learning rate:0.001; 
Batch_size:16; 
Epochs:50; 
Steps_per_epochs:53; 
Validation_steps:11;
Max acc:0.9257; 
Max val_acc:0.7479;

### Third model: boat_reduced_2. 
Use 4 class of the dataset with 3 convolutional layers (one with 5,5 and the others with 3,3), 2 max pooling layers (2,2) and 2 dense layers.

Optimization function:RMSprop; 
Learning rate:0.0002; 
Batch_size:32; 
Epochs:50; 
Steps_per_epochs:26; 
Validation_steps:11; 
Max acc:0.9670; 
Max val_acc:0.7596; 
