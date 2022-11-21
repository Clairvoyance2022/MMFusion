# MMFusion

## Overview

A multi-modality fusion method using Lidar, Camera and Radar. The interaction and fusion of cross-modality features are performed successively in several different feature extraction stages. Sparse radar point clouds are also used to further improve the velocity estimation with little computational costs. 


## Nuscenes 3D Detetion Performance

### Val set

| method              | mAP   | NDS   |
| --------------------| ----- | ----- |
| voxel0075-single-model without TTA | 0.707 | 0.744 |

### Test set

| method              | mAP   | NDS   |
| --------------------| ----- | ----- |
| 5-voxel-sizes-ensemble with TTA  | 0.750 | 0.771 |
