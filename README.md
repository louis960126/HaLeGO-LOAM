# HaLeGO-LOAM












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
