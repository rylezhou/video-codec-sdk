# video-codec-sdk
NVIDIA Video Codec SDK provides a comprehensive set of APIs, samples, and documentation for fully hardware accelerated video encoding, decoding and transcoding on Windows and Linux platforms.


```
sudo apt-get install libglu1-mesa-dev freeglut3-dev mesa-common-dev
apt-get install libavcodec-dev libavformat-dev libglew-dev xorg openbox
sudo apt-get update
wget -qO - http://packages.lunarg.com/lunarg-signing-key-pub.asc | sudo apt-key add -
sudo wget -qO /etc/apt/sources.list.d/lunarg-vulkan-1.1.121-bionic.list http://packages.lunarg.com/vulkan/1.1.121/lunarg-vulkan-1.1.121-bionic.list
sudo apt update
sudo apt install vulkan-sdk
cmake CMakeLists.txt -DCMAKE_BUILD_TYPE=Release ..
sudo apt-get install mesa-common-dev libegl1-mesa-dev libgles2-mesa-dev
sudo apt-get install mesa-utils
make
make install
```
