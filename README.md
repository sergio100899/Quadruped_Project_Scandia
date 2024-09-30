# Quadruped_Project_Scandia
## Quadruped Robot

## Índice

1. [Descripcion de paquetes](./doc/packages_doc.md)
2. [Instalacion ROS2](./doc/install_ros.md)
3. [Quadruped descripion](quadruped_description/README.md)
3. [Quadruped gazebo](quadruped_gazebo/README.md)



1. ### Creación de espacio de trabajo
```bash
    cd ~
    mkdir -p quadruped_robot_ws/src
```
2. ### Descarga de repositorio
```bash
cd quadruped_robot_ws/src
git clone https://github.com/sergio100899/Quadruped_Project_Scandia.git 
```
3. ### Compilación de espacio de trabajo

```bash
cd ~/quadruped_robot_ws
source /opt/ros/humble/setup.bash 
colcon build --symlink-install
source install/setup.bash
```
