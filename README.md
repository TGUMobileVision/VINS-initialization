# VINS-initialization
In our method, We recover extrinsic rotation, gyroscope bias, metric scale and gravity vector. We do not estimate the velocity but
optimize the extrinsic translation parameter in visual-inertial alignment step. After getting all variables, the velocity can be obtained from the relevant equations. The accelerometer bias is not estimated in this initialization.

**The code frame is based on [**VINS-Mono**](https://github.com/HKUST-Aerial-Robotics/VINS-Mono).**

**The Related Papers**:

**Online Temporal Calibration for Monocular Visual-Inertial Systems**, Tong Qin, Shaojie Shen, IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS, 2018). [PDF](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8593603)

**VINS-Mono: A Robust and Versatile Monocular Visual-Inertial State Estimator**, Tong Qin, Peiliang Li, Zhenfei Yang, Shaojie Shen, IEEE Transactions on Robotics. [PDF](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8421746)

*We mainly modified the following files: initial_alignment.h, initial_aligment.cpp, visualization.cpp, etc.*

