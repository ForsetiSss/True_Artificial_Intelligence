sudo apt-get install ros-kinetic-openni-* ros-kinetic-openni2-* ros-kinetic-freenect-*


roslaunch openni_launch openni.launch 
roslaunch freenect_launch freenect.launch


rosrun rqt_image_view rqt_image_view 
