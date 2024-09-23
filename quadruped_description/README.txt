## Quadruped descripion

### 1. Descarga de repositorio
    ```bash
    cd quadruped_robot_ws/src
    git clone https://github.com/sergio100899/Quadruped_Project_Scandia.git 
    ```
### 2. Compilar y Configuración de entorno
    ```bash
    cd quadruped_robot_ws/src
    colcon build --symlink-install
    source /opt/ros/humble/setup.bash
    cd  quadruped_robot_ws/
    source install setup.bash
    ```
### 3. Lanzamiento 
    ```bash
    ros2 launch quadruped_description rviz_fake_joints.launch.py
    ```
    #### Output 
    
    <img src="../images/rviz.png" alt="rviz" width="200"/>  

