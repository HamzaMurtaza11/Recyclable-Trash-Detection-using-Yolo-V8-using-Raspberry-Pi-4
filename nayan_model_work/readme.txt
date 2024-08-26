####################################################

package installation:

run :  pip install -r requirements.txt

to install all the packages 

OR 

run : 

pip install ultralytics
pip install opencv-python-headless



#####################################################

model file :

"torch_optimized_model.pt " is the custom object detection nano yolov8 pytorch model trained on provided images for 200 epochs.

###############################################################


cv_code.py

is the detection code , after installing all the packages, run the code to start detection.


#####################################################################


NOTE : FOR RASPBIAN OS : some adjustments might to be make in code or packages because raspberry pi OS is linux based.

USE RASPBERRY PI 4 OS 64 BIT to perform code executions.


###################################################################
some issues might occur in windows or linux after all packages installation, if occur run these commands:

FOR WINDOWS
pip install -U pip
pip cache purge
pip install opencv-contrib-python

FOR LINUX:
sudo apt-get install libgtk2.0-dev and pkg-config
 