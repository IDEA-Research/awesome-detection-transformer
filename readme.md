# Awesome Detection Transformer [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/IDEACVR/awesome-detection-transformer)
This a collecttion of papers for detection and segmentation with Transformer . 
We reorginize the repo by reserach fields. 
</br>
If you find some overlooked papers or resourses, please open issues or pull requests (recommended).


# Table of Contents
- [Awesome Detection Transformer](https://github.com/IDEACVR/awesome-detection-transformer) [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/IDEACVR/awesome-detection-transformer)
- [Table of Contents](#table-of-contents)
- [Toolbox](#toolbox)
- [Papers](#papers)
  - [DETR](#detr)
  - [Object Detection](#object-detection)
  - [Open Vocabulary and Multi-Modal Objection Detection](#open-vocabulary-and-multi-modal-objection-detection)
  - [3D Object Detection](#3d-object-detection)
  - [Segmentation](#segmentation)
- [Benchmarks](#benchmarks)
- [Acknowledgements](#acknowledgements)

# Toolbox
<p>
<font size=3><a href='https://github.com/IDEA-Research/detrex'><b>detrex</b></a></font>: A toolbox dedicated for Transforme-based object detectors including DETR, Deformable DETR, DAB-DETR, DN-DETR, DINO, etc.
</p>

<p>
<font size=3><a href='https://github.com/open-mmlab/mmdetection'><b>mmdetection</b></a></font>: An open source object detection toolbox including DETR and Deformable DETR.
</p>


# Papers

## DETR
<p>
<font size=3><a href='https://alcinos.github.io/detr_page/'><b>[DETR] End-to-End Object Detection with Transformers.</b></a></font>
<br>
<font size=2>Nicolas Carion, Francisco Massa, Gabriel Synnaeve, Nicolas Usunier, Alexander Kirillov, Sergey Zagoruyko.</font>
<br>
<font size=2>ECCV 2020.</font>
<a href='https://arxiv.org/abs/2005.12872'>[paper]</a> <a href='https://github.com/facebookresearch/detr'>[code]</a> <a href='https://github.com/IDEA-Research/detrex'>[detrex code]</a>    
</p>

## Object Detection
<p>
<font size=3><b>Group DETR v2: Strong Object Detector with Encoder-Decoder Pretraining
</b></font>
<br>
<font size=2>Qiang Chen, Jian Wang, Chuchu Han, Shan Zhang, Zexian Li, Xiaokang Chen, Jiahui Chen, Xiaodi Wang, Shuming Han, Gang Zhang, Haocheng Feng, Kun Yao, Junyu Han, Errui Ding, Jingdong Wang</font>
<br>
<font size=2>arxiv 2022.</font>
<a href='https://arxiv.org/abs/2211.03594'>[paper]</a> 
</p>
<p>
<font size=3><b>Towards Efficient Use of Multi-Scale Features in Transformer-Based Object Detectors</b></font>
<br>
<font size=2>Gongjie Zhang, Zhipeng Luo, Yingchen Yu, Zichen Tian, Jingyi Zhang, Shijian Lu</font>
<br>
<font size=2>arxiv 2022.</font>
<a href='https://arxiv.org/abs/2208.11356'>[paper]</a> <a href='https://github.com/ZhangGongjie/IMFA'>[code]</a>  
</p>

<p>
<font size=3><b>Semantic-Aligned Matching for Enhanced DETR Convergence and Multi-Scale Feature Fusion</b></font>
<br>
<font size=2>Gongjie Zhang, Zhipeng Luo, Yingchen Yu, Jiaxing Huang, Kaiwen Cui, Shijian Lu, Eric P. Xing</font>
<br>
<font size=2>arxiv 2022.</font>
<a href='https://arxiv.org/abs/2207.14172'>[paper]</a> <a href='https://github.com/ZhangGongjie/SAM-DETR'>[code]</a>  
</p>

<p>
<font size=3><b>Group DETR: Fast DETR Training with Group-Wise One-to-Many Assignment</b></font>
<br>
<font size=2>Qiang Chen, Xiaokang Chen, Jian Wang, Haocheng Feng, Junyu Han, Errui Ding, Gang Zeng, Jingdong Wang</font>
<br>
<font size=2>arxiv 2022.</font>
<a href='https://arxiv.org/abs/2207.13085'>[paper]</a> 
</p>

<p>
<font size=3><b>DETRs with Hybrid Matching.</b></font>
<br>
<font size=2>Ding Jia, Yuhui Yuan, Haodi He, Xiaopei Wu, Haojun Yu, Weihong Lin, Lei Sun, Chao Zhang, Han Hu</font>
<br>
<font size=2>arxiv 2022.</font>
<a href='https://arxiv.org/abs/2207.13080'>[paper]</a> <a href='https://github.com/HDETR/H-Deformable-DETR'>[code]</a>    
</p>

<p>
<font size=3><b>Mask DINO: Towards A Unified Transformer-based Framework for Object Detection and Segmentation.</b></font>
<br>
<font size=2>Feng Li*, Hao Zhang*, Huaizhe xu, Shilong Liu, Lei Zhang, Lionel M. Ni, Heung-Yeung Shum.</font>
<br>
<font size=2>arxiv 2022.</font>
<a href='https://arxiv.org/pdf/2206.02777.pdf'>[paper]</a> <a href='https://github.com/IDEACVR/MaskDINO'>[code]</a>    
</p>

<p>
<font size=3><b>[MIMDet] Unleashing Vanilla Vision Transformer with Masked Image Modeling for Object Detection.</b></font>
<br>
<font size=2>Yuxin Fang*, Shusheng Yang*, Shijie Wang*, Yixiao Ge, Ying Shan, Xinggang Wang</font>
<br>
arxiv 2022.
<a href='https://arxiv.org/abs/2204.02964'>[paper]</a> <a href='https://github.com/hustvl/MIMDet'>[code]</a>  
</p>

<p>
<font size=3><b>DINO: DETR with Improved DeNoising Anchor Boxes for End-to-End Object Detection.</b></font>
<br>
<font size=2>Hao Zhang*, Feng Li*, Shilong Liu*, Lei Zhang, Hang Su, Jun Zhu, Lionel M. Ni, Heung-Yeung Shum</font>
<br>
arxiv 2022.
<a href='https://arxiv.org/abs/2203.03605'>[paper]</a> <a href='https://github.com/IDEACVR/DINO'>[code]</a> <a href='https://github.com/IDEA-Research/detrex'>[detrex code]</a> 
</p>

<p>
<font size=3><b>Recurrent Glimpse-based Decoder for Detection with Transformer.</b></font>
<br>
<font size=2>Zhe Chen, Jing Zhang, Dacheng Tao.</font>
<br>
<font size=2>CVPR 2022.</font>
<a href='https://arxiv.org/abs/2112.04632'>[paper]</a> <a href='https://github.com/zhechen/Deformable-DETR-REGO'>[code]</a>    
</p>

<p>
<font size=3><b>AdaMixer: A Fast-Converging Query-Based Object Detector.</b></font>
<br>
<font size=2>Ziteng Gao, Limin Wang, Bing Han, Sheng Guo.</font>
<br>
<font size=2>CVPR 2022.</font>
<a href='https://arxiv.org/abs/2203.16507'>[paper]</a> <a href='https://github.com/MCG-NJU/AdaMixer'>[code]</a>    
</p>


<p>
<font size=3><b>DN-DETR: Accelerate DETR Training by Introducing Query DeNoising.</b></font>
<br>
<font size=2>Feng Li*, Hao Zhang*, Shilong Liu, Jian Guo, Lionel M. Ni, Lei Zhang.</font>
<br>
<font size=2>CVPR 2022.</font>
<a href='https://arxiv.org/abs/2203.01305'>[paper]</a> <a href='https://github.com/FengLi-ust/DN-DETR'>[code]</a> <a href='https://github.com/IDEA-Research/detrex'>[detrex code]</a>    
</p>

<p>
<font size=3><b>Accelerating DETR Convergence via Semantic-Aligned Matching.</b></font>
<br>
<font size=2>Gongjie Zhang,Zhipeng Luo,Yingchen Yu,Kaiwen Cui,Shijian Lu.</font>
<br>
<font size=2>CVPR 2022.</font>
<a href='https://arxiv.org/abs/2203.06883'>[paper]</a> <a href='https://github.com/ZhangGongjie/SAM-DETR'>[code]</a>    
</p>

<p>
<font size=3><b>DETReg: Unsupervised Pretraining with Region Priors for Object Detection.</b></font>
<br>
<font size=2>Amir Bar, Xin Wang, Vadim Kantorov, Colorado J Reed, Roei Herzig, Gal Chechik, Anna Rohrbach, Trevor Darrell, Amir Globerson.</font>
<br>
<font size=2>CVPR 2022.</font>
<a href='https://arxiv.org/abs/2106.04550'>[paper]</a> <a href='https://github.com/amirbar/DETReg'>[code]</a>    
</p>

<p>
<font size=3><b>QueryDet: Cascaded Sparse Query for Accelerating High-Resolution Small Object Detection.</b></font>
<br>
<font size=2>Chenhongyi Yang, Zehao Huang, Naiyan Wang.</font>
<br>
<font size=2>CVPR 2022.</font>
<a href='https://arxiv.org/abs/2103.09136'>[paper]</a> <a href='https://github.com/ChenhongyiYang/QueryDet-PyTorch'>[code]</a>    
</p>

<p>
<font size=3><b>DAB-DETR: Dynamic Anchor Boxes are Better Queries for DETR.</b></font>
<br>
<font size=2>Shilong Liu, Feng Li, Hao Zhang, Xiao Yang, Xianbiao Qi, Hang Su, Jun Zhu, Lei Zhang.</font>
<br>
<font size=2>ICLR 2022.</font>
<a href='https://arxiv.org/abs/2201.12329'>[paper]</a> <a href='https://github.com/SlongLiu/DAB-DETR'>[code]</a> <a href='https://github.com/IDEA-Research/detrex'>[detrex code]</a>    
</p>

<p>
<font size=3><b>ViDT: An Efficient and Effective Fully Transformer-based Object Detector.</b></font>
<br>
<font size=2>Hwanjun Song, Deqing Sun, Sanghyuk Chun, Varun Jampani, Dongyoon Han, Byeongho Heo, Wonjae Kim, Ming-Hsuan Yang.</font>
<br>
<font size=2>ICLR 2022.</font>
<a href='https://arxiv.org/abs/2110.03921'>[paper]</a> <a href='https://github.com/naver-ai/vidt'>[code]</a>    
</p>

<p>
<font size=3><b>CF-DETR: Coarse-to-Fine Transformers for End-to-End Object Detection.</b></font>
<br>
<font size=2>Xipeng Cao, Peng Yuan, Bailan Feng, Kun Niu.</font>
<br>
<font size=2>AAAI 2022.</font>
<a href='https://www.aaai.org/AAAI22Papers/AAAI-6312.XipengC.pdf'>[paper]</a> 
</p>

<p>
<font size=3><b>FP-DETR: Detection Transformer Advanced by Fully Pre-training.</b></font>
<br>
<font size=2>Wen Wang, Yang Cao, Jing Zhang, Dacheng Tao.</font>
<br>
<font size=2>ICLR 2022.</font>
<a href='https://openreview.net/pdf?id=yjMQuLLcGWK'>[paper]</a>
</p>

<p>
<b>D^2ETR: Decoder-Only DETR with Computationally Efficient Cross-Scale Attention.</b> 
<br>
<font size=2>Junyu Lin, Xiaofeng Mao, Yuefeng Chen, Lei Xu, Yuan He, Hui Xue</font>
<br>
arxiv 2022.
<a href='https://arxiv.org/abs/2203.00860'>[paper]</a> <a href='https://github.com/alibaba/easyrobust/tree/main/ddetr'>[code]</a> 
</p>


<p>
<font size=3><b>Sparse DETR: Efficient End-to-End Object Detection with Learnable Sparsity.</b></font>
<br>
<font size=2>Byungseok Roh, JaeWoong Shin, Wuhyun Shin, Saehoon Kim.</font>
<br>
<font size=2>ICLR 2022.</font>
<a href='https://arxiv.org/abs/2111.14330v2'>[paper]</a> <a href='https://github.com/kakaobrain/sparse-detr'>[code]</a>    
</p>

<p>
<font size=3><b>Anchor DETR: Query Design for Transformer-Based Object Detection.</b></font>
<br>
<font size=2>Yingming Wang, Xiangyu Zhang, Tong Yang, Jian Sun.</font>
<br>
<font size=2>AAAI 2022.</font>
<a href='https://arxiv.org/abs/2109.07107v2'>[paper]</a> <a href='https://github.com/megvii-research/AnchorDETR'>[code]</a>    
</p>

<p>
<font size=3><b>Exploring Plain Vision Transformer Backbones for Object Detection.</b></font>
<br>
<font size=2>Yanghao Li, Hanzi Mao, Ross Girshick, Kaiming He.</font>
<br>
<font size=2>arXiv 2022.</font>
<a href='https://arxiv.org/abs/2203.16527'>[paper]</a> <a href='https://github.com/ViTAE-Transformer/ViTDet'>[code]</a>    
</p>

<p>
<font size=3><b>[YOLOS] You Only Look at One Sequence: Rethinking Transformer in Vision through Object Detection.</b></font>
<br>
<font size=2>Yuxin Fang*, Bencheng Liao*, Xinggang Wang, Jiemin Fang, Jiyang Qi, Rui Wu, Jianwei Niu, Wenyu Liu.</font>
<br>
<font size=2>NeurIPS 2021.</font>
<a href='https://arxiv.org/abs/2106.00666'>[paper]</a> <a href='https://github.com/hustvl/YOLOS'>[code]</a>    
</p>

<p>
<font size=3><b>Dynamic DETR: End-to-End Object Detection With Dynamic Attention.</b></font>
<br>
<font size=2>Xiyang Dai, Yinpeng Chen, Jianwei Yang, Pengchuan Zhang, Lu Yuan, Lei Zhang.</font>
<br>
<font size=2>ICCV 2021.</font>
<a href='https://openaccess.thecvf.com/content/ICCV2021/papers/Dai_Dynamic_DETR_End-to-End_Object_Detection_With_Dynamic_Attention_ICCV_2021_paper.pdf'>[paper]</a> 
<!-- <a href='https://github.com/atten4vis/conditionaldetr'>[code]</a>     -->
</p>

<p>
<font size=3><b>PnP-DETR: Towards Efficient Visual Analysis with Transformers.</b></font>
<br>
<font size=2>Tao Wang, Li Yuan, Yunpeng Chen, Jiashi Feng, Shuicheng Yan.</font>
<br>
<font size=2>ICCV 2021.</font>
<a href='https://openaccess.thecvf.com/content/ICCV2021/papers/Wang_PnP-DETR_Towards_Efficient_Visual_Analysis_With_Transformers_ICCV_2021_paper.pdf'>[paper]</a> 
<a href='https://github.com/twangnh/pnp-detr'>[code]</a>
</p>

<p>
<font size=3><b>WB-DETR: Transformer-Based Detector without Backbone.</b></font>
<br>
<font size=2>Fanfan Liu, Haoran Wei, Wenzhe Zhao, Guozhen Li, Jingquan Peng, Zihao Li.</font>
<br>
<font size=2>ICCV 2021.</font>
<a href='https://openaccess.thecvf.com/content/ICCV2021/papers/Liu_WB-DETR_Transformer-Based_Detector_Without_Backbone_ICCV_2021_paper.pdf'>[paper]</a> 
</p>

<p>
<font size=3><b>Conditional DETR for Fast Training Convergence.</b></font>
<br>
<font size=2>Depu Meng*, Xiaokang Chen*, Zejia Fan, Gang Zeng, Houqiang Li, Yuhui Yuan, Lei Sun, Jingdong Wang.</font>
<br>
<font size=2>ICCV 2021.</font>
<a href='https://arxiv.org/abs/2108.06152v2'>[paper]</a> <a href='https://github.com/atten4vis/conditionaldetr'>[code]</a> <a href='https://github.com/IDEA-Research/detrex'>[detrex code]</a>  
</p>

<p>
<font size=3><b>Rethinking Transformer-based Set Prediction for Object Detection.</b></font>
<br>
<font size=2>Zhiqing Sun, Shengcao Cao, Yiming Yang, Kris Kitani.</font>
<br>
<font size=2>ICCV 2021.</font>
<a href='https://arxiv.org/abs/2011.10881'>[paper]</a> <a href='https://github.com/edward-sun/tsp-detection'>[code]</a>    
</p>

<p>
<font size=3><b>Fast Convergence of DETR with Spatially Modulated Co-Attention.</b></font>
<br>
<font size=2>Peng Gao, Minghang Zheng, Xiaogang Wang, Jifeng Dai, Hongsheng Li .</font>
<br>
<font size=2>ICCV 2021.</font>
<a href='https://arxiv.org/abs/2101.07448'>[paper]</a> <a href='https://github.com/gaopengcuhk/SMCA-DETR'>[code]</a>    
</p>

<p>
<font size=3><b>Efficient DETR: Improving End-to-End Object Detector with Dense Prior.</b></font>
<br>
<font size=2>Zhuyu Yao, Jiangbo Ai, Boxun Li, Chi Zhang.</font>
<br>
<font size=2>arxiv 2021.</font>
<a href='https://arxiv.org/abs/2104.01318'>[paper]</a>
<!-- <a href='https://github.com/dddzg/up-detr'>[code]</a>     -->
</p>

<p>
<font size=3><b>UP-DETR: Unsupervised Pre-training for Object Detection with Transformers.</b></font>
<br>
<font size=2>Zhigang Dai, Bolun Cai, Yugeng Lin, Junying Chen.</font>
<br>
<font size=2>CVPR 2021.</font>
<a href='https://arxiv.org/abs/2011.09094'>[paper]</a> <a href='https://github.com/dddzg/up-detr'>[code]</a>    
</p>

<p>
<font size=3><b>Deformable DETR: Deformable Transformers for End-to-End Object Detection.</b></font>
<br>
<font size=2>Xizhou Zhu, Weijie Su, Lewei Lu, Bin Li, Xiaogang Wang, Jifeng Dai.</font>
<br>
<font size=2>ICLR 2021.</font>
<a href='https://arxiv.org/abs/2010.04159v4'>[paper]</a> <a href='https://github.com/fundamentalvision/Deformable-DETR'>[code]</a> <a href='https://github.com/IDEA-Research/detrex'>[detrex code]</a>    
</p>


## Open Vocabulary and Multi-Modal Objection Detection
<p>
<font size=3><b>Open-Vocabulary DETR with Conditional Matching Yuhang.</b></font>
<br>
<font size=2>Yuhang Zang, Wei Li, Kaiyang Zhou, Chen Huang, Chen Change Loy.</font>
<br>
<font size=2>ECCV 2022.</font>
<a href='https://arxiv.org/abs/2203.11876'>[paper]</a> <a href='https://github.com/yuhangzang/ov-detr'>[code]</a>    
</p>

<p>
<font size=3><b>OW-DETR: Open-world Detection Transformer.</b></font>
<br>
<font size=2>Akshita Gupta, Sanath Narayan, K J Joseph, Salman Khan, Fahad Shahbaz Khan, Mubarak Shah.</font>
<br>
<font size=2>CVPR 2022.</font>
<a href='https://arxiv.org/pdf/2112.01513.pdf'>[paper]</a> <a href='https://github.com/akshitac8/OW-DETR'>[code]</a>    
</p>

<p>
<font size=3><b>Simple Open-Vocabulary Object Detection with Vision Transformers.</b></font>
<br>
<font size=2>Matthias Minderer, Alexey Gritsenko, Austin Stone, Maxim Neumann, Dirk Weissenborn, Alexey Dosovitskiy, Aravindh Mahendran, Anurag Arnab, Mostafa Dehghani, Zhuoran Shen, Xiao Wang, Xiaohua Zhai, Thomas Kipf, Neil Houlsby.</font>
<br>
<font size=2>arxiv 2022.</font>
<a href='https://arxiv.org/abs/2205.06230'>[paper]</a>     
</p>

<p>
<font size=3><b>X-DETR: A Versatile Architecture for Instance-wise Vision-Language Tasks.</b></font>
<br>
<font size=2>Zhaowei Cai, Gukyeong Kwon, Avinash Ravichandran, Erhan Bas, Zhuowen Tu, Rahul Bhotika, Stefano Soatto.</font>
<br>
<font size=2>arxiv 2022.</font>
<a href='https://arxiv.org/abs/2204.05626'>[paper]</a>     
</p>

<p>
<font size=3><b>MDETR -- Modulated Detection for End-to-End Multi-Modal Understanding.</b></font>
<br>
<font size=2>Aishwarya Kamath, Mannat Singh, Yann LeCun, Gabriel Synnaeve, Ishan Misra, Nicolas Carion.</font>
<br>
<font size=2>ICCV 2021.</font>
<a href='https://arxiv.org/abs/2104.12763'>[paper]</a> <a href='https://github.com/ashkamath/mdetr'>[code]</a>    
</p>

<p>
<font size=3><b>Class-agnostic Object Detection with Multi-modal Transformer.</b></font>
<br>
<font size=2>Muhammad Maaz, Hanoona Rasheed, Salman Khan, Fahad Shahbaz Khan, Rao Muhammad Anwer and Ming-Hsuan Yang.</font>
<br>
<font size=2>ECCV 2022.</font>
<a href='https://arxiv.org/abs/2111.11430'>[paper]</a> <a href='https://github.com/mmaaz60/mvits_for_class_agnostic_od'>[code]</a>    
</p>

<p>
<font size=3><b>[Object Centric OVD] -- Bridging the Gap between Object and Image-level Representations for Open-Vocabulary Detection.</b></font>
<br>
<font size=2>Hanoona Rasheed, Muhammad Maaz, Muhammad Uzair Khattak, Salman Khan, Fahad Shahbaz Khan.</font>
<br>
<font size=2>arXiv:2207.03482.</font>
<a href='https://arxiv.org/abs/2207.03482'>[paper]</a> <a href='https://github.com/hanoonaR/object-centric-ovd'>[code]</a>    
</p>


## 3D Object Detection
<p>
<font size=3><b>BEVFormer: Learning Bird's-Eye-View Representation from Multi-Camera Images via Spatiotemporal Transformers.</b></font>
<br>
<font size=2>Zhiqi Li, Wenhai Wang, Hongyang Li, Enze Xie, Chonghao Sima, Tong Lu, Qiao Yu, Jifeng Dai.</font>
<br>
<font size=2>ECCV 2022.</font>
<a href='https://arxiv.org/abs/2203.17270'>[paper]</a>  <a href='https://github.com/zhiqi-li/BEVFormer'>[code]</a> 
</p>

<p>
<font size=3><b>PersFormer: 3D Lane Detection via Perspective Transformer and the OpenLane Benchmark.</b></font>
<br>
<font size=2>Li Chen, Chonghao Sima, Yang Li, Zehan Zheng, Jiajie Xu, Xiangwei Geng, Hongyang Li†, Conghui He, Jianping Shi, Yu Qiao, Junchi Yan.</font>
<br>
<font size=2>ECCV 2022.</font>
<a href='https://arxiv.org/abs/2203.11089'>[paper]</a>  <a href='https://github.com/OpenPerceptionX/PersFormer_3DLane'>[code]</a> 
</p>

<p>
<font size=3><b>PETRv2: A Unified Framework for 3D Perception from Multi-Camera Images.</b></font>
<br>
<font size=2>Yingfei Liu, Junjie Yan, Fan Jia, Shuailin Li, Qi Gao, Tiancai Wang, Xiangyu Zhang, Jian Sun.</font>
<br>
<font size=2>arxiv 2022.</font>
<a href='https://arxiv.org/abs/2206.01256'>[paper]</a>  <a href='https://github.com/megvii-research/petr'>[code]</a> 
</p>

<p>
<font size=3><b>PETR: Position Embedding Transformation for Multi-View 3D Object Detection.</b></font>
<br>
<font size=2>Yingfei Liu, Tiancai Wang, Xiangyu Zhang, Jian Sun.</font>
<br>
<font size=2>ECCV 2022.</font>
<a href='https://arxiv.org/abs/2203.05625'>[paper]</a>  <a href='https://github.com/megvii-research/petr'>[code]</a> 
</p>

<p>
<font size=3><b>BEVSegFormer: Bird’s Eye View Semantic Segmentation From Arbitrary Camera Rigs.</b></font>
<br>
<font size=2>Lang Peng, Zhirong Chen, Zhangjie Fu, Pengpeng Liang and Erkang Cheng.</font>
<br>
<font size=2>arxiv 2022.</font>
<a href='https://arxiv.org/pdf/2203.04050.pdf'>[paper]</a>
</p>

<p>
<font size=3><b>CAT-Det: Contrastively Augmented Transformer for Multi-modal 3D Object Detection.</b></font>
<br>
<font size=2>Yanan Zhang, Jiaxin Chen, Di Huang.</font>
<br>
<font size=2>CVPR 2022.</font>
<a href='https://arxiv.org/abs/2204.00325'>[paper]</a> 
</p>

<p>
<font size=3><b>TransFusion: Robust LiDAR-Camera Fusion for 3D Object Detection with Transformers.</b></font>
<br>
<font size=2>Xuyang Bai, Zeyu Hu, Xinge Zhu, Qingqiu Huang, Yilun Chen, Hongbo Fu, Chiew-Lan Tai.</font>
<br>
<font size=2>CVPR 2022.</font>
<a href='https://arxiv.org/abs/2203.11496'>[paper]</a> <a href='https://github.com/XuyangBai/TransFusion'>[code]</a>    
</p>

<p>
<font size=3><b>Omni-DETR: Omni-Supervised Object Detection with Transformers.</b></font>
<br>
<font size=2>Pei Wang, Zhaowei Cai, Hao Yang, Gurumurthy Swaminathan, Nuno Vasconcelos, Bernt Schiele, Stefano Soatto.</font>
<br>
<font size=2>CVPR 2022.</font>
<a href='https://arxiv.org/abs/2203.16089'>[paper]</a>
</p>

<p>
<font size=3><b>MonoDETR: Depth-aware Transformer for Monocular 3D Object Detection.</b></font>
<br>
<font size=2>Renrui Zhang, Han Qiu, Tai Wang, Xuanzhuo Xu, Ziyu Guo, Yu Qiao, Peng
  Gao, Hongsheng Li.</font>
<br>
<font size=2>CVPR 2022.</font>
<a href='https://arxiv.org/abs/2203.13310'>[paper]</a> <a href='https://github.com/ZrrSkywalker/MonoDETR'>[code]</a>    
</p>

<p>
<font size=3><b>MonoDTR: Monocular 3D Object Detection with Depth-Aware Transformer.</b></font>
<br>
<font size=2>Kuan-Chih Huang, Tsung-Han Wu, Hung-Ting Su, Winston H. Hsu.</font>
<br>
<font size=2>CVPR 2022.</font>
<a href='https://arxiv.org/abs/2203.10981'>[paper]</a> <a href='https://github.com/kuanchihhuang/MonoDTR'>[code]</a>    
</p>

<p>
<font size=3><b>[VoxSeT] Voxel Set Transformer: A Set-to-Set Approach to 3D Object Detection from Point Clouds.</b></font>
<br>
<font size=2>Chenhang He, Ruihuang Li, Shuai Li, Lei Zhang.</font>
<br>
<font size=2>CVPR 2022.</font>
<a href='https://www4.comp.polyu.edu.hk/~cslzhang/paper/VoxSeT_cvpr22.pdf'>[paper]</a> <a href='https://github.com/skyhehe123/VoxSeT'>[code]</a>    
</p>

<p>
<font size=3><b>[SST] Embracing Single Stride 3D Object Detector with Sparse Transformer.</b></font>
<br>
<font size=2>Lue Fan, Ziqi Pang, Tianyuan Zhang, Yu-Xiong Wang, Hang Zhao, Feng Wang, Naiyan Wang, Zhaoxiang Zhang.</font>
<br>
<font size=2>CVPR 2022.</font>
<a href='https://arxiv.org/abs/2112.06375'>[paper]</a> <a href='https://github.com/TuSimple/SST'>[code]</a>    
</p>

<p>
<font size=3><b>DETR3D: 3D Object Detection from Multi-view Images via 3D-to-2D Queries.</b></font>
<br>
<font size=2>Yue Wang, Vitor Guizilini, Tianyuan Zhang, Yilun Wang, Hang Zhao, Justin Solomon.</font>
<br>
<font size=2>CORL 2021.</font>
<a href='https://arxiv.org/abs/2110.06922'>[paper]</a> <a href='https://github.com/WangYueFt/detr3d'>[code]</a>    
</p>

<p>
<font size=3><b>[VOTR] Voxel Transformer for 3D object detection.</b></font>
<br>
<font size=2>Jiageng Mao, Yujing Xue, Minzhe Niu, Haoyue Bai, Jiashi Feng, Xiaodan Liang, Hang Xu, Chunjing Xu.</font>
<br>
<font size=2>ICCV 2021.</font>
<a href='https://arxiv.org/abs/2109.02497'>[paper]</a> <a href='https://github.com/PointsCoder/VOTR'>[code]</a>    
</p>

<p>
<font size=3><b>[SRDet] Suppress-and-Refine Framework for End-to-End 3D Object Detection.</b></font>
<br>
<font size=2>Zili Liu, Guodong Xu, Honghui Yang, Minghao Chen, Kuoliang Wu, Zheng Yang, Haifeng Liu, Deng Cai.</font>
<br>
<font size=2>arxiv 2021.</font>
<a href='https://arxiv.org/abs/2103.10042'>[paper]</a> <a href='https://github.com/ZJULearning/SRDet'>[code]</a>    
</p>

<p>
<font size=3><b>[3DETR] An End-to-End Transformer Model for 3D Object Detection.</b></font>
<br>
<font size=2>Ishan Misra, Rohit Girdhar, Armand Joulin.</font>
<br>
<font size=2>ICCV 2021.</font>
<a href='https://arxiv.org/abs/2109.08141'>[paper]</a> <a href='https://github.com/facebookresearch/3detr'>[code]</a>    
</p>


<p>
<font size=3><b>[PointTransformer] Point Transformer.</b></font>
<br>
<font size=2>Hengshuang Zhao, Li Jiang, Jiaya Jia, Philip Torr, Vladlen Koltun.</font>
<br>
<font size=2>ICCV 2021.</font>
<a href='https://arxiv.org/pdf/2012.09164.pdf'>[paper]</a> <a href='https://github.com/POSTECH-CVLab/point-transformer'>[code]</a>    
</p>

<p>
<font size=3><b>[GroupFree3D] Group-Free 3D Object Detection via Transformers.</b></font>
<br>
<font size=2>Ze Liu, Zheng Zhang, Yue Cao, Han Hu, Xin Tong.</font>
<br>
<font size=2>ICCV 2021.</font>
<a href='https://arxiv.org/abs/2104.00678'>[paper]</a> <a href='https://github.com/zeliu98/Group-Free-3D'>[code]</a>    
</p>

## Segmentation
<p>
<font size=3><b>Mask DINO: Towards A Unified Transformer-based Framework for Object Detection and Segmentation.</b></font>
<br>
<font size=2>Feng Li*, Hao Zhang*, Huaizhe xu, Shilong Liu, Lei Zhang, Lionel M. Ni, Heung-Yeung Shum.</font>
<br>
<font size=2>arxiv.</font>
<a href='https://arxiv.org/pdf/2206.02777.pdf'>[paper]</a> <a href='https://github.com/IDEACVR/MaskDINO'>[code]</a>    
</p>

<p>
<font size=3><b>[KMaX-DeepLab] k-means Mask Transformer.</b></font>
<br>
<font size=2>Qihang Yu, Huiyu Wang, Siyuan Qiao, Maxwell Collins, Yukun Zhu, Hatwig Adam, Alan Yuille, Liang-Chieh Chen.</font>
<br>
<font size=2>ECCV 2022.</font>
<a href='https://arxiv.org/abs/2207.04044'>[paper]</a> <a href='https://github.com/google-research/deeplab2'>[code]</a>
</p>

<p>
<font size=3><b>[Mask2Former] Masked-attention Mask Transformer for Universal Image Segmentation .</b></font>
<br>
<font size=2>Bowen Cheng, Ishan Misra, Alexander G. Schwing, Alexander Kirillov, Rohit Girdhar.</font>
<br>
<font size=2>CVPR 2022.</font>
<a href='https://arxiv.org/abs/2112.01527'>[paper]</a> <a href='https://github.com/facebookresearch/Mask2Former'>[code]</a>    
</p>

<p>
<font size=3><b>[CMT-DeepLab] CMT-DeepLab: Clustering Mask Transformers for Panoptic Segmentation.</b></font>
<br>
<font size=2>Qihang Yu, Huiyu Wang, Dahun Kim, Siyuan Qiao, Maxwell Collins, Yukun Zhu, Hartwig Adam, Alan Yuille, Liang-Chieh Chen.</font>
<br>
<font size=2>CVPR 2022.</font>
<a href='https://arxiv.org/abs/2206.08948'>[paper]</a>
</p>

<p>
<font size=3><b>[Panoptic SegFormer] Panoptic SegFormer: Delving Deeper into Panoptic Segmentation with
Transformers.</b></font>
<br>
<font size=2>Zhiqi Li, Wenhai Wang, Enze Xie, Zhiding Yu, Anima Anandkumar, Jose M. Alvarez, Ping Luo, Tong Lu.</font>
<br>
<font size=2>arxiv 2021.</font>
<a href='https://arxiv.org/pdf/2109.03814.pdf?ref=https://githubhelp.com'>[paper]</a> <a href='https://github.com/zhiqi-li/Panoptic-SegFormer'>[code]</a>    
</p>

<p>
<font size=3><b>[MaskFormer] Per-Pixel Classification is Not All You Need for Semantic Segmentation.</b></font>
<br>
<font size=2>Bowen Cheng, Alexander G. Schwing, Alexander Kirillov.</font>
<br>
<font size=2>NeurIPS 2021.</font>
<a href='https://arxiv.org/abs/2107.06278'>[paper]</a> <a href='https://github.com/facebookresearch/MaskFormer'>[code]</a>    
</p>

<p>
<font size=3><b>[SETR] Rethinking Semantic Segmentation from a Sequence-to-Sequence Perspective with Transformers.</b></font>
<br>
<font size=2>Zheng, Jiachen Lu, Hengshuang Zhao, Xiatian Zhu, Zekun Luo, Yabiao Wang, Yanwei Fu, Jianfeng Feng, Tao Xiang, Philip HS Torr, Li Zhang.</font>
<br>
<font size=2>CVPR 2021.</font>
<a href='https://arxiv.org/abs/2012.15840'>[paper]</a> <a href='https://github.com/fudan-zvg/SETR'>[code]</a>    
</p>

<p>
<font size=3><b>[MaX-DeepLab] MaX-DeepLab: End-to-End Panoptic Segmentation with Mask Transformers.</b></font>
<br>
<font size=2>Huiyu Wang, Yukun Zhu, Hartwig Adam, Alan Yuille, Liang-Chieh Chen.</font>
<br>
<font size=2>CVPR 2021.</font>
<a href='https://arxiv.org/abs/2012.00759'>[paper]</a> <a href='https://github.com/google-research/deeplab2'>[code]</a>
</p>

<p>
<font size=3><b>[SegFormer] SegFormer: Simple and Efficient Design for Semantic Segmentation with Transformers.</b></font>
<br>
<font size=2>Enze Xie, Wenhai Wang, Zhiding Yu, Anima Anandkumar, Jose M. Alvarez, Ping Luo.</font>
<br>
<font size=2>NuerIPS 2021.</font>
<a href='https://arxiv.org/pdf/2105.15203.pdf'>[paper]</a> <a href='https://github.com/NVlabs/SegFormer'>[code]</a>    
</p>


# Benchmarks
[COCO Detection on Paperswithcode.](https://paperswithcode.com/sota/object-detection-on-coco)

[COCO Instance Segmentation on Paperswithcode.](https://paperswithcode.com/sota/instance-segmentation-on-coco)

[COCO Panoptic Segmentation on Paperswithcode.](https://paperswithcode.com/sota/panoptic-segmentation-on-coco-test-dev)

[Semantic Segmentation on Paperswithcode.](https://paperswithcode.com/task/semantic-segmentation)

[3D Object Detection on Paperswithcode.](https://paperswithcode.com/task/3d-object-detection)





# Acknowledgements
We thank all the authors above for their great works!
