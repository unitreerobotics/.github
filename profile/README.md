# [Unitree Robotics](https://www.unitree.com)

<img src="https://oss-global-cdn.unitree.com/static/43970428169e40dc9176daadbbbb0a39_510x128.png" align="center">

Unitree Robotics is focusing on the R&D, production, and sales of consumer and industry-class high-performance general-purpose legged and humanoid robots, six-axis manipulators, and so on. We attaches great importance to independent research and development and technological innovation, fully self-researching key core robot components such as motors, reducers, controllers, LIDAR and high-performance perception and motion control algorithms, integrating the entire robotics industry chain.

[![Twitter](https://img.shields.io/badge/-Twitter-1ca0f1?style=flat&labelColor=1ca0f1&logo=twitter&logoColor=white)](https://twitter.com/UnitreeRobotics)
[![YouTube](https://img.shields.io/badge/YouTube-ff0000?style=flat&logo=youtube&logoColor=white)](https://www.youtube.com/channel/UCsMbp4V8oxzHCMdOUP-3oWw/featured)
[![Facebook](https://img.shields.io/badge/facebook-%231877F2?style=flat&labelColor=231877F2&logo=facebook&logoColor=white)](http://www.facebook.com/UnitreeRobotics)
[![Bilibili](https://img.shields.io/badge/-bilibili-ff69b4?style=flat&labelColor=ff69b4&logo=bilibili&logoColor=white)](https://space.bilibili.com/521974986)
[![Doc](https://img.shields.io/badge/Doc-FFA500?style=flat&logo=rss&logoColor=white)](https://support.unitree.com/main)
[![Email](https://img.shields.io/badge/-Email-c14438?style=flat&logo=Gmail&logoColor=white)](mailto:Laikago@unitree.cc)
<a href="https://github.com/unitreerobotics">
<img src="https://badges.strrl.dev/years/unitreerobotics?style=flat-square&logo=github">
</a>
<a href="https://github.com/unitreerobotics?tab=repositories">
<img src="https://badges.strrl.dev/repos/unitreerobotics?style=flat-square&logo=github">
</a>


<table><tbody>

<div>
    <img src="https://149753425.v2.pressablecdn.com/wp-content/uploads/2009/06/osi_symbol_100X100_0.png" width="20" height="20" style="display:inline-block; vertical-align:top;">
    <span style="display:inline-block; vertical-align:top;">Open Source Projects</span> 
</div>

<tr><td colspan="1" rowspan="4">

<table class="table table-striped table-bordered table-vcenter"/>
    <tbody>
    <tr><th> Title </th> <th>Description</th> <th>Stars</th> <th>Forks</th></tr>
    <tr>
        <td align="center" ><a href="https://github.com/unitreerobotics/unitree_ros"> unitree_ros </a></td>
        <td>  ROS simulation package. It has urdf files of all Unitree series robots, <br>contain information such as  mass, inertia, moment, limit and so on.  </td>
        <td><img alt="Stars" src="https://img.shields.io/github/stars/unitreerobotics/unitree_ros?style=flat-square"/></td>
        <td><img alt="Forks" src="https://img.shields.io/github/forks/unitreerobotics/unitree_ros?style=flat-square"/></td>
    </tr>
    <tr>
        <td align="center" ><a href="https://github.com/unitreerobotics/unitree_guide"> unitree_guide </a></td>
        <td>  An instance control algorithm by book <br>"Quadruped Robot Control Algorithm--Modeling, Control and Practice" <br>published by Unitree. It demonstrates the robot joint motor control <br>method, simple foot movements, and force control algorithm. <br>Both simulation and real robot development environments supports. </td>
        <td><img alt="Stars" src="https://img.shields.io/github/stars/unitreerobotics/unitree_guide?style=flat-square"/></td>
        <td><img alt="Forks" src="https://img.shields.io/github/forks/unitreerobotics/unitree_guide?style=flat-square"/></td>
    </tr>
    <tr>
        <td align="center" ><a href="https://github.com/unitreerobotics/unitree_rl_gym"> RL example Go2 </a></td>
        <td>  A simulation example of reinforcement learning controlling Go2 in Issac. </td>
        <td><img alt="Stars" src="https://img.shields.io/github/stars/unitreerobotics/unitree_rl_gym?style=flat-square"/></td>
        <td><img alt="Forks" src="https://img.shields.io/github/forks/unitreerobotics/unitree_rl_gym?style=flat-square"/></td>
    </tr>
    <tr>
        <td align="center" ><a href="https://github.com/unitreerobotics/unitree_rl_gym"> RL example H1 </a></td>
        <td> A simulation example of reinforcement learning controlling H1 in Issac. </sub> </td>
        <td><img alt="Stars" src="https://img.shields.io/github/stars/unitreerobotics/unitree_rl_gym?style=flat-square"/></td>
        <td><img alt="Forks" src="https://img.shields.io/github/forks/unitreerobotics/unitree_rl_gym?style=flat-square"/></td>
    </tr>
    <tr>
        <td align="center" ><a href="https://github.com/unitreerobotics/unitree_sdk2"> unitree_sdk2 </a></td>
        <td> An SDK package used to develop Go2, B2, and H1 robots in real <br>environments. Its functional positioning is similar to the <br>unitree_legged_sdk package. </td>
        <td><img alt="Stars" src="https://img.shields.io/github/stars/unitreerobotics/unitree_sdk2?style=flat-square"/></td>
        <td><img alt="Forks" src="https://img.shields.io/github/forks/unitreerobotics/unitree_sdk2?style=flat-square"/></td>
    </tr>
    <tr>
        <td align="center" ><a href="https://github.com/unitreerobotics/unitree_ros2"> unitree_ros2 </a></td>
        <td> Develop Go2 and B2 robots in the ros2 environment. <br>The interface types provided are consistent with unitree_sdk2. </td>
        <td><img alt="Stars" src="https://img.shields.io/github/stars/unitreerobotics/unitree_ros2?style=flat-square"/></td>
        <td><img alt="Forks" src="https://img.shields.io/github/forks/unitreerobotics/unitree_ros2?style=flat-square"/></td>
    </tr>
    <tr>
        <td align="center" ><a href="https://github.com/unitreerobotics/point_lio_unilidar"> point_lio_unilidar </a></td>
        <td>  This repository adapts the state-of-the-art lidar inertial odometry <br>algorithm, Point-LIO, for use Unitree 4D Lidar L1. <br>It can complete SLAM using only its piontcloud and built-in IMU. </td>
        <td><img alt="Stars" src="https://img.shields.io/github/stars/unitreerobotics/point_lio_unilidar?style=flat-square"/></td>
        <td><img alt="Forks" src="https://img.shields.io/github/forks/unitreerobotics/point_lio_unilidar?style=flat-square"/></td>
    </tr>
    </tbody>
</table>


