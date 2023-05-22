# Siga a trilha de instalação para a ultima versão do ros 1 (ROS Noetic Ninjemys) : 
comandos serão marcados por sequencia com $

primeiro lugar voce vai copiar esse comando para acessar o repositorio do ROS :

$ sudo sh -c 'echo "deb http://packages.ros.org/ros/ubuntu $(lsb_release -sc) main" > /etc/apt/sources.list.d/ros-latest.list'

Se você n tiver o "curl" indico instalalo, segue o comando : 

$ sudo apt install curl
$ curl -s https://raw.githubusercontent.com/ros/rosdistro/master/ros.asc | sudo apt-key add -

Antes de instalar verifique se esta tudo atulizado com: 

$ sudo apt update

Agora instalando o ROS 1 

$ sudo apt install ros-noetic-desktop-full

Se tudo correr como o planejado e corretamente voce deve da o sequinte comando :

$ source /opt/ros/noetic/setup.bash

Se ocorrer o erro indico acessar o sequinte link : http://wiki.ros.org/pt_BR/ROS/Tutorials/InstallingandConfiguringROSEnvironment
