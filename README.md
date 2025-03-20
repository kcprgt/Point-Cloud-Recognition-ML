**Object Classification in LIDAR Point Clouds**
This project focuses on developing and comparing methods based on machine learning models for object classification in point clouds from LIDAR scans. The following models are evaluated:
Random Forest
XGBoost
PointNet
PointNet++
RandLa-Net

Data
The dataset consists of four point clouds from topographic LIDAR scans of the Gdańsk area. Each point is labeled with one of the following classes:
-Never Classified
-Ground
-Low Vegetation
-Medium Vegetation
-High Vegetation
-Building
-Noise
-Water

Goal
The aim is to assess the performance of traditional machine learning models (Random Forest, XGBoost) and deep learning architectures (PointNet, PointNet++, RandLa-Net) in classifying objects in point cloud data.
