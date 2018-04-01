# autonomous-rc-car

#precondition

## install opencv 2.4 and phyton 2.7
https://www.pyimagesearch.com/2015/02/23/install-opencv-and-python-on-your-raspberry-pi-2-and-b/

## install opencv 3x and phyton 3x
https://www.pyimagesearch.com/2016/10/24/ubuntu-16-04-how-to-install-opencv/

and 

https://docs.opencv.org/3.4.1/d7/d9f/tutorial_linux_install.html


##update opencv version
```bash
wget -O opencv-3.4.1.zip http://sourceforge.net/projects/opencvlibrary/files/opencv-unix/3.4.1/opencv-3.4.1.zip/download
unzip opencv-3.4.1.zip
cd opencv-3.4.1


##change / simplify build
```bash
cmake -D CMAKE_BUILD_TYPE=RELEASE -D CMAKE_INSTALL_PREFIX=/usr/local -D BUILD_NEW_PYTHON_SUPPORT=ON -D INSTALL_C_EXAMPLES=ON -D INSTALL_PYTHON_EXAMPLES=ON  -D BUILD_EXAMPLES=ON ..


cmake -D CMAKE_BUILD_TYPE=Release -D CMAKE_INSTALL_PREFIX=/usr/local ..
```
