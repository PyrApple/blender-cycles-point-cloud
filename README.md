# Point-Cloud rendering in Cycles from Kinect Depth/RGB videos

* Recorded kinect2 depth/rgb videos with [libfreenect2](https://github.com/OpenKinect/libfreenect2).
* Duplivert applied on a subdivided plane (screen) parent of a small sphere (pixel)
* Sphere texture defined based on RGB video, depth serves as depth map for mesh deform modifier.
* Mesh deform applied to reproduce Kinect2 pyramid frustum
* Transparent shader applied from texture and pixel position to remove unwanted artifacts
