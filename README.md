# HaLeGO-LOAM

## HaLeGO-LOAM: A Real-Time LiDAR SLAM System that uses Homogenized Point Cloud Sampling and Adaptive Feature Extraction
- HaLeGO-LOAM is an optimized LiDAR-based SLAM system that enhances feature extraction and point representation, eliminating the need for high-precision IMU sensors.

![圖片1](https://github.com/louis960126/HaLeGO-LOAM/assets/43161306/aac7825a-cc15-4d2a-90bf-9dfa1fb60a3c)

## Embedded Real-time Lidar SLAM: 
## Sc-LeGO-LOAM (22 Sensors) + ALeGO-LOAM (2020 IEEE Intelligent Vehicles Symposium (IV))
- SC-LeGO-LOAM is a lightweight, user-friendly, and fast LiDAR SLAM system, allowing for efficient loop detection and scan context creation with just two API functions.
- ALeGO-LOAM leverages pole maps and fast point cloud feature extraction to significantly enhance vehicle localization accuracy and trajectory correction in self-driving systems.


## Features
- Homogenized Point Cloud Sampling: Ensures clearer edge and planar extraction, boosting path estimation accuracy.
- Adaptive Feature Extraction: Maintains point cloud density at vast distances and minimizes short-ranges feature sampling.

  
## Performance
- Consistently outperforms LeGO-LOAM, LiTAMIN2, and MULLS-SLAM on the KITTI dataset, offering significantly improved accuracy. In LGSVL simulations, it demonstrates 7-15% better edge position accuracy. 


## Application
- Achieving approximately 30 fps on NVIDIA Xavier, HaLeGO-LOAM stands as a viable solution for embedded applications.








- Current version: September, 2023.  






## Dependencies
- All dependencies are same as LeGO-LOAM (i.e., ROS, PCL, and GTSAM).
- C++14.


## How to use 
- Place the directory `HaLeGO-LOAM` under user catkin work space 
- For example, 
    ```
    cd ~/catkin_ws/src
    git clone https://github.com/louis960126/HaLeGO-LOAM.git
    cd ..
    catkin_make
    source devel/setup.bash
    roslaunch lego_loam run.launch
    ```

    
## Demo
![圖片2](https://github.com/louis960126/HaLeGO-LOAM/assets/43161306/1545e96e-374b-4683-8965-eaeb2ca9f5c8) ![圖片3](https://github.com/louis960126/HaLeGO-LOAM/assets/43161306/9a4aebb3-cbf3-4f6d-a861-6291caddbade)

- Dataset (Ouster 128)(Ouster 32) (Uploading)
- video (https://www.youtube.com/watch?v=UxahkPNjOMg&ab_channel=Sheng-weiLee)


## Cite ALeGO-LOAM
```
@INPROCEEDINGS{9304747,
  author={Lee, Sheng-Wei and Lin, Peng-Wei and Fu, Yuan-Ting and Hsu, Chih-Ming and Chan, Chen-Yu and Lin, Jhih-Hong and Chiang, Yen-Hung},
  booktitle={2020 IEEE Intelligent Vehicles Symposium (IV)}, 
  title={Improving vehicle localization using pole-like landmarks extracted from 3-D lidar scans}, 
  year={2020},
  pages={2052-2057},
  organization={IEEE}
}
```
## Cite SC-LeGO-LOAM
```
@INPROCEEDINGS { gkim-2018-iros,
  author = {Kim, Giseop and Kim, Ayoung},
  title = { Scan Context: Egocentric Spatial Descriptor for Place Recognition within {3D} Point Cloud Map },
  booktitle = { Proceedings of the IEEE/RSJ International Conference on Intelligent Robots and Systems },
  year = { 2018 },
  month = { Oct. },
  address = { Madrid }
}
```
and 
```
@inproceedings{legoloam2018,
  title={LeGO-LOAM: Lightweight and Ground-Optimized Lidar Odometry and Mapping on Variable Terrain},
  author={Shan, Tixiao and Englot, Brendan},
  booktitle={IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)},
  pages={4758-4765},
  year={2018},
  organization={IEEE}
}
```
## Contact 
- Maintainer: Sheng-Wei Lee (`louis960126@gmail.com`)

## NOTE
- Code is currently being organized and will be continuously uploaded.
