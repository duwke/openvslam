rosparam set image_topics ["/head/left/image_raw"]
roslaunch tagslam sync_and_detect.launch bag:=/bags/darin_aruco.bag images_are_compressed:=false 