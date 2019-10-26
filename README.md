## Setup
Ubuntu 18.04

  CUDA 9.2

  cuDNN 7.1.4.18

  Python 3.6

  TensorFlow 1.8
  
  Keras 2.2.4
  
  ROS2 Crystal + rosbridge

Step 1: Update and Upgrade your system:

sudo apt-get update 

sudo apt-get upgrade

Step 2: Verify You Have a CUDA-Capable GPU:

lspci | grep -i nvidia
