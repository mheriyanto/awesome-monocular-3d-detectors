# awesome-monocular-3d-detectors
A curated list of dedicated resources to research 3D monocular object detection. Mostly resources is cloned from *Review of Monocular 3D Object Detection* by [**@patrick-llgc**](https://github.com/patrick-llgc/Learning-Deep-Learning/blob/master/paper_notes/review_mono_3dod.md), *Awesome Monocular 3D Detection* by [**@BigTeacher-777**](https://github.com/BigTeacher-777/Awesome-Monocular-3D-detection) and [Google Scholar's index](https://scholar.google.com/scholar?as_vis=1&q=%22monocular+3d%22++detection&hl=en&scisbd=1&as_sdt=0,5). 

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/mheriyanto/awesome-monocular-3d-detectors/issues)
![GitHub contributors](https://img.shields.io/github/contributors/mheriyanto/awesome-monocular-3d-detectors.svg)
[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fmheriyanto%2Fawesome-monocular-3d-detectors&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=hits&edge_flat=false)](https://hits.seeyoufarm.com)

_Update Notes_
- 04/18/2021: delete some columns from [original repository](https://github.com/patrick-llgc/Learning-Deep-Learning/blob/master/paper_notes/review_mono_3dod.md) and add some metrics from KITTI & nuScenes dataset.

| **Nama** | Time (Vanue)  | **KITTI (Moderate)** | **nuScenes (mAP)** | Predecessor | Backbone | **Runtime** | Environtment |
| --- | ---  | --- | --- | --- | --- | --- | --- |
| [**Kinematic3D**](https://arxiv.org/abs/2007.09548) | 2007 | **12.72** | --- | --- | --- | [0.12 s](http://cvlab.cse.msu.edu/project-kinematic.html) | 1 core @ 1.5 Ghz (C/C++) |
| [**SMOKE**](https://arxiv.org/abs/2002.10111v1) | 2002  | **9.76** | --- | --- | --- | [0.03 s](https://github.com/lzccccc/SMOKE) | GPU @ 2.5 Ghz (Python) |
| [**M3D-RPN**](https://arxiv.org/abs/1907.06038) | 1907 (ICCV 2019) | **9.71** | --- | --- | Faster RCNN | [0.16 s](http://cvlab.cse.msu.edu/project-m3d-rpn.html) | GPU @ 1.5 Ghz (Python) |
| [**Center3D**](https://arxiv.org/abs/2005.13423) | 2005  | **9.31** | --- | --- | --- | 0.05 s | GPU @ 3.5 Ghz (Python) |
| [**SS3D**](https://arxiv.org/abs/1906.08070) | 1906 | **7.68** | --- | --- | U-Net like arch | 48 ms | Tesla V100 (Python) |
| [**D4LCN**](https://arxiv.org/abs/1912.04799) | 1912 | **3.42** | --- | --- | --- | [0.2 s](https://github.com/dingmyu/D4LCN) | GPU @ 2.5 Ghz (Python + C/C++) |
| [**Deep3DBox**](https://arxiv.org/abs/1612.00496) | 1612 (CVPR 2017) | --- | --- | Deep3DBox | MS-CNN | --- | --- |
| [**Mono3D**](https://www.cs.toronto.edu/~urtasun/publications/chen_etal_cvpr16.pdf) | 1512 (CVPR 2016) | --- | --- | Mono3D | Faster RCNN | --- | --- |
| [**CenterNet**](https://arxiv.org/abs/1904.07850) | 1904 | --- | 0.338 | CenterNet | DLA (Unet) | --- | --- |
| [**MonoDIS**](https://arxiv.org/abs/1905.12365) | 1905 (ICCV 2019) | --- | 0.304 | MonoGRNet | RetinaNet+2D/3D head | --- | --- |

## References
<ins>**Awesome repository**</ins>
+ 2019-11-26 [Review of Monocular 3D Object Detection](https://github.com/patrick-llgc/Learning-Deep-Learning/blob/master/paper_notes/review_mono_3dod.md): [towarddatascience](https://towardsdatascience.com/monocular-3d-object-detection-in-autonomous-driving-2476a3c7f57e?source=friends_link&sk=160d236be1881b6ee1b431a943666fdb) and google [spreadsheet](https://docs.google.com/spreadsheets/d/1X_ViM-W4QbHPbJ2dHouRgkRAyzEnBS6J_9VxPEXvDM4/edit#gid=0).
+ Awesome Monocular 3D detection by Zhikang Zou [@BigTeacher-777](https://github.com/BigTeacher-777/Awesome-Monocular-3D-detection)

<ins>**Dataset**</ins>
+ KITTI Dataset Leaderboard: [Official](http://www.cvlibs.net/datasets/kitti/eval_object.php?obj_benchmark=3d) | [PaperwithCode](https://paperswithcode.com/sota/3d-object-detection-on-kitti-cars-moderate)
+ nuScenes Dataset Leaderboard: [Official](https://www.nuscenes.org/object-detection?externalData=all&mapData=all&modalities=Camera) | [PaperwithCode](https://paperswithcode.com/sota/3d-object-detection-on-nuscenes) 

<ins>**Conferences for Image Processing & Computer Vision**</ins>: [guide2research.com](http://www.guide2research.com/topconf/computer-vision) | [openaccess.thecvf.com](https://openaccess.thecvf.com/menu)
+ **CVPR**: IEEE/CVF Conference on Computer Vision and Pattern Recognition: http://cvpr2021.thecvf.com/
+ **ICCV**: IEEE/CVF International Conference on Computer Vision: http://iccv2021.thecvf.com/home
+ **ECCV**: European Conference on Computer Vision: https://eccv2020.eu/
+ **WACV**: Workshop on Applications of Computer Vision: http://wacv2021.thecvf.com/home 
+ **3DV**: International Conference on 3D Vision: http://3dv2020.dgcv.nii.ac.jp/index.html
