## SFM Install notes
This project requires:

- Ubuntu 16.04
- OpenCV3 (3.1.0 With extra contrib modules)
- PCL (1.8.1)
- Ceres solver (1.14.0)

## Clean Install
The following dependencies are required:

```
sudo apt install git
sudo apt-get update
sudo apt-get install cmake
sudo apt-get install libboost-all-dev
sudo apt-get install freeglut3-dev
sudo apt-get install doxygen
```

## OpenCV3

Followed the instructions [here](https://www.pyimagesearch.com/2016/10/24/ubuntu-16-04-how-to-install-opencv/) to install version 3.1.0

## PCL
Compile PCL 1.8.1 from source. Need to compile VTK from source too (Used VTK-7.1.1 due to OpenGL errors on parallels).
Also, ccmake required to configure the PCL installation.

## Ceres
Followed instructions [here](http://ceres-solver.org/installation.html#linux)