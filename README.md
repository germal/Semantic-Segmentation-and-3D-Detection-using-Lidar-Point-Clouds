# Semantic-Awareness-&-3D-Detection-using-Lidar-Point-Clouds
It's a repository which contains SOTA Algorithms list for semantic understanding of the environment using Lidar Point Clouds.

## Dataset:
1. KITTI dataset for semantic segmentation: http://www.semantic-kitti.org/
2. KITTI dataset release video: https://www.youtube.com/watch?v=3qNOXvkpK4I
3. KITTI dataset for 3D object detection: http://www.cvlibs.net/datasets/kitti/eval_object.php?obj_benchmark=3d

## Dataset Conversion Tool:
The dataset that we commonly face is a pointcloud topic inside a rosbag file. We can convert the pointcloud topic to a .pcd file and then to a .bin (kitti format) file for importing inside labeler tools in order to label the pointclouds.
1. https://github.com/leofansq/Tools_RosBag2KITTI

If one wants to do otherwise, I mean, wants to convert kitti dataset to rosbag format, you can find the way here.
1. https://github.com/tomas789/kitti2bag

## Dataset Labeling Tool:
1. https://github.com/jbehley/point_labeler
2. https://github.com/jbehley/voxelizer
3. https://github.com/bernwang/latte
4. https://github.com/unmannedlab/point_labeler
5. https://www.youtube.com/watch?v=kxtBvoitnbk

## State of the Art Approaches:
1. https://github.com/xinge008/Cylinder3D
2. https://github.com/mit-han-lab/e3d
3. https://github.com/PRBonn/lidar-bonnetal
4. https://github.com/charlesq34/pointnet
5. https://github.com/charlesq34/pointnet2
6. https://github.com/yanx27/Pointnet_Pointnet2_pytorch
7. https://github.com/qianguih/voxelnet
8. https://github.com/open-mmlab/OpenPCDet
9. https://github.com/AhmedARadwan/Super-Fast-Accurate-3D-Object-Detection
## ROS Implementation:
1. http://wiki.ros.org/semantic_point_annotator
2. https://github.com/edward0im/voxelnet_ros
3. https://github.com/AbangLZU/VoxelNetRos
4. https://github.com/AhmedARadwan/Super-Fast-Accurate-3D-Object-Detection/tree/master/ros/src/super_fast_object_detection
5. https://github.com/YonoHub/waymo_ros
