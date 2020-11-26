# CLAWS: Clustering Assisted Weakly Supervised Learning with Normalcy Suppression for Anomalous Event Detection (ECCV 2020)

<!-- Project page for the 'CLAWS: Clustering Assisted Weakly Supervised Learning with Normalcy Suppression for Anomalous Event Detection', ECCV 2020 paper.(http://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123670358.pdf).-->

[10 Minutes Presentation](https://www.youtube.com/watch?v=wjPX0P7AuAA&) || [1 minute Presentation](https://www.youtube.com/watch?v=wvBtEtsoT0U) || [Video Results on UCF-Crime dataset](https://youtu.be/wjPX0P7AuAA?t=500) || [More Video Results](https://www.youtube.com/watch?v=8TKkPePFpiE) || [Paper PDF](https://arxiv.org/abs/2011.12077) || [Supplementary Material](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123670358-supp.zip)



<p align="center">
<img src="https://github.com/xaggi/claws_eccv/blob/master/imgs/architecture.JPG" width="1050">
</p>

## Other Related Publications from my Project on Anomaly Detection
- A Self-Reasoning Framework for Anomaly Detection Using Video-Level Labels 
  - Evaluated on: UCF-Crime, ShanghaiTech and UCSD Ped2 anomaly datasets.
  - Venue: Signal Processing Letters (SPL) Journal
  - PDF [[IEEEXplore](https://ieeexplore.ieee.org/document/9204830/)] [[Arxiv](https://arxiv.org/abs/2008.11887)] 
  - Authors: M. Z. Zaheer, A. Mahmood, S.H. Shin, S. I. Lee

- Cleaning Label Noise with Clusters for Minimally Supervised Anomaly Detection 
  - Evaluated on: UCF-Crime and ShanghaiTech anomaly datasets.
  - Venue: Computer Vision and Pattern Recognition Workshops (CVPRW), 2020
  - CVPR talk [[Link1](https://www.youtube.com/watch?v=nJJbueHVot8)] [[Link2](https://sites.google.com/view/luv2020/talks/zaheer)]
  - Workshop on Learning from Unlabeled Videos [[Link](https://sites.google.com/view/luv2020)]
  - Non-archieved
  - Authors: M. Z. Zaheer, J. Lee, M. Astrid, A. Mahmood, S. I. Lee
  
- Old is Gold: Redefining the Adversarially Learned One-Class Classifier Training Paradigm
  - Evaluated on: UCSD Pedestrian2, Caltech256 and MNIST for anomalies and outliers detection.
  - Venue: Conference on Computer Vision and Pattern Recognition (CVPR), 2020
  - CVPR talk [[Link1](https://www.youtube.com/watch?v=mAfAUwFlUpU)] [[Link2](https://www.youtube.com/watch?v=TQNRR3dvOt0)]
  - Paper PDF [[Link1](https://www.researchgate.net/publication/340683607_Old_is_Gold_Redefining_the_Adversarially_Learned_One-Class_Classifier_Training_Paradigm)] [[Link2](https://arxiv.org/abs/2004.07657)]
  - Results video [[Link](https://www.youtube.com/watch?v=59Lqkkyy9bQ&t=7s)]
  - Authors: M. Z. Zaheer, J. Lee, M. Astrid, A. Mahmood, S. I. Lee

- Ensemble Grid Formation to Detect Potential Anomalous Regions Using Context Encoders
  - Evaluated on: Self-recorded dataset for anomaly detection in moving-camera videos
  - Venue: International Conference on Control, Automation and Systems (ICCAS), 2018
  - Paper PDF [[Link](https://ieeexplore.ieee.org/abstract/document/8571926)]
  - Results videos [[Video1](https://www.youtube.com/watch?v=KW4wPLv1HYM)] | [[Video2](https://www.youtube.com/watch?v=l5EVXkLWNVc)] | [[Video3](https://www.youtube.com/watch?v=jF_Kuof0Y0A)]
  - Authors: M. Z. Zaheer, M. Astrid, S. I. Lee, H. C. Shin

## CLAWS Net Results and Comparisons
- AUC Performance on UCF-Crime
  - 83.03 % AUC of the ROC curve
  - Comparison provided against [Hassan et al.](https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Hasan_Learning_Temporal_Regularity_CVPR_2016_paper.pdf), [Lu et al.](https://www.cse.cuhk.edu.hk/leojia/papers/abnormaldect_iccv13.pdf), [Sultani et al.](https://openaccess.thecvf.com/content_cvpr_2018/papers/Sultani_Real-World_Anomaly_Detection_CVPR_2018_paper.pdf), [Zaheer et al.](https://sites.google.com/view/luv2020/talks/zaheer), [Zhong et al.](https://openaccess.thecvf.com/content_CVPR_2019/papers/Zhong_Graph_Convolutional_Label_Noise_Cleaner_Train_a_Plug-And-Play_Action_Classifier_CVPR_2019_paper.pdf), and [SRF](https://arxiv.org/abs/2008.11887).
  
<p align="center">
<img src="https://github.com/xaggi/claws_eccv/blob/master/imgs/ucf-auc.JPG" width="650">
</p>

- AUC Performance on ShanghaiTech
  - 89.67 % AUC of the ROC curve
  - Comparison provided against [Zaheer et al.](https://sites.google.com/view/luv2020/talks/zaheer), [Zhong et al.](https://openaccess.thecvf.com/content_CVPR_2019/papers/Zhong_Graph_Convolutional_Label_Noise_Cleaner_Train_a_Plug-And-Play_Action_Classifier_CVPR_2019_paper.pdf),  and [SRF](https://arxiv.org/abs/2008.11887).

<p align="center">
<img src="https://github.com/xaggi/claws_eccv/blob/master/imgs/st-auc.JPG" width="650">
</p>

- ROC Performance
  - Numerical data of the CLAWS Net ROC plots is provide in an excel file. [[Link](https://github.com/xaggi/claws_eccv/blob/master/ROC_graphs_CLAWS_Net.xlsx)]

<p align="center">
<img src="https://github.com/xaggi/claws_eccv/blob/master/imgs/roc.JPG" width="650">
</p>


## Anomaly Datasets
- UCF-Crime  [[Link](https://www.crcv.ucf.edu/projects/real-world/)]
- Shanghai Tech [[Link](https://svip-lab.github.io/dataset/campus_dataset.html)]
  - Shannghai Tech anomaly dataset is orgioanlly a one-class training dataset
  - The two-class split used in our paper (proposed by Zhong et al. CVPR19) can be downloaded here. [[Link](https://github.com/xaggi/claws_eccv/tree/master/shanghai_tech_binary_training_split)] 
- UCSD Ped2 [[Link1](http://www.svcl.ucsd.edu/projects/anomaly/dataset.htm)] [[Link2](https://drive.google.com/drive/folders/15tFcgb7VfeFkfv9qkpQ2t_Al2UtXE_2M?usp=sharing)]


## Updates
[22/08/2020] Our project is still ongoing. The code will be released after completion of the project.  
[02/08/2020] CLAWS Net ECCV 2020 github page created.

## Misc.

If you have any query, please feel free to contact Zaigham through mzz.pieas /@/ gmail/./com

 
```
@article{zaheerclaws,
  title={CLAWS: Clustering Assisted Weakly Supervised Learning with Normalcy Suppression for Anomalous Event Detection},
  author={Zaheer, Muhammad Zaigham and Mahmood, Arif and Astrid, Marcella and Lee, Seung-Ik}
  booktitle={Proceedings of the IEEE/CVF Europeon Conference on Computer Vision},
  year={2020}
  }
 ```
