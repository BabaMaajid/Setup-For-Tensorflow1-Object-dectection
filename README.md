# Steps for setting Environment For Tensorflow(1)-Object-Detection(TFOD) 
Step 1  [Download Repo](https://github.com/tensorflow/models/tree/v1.13.0)\
Step 2  [Download Dataset and Utils](https://drive.google.com/file/d/12F5oGAuQg7qBM_267TCMt_rlorV-M7gf/view?usp=sharing)\
Step 3  [Download Repo](http://download.tensorflow.org/models/object_detection/faster_rcnn_inception_v2_coco_2018_01_28.tar.gz)\
Step 4  Creating virtual Environment using conda\
         ***conda create -n your_env_name python=3.6***\
Step 5  Activate Environment\
         ***conda activate env_name***\
Step 6  Install Dependencies\
        ***pip install pillow lxml Cython contextlib2 jupyter matplotlib pandas opencv-python tensorflow==1.14.0***\
Step 7 From Research Folder install setup.py\
       ***python setup.py install***\
Step 8 Install Conda Package Manager\
       ***conda install -c anaconda protobuf***\
Step 9 For Coversion\
       - For windows\
         - ***protoc object_detection/protos/*.proto --python_out=.***\
       - For Linux\
         - ***protoc object_detection/protos/*.proto --python_out=.***\
Step 10 open the object detection Jupyternotebook(obj_dec.py)\
# Miscellaneous
1.[Model ZOO link](https://github.com/tensorflow/models/blob/master/research/object_detection/g3doc/tf1_detection_zoo.md)\
2.[Google Colab Setup for tfod](https://c17hawke.github.io/tfod-setup/p02/)


           
