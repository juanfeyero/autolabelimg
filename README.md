# autolabelimg
Automatic annotation tool for LabelImg

# Requirements
TensorFlow 1
It can be installed in Windows with Anaconda using the following command:

conda create -n tf1 tensorflow==1.15.0

activate tf1

# Download the code from github
  
  git clone https://github.com/juanfeyero/autolabelimg
  
# To run the program
  
  python labelImg.py
  
To use your custom model ADD it into the folder object_detection/model 
and modified the number of classes on the file labelImg.py
