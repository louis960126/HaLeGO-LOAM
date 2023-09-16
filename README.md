# HaLeGO-LOAM









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


## Cite ALeGO-LOAM
```
  inproceedings{
  author={Lee, Sheng-Wei and Hsu, Chih-Ming and Lee, Ming-Che and Fu, Yuan-Ting and Atas, Fetullah and Tsai, Augustine},
  booktitle={2019 International Automatic Control Conference (CACS)}, 
  title={Fast Point Cloud Feature Extraction for Real-time SLAM}, 
  year={2019},
  pages={1-6},
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
