*Multi-Depot Traffic & Fleet Management*
========
In recent years, the adoption of autonomous mobile robot fleets has seen a significant rise, surpassing conventional conveying systems like manual maneuvers and conveyor systems. This shift is primarily due to the inherent advantages offered by autonomous mobile robots, such as enhanced flexibility, the ability to modify target positions, and consistent performance. To effectively harness the potential of such robot fleets and cater to diverse user requirements, a comprehensive software solution is essential. This software must encompass environment configuration, visualization, and motion planning capabilities, along with robust traffic management and seamless communication with individual robots. The amalgamation of these elements constitutes a convergence of logistics and robotics, yet currently, the industry lacks a commercially available software solution in this domain. Furthermore, there is a lack of standardized usage guidelines for such software. Consequently, this research endeavor focuses on developing an interconnected system that enables efficient collaboration between robots, users, and automated fleet management in real-world factory conditions. The proposed software empowers users to modify robot paths and important locations within the factory, while also facilitating goal planning for each robot. By leveraging the robot's intended targets, the software effectively devises optimal routes, supplemented by an internal traffic management system that provides commands to prevent traffic deadlock.




Credit
************
* The objective of this project is to establish seamless connectivity and coordination among users, fleet management, and traffic management for autonomous mobile robots.
* For fleet management, this project incorporates and builds upon Kimbim's MDVRP framework (source: https://github.com/kimbim/MDVRP) to ensure efficient management of the robot fleet.
* The visualization aspect of this project utilizes the Multi-Turtlesim library (source: https://github.com/tchoopojcharoen/multi_turtlesim) to provide a comprehensive visual representation.
* The interface designed for fleet and traffic management in a multi-depot scenario is fully compatible with ROS2. (Please note that usage outside of the ROS2 framework may result in limited functionality, particularly regarding the visualization aspect with the Traffic Service Server Node.)


.. toctree::
   :maxdepth: 1
   :caption: USER GUIDE


   Installation.rst
   howtouse.rst
   guild_traffic_lib.rst
   api-ref.rst
   limitations-of-system.rst
   


.. _Multi-Turtlesim: https://github.com/tchoopojcharoen/multi_turtlesim
