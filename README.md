# Awesome Human Pose Estimation

<div align="center">

  ![parkour](https://user-images.githubusercontent.com/38063309/124941540-d40e3c00-e045-11eb-99b8-c06b706e6218.gif)

  ![image](https://user-images.githubusercontent.com/38063309/124938890-a1634400-e043-11eb-8196-e588d25f0284.png)

  
</div>

  A collection of resources on human pose related problem: mainly focus on 2D/3D human pose estimation, and will include action recognition, Transformer, mesh representation, flow calculation, (inverse) kinematics, affordance, robotics or sequence learning.
  
  
## Why awesome human pose estimation?
This is a collection of papers and resources I curated when learning the ropes in Human Pose estimation. And This is a fork from https://github.com/wangzheallen/awesome-human-pose-estimation (thanks for wangzheallen) and customized for personal study and sharing. I will be continuously updating this list with the latest papers and resources.

## Contributing
If you think I have missed out on something (or) have any suggestions (papers, implementations and other resources), feel free to [pull a request](./pulls)

Feedback and contributions are welcome!

## Table of Contents
- [Basics](#Basics)
- [Papers](#Papers)
  - [2D Pose Estimation](#2D-Pose-Estimation)
  - [3D Pose Estimation](#3D-Pose-Estimation)
  - [Action Recognition](#Action-Recognition)
  - [Geometry](#Geometry)
- [Datasets](#Datasets)
- [Benchmarks](#Benchmarks)

## Basics
- [pose_related_human_knowledge](https://nanonets.com/blog/human-pose-estimation-2d-guide/)

## Papers
### 2D Pose Estimation
- [Learning Human Pose Estimation Features with Convolutional Networks](https://arxiv.org/pdf/1312.7302.pdf) - Jain, A., Tompson, J., Andriluka, M., Taylor, G.W., & Bregler, C. (ICLR 2013)
- [DeepPose: Human Pose Estimation via Deep Neural Networks](https://arxiv.org/pdf/1312.4659.pdf) - Toshev, A., & Szegedy, C. (CVPR 2014)
- [MoDeep: A Deep Learning Framework Using Motion Features for Human Pose Estimation](https://arxiv.org/pdf/1409.7963.pdf) - Jain, A., Tompson, J., LeCun, Y., & Bregler, C. (ACCV 2014)
- [Efficient Object Localization Using Convolutional Networks](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.858.5872&rep=rep1&type=pdf) - Tompson, J., Goroshin, R., Jain, A., LeCun, Y., & Bregler, C (CVPR 2015)
- [Stacked Hourglass Networks for Human Pose Estimation](https://arxiv.org/pdf/1603.06937.pdf) - [[CODE]](https://github.com/umich-vl/pose-hg-demo) - Newell, A., Yang, K., & Deng, J. (ECCV 2016)
- [Realtime Multi-person 2D Pose Estimation Using Part Affinity Fields](https://arxiv.org/pdf/1611.08050.pdf) - [[CODE]](https://github.com/ZheC/Realtime_Multi-Person_Pose_Estimation) - Cao, Z., Simon, T., Wei, S., & Sheikh, Y. (CVPR 2017)
- [RMPE: Regional Multi-person Pose Estimation](https://arxiv.org/pdf/1612.00137.pdf) - [[CODE1]](https://github.com/Fang-Haoshu/RMPE)[[CODE2]](https://github.com/MVIG-SJTU/AlphaPose) - Fang, H., Xie, S., & Lu, C. (ICCV 2017)
- [Multi-context Attention for Human Pose Estimation](https://arxiv.org/pdf/1702.07432.pdf) - [[CODE]](https://github.com/bearpaw/pose-attention) - Chu, X., Yang, W., Ouyang, W., Ma, C., Yuille, A.L., & Wang, X. (CVPR 2017)
- [Simple Baselines for Human Pose Estimation
and Tracking](http://openaccess.thecvf.com/content_ECCV_2018/papers/Bin_Xiao_Simple_Baselines_for_ECCV_2018_paper.pdf) - [[CODE]](https://github.com/Microsoft/human-pose-estimation.pytorch) - Bin, Xiao, Haiping Wu, Yichen Wei (ECCV 2018)
- [Rethinking on Multi-Stage Networks for Human Pose Estimation](https://arxiv.org/pdf/1901.00148.pdf)  - Wenbo Li, Zhicheng Wang, Binyi Yin, Qixiang Peng, Yuming Du, Tianzi Xiao, Gang Yu,Hongtao Lu, Yichen Wei, and Jian Sun (Arxiv 2018)
- [CrowdPose: Efficient Crowded Scenes Pose Estimation and A New Benchmark](https://arxiv.org/abs/1812.00324) - [[CODE]](https://github.com/Jeff-sjtu/CrowdPose) - Jiefeng Li, Can Wang, Hao Zhu, Yihuan Mao, Hao-Shu Fang, Cewu Lu (CVPR 2019)
- [Deep High-Resolution Representation Learning for Human Pose Estimation](https://arxiv.org/abs/1902.09212) - [[CODE]](https://github.com/leoxiaobin/deep-high-resolution-net.pytorch) - [[CODE2]](https://github.com/stefanopini/simple-HRNet) - Ke Sun, Bin Xiao, Dong Liu, Jingdong Wang (CVPR 2019)
- [PoseFix: Model-agnostic General Human Pose Refinement Network](https://arxiv.org/abs/1812.03595)  - [[CODE]](https://github.com/mks0601/PoseFix_RELEASE) - Moon, Gyeongsik and Chang, Juyong and Lee, Kyoung Mu (CVPR 2019)
- [Fast Human Pose Estimation](https://arxiv.org/abs/1811.05419) - [[CODE]](https://github.com/yuanyuanli85/Fast_Human_Pose_Estimation_Pytorch) - Feng Zhang, Xiatian Zhu, Mao Ye (CVPR 2019)
- [Falls Prediction Based on Body Keypoints and Seq2Seq Architecture](https://arxiv.org/abs/1908.00275)  - Minjie Hua, Yibing Nan, Shiguo Lian (Arxiv 2019)
- [The Devil is in the Details: Delving into Unbiased Data Processing for Human Pose Estimation](https://arxiv.org/abs/1911.07524)   - Junjie Huang, Zheng Zhu, Feng Guo, Guan Huang (Arxiv 2019)
- [The Devil is in the Details: Delving into Unbiased Data Processing for Human Pose Estimation](https://arxiv.org/abs/1911.07524)  - Junjie Huang, Zheng Zhu, Feng Guo, Guan Huang (ICCV 2019)
- [Context-Guided Adaptive Network for Efficient Human Pose Estimation](https://ojs.aaai.org/index.php/AAAI/article/view/16463) - Zhao, L., Wen, J., Wang, P., & Zheng, N. (AAAI 2021)

### 3D Pose Estimation
- [Reconstruction of Articulated Objects from Point Correspondences in a Single Uncalibrated Image](https://pdfs.semanticscholar.org/4034/943de699dd4d672d3d59b408459168785e9c.pdf) - CJ Taylor. (CVIU 2000)
- [Covariance-Scaled Sampling for Monocular 3D Body Tracking](http://www.maths.lth.se/sminchisescu/media/papers/css_cvpr01.pdf) - Cristian Sminchisescu and Bill Triggs. (CVPR 2001)
- [Improving the Scope of Deformable Model Shape and Motion Estimation](http://www.maths.lth.se/sminchisescu/media/papers/deform_cvpr01.pdf) - C. Sminchisescu and D. Metaxas and S. Dickinson. (CVPR 2001)
- [Recovering 3D Human Posefrom Monocular Images](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/agarwal-triggs-pami06.pdf) - Ankur Agarwal and Bill Triggs. (PAMI 2006)

### Action Recognition
- [RSA: Randomized Simulation as Augmentation for Robust Human Action Recognition](https://arxiv.org/abs/1912.01180) - Yi Zhang, Xinyue Wei, Weichao Qiu, Zihao Xiao, Gregory D. Hager, Alan Yuille. (Arxiv 2019)
- [Simultaneous Implementation Features Extraction and Recognition Using C3DNetwork for WiFi-based Human Activity Recognition](https://arxiv.org/pdf/1911.09325.pdf) - Yafeng  Liu et al. (Arxiv 2019)
- [Action Recognition via Pose-Based Graph Convolutional Networks with Intermediate Dense Supervision](https://arxiv.org/abs/1911.12509) - Lei Shi, Yifan Zhang, Jian Cheng, Hanqing Lu (Arxiv 2019)
- [Semi-Supervised Action Recognition with Temporal Contrastive Learning](https://arxiv.org/abs/2102.02751) - Ankit Singh, Omprakash Chakraborty, Ashutosh Varshney, Rameswar Panda, Rogerio Feris, Kate Saenko, Abir Das(CVPR 2021)
- [Revisiting Skeleton-based Action Recognition](https://arxiv.org/abs/2104.13586) - Haodong Duan, Yue Zhao, Kai Chen, Dian Shao, Dahua Lin, Bo Dai(CVPR 2021)

### Geometry
- [SD-Pose: Semantic Decomposition for Cross-Domain 6D Object Pose Estimation](https://ojs.aaai.org/index.php/AAAI/article/view/16298) - Li, Z., Hu, Y., Salzmann, M., & Ji, X. (AAAI 2021)
