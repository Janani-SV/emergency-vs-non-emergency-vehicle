# emergency-vs-non-emergency-vehicle-classification
Classification of Emergency and non Emergency vehicle

Environment : GCP 
Framework : Keras 

First model was developed from scratch using keras framework 

Before Data arrives in datawarehouse, the images from datalaske was preprocessed 
for same dimensions and image augmentation was done to have more training data 

A python function is written for preprocessing and storing the image in datawarehouse.
When data arrives in cloud storage, cloud function is triggred to preprocess the image and store it in datawarehouse. 

- Loading the dataset
- Preprocessing the data 
- Creating training and calidation set
- Defining the model architecture
- Compiling the model 
- Training the model 
- Evaluating the model

Model is continously trained to improve the accuracy by changing the hyperparameters


Second model was developed using the transfer learning

