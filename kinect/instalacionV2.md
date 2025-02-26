# kinect versión 2

Para instalar drivers de KinectV1 en Mac: 

https://github.com/OpenKinect/libfreenect2

Primer paso: Instalar [Homebrew](https://brew.sh/)

Instalar git con brew 

`brew update`

`brew install git`

`brew install libusb`

`brew install glfw3`

`git clone https://github.com/OpenKinect/libfreenect2.git`

`cd libfreenect2`

`mkdir build && cd build`

`cmake ..`

`make`

`make install`