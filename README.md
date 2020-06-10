# amock_yd_cartographer

git clone https://github.com/amock82/yd_ws.git
unzip build.zip
unzip devel.zip
rm build.zip
rm devel.zip
mkdir src
unzip ydlidar_ros.zip -d src
unzip x2_cartographer.zip -d src
rm ydlidar_ros.zip
rm x2_cartographer.zip
mv CMakeLists.txt src

roslaunch carto_mapper mapG2.launch
