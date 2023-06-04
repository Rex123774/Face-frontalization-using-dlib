# Face-frontalization-using-dlib
As we know most of us are using Generative Advisorial Networks(GANs) for face frontalization features. 
So to implement one gan it really needs opencv for facial alignment and when the facial alignment gets generated it go to the generator part of gans to build a simple face 
CNNs are used to generate the landmarks of an image and then it sends to the discriminator to forntalize the image 
But the problem in gans is the architecture is quite verry complex because to build a simple face is not quite an easy task 
so in order to reduce the problem there are two ways as follows
1)Pretrained model:-Nowadays people instead of implementing the whole gan they used the pretrained models because pretrained models are those models which has already been tested by the NVIDIA LABS or any research community.It is also easily available in github platforms
2)Dlib:-DLIB is primarily known for its face detection and facial landmark detection capabilities.Its is verry simple as compare to gans 
To perform face frontalization using Dlib as follows
Step1:-Download DLIB library
step2:-Install facial landmarks by using the following command
!wget   http://dlib.net/files/shape_predictor_68_face_landmarks.dat.bz2
!bunzip2 /content/shape_predictor_68_face_landmarks.dat.bz2
Step3:- use face_frontalization.ipynb to perform face frontalization
