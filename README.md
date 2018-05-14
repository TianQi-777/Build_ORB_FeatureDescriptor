# Build_ORB_FeatureDescriptor
The purpose of this demo is to better understand the underlying implementation of ORB.

## Related theory
[Oriented FAST and rotated BRIEF (ORB)](https://en.wikipedia.org/wiki/Oriented_FAST_and_rotated_BRIEF) is a fast robust local feature detector, first presented by Ethan Rublee et al. It can be used in computer vision tasks like object recognition or 3D reconstruction. It is based on the FAST keypoint detector and the visual descriptor BRIEF (Binary Robust Independent Elementary Features). Its aim is to provide a fast and efficient alternative to SIFT.

## Additional Prerequisites for this project
Besides,to build this project, you need the followings:  

**OpenCV**  
Use [OpenCV](http://opencv.org) to process images.

**C++11 or C++0x Compiler**  
Use the some functionalities of C++11.

## Build and Run
```
cd XX/XX(include computeORB.cpp ,1.png , 2.png and CMakeLists.txt)  
mkdir build  
cd build  
cmake ..  
make -j2  
./compute_Angle
```

## Result
<div align=center>  
  
![](https://github.com/TianQi-777/Build_ORB_FeatureDescriptor/blob/master/Images/input)
</div>

<div align=center>  
  
![](https://github.com/TianQi-777/Build_ORB_FeatureDescriptor/blob/master/Images/features)
</div>

<div align=center>  
  
![](https://github.com/TianQi-777/Build_ORB_FeatureDescriptor/blob/master/Images/match)
</div>
