# tutorial_gazebo
Dear Students from NTU MA4890 Autonomous Driving,

Welcome to our tutorial on Gazebo! Here is the source code presented in the class. We're excited to have you as part of this tutorial and we hope you find this tutorial both informative and instructive.

As you may know, the open source software we applied is developed and maintained by a community of volunteers on Github. By using this program, you're not only benefiting from its features, but also contributing to its improvement and evolution.

Throughout this tutorial, we'll cover the basics of Gazebo Simulation, ROS and ROS Navigation, from its installation to its key features and capabilities. You'll have the opportunity to explore the program and practice with real-life examples and gain a solid understanding of its potential and how it can be leveraged for your own projects.

We encourage you to ask questions, share your feedback, and engage with your fellow students throughout this tutorial. Remember, learning is a collaborative effort, and we're all here to support each other in this journey. Please feel free to contact me (my email is provided in my slides).

We hope you enjoy this tutorial and find it valuable for your personal and professional development. As you dive into this and other lectures and tutorials of MA4890, we wish you all the best and look forward to seeing what you'll learn from this course.

Let's get started!
Ensure you have completely install [ROS Noetic](http://wiki.ros.org/noetic/Installation/Ubuntu), [Gazebo 11](https://classic.gazebosim.org/tutorials?tut=install_ubuntu), [gazebo_ros_pkgs](https://classic.gazebosim.org/tutorials?tut=ros_installing&cat=connect_ros), [ROS Control](http://wiki.ros.org/ros_control) and [ROS Navigation](https://automaticaddison.com/how-to-set-up-the-ros-navigation-stack-on-a-robot/).
1. Get to a file folder to build up your workspace
```
git clone https://github.com/ba1Sta/tutorial_gazebo.git
```
2. Get into the workspace and source setup.bash
```
cd tutorial_gazebo/
source devel/setup.bash
```
3. Open gazebo with base controller
```
roslaunch cart_description cart_description.launch
```
4. Open another terminal conduct step 2 as well and then run navigation stack by
```
roslaunch cart_description cart_nav.launch
```
