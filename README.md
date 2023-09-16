# ROS2 Humble Hawkbill Installation Guide for Ubuntu 22.04 LTS

### What is ROS and why is it used? 

The Robot Operating System (ROS) is a set of software libraries and tools that help you build robot applications. From drivers to state-of-the-art algorithms, and with powerful developer tools, ROS has what you need for your next robotics project. And it's all open source. For over 10+ years the ROS project has produced a vast ecosystem of software for robotics by nurturing a global community of millions of developers and users who contribute to and improve that software. ROS is developed by and for that community, who will be its stewards into the future. ROS provides the tools, libraries, and capabilities that you need to develop your robotics applications, allowing you to spend more time on the work that is important for your business. Because it is open-source, you have the flexibility to decide where and how to use ROS, as well as the freedom to customize it for your needs. Moreover, ROS isn’t exclusive, you don’t need to choose between ROS or some other software stack; ROS easily integrates with your existing software to bring its tools to your problem. ROS is ready for use across a wide array of robotics applications, from indoor to outdoor, home to automotive, underwater to space, and consumer to industrial.


Before beginning the installation, it is essential to understand the specifice requirements of your project and your lab system to make decisions regarding the distribution and version of ROS to be installed for your use-case.

### Question 1: To install ROS1 or ROS2 ?

Even though ROS1 became extremely popular among the open source robotics community, it still lacked some of the most important requirements, such as real-time, safety, certification, security. Thus, came ROS2, to meet these requirements and be compatible with industrial applications.


### Question 2 : To install Which ROS distribution? 

Summary : 

Ubuntu18 -> ROS1 Melodic

Ubuntu20 -> ROS1 Noetic

Ubuntu22 -> ROS2 Humble / Iron 

Details : 
For ROS1 : ROS Noetic Ninjemys (release date: 2020) is the latest and final version of ROS1 was specifically designed to work with Ubuntu 20.04 (Focal Fossa) This final ROS1 version main’s goal is to provide Python3 support for developers/organizations who need to continue working with ROS1 for a while. It is not directly compatible with Ubuntu 22.04. and hence will lead to compatibility issues if used with Ubuntu 22.04. If it is still absolutely essential to use Noetic with Ubuntu 22.04, it can be docekerized for use. The steps for the same are outlined in this repo. However, it is important to note that Noetic on Ubuntu22 may not always work perfectly due to missing dependencies or other issues. ROS Noetic’s EOL (End of Life) is scheduled for 2025 i.e. any big code in ROS1 going beyond will need to be migrated to ROS2. 




### References : 

[1] https://www.ros.org/

[2] https://docs.ros.org/en/humble/Installation.html

[3] https://docs.ros.org/en/humble/Installation/Alternatives/Ubuntu-Development-Setup.html

[4] https://docs.ros.org/en/foxy/Releases.html

[5] https://devicetests.com/ros-noetic-compatible-ubuntu-22-04-guide#google_vignette

[6] https://roboticsbackend.com/ros1-vs-ros2-practical-overview/

[7] https://www.reddit.com/r/ROS/comments/uc6ef3/how_can_i_install_ros_in_ubuntu_2204_is_it/


