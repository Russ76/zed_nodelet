# zed_nodelet

Use this custom launch file to launch the Zed nodelet from stereolabs/zed-ros-wrapper.

First compile the sample nodelet manager included here; this is needed to lauch the Zed nodelet. (Thanks to cryborg21/sample_nodelet)

The Zed nodelet allows publishing PointCloud2 data (and other image streams) from the Zed camera to your ROS nodes. The larger Zed node isn't fast enough to publish the point cloud but the nodelet can do it.


