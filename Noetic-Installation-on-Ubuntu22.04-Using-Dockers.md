## ROS1 Noetic Installation on Ubuntu22.04 Using Dockers 
ROS Noetic Ninjemys, the latest and final version of ROS1 was specifically designed to work with Ubuntu 20.04 (Focal Fossa) It is not directly compatible with Ubuntu 22.04. and hence will lead to compatibility issues if used with Ubuntu 22.04. If it is still absolutely essential to use Noetic with Ubuntu 22.04, it can be docekerized for use. The steps for the same are outlined in this repo. However, it is important to note that Noetic on Ubuntu22 may not always work perfectly due to missing dependencies or other issues.

Using Dockers, ROS1 Noetic can be containerized and then used with Ubuntu22.04.

The following commands to be run on the Ubuntu terminal : 
Step 1 : Install Dockers on Ubuntu22.04 :
```
sudo apt-get install docker-ce docker-ce-cli containerd.io 
```

Step 2 : Pull the ROS Noetic Docker image :
```
docker pull ros:noetic
```

Step 3 : Start a new Docker container running ROS Noetic i.e. start a new Docker container and open a bash shell inside :
```
docker run -it ros:noetic /bin/bash
```

ROS1 Noetic is ready for use on Ubuntu22.04. 

