---
name: 'YOLOngv8: From Imbalanced to Accurate Object Detection in Long Tailed
iSAID Dataset'
tools: []
image: ../images/projects/
description: 'Object detection in aerial images poses unique chal-
lenges unlike in regular detection settings. The iSAID
dataset, in particular, has a high density of object instances,
scale variations, large aspect ratios, and a long tail dis-
tribution in the classes. Recent works have shown the
need and effectiveness of handling the long-tail distribu-
tion of data in the detection pipeline. In this work, we
show the capability of using prototype-based supervised
contrastive learning, with dynamically adjusted weights to
enable better feature representation learning for the tail
classes, thus improving the overall performance of ob-
ject detection on the iSAID dataset. We also incorpo-
rate a weighted binary cross entropy loss based on class
probability priors to facilitate learning across all classes
and adapt the GIoU metric for Non-Maximum Suppression
(NMS) for better post-processing. We show that our pro-
posed model YOLOngv8 adapts the YOLOv8 model bet-
ter for accurate object detection for the long-tailed iSAID
dataset.'
external_url: ''
code: 'https://github.com/salwaalkhatib/ultralytics'
paper: 'https://mbzuaiac-my.sharepoint.com/:b:/g/personal/mohamed_boudjoghra_mbzuai_ac_ae/EaxnGPkBSiNFg01tcvomJmkBl4O4AoXU4WWqsS6_jC8i9w?e=h73w7Y'
---