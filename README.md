# CUC
Detecting major changes and anomalies in a real time CCTV frame.

# Yolo algorithm is used for the real time detection.

# Project description:

Most of the time CCTVs are used at post-event for the verification of any incident. This project will equip CCTV as a pre-event tool. This project is to avoid any unwanted event by creating a pre-event warning whenever there are anomalies in the CCTV frame.

Download the weight from here.
https://pjreddie.com/media/files/yolov3.weights

The algo is written for webcam you can also upload it on your CCTV.

# Steps to run the program
1) Install the following packages on your system by using given commands in bracket.

      a) OPENCV     (pip install opencv-python)
      
      b) Numpy      (pip install numpy)
      
      c) Playsound  (pip install playsound)
      
      d) Datetime   (pip install datetime)
     
2) Clone the directory on your system by using command : git clone https://github.com/sanjulsharma/CUC-CCTV-Under-Check.git

3) Download the weight from the given link (https://pjreddie.com/media/files/yolov3.weights) and place it in cloned floder of the repository.

4) Open security++.py and run it.

# Note:
 You can adjust list of anomalies as per your convenience by changing the the list from "anomalies" file. This model can only detect 80 classes which are enlisted in "classes to detect" file.
 
# Now your security system is never OFF duty.
