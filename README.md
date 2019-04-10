## Visual Trackers for Single Object

-----------------------
### Dataset

* **GOT-10k:** Lianghua Huang, Xin Zhao, Kaiqi Huang. GOT-10k: A Large High-Diversity Benchmark for Generic Object Tracking in the Wild. [[paper](https://arxiv.org/pdf/1810.11981.pdf)][[github](https://github.com/got-10k/toolkit-matlab)][[project](http://got-10k.aitestunion.com/)]

* **LaSOT:** Heng Fan, Liting Lin, Fan Yang, Peng Chu, Ge Deng, Sijia Yu, Hexin Bai, Yong Xu, Chunyuan Liao, Haibin Ling. "LaSOT: A High-quality Benchmark for Large-scale Single Object Tracking." CVPR (2019). [[paper](https://arxiv.org/pdf/1809.07845.pdf)][[project](https://cis.temple.edu/lasot/)]  

* **NFS:** H. Kiani Galoogahi, A. Fagg, C. Huang, D. Ramanan, S.Lucey. Need for Speed: A Benchmark for Higher Frame Rate Object Tracking, 2017, arXiv preprint arXiv:1703.05884[[paper](https://arxiv.org/abs/1703.05884.pdf)][[project](http://ci2cv.net/nfs/index.html)]

* **UAV123:** A Benchmark and Simulator for UAV Tracking.[[project](https://ivul.kaust.edu.sa/Pages/Dataset-UAV123.aspx)] 

* **TrackNet:** Chenge Li, Gregory Dobler, Xin Feng, Yao Wang. TrackNet: Simultaneous Object Detection and Tracking and Its Application in Traffic Video Analysis.[[paper](https://arxiv.org/pdf/1902.01466.pdf)][project](https://tracking-net.org/)]  

* **VOT2018:** VOT2018 Challenge. [[project](http://www.votchallenge.net/vot2018/dataset.html)]  

* **OTB2015:** Wu Y, Lim J, Yang M H. Object tracking benchmark[J]. IEEE Transactions on Pattern Analysis and Machine Intelligence, 2015, 37(9): 1834-1848.[[paper](https://www.researchgate.net/profile/Ming-Hsuan_Yang2/publication/273279481_Object_Tracking_Benchmark/links/5556e2d908ae6943a8734e3e/Object-Tracking-Benchmark.pdf)][[project](http://cvlab.hanyang.ac.kr/tracker_benchmark/datasets.html)]  

-------------------

### CVPR2019

* **SPM-Tracker:** Guangting Wang, Chong Luo, Zhiwei Xiong, Wenjun Zeng. SPM-Tracker: Series-Parallel Matching for Real-Time Visual Object Tracking. [[paper](https://arxiv.org/pdf/1904.04452.pdf)]

* **ATOM:** Martin Danelljan, Goutam Bhat, Fahad Shahbaz Khan, Michael Felsberg. ATOM: Accurate Tracking by Overlap Maximization[[paper](https://arxiv.org/pdf/1811.07628.pdf)][[code](https://github.com/visionml/pytracking)]

* **TADT:** Xin Li, Chao Ma, Baoyuan Wu, Zhenyu He, Ming-Hsuan Yang. "Target-Aware Deep Tracking" CVPR (2019).[[paper](https://arxiv.org/pdf/1904.01772.pdf)][[project](https://xinli-zn.github.io/TADT-project-page/)][[official-code-matlab](https://github.com/XinLi-zn/TADT)]

* **UDT:** Wang, Ning and Song, Yibing and Ma, Chao and Zhou, Wengang and Liu, Wei and Li, Houqiang. "Unsupervised Deep Tracking." CVPR (2019).[[paper](https://arxiv.org/pdf/1904.01828.pdf)][[official-code-matlab](https://github.com/594422814/UDT)][[official-code-pytorch](https://github.com/594422814/UDT_pytorch)]

* **Tencent:** Visual Tracking via Adaptive Spatially-Regularized Correlation Filters. CVPR (2019)
![image](http://5b0988e595225.cdn.sohucs.com/images/20190309/54f42a4cdadf491293784d707b6d847f.jpeg)
  * 提出自适应空间约束相关滤波算法来同时优化滤波器权重及空间约束矩阵。自适应空间约束机制可以高效地学习得到一个空间权重以适应目标外观变化，因此可以得到更加鲁棒的目标跟踪结果。  
  * 通过交替迭代算法来高效进行求解，基于此，每个子问题都可以得到闭合的解形式  
  * 使用两种相关滤波模型来分别估计目标的位置及尺度，可以在得到较高定位精度的同时有效减少计算量
  * 大量的在综合数据集上的实验结果证明了本文所提出的算法可以与现有的先进算法取得相当的跟踪结果，并且达到了实时的跟踪速度。

* **SiamMask:** Qiang Wang, Li Zhang, Luca Bertinetto, Weiming Hu, Philip H.S. Torr. "Fast Online Object Tracking and Segmentation: A Unifying Approach." CVPR (2019).[[paper](https://arxiv.org/pdf/1812.05050.pdf)][[project](http://www.robots.ox.ac.uk/~qwang/SiamMask/)][[code](https://github.com/foolwood/SiamMask?utm_campaign=explore-email&utm_medium=email&utm_source=newsletter&utm_term=daily)]

* **CIR:** Zhipeng Zhang, Houwen Peng. "Deeper and Wider Siamese Networks for Real-Time Visual Tracking." CVPR (2019).[[paper](https://arxiv.org/pdf/1901.01660.pdf)][[code](https://gitlab.com/MSRA_NLPR/deeper_wider_siamese_trackers)]

* **SiamRPN++:** Bo Li, Wei Wu, Qiang Wang, Fangyi Zhang, Junliang Xing, Junjie Yan. "SiamRPN++: Evolution of Siamese Visual Tracking with Very Deep Networks." CVPR (2019).[[paper](https://arxiv.org/pdf/1812.11703.pdf)][[project](http://bo-li.info/SiamRPN++/)]

* **C-RPN:** Heng Fan, Haibin Ling. "Siamese Cascaded Region Proposal Networks for Real-Time Visual Tracking." CVPR (2019).[[paper](https://arxiv.org/pdf/1812.06148.pdf)]

### 2019

* **BoLTVOS:** Paul Voigtlaender, Jonathon Luiten, Bastian Leibe. BoLTVOS: Box-Level Tracking for Video Object Segmentation. [[paper](https://arxiv.org/pdf/1904.04552.pdf)]

* **PTS:** Jianren Wang, Yihui He, Xiaobo Wang, Xinjia Yu, Xia Chen. Prediction-Tracking-Segmentation[[paper](https://arxiv.org/pdf/1904.03280.pdf)]

* **TCDCaps:** Ding Ma, Xiangqian Wu. TCDCaps: Visual Tracking via Cascaded Dense Capsules[[paper](https://arxiv.org/pdf/1902.10054.pdf)]  
* **SiamVGG:** Yuhong Li, Xiaofan Zhang. SiamVGG: Visual Tracking using Deeper Siamese Networks[[paper](https://arxiv.org/pdf/1902.02804.pdf)][[code](https://github.com/leeyeehoo/SiamVGG)]  

### 2018.12

* **AM-Net:** Xiaolong Jiang, Peizhao Li, Xiantong Zhen, Xianbin Cao. Model-free Tracking with Deep Appearance and Motion Features Integration.(WACV), 2019 [[paper](https://arxiv.org/pdf/1812.06418.pdf)]

### AAAI2019

* **LDES:** Yang Li, Jianke Zhu, Steven C.H. Hoi, Wenjie Song, Zhefeng Wang, Hantang Liu. "Robust Estimation of Similarity Transformation for Visual Object Tracking." AAAI (2019). [[paper](https://arxiv.org/pdf/1712.05231.pdf)][[code](https://github.com/ihpdep/LDES)]  

----------------------------

### NIPS2018  

* **DAT:** Shi Pu, Yibing Song, Chao Ma, Honggang Zhang, Ming-Hsuan Yang. "Deep Attentive Tracking via Reciprocative Learning." NIPS (2018). [[paper](https://arxiv.org/pdf/1810.03851.pdf)][[project](https://ybsong00.github.io/nips18_tracking/index)][[code](https://github.com/shipubupt/NIPS2018)] 

### ECCV2018

* **UPDT:** Goutam Bhat, Joakim Johnander, Martin Danelljan, Fahad Shahbaz Khan, Michael Felsberg. "Unveiling the Power of Deep Tracking." ECCV (2018). [[paper](http://openaccess.thecvf.com/content_ECCV_2018/papers/Goutam_Bhat_Unveiling_the_Power_ECCV_2018_paper.pdf)]  
  
* **DaSiamRPN:** Zheng Zhu, Qiang Wang, Bo Li, Wu Wei, Junjie Yan, Weiming Hu. "Distractor-aware Siamese Networks for Visual Object Tracking." ECCV (2018). [[paper](http://openaccess.thecvf.com/content_ECCV_2018/papers/Zheng_Zhu_Distractor-aware_Siamese_Networks_ECCV_2018_paper.pdf)][[github](https://github.com/foolwood/DaSiamRPN)]
  
* **SACF:** Mengdan Zhang, Qiang Wang, Junliang Xing, Jin Gao, Peixi Peng, Weiming Hu, Steve Maybank. "Visual Tracking via Spatially Aligned Correlation Filters Network." ECCV (2018). [[paper](http://openaccess.thecvf.com/content_ECCV_2018/papers/mengdan_zhang_Visual_Tracking_via_ECCV_2018_paper.pdf)]
  
* **RTINet:** Yingjie Yao, Xiaohe Wu, Lei Zhang, Shiguang Shan, Wangmeng Zuo. "Joint Representation and Truncated Inference Learning for Correlation Filter based Tracking." ECCV (2018). [[paper](http://openaccess.thecvf.com/content_ECCV_2018/papers/Yingjie_Yao_Joint_Representation_and_ECCV_2018_paper.pdf)]
  
* **Meta-Tracker:** Eunbyung Park, Alexander C. Berg. "Meta-Tracker: Fast and Robust Online Adaptation for Visual Object Trackers." [[paper](http://openaccess.thecvf.com/content_ECCV_2018/papers/Eunbyung_Park_Meta-Tracker_Fast_and_ECCV_2018_paper.pdf)][[github](https://github.com/silverbottlep/meta_trackers)]

* **DSLT:** Xiankai Lu, Chao Ma*, Bingbing Ni, Xiaokang Yang, Ian Reid, Ming-Hsuan Yang. "Deep Regression Tracking with Shrinkage Loss." ECCV (2018). [[paper](http://openaccess.thecvf.com/content_ECCV_2018/papers/Xiankai_Lu_Deep_Regression_Tracking_ECCV_2018_paper.pdf)][[github](https://github.com/chaoma99/DSLT)]
  
* **DRL-IS:** Liangliang Ren, Xin Yuan, Jiwen Lu, Ming Yang, Jie Zhou. "Deep Reinforcement Learning with Iterative Shift for Visual Tracking." ECCV (2018). [[paper](http://openaccess.thecvf.com/content_ECCV_2018/papers/Liangliang_Ren_Deep_Reinforcement_Learning_ECCV_2018_paper.pdf)]
  
* **RT-MDNet:** Ilchae Jung, Jeany Son, Mooyeol Baek, Bohyung Han. "Real-Time MDNet." ECCV (2018). [[paper](http://openaccess.thecvf.com/content_ECCV_2018/papers/Ilchae_Jung_Real-Time_MDNet_ECCV_2018_paper.pdf)]
  
* **ACT:** Boyu Chen, Dong Wang, Peixia Li, Huchuan Lu. "Real-time 'Actor-Critic' Tracking." ECCV (2018).[[paper](http://openaccess.thecvf.com/content_ECCV_2018/papers/Boyu_Chen_Real-time_Actor-Critic_Tracking_ECCV_2018_paper.pdf)][[github](https://github.com/bychen515/ACT)]

* **StructSiam:** Yunhua Zhang, Lijun Wang, Dong Wang, Mengyang Feng, Huchuan Lu, Jinqing Qi. "Structured Siamese Network for Real-Time Visual Tracking." ECCV (2018). [[paper](http://openaccess.thecvf.com/content_ECCV_2018/papers/Yunhua_Zhang_Structured_Siamese_Network_ECCV_2018_paper.pdf)]
  
* **MemTrack:** Tianyu Yang, Antoni B. Chan. "Learning Dynamic Memory Networks for Object Tracking." ECCV (2018). [[paper](http://openaccess.thecvf.com/content_ECCV_2018/papers/Tianyu_Yang_Learning_Dynamic_Memory_ECCV_2018_paper.pdf)]
  
* **SiamFC-tri:** Xingping Dong, Jianbing Shen. "Triplet Loss in Siamese Network for Object Tracking." ECCV (2018). [[paper](http://openaccess.thecvf.com/content_ECCV_2018/papers/Xingping_Dong_Triplet_Loss_with_ECCV_2018_paper.pdf)][[github](https://github.com/shenjianbing/TripletTracking)]

* **OxUvA long-term dataset+benchmark:** Jack Valmadre, Luca Bertinetto, João F. Henriques, Ran Tao, Andrea Vedaldi, Arnold Smeulders, Philip Torr, Efstratios Gavves. "Long-term Tracking in the Wild: a Benchmark." ECCV (2018). [[paper](http://openaccess.thecvf.com/content_ECCV_2018/papers/Efstratios_Gavves_Long-term_Tracking_in_ECCV_2018_paper.pdf)][[project](https://oxuva.github.io/long-term-tracking-benchmark/)]
  
* **TrackingNet:** Matthias Müller, Adel Bibi, Silvio Giancola, Salman Al-Subaihi, Bernard Ghanem. "TrackingNet: A Large-Scale Dataset and Benchmark for Object Tracking in the Wild." ECCV (2018). [[paper](http://openaccess.thecvf.com/content_ECCV_2018/papers/Matthias_Muller_TrackingNet_A_Large-Scale_ECCV_2018_paper.pdf)] [[project](http://tracking-net.org/)]

### CVPR2018

* **VITAL:** Yibing Song, Chao Ma, Xiaohe Wu, Lijun Gong, Linchao Bao, Wangmeng Zuo, Chunhua Shen, Rynson Lau, and Ming-Hsuan Yang.
  "VITAL: VIsual Tracking via Adversarial Learning." CVPR (2018 **Spotlight**). 
  [[project](https://ybsong00.github.io/cvpr18_tracking/index)]
  [[paper](http://openaccess.thecvf.com/content_cvpr_2018/papers/Song_VITAL_VIsual_Tracking_CVPR_2018_paper.pdf)]
  [[github](https://github.com/ybsong00/Vital_release)]

* **LSART:** Chong Sun, Dong Wang, Huchuan Lu, Ming-Hsuan Yang.
  "Learning Spatial-Aware Regressions for Visual Tracking." CVPR (2018 **Spotlight**). 
  [[paper](http://openaccess.thecvf.com/content_cvpr_2018/papers/Sun_Learning_Spatial-Aware_Regressions_CVPR_2018_paper.pdf)]

* **SiamRPN:** Bo Li, Wei Wu, Zheng Zhu, Junjie Yan.
  "High Performance Visual Tracking with Siamese Region Proposal Network." CVPR (2018 **Spotlight**). 
  [[paper](http://openaccess.thecvf.com/content_cvpr_2018/papers/Li_High_Performance_Visual_CVPR_2018_paper.pdf)]

* **TRACA:** Jongwon Choi, Hyung Jin Chang, Tobias Fischer, Sangdoo Yun, Kyuewang Lee, Jiyeoup Jeong, Yiannis Demiris, Jin Young Choi.
  "Context-aware Deep Feature Compression for High-speed Visual Tracking." CVPR (2018). 
  [[project](https://sites.google.com/site/jwchoivision/)]
  [[paper](http://openaccess.thecvf.com/content_cvpr_2018/papers/Choi_Context-Aware_Deep_Feature_CVPR_2018_paper.pdf)]

* **RASNet:** Qiang Wang, Zhu Teng, Junliang Xing, Jin Gao, Weiming Hu, Stephen Maybank.
  "Learning Attentions: Residual Attentional Siamese Network for High Performance Online Visual Tracking." CVPR 2018. 
  [[paper](http://openaccess.thecvf.com/content_cvpr_2018/papers/Wang_Learning_Attentions_Residual_CVPR_2018_paper.pdf)]

* **SA-Siam:** Anfeng He, Chong Luo, Xinmei Tian, Wenjun Zeng.
  "A Twofold Siamese Network for Real-Time Object Tracking." CVPR (2018). 
  [[paper](http://openaccess.thecvf.com/content_cvpr_2018/papers/He_A_Twofold_Siamese_CVPR_2018_paper.pdf)]

* **STRCF:** Feng Li, Cheng Tian, Wangmeng Zuo, Lei Zhang, Ming-Hsuan Yang.
  "Learning Spatial-Temporal Regularized Correlation Filters for Visual Tracking." CVPR (2018). 
  [[paper](http://openaccess.thecvf.com/content_cvpr_2018/papers/Li_Learning_Spatial-Temporal_Regularized_CVPR_2018_paper.pdf)]
  [[github](https://github.com/lifeng9472/STRCF)]

* **FlowTrack:** Zheng Zhu, Wei Wu, Wei Zou, Junjie Yan.
  "End-to-end Flow Correlation Tracking with Spatial-temporal Attention." CVPR (2018). 
  [[paper](http://openaccess.thecvf.com/content_cvpr_2018/papers/Zhu_End-to-End_Flow_Correlation_CVPR_2018_paper.pdf)]

* **DEDT:** Kourosh Meshgi, Shigeyuki Oba, Shin Ishii.
  "Efficient Diverse Ensemble for Discriminative Co-Tracking." CVPR (2018). 
  [[paper](http://openaccess.thecvf.com/content_cvpr_2018/papers/Meshgi_Efficient_Diverse_Ensemble_CVPR_2018_paper.pdf)]

* **SINT++:** Xiao Wang, Chenglong Li, Bin Luo, Jin Tang.
  "SINT++: Robust Visual Tracking via Adversarial Positive Instance Generation." CVPR (2018).
  [[paper](http://openaccess.thecvf.com/content_cvpr_2018/papers/Wang_SINT_Robust_Visual_CVPR_2018_paper.pdf)]

* **DRT:** Chong Sun, Dong Wang, Huchuan Lu, Ming-Hsuan Yang.
  "Correlation Tracking via Joint Discrimination and Reliability Learning." CVPR (2018). 
  [[paper](http://openaccess.thecvf.com/content_cvpr_2018/papers/Sun_Correlation_Tracking_via_CVPR_2018_paper.pdf)]

* **MCCT:** Ning Wang, Wengang Zhou, Qi Tian, Richang Hong, Meng Wang, Houqiang Li.
  "Multi-Cue Correlation Filters for Robust Visual Tracking." CVPR (2018). 
  [[paper](http://openaccess.thecvf.com/content_cvpr_2018/papers/Wang_Multi-Cue_Correlation_Filters_CVPR_2018_paper.pdf)]
  [[github](https://github.com/594422814/MCCT)]

* **MKCF:** Ming Tang, Bin Yu, Fan Zhang, Jinqiao Wang.
  "High-speed Tracking with Multi-kernel Correlation Filters." CVPR (2018).
  [[paper](http://openaccess.thecvf.com/content_cvpr_2018/papers/Tang_High-Speed_Tracking_With_CVPR_2018_paper.pdf)]
  
* **HP:** Xingping Dong, Jianbing Shen, Wenguan Wang, Yu, Liu, Ling Shao, and Fatih Porikli.
  "Hyperparameter Optimization for Tracking with Continuous Deep Q-Learning." CVPR (2018).
  [[paper](http://openaccess.thecvf.com/content_cvpr_2018/papers/Dong_Hyperparameter_Optimization_for_CVPR_2018_paper.pdf)]
