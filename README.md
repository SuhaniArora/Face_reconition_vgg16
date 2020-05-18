# Face_reconition_vgg16

# 1. Collecting Dataset

The first step before training any model is collecting the dataset.

In the jupyter file uploaded I have used cv2 for the same - it uses the camera of the laptop to take pictures of your face and store them in the directory specified.

I had collected dataset for my face and my brother's face i.e. 2 classes and after collecting 1000 images for each , then manually splitted it into 2 folders - train and validation.

# 2. Training Model

After the collection of dataset , pre-trained model is used - of which all the convolution layers are freezed and new dense / fully connected layers are added which are then trained for the dataset collected previously.

# 3. Saving the Model

The trained model is saved is then saved which can loaded at any point of time in any file to predict the results.

# 4. Predicting Results

You can either use a photo you have or use your camera to predict the face in real time , here i had used my camera to take a picture of mine and then predicted the result.

Also , whlie predicting since I only had two files so I wrote a simple if else condition but in case of more classes the python cade can be modified.
