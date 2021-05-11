---
layout: post
title: "Egocentric Action Segmentation"  
image: /assets/EAS.png
categories: projects
---
# Egocentric Action Segmentation
<img class="img-responsive" src="/assets/EAS.png">
### Abstract
Temporal relations among multiple action segments play an important role in action segmentation especially when observations are limited (e.g., actions are occluded by other objects or happen outside a field of view). 
In this paper, we propose a network module called Graph-based Temporal Reasoning Module (\model) that can be built on top of existing action segmentation models to learn the relation of multiple action segments in various time spans. 
We model the relations by using two Graph Convolution Networks (GCNs) where each node represents an action segment. The two graphs have different edge properties to account for boundary regression and classification tasks, respectively. By applying graph convolution, we can update each node's representation based on its relation with neighboring nodes. The updated representation is then used for improved action segmentation.
We evaluate our model on the challenging egocentric datasets namely EGTEA and EPIC-Kitchens, where actions may be partially observed due to the viewpoint restriction. The results show that our proposed GTRM outperforms state-of-the-art action segmentation models by a large margin. We also demonstrate the effectiveness of our model on two third-person video datasets, the 50Salads dataset and the Breakfast dataset.
## Publication:
<u>Y. Huang</u>, Y. Sugano, and Y. Sato, &quot;Improving Action Segmentation via Graph Based Temporal Reasoning,&quot; <i>Proceedings of IEEE/CVF Conference on Computer Vision and Pattern Recognition (**CVPR**)</i>, 2020.   
[[pdf]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Huang_Improving_Action_Segmentation_via_Graph-Based_Temporal_Reasoning_CVPR_2020_paper.pdf)
[[code]](https://drive.google.com/file/d/1Bc02QyoWzPNAd1djswCoYxxAHBjITrQ3/view)
