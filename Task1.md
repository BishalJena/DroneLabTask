### **Task 1: Waypoint Navigation with Gazebo Simulator**

#### **Task Overview**
Participants are required to design and implement a program that enables a drone to autonomously follow a sequence of GPS waypoints in the Gazebo simulator. The drone will navigate through a virtual environment, moving from one waypoint to the next.

The goal of this task is to introduce participants to key concepts in drone flight autonomy, such as GPS waypoint navigation and path planning, while using ROS (Robot Operating System) to interface with the Gazebo simulator.

#### **Task Objectives**
1. **Autonomous Navigation**: The drone must fly from a starting position to a series of pre-defined GPS waypoints.
2. **Efficient Path Planning**: Participants should design algorithms that optimize the path between waypoints, reducing travel time and ensuring smooth transitions.
3. **Integration with ROS**: The solution should be implemented using ROS, leveraging its packages for controlling the drone and handling GPS inputs.

#### **Drone Capabilities**
- **Sensors**: GPS and IMU (for stabilization).
- **Control Interface**: Participants will use ROS to send control commands (throttle, pitch, yaw, etc.) to the drone.
- **Simulation Environment**: Gazebo will be used to simulate the flight. A map with defined waypoints can be pre-configured for the simulation.

#### **Task Deliverables**
1. **Code**: The complete ROS package for the drone navigation system.
2. **Simulation Setup**: The Gazebo world file with waypoints clearly marked.
3. **Video Recording**: A short video demonstrating the drone navigating through the waypoints.
4. **Documentation**: A brief document explaining the strategy used for path planning, along with instructions to set up and run the simulation.

---

### **Resources for Participants**

To succeed in this task, participants need a strong grasp of key concepts such as ROS, drone control, waypoint navigation, and Gazebo simulator functionalities. Below are some carefully selected resources to help participants gain the necessary knowledge and skills.

#### **1. ROS (Robot Operating System) Basics**
Understanding ROS is crucial for this task since it will be the primary framework used to control the drone and interface with the Gazebo simulator.

- **Official ROS Tutorials**: Beginner Level Tutorials
  - These cover the essentials of ROS, including setting up ROS nodes, publishing and subscribing to topics, and creating packages.  
  (http://wiki.ros.org/ROS/Tutorials)
  
- **ROS Navigation Stack**: ROS Navigation Stack
  - This is the key component for handling navigation, especially for controlling the movement of the drone in the simulation and integrating GPS inputs.  
  (http://wiki.ros.org/navigation)

#### **2. Waypoint Navigation and Path Planning**
Participants need to understand the theory and implementation of waypoint navigation and path planning.

- **Waypoint Navigation Overview**: Waypoint Navigation Explained
  - Provides a high-level understanding of how waypoint navigation works, including setting goals and transitioning between waypoints.  
  (https://madhur.ca/2011/02/12/waypointnav.html)

- **ROS for Path Planning**: Path Planning in ROS
  - A useful introduction to implementing path planning in ROS, focusing on how to make the drone move efficiently between waypoints.  
  (https://www.theconstructsim.com/path-planning-with-ros/)

#### **3. Gazebo Simulator**
Participants should be familiar with Gazebo to set up the simulation environment and interact with it.

- **Gazebo Tutorials**: Gazebo Simulation Tutorials
  - Official tutorials that teach how to use Gazebo for simulating environments, adding drones, and configuring waypoints.  
  (http://gazebosim.org/tutorials)

- **Gazebo-ROS Integration**: Integrating Gazebo with ROS
  - This tutorial shows how to link ROS to the Gazebo simulator to send and receive commands to/from the drone.  
  (https://classic.gazebosim.org/tutorials?tut=ros_overview)

#### **4. Drone Control and Simulation**
Participants need to learn how to control drones in simulation environments.

- **PX4 Autopilot with Gazebo**: PX4-Gazebo Simulation
  - This tutorial explains how to simulate drones with PX4 autopilot in Gazebo and is a good resource for controlling drones via waypoints.  
  (https://dev.px4.io/v1.9.0/en/simulation/gazebo.html)

---

### **Additional Tools and Resources**
1. **Gazebo Plugins for Drones**: Gazebo Model Plugins  
   (http://gazebosim.org/tutorials?tut=plugins)  
   This will help participants understand how to enhance the drone's capabilities using plugins.
   
2. **MAVROS (MAVLink for ROS)**: MAVROS Documentation  
   (http://wiki.ros.org/mavros)  
   A ROS package to communicate with autopilot flight stacks using MAVLink, useful for drone control in Gazebo.

3. **ROS Noetic + Gazebo Setup**: How to Install ROS Noetic and Gazebo  
   (https://www.theconstructsim.com/install-ros-noetic/)  
   Instructions to set up ROS Noetic and Gazebo on a system, ensuring participants have the right environment for the simulation.

---

### **Evaluation Criteria**
- **Successful Waypoint Navigation**: The drone reaches all waypoints without getting stuck or deviating significantly from the path.
- **Path Optimization**: The drone follows an efficient path, minimizing travel time and ensuring smooth transitions.
- **Code Efficiency**: Well-structured, readable, and efficient code with clear documentation.
- **Innovation**: Creative approaches to improving navigation efficiency.
- **Simulation Demonstration Video**: A clear video showing the drone's navigation performance.

---

### **Grading Criterion**

Participants will be graded on a total of 100 points, divided as follows:

1. **Autonomous Waypoint Navigation (30 points)**  
   - 30 points: The drone successfully reaches all waypoints in the correct order.
   - 20 points: The drone reaches 80-99% of the waypoints.
   - 10 points: The drone reaches fewer than 80% of the waypoints.
   - 0 points: The drone does not follow the waypoint sequence.

2. **Path Planning and Optimization (30 points)**  
   - 30 points: The path is highly optimized, minimizing travel time and ensuring smooth transitions.
   - 20 points: The path is moderately optimized but could be smoother.
   - 10 points: The path is inefficient, with notable detours or sharp turns.
   - 0 points: No visible path optimization.

3. **ROS Integration (20 points)**  
   - 20 points: Full integration with ROS, utilizing relevant packages effectively.
   - 15 points: ROS is used effectively, but some aspects could be improved.
   - 10 points: Basic ROS integration, but key functionalities are missing.
   - 0 points: No significant ROS integration.

4. **Code Quality and Documentation (10 points)**  
   - 10 points: Well-structured code, fully documented with clear instructions.
   - 7 points: Mostly readable code with some comments, and minimal documentation.
   - 5 points: Functional but poorly structured code with insufficient comments.
   - 0 points: No clear structure or documentation.

5. **Simulation Demonstration Video (10 points)**  
   - 10 points: Clear video showing successful waypoint navigation.
   - 7 points: Video showing moderate success, with minor issues in navigation.
   - 5 points: Video showing significant navigation issues.
   - 0 points: No video provided or the video does not show relevant aspects.

---

### **Total Points Breakdown**
| Criteria                        | Points |
|----------------------------------|--------|
| Autonomous Waypoint Navigation   | 30     |
| Path Planning and Optimization   | 30     |
| ROS Integration                  | 20     |
| Code Quality and Documentation   | 10     |
| Simulation Demonstration Video   | 10     |
| **Total**                        | 100    |




### **Bonus Task: Autonomous Obstacle Avoidance in Gazebo Simulator**

#### **Task Overview**
In this bonus task, participants are required to develop and implement an autonomous obstacle avoidance system for a drone using the Gazebo simulator and ROS. The drone must navigate through an environment filled with static and dynamic obstacles, avoiding collisions while following a predefined path. This task is designed to test the participants' understanding of sensor fusion, real-time decision-making, and dynamic path planning.

Participants are expected to make use of sensor data (such as LIDAR and camera feeds) and apply algorithms to help the drone autonomously avoid obstacles while maintaining a smooth flight path.

#### **Task Objectives**
1. **Obstacle Detection**: The drone must be able to detect both static and dynamic obstacles using sensors such as LIDAR, camera, or ultrasonic sensors.
2. **Autonomous Obstacle Avoidance**: The drone must avoid obstacles in real time without any manual intervention, using path planning and decision-making algorithms.
3. **Path Replanning**: In case the current path is blocked, the drone must dynamically replan the path to continue moving towards its goal.
4. **Smooth Flight**: The drone should not make abrupt maneuvers that could destabilize the flight or lead to erratic behavior.
5. **Integration with ROS**: The solution must be implemented using ROS, utilizing its existing sensor packages, control systems, and messaging infrastructure.

---

### **Drone Capabilities**
- **Sensors**:
  - **LIDAR**: For obstacle detection and distance measurement.
  - **RGB Camera**: For visual detection of obstacles and dynamic objects.
  - **IMU**: For stability and orientation control.
  - **Ultrasonic Sensors** (optional): For short-range obstacle detection.

- **Control Interface**: Participants will control the drone using ROS, which will handle throttle, pitch, roll, and yaw commands.
  
- **Simulation Environment**: The Gazebo simulator will provide an environment populated with both static obstacles (walls, buildings) and dynamic obstacles (moving objects like cars or other drones).

---

### **Task Deliverables**
1. **ROS Package**: Complete ROS package for autonomous obstacle avoidance, including all relevant nodes for sensor processing, decision-making, and control.
2. **Gazebo World File**: A pre-configured Gazebo world with static and dynamic obstacles.
3. **Video Demonstration**: A video showing the drone autonomously avoiding obstacles while following a set path.
4. **Documentation**: A document detailing the algorithms used for obstacle detection, avoidance, and path replanning. It should also include installation and setup instructions for running the simulation.
5. **Evaluation Script**: An optional Python script to evaluate the distance maintained from obstacles, flight smoothness, and efficiency of avoidance.

---

### **Evaluation and Grading Criteria**

The evaluation of this task will be based on the following key criteria:

1. **Obstacle Detection** (20 points)
   - The drone should be able to detect static and dynamic obstacles accurately.
   - Grading:
     - **20 points**: Detects all obstacles within range with minimal latency.
     - **15 points**: Detects most obstacles but with slight inaccuracies or delay.
     - **10 points**: Misses some obstacles or has significant delay in detection.
     - **5 points**: Poor detection with frequent failures.

2. **Obstacle Avoidance** (30 points)
   - The drone should autonomously avoid detected obstacles without requiring manual intervention.
   - Grading:
     - **30 points**: Successfully avoids all obstacles with smooth and planned maneuvers.
     - **20 points**: Avoids most obstacles but has some jerky movements or inefficient avoidance strategies.
     - **10 points**: Frequent near-collisions, unstable maneuvers during avoidance.
     - **5 points**: Poor avoidance, resulting in collisions or frequent stoppages.

3. **Path Replanning** (20 points)
   - The drone must dynamically replan its path if the current one is blocked by an obstacle.
   - Grading:
     - **20 points**: Smooth and efficient path replanning with no stalling.
     - **15 points**: Occasional delays in replanning, but overall successful in rerouting.
     - **10 points**: Frequent delays or inefficient replanning strategies.
     - **5 points**: Path replanning frequently fails, causing the drone to stop or take excessive time to adjust.

4. **Flight Stability and Smoothness** (10 points)
   - The drone must maintain a stable flight, avoiding abrupt maneuvers.
   - Grading:
     - **10 points**: Flight is smooth, with gradual turns and accelerations.
     - **7 points**: Minor jerky movements but overall flight is stable.
     - **4 points**: Several abrupt movements, resulting in an unsteady flight.
     - **1 point**: Extremely jerky and unstable flight, with frequent abrupt stops or erratic behavior.

5. **Code Quality and Efficiency** (10 points)
   - The solution must be well-organized, documented, and efficient in terms of performance.
   - Grading:
     - **10 points**: Code is clean, efficient, modular, and well-documented.
     - **7 points**: Code is functional and mostly efficient but could be better organized.
     - **4 points**: Code works but has major inefficiencies or lacks documentation.
     - **1 point**: Code is poorly written, inefficient, or missing key components.

6. **Innovation and Creativity** (10 points)
   - Bonus points for creative or innovative approaches to solving the problem.
   - Grading:
     - **10 points**: Implements novel solutions or creative improvements that enhance the system's performance.
     - **5 points**: Some creative elements, but not fully realized or impactful.
     - **0 points**: No significant innovation beyond the basic task requirements.

---

### **Resources for Participants**

To complete this bonus task, participants will need a deeper understanding of ROS, obstacle avoidance algorithms, and sensor data processing. Below are some useful resources:

1. **ROS Tutorials for Sensor Integration**
   - **LIDAR with ROS**: A detailed guide on integrating LIDAR with ROS, essential for obstacle detection.
     (https://automaticaddison.com/how-to-use-a-lidar-with-ros-noetic/)

   - **RGB Camera Integration**: Guide on integrating and using a camera with ROS.
     (http://wiki.ros.org/camera_drivers)

2. **Obstacle Avoidance Algorithms**
   - **Dynamic Window Approach (DWA)**: This algorithm is commonly used for real-time collision avoidance.
     (https://www.ros.org/news/2016/01/dynamic-window-approach.html)

   - **Potential Fields Method**: A simple but effective technique for obstacle avoidance.
     (http://planning.cs.uiuc.edu/node62.html)

3. **Gazebo Simulation Setup**
   - **Creating Complex Environments in Gazebo**: Instructions for setting up complex worlds in Gazebo with obstacles.
     (http://gazebosim.org/tutorials?tut=building_world)

   - **Gazebo-ROS Integration**: Learn how to link ROS to Gazebo for real-time simulation.
     (http://gazebosim.org/tutorials?tut=ros_overview)

4. **Path Replanning Strategies**
   - **Real-Time Path Replanning in ROS**: A guide to implementing path replanning when obstacles block the original path.
     (https://www.theconstructsim.com/path-planning-replanning-with-ros/)

---

### **Challenge and Learning Outcomes**

This bonus task challenges participants to build more sophisticated systems for real-time decision-making and obstacle avoidance, which are critical in autonomous drone applications. By completing this task, participants will gain:
- Experience in sensor fusion, using multiple data sources (LIDAR, camera, etc.) to make decisions.
- Skills in dynamic path planning, which is crucial for real-world autonomous systems.
- A deeper understanding of the Gazebo simulator and ROS framework for more complex simulations.
