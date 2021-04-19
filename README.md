# Traffic-Sign-Detection

# Problem Statement :
Nowadays, there is a lot of attention being given to the ability of self driving cars(Smart Cars). One of the many important aspects for a self driving car is the ability of detecting traffic signs to provide safety and security for the people not only inside the car, but also outside the car.

Road is full of surprises!!
The  traffic environment consists of different aspects whose main purpose is to regulate flow of traffic, make sure each driver is adhering to the rules so as to provide a safe and secure environment. But not all the drivers are equally skilled and aware of the available traffic signs, which indeed poses high chances of road mishaps as well as a disturbed and inconvenience in  traffic regulation.

# Solution : 
As a solution to the proposed problem, we designed our own model of Convolutional Neural Network (CNN) which can be integrated into the system working along hi-tech camera and sensors to provide better judgement and recognition of traffic signs. 

Our concern is to provide solution to such a problem which haven’t been acknowledged by many others. Our model will promote smooth and safe conduct of traffic with lesser traffic disturbances and road mishaps. In layman's term, our work is a contribution in uplifting the concept of already existing Self driving cars, by adding some extensions in its model. The car will alert the drivers about the nearby traffic signs and help in maintaining a healthy road presence.

In addition to all the above points, the inexperienced drivers who don’t know much about traffic signs won’t feel unconfident and will be getting guidance on the go!!

# REQUIREMENTS & Dataset :
The following Software and Hardware Requirements are the minimum requirements before starting with this project.

Software:
● Programming Language: Python 3
● Software: Google Colab, Jupyter
● Packages: Anaconda 3.5.6
● Libraries:  NumPy, Tensorflow, keras, Pandas, matplotlib, Json.

Hardware Specifications:
● Operating System: Windows 10 (64-bit)
● Hardware Requirements:
● RAM: 4GB with 4GB NVIDIA Graphics Card
● Internal Storage: >10 GB

Dataset:
The German Traffic sign Detection is provided https://www.kaggle.com/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign. The dataset consists of 39209 images and 43 classes.

# Working process :
1. Data Transformation
   . resize all the images into same size 32*32
   . Normalize all the grayscale images to [0,1]
   . Apply data augmentation to train images in all possible condition.

2. Divide training data into validation part and training part, size of validation 20%.

3. Train the model with 10 convolutional layers.There are 4 dense layers in neural network in every hidden layers have different neurons. Input layer have 1024 neurons, first  hidden layer have 512 neurons, second hidden layer have 256 neurons, third layer have 128 neurons. All hidden layers use relu activation function and output layer use softmax function to desire output.


