---
layout: archive
title: "project"
permalink: /news/
author_profile: true
redirect_from:
  - /resume
---

## [Dip-NeRF: Depth-Based Anti-Aliased Neural Radiance Fields](https://qinshihao12.github.io/Dip-NeRF/"悬停显示")
[<img  align="left" src="https://github.com/nimtecv/nimtecv.github.io/raw/master//images/333.png"   width="1000px" />](https://qinshihao12.github.io/Dip-NeRF/"悬停显示")
Neural radiation field (NeRF)-based novel view synthesis methods are gaining popularity for their ability to generate detailed and realistic images. However, most NeRF-based methods only use images to learn scene representations, ignoring the importance of depth information. The Zip-NeRF method has achieved impressive results in unbounded scenes by combining anti-aliasing techniques and mesh representations. However, the method requires a large number of input images and may perform poorly in complex scenes. Our method incorporates the advantages of Zip-NeRF and incorporates depth information to reduce the number of required images and solve the scale-free problem in borderless scenes. Experimental results show that our method effectively reduces the training time.And we can generate high-quality images and fine point cloud models using few images, even in complex scenes with numerous occlusions.


## [IPAL: Infinite Planes as Lines for Consistent Mapping in Indoor Multi-floor Environments](https://zxczhai.github.io/IPAL/) 
[<img  align="left" src="https://github.com/nimtecv/nimtecv.github.io/raw/master//images/jin.png"   width="1000px" />](https://zxczhai.github.io/IPAL/"悬停显示") 
Indoor high-precision maps are harder to obtain. Numerous researchers considered the extendibility of indoor plane features to constrain the poses and improve mapping consistency. However, the usage of parametric planar or line features requires complex modeling, and threshold-based matching methods are eager to lead to degradation. Indeed, planes can be more simply represented as line projections, with the projection direction perpendicular to the plane’s normal vector. In this paper, we proposed a novel mapping optimization framework that incorporates building outline features specifically designed for multi-story buildings. The framework consists of three main components: LiDAR Bundle Adjustment(LBA), global constraints based on building outline features, and factor graph optimization. The method extracts the ground only for horizontal correction, while the core idea is based on the assumption of vertical structure, projecting the point cloud contours of multistory buildings to the top view perspective for independent spatial pose correlation, which is a strong constraint and very effective. Finally, constraints are constructed based on keyframes and intermediate frames are refined by a factor graph. Through extensive experiments conducted on multi-story buildings, we demonstrate that our algorithm significantly enhances mapping consistency and local accuracy compared to existing methods.
