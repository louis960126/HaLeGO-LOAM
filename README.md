# HaLeGO-LOAM

## HaLeGO-LOAM: A Real-Time LiDAR SLAM System that uses Homogenized Point Cloud Sampling and Adaptive Feature Extraction
- HaLeGO-LOAM is an optimized LiDAR-based SLAM system that enhances feature extraction and point representation, eliminating the need for high-precision IMU sensors.
![圖片1](https://github.com/louis960126/HaLeGO-LOAM/assets/43161306/aac7825a-cc15-4d2a-90bf-9dfa1fb60a3c)

## Features
- Homogenized Point Cloud Sampling: Ensures clearer edge and planar extraction, boosting path estimation accuracy.

- Adaptive Feature Extraction: Maintains point cloud density at vast distances and minimizes short-ranges feature sampling.

## Performance
- Consistently outperforms LeGO-LOAM, LiTAMIN2, and MULLS-SLAM on the KITTI dataset, offering significantly improved accuracy. In LGSVL simulations, it demonstrates 7-15% better edge position accuracy. 

## Application
- Achieving approximately 30 fps on NVIDIA Xavier, HaLeGO-LOAM stands as a viable solution for embedded applications.


## Embedded Real-time Lidar SLAM: Sc-LeGO-LOAM (22 Sensors) + ALeGO-LOAM (2020 IEEE Intelligent Vehicles Symposium (IV))






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
- Dataset (Ouster 128)(Ouster 32) (Uploading)


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
