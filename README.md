# Face-Landmark-detection-OpenCV-and-dlib-
Face Landmark Detection using Dlib and OpenCV. So I thought of writing a bit about Computer Vision based libraries because of how much they can help us with a number of applications and I was thinking of building a computer vision based application in my coming blogs. 
Now using OpenCV we can definitely identify features of a face but if we want to identify specific features of the face, our goto library is Dlib. So Dlib is going to help us identify the essential landmarks of our face such as eyebrows, eyes , jawline etc. It basically consists of a pre-trained model and it helps us with the identification of these features.

The different points in the diagram represent the different features of the face and they are used to map out the model or project that I am trying to create. These points basically represent the outline of all the major features of the face such as the lips, eyebrows etc. For the project that I am creating, we are going to be working with the eyes. The model mainly identifies 68 different points. 
As a prerequisite, you may need to run the following commands using pip to install some libraries into your environment:<br>
`pip install cmake`<br>
`pip install dlib`<br>
`pip install cv2`<br>
In case you're wondering, cmake is a library you need to install dlib library which we are using for the model and cv2 is used as the computer vision library.

For more detailed info, check the blog out in the link: 
### https://medium.com/100daysofmlcode/day-33-of-100daysofml-9483d54a0121

# Drowsiness Detector
Use the given notebook for drowsiness detector for the same. I have basically copied most of the elements from the facial landmark detection apart from a couple of functions and the main execution code. 
I am working on a Drowsiness detector which would be able to identify whenever a user is feeling drowsy or when the distance between the tip of the eyelid and the base of the eyes decreases. I shall explain a bit more about the analogy and code in the coming lines. So the code is more or less same but we will be using an extra library called Distance from scipy. Now, the first step is to draw an outline around my eye and to identify the points which indicate the left as well as right eye.

For more detailed info, check the blog out in the link: 
### https://medium.com/100daysofmlcode/day-34-of-100daysofml-7829d324ede0
