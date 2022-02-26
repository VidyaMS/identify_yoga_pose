## identify_yoga_pose 
  
This is a part of my learning journey in Deep learning using tensorflow.  

Very motivated by Laurence Moroney - Google AI Advocate.   
In his website , he has provided some data sets for those interested in learning image classification using Deep Learning.   
The data set used for this repo consist of images created using CGI of 5 different forms of yoga pose.  
The data set and the details can be found at https://laurencemoroney.com/2021/08/23/yogapose-dataset.html
  
### About the data :  
There are 5 different type of poses. For each type, the images differ in gender , skin tone, hair , back ground, the view angle and are in different stages/position of yoga.
There are 1000 images for training, validation and 495 images for testing.  

### Building a classifier:  
There is an attempt to build a CNN classifier from scratch . How ever found out that the accuracy obtained is very very poor at 0.5.   

### Tranfer Learning:  
Using the various pretrained models in Keras Application , feature extraction using transfer learning is attempted.  
Its seen that using the weights of VGG19 model , accuracy of 0.97 is achieved on test images. When this model is tested on other images that are downloaded from the net , the accuracy dropped to 0.73.
With fine tuning few layers of VGG19 , this accuracy increased a bit further to 0.77. 

 

