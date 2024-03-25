# How to use this package?

This tutorial assumes catkin_ws was not created previously on the device.

## 1. Create a catkin workspace

In your /home/student directory of WSL-ROS, create a folder catkin_ws. Inside catkin_ws, create a folder called src.

**WSL-ROS terminal:**
```
cd /home/student
mkdir catkin_ws
ls
cd catkin_ws
mkdir src
ls
cd src
```

cd - change directory, mkdir - make directory, ls - list files

## 2. Clone the github repository

**While in the src folder type:**
```
git clone https://github.com/JanUniAccount/mars_rover_pkg.git
```
## 3. Go back to catkin_ws and finish creating the workspace package
```
cd catkin_ws
catkin_make
```
## 4. Finally, source the code and launch the package

**While in the catkin_ws folder type:**
```
source ~/.bashrc
roslaunch mars_rover_pkg robot.launch
```
   
