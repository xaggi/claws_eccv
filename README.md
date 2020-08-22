# CLAWS: Clustering Assisted Weakly Supervised Learning with Normalcy Suppression for Anomalous Event Detection (ECCV 2020)

<!-- Project page for the 'CLAWS: Clustering Assisted Weakly Supervised Learning with Normalcy Suppression for Anomalous Event Detection', ECCV 2020 paper.(http://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123670358.pdf).-->

[10 Minutes Presentation](https://www.youtube.com/watch?v=wjPX0P7AuAA&) || [1 minute Presentation](https://www.youtube.com/watch?v=wvBtEtsoT0U) || [Video Results on UCF-Crime dataset](https://youtu.be/wjPX0P7AuAA?t=500) || [More Video Results](https://www.youtube.com/watch?v=8TKkPePFpiE) || [Paper PDF](http://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123670358.pdf) || [Supplementary Material]()



<p align="center">
<img src="https://github.com/xaggi/claws_eccv/blob/master/imgs/architecture.JPG" width="1050">
</p>

## Anomaly Datasets
- UCF-Crime  [[Link](https://www.crcv.ucf.edu/projects/real-world/)]
- Shanghai Tech [[Link](https://svip-lab.github.io/dataset/campus_dataset.html)]
  - Shannghai Tech anomaly dataset is orgioanlly a one-class training dataset
  - The two-class split used in our paper (proposed by Zhong et al. CVPR19) can be downloaded here. [[Link](https://github.com/xaggi/claws_eccv/tree/master/shanghai_tech_binary_training_split)] 
- UCSD Ped2 [[Link](http://www.svcl.ucsd.edu/projects/anomaly/dataset.htm)]

## Other Related Publication from my Project on Anomaly Detection
- Cleaning Label Noise with Clusters for Minimally Supervised Anomaly Detection 
  - Authors: M. Z. Zaheer, J. Lee, M. Astrid, A. Mahmood, S. I. Lee
  - Venue: Computer Vision and Pattern Recognition Workshops (CVPRW), 2020
  - CVPR talk [[Link1](https://www.youtube.com/watch?v=nJJbueHVot8)] [[Link2](https://sites.google.com/view/luv2020/talks/zaheer)]
  - Workshop on Learning from Unlabeled Videos [[Link](https://sites.google.com/view/luv2020)]
  - Non-archieved paper
  - Dataset used: UCF-Crime and ShanghaiTech anomaly datasets.
  
- Old is Gold: Redefining the Adversarially Learned One-Class Classifier Training Paradigm
  - Authors: M. Z. Zaheer, J. Lee, M. Astrid, A. Mahmood, S. I. Lee
  - Venue: Conference on Computer Vision and Pattern Recognition (CVPR), 2020
  - CVPR talk [[Link1](https://www.youtube.com/watch?v=mAfAUwFlUpU)] [[Link2](https://www.youtube.com/watch?v=TQNRR3dvOt0)]
  - Paper PDF [[Link1](https://www.researchgate.net/publication/340683607_Old_is_Gold_Redefining_the_Adversarially_Learned_One-Class_Classifier_Training_Paradigm)] [[Link2](https://arxiv.org/abs/2004.07657)]
  - Results video [[Link](https://www.youtube.com/watch?v=59Lqkkyy9bQ&t=7s)]
  - Datasets used: UCSD Pedestrian2, Caltech256 and MNIST for anomalies and outliers detection.

- Ensemble Grid Formation to Detect Potential Anomalous Regions Using Context Encoders
  - Authors: M. Z. Zaheer, M. Astrid, S. I. Lee, H. C. Shin
  - Venue: International Conference on Control, Automation and Systems (ICCAS), 2018
  - Paper PDF [[Link](https://ieeexplore.ieee.org/abstract/document/8571926)]
  - Results videos [[Video1](https://www.youtube.com/watch?v=KW4wPLv1HYM)] | [[Video2](https://www.youtube.com/watch?v=l5EVXkLWNVc)] | [[Video3](https://www.youtube.com/watch?v=jF_Kuof0Y0A)]
  - Datasets used: Self-recorded dataset for anomaly detection in moving-camera videos

## CLAWS Net Results and Comparisons
- AUC Performance on UCF-Crime
  - 83.03 % AUC of the ROC curve
  - Comparison provided against [Hassan et al.](https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Hasan_Learning_Temporal_Regularity_CVPR_2016_paper.pdf), [Lu et al.](https://www.cse.cuhk.edu.hk/leojia/papers/abnormaldect_iccv13.pdf), [Sultani et al.](https://openaccess.thecvf.com/content_cvpr_2018/papers/Sultani_Real-World_Anomaly_Detection_CVPR_2018_paper.pdf), [Zaheer et al.](https://sites.google.com/view/luv2020/talks/zaheer), and [Zhong et al.](https://openaccess.thecvf.com/content_CVPR_2019/papers/Zhong_Graph_Convolutional_Label_Noise_Cleaner_Train_a_Plug-And-Play_Action_Classifier_CVPR_2019_paper.pdf)
  
<p align="center">
<img src="https://github.com/xaggi/claws_eccv/blob/master/imgs/ucf-auc.JPG" width="650">
</p>

- AUC Performance on ShanghaiTech
  - 89.67 % AUC of the ROC curve
  - Comparison provided against [Zaheer et al.](https://sites.google.com/view/luv2020/talks/zaheer) and [Zhong et al.](https://openaccess.thecvf.com/content_CVPR_2019/papers/Zhong_Graph_Convolutional_Label_Noise_Cleaner_Train_a_Plug-And-Play_Action_Classifier_CVPR_2019_paper.pdf)

<p align="center">
<img src="https://github.com/xaggi/claws_eccv/blob/master/imgs/st-auc.JPG" width="650">
</p>

- ROC Performance

<p align="center">
<img src="https://github.com/xaggi/claws_eccv/blob/master/imgs/roc.JPG" width="650">
</p>


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
