# zed_nodelet

Use this custom launch file to launch the Zed nodelet from github.com/stereolabs/zed-ros-wrapper.

First compile the sample nodelet manager from github.com/cryborg21/sample_nodelet and source the devil. This is also needed to lauch the Zed nodelet.

The Zed nodelet allows publishing PointCloud2 data (and other image streams) from the Zed camera to your ROS nodes. The larger Zed node isn't fast enough to publish the point cloud but the nodelet can do it.


