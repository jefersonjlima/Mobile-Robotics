

# Kinect mapping

We used the RTAB-Map (Real-Time Appearance-Based Mapping), a RGB-D SLAM approach based on a global loop closure detector with real-time constraints. 

* **Kinect for Xbox 360**
Openni and kinnect Xbox 360:

```bash
$ roslaunch openni_launch openni.launch depth_registration:=true
```
and next:
```bash
$ roslaunch rtabmap_ros rtabmap.launch rtabmap_args:="--delete_db_on_start"
```

Use this command to view the saved map:

```bash
rtabmap-databaseViewer ~/.ros/rtabmap.db
```

















# References
* http://wiki.ros.org/rtabmap_ros/Tutorials/HandHeldMapping
* https://github.com/introlab/rtabmap/wiki/Kinect-mapping
* http://wiki.ros.org/rtabmap_ros