# Augmentation using Albumentation

- Data Augmentation : A Technique in machine learning used to reduce overfitting when training a machine learning model, by training models on several slightly-modified copies of existing data.
- Albumentation : A computer vision tool that boosts the performance of deep convolutional neural networks.

## Example of Original Dog Image
<!-- ![ORIDOG](https://hips.hearstapps.com/hmg-prod/images/dog-puppy-on-garden-royalty-free-image-1586966191.jpg?crop=0.752xw:1.00xh;0.175xw,0&resize=1200:*) -->
<img src="https://hips.hearstapps.com/hmg-prod/images/dog-puppy-on-garden-royalty-free-image-1586966191.jpg?crop=0.752xw:1.00xh;0.175xw,0&resize=1200:*" alt="Ori Dog" width="400">

- Some different Augmentation parameters can be found : https://albumentations.ai/docs/getting_started/image_augmentation/
- Depending on your image classification task, keep in mind that some of the parameters should not be used as it will change the traits of the image completely



## Example of Augmentation on Dog Image
<!-- ![AugDog1](images/augmented_1_dog_example.jpg) -->

<img src="images/augmented_1_dog_example.jpg" alt="augdog1" width="300">

<img src="images/augmented_2_dog_example.jpg" alt="augdog2" width="300">

<img src="images/augmented_3_dog_example.jpg" alt="augdog3" width="300">

<img src="images/augmented_4_dog_example.jpg" alt="augdog4" width="300">

<img src="images/augmented_5_dog_example.jpg" alt="augdog5" width="300">

## Parameters
- It is important to know the task that you are trying to do while also implementing the parameters
- For example, if you are doing a color classification, it is important to understand your data and keep in mind whether to put parameters that can change the color scheme


