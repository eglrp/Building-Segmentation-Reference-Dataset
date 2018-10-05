# Building-Segmentation-Reference-Dataset
This is the data set used as the reference for the segmentation of LiDAR building point clouds

### Manully segmented reference

This reference dataset is produced manually. Two subsets of point clouds are selected from the experimental datasets as ground truth. The rules for manual segmentation is fixed: each segment should correspond to a semantic object of the building component. For example, a planar segment representing the northern wall of the building, the frame structure representing to one of the windows in the facade, and the curved surface standing for one of the roof facets of the building.

Furthermore, to avoid personal preferences when manually segmenting the dataset, we utilize the strategy propose in [Vo et al.](https://www.sciencedirect.com/science/article/pii/S0924271615000283), namely each reference dataset are segmented independently by persons who are familiar with point cloud segmentation work. For the reference datasets 1, there are in total 101 and 66 segments obtained for the scenes of Townsquare and St.Gallencathedral, respectively. Whereas for the reference datasets 2, there are in total 101 and 84 segments obtained for the scenes of STownsquare and St.Gallencathedral, respectively.

### Download link

Please contact [Prof. Uwe Stilla, Dr. Ludwig Hoegner, or Yusheng Xu](http://www.pf.bgu.tum.de/sta.html) for getting this dataset. 

![Illustration](/figure/Reference_BuildingSegmentation.png)

### Copyright
The datasets provided are published under the Creative Commons Attribution-NonCommercial-ShareAlike 3.0 License, which is following the license of [Semantic3D dataset](http://semantic3d.net/).

### Reference:

This reference dataset is original cropped from ETH Zurich [Semantic3D dataset](http://semantic3d.net/), and manully segmented by [Photogrammetry & Remote Sensing](http://www.pf.bgu.tum.de) of TUM.

Please refer the following publication and other necessary references of [Semantic3D dataset](http://semantic3d.net/), if this reference dataset is used in your work:

```
@article{xu2018unsupervised,
  title={Unsupervised Segmentation of Point Clouds From Buildings Using Hierarchical Clustering Based on Gestalt Principles},
  author={Xu, Yusheng and Yao, Wei and Tuttas, Sebastian and Hoegner, Ludwig and Stilla, Uwe},
  journal={IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing},
  year={2018},
  publisher={IEEE},
  doi={10.1109/JSTARS.2018.2817227}
}
```
