---
name: 'YOLOngv8: From Imbalanced to Accurate Object Detection in Long Tailed iSAID Dataset'
tools: []
image: ../images/projects/yolong.png
description: 'Object detection in aerial images poses unique challenges unlike in regular detection settings. The iSAID
dataset, in particular, has a high density of object instances,
scale variations, large aspect ratios, and a long tail distribution in the classes. Recent works have shown the
need and effectiveness of handling the long-tail distribution of data in the detection pipeline. In this work, we
show the capability of using prototype-based supervised
contrastive learning, with dynamically adjusted weights to
enable better feature representation learning for the tail
classes, thus improving the overall performance of object detection on the iSAID dataset. We also incorporate a weighted binary cross entropy loss based on class
probability priors to facilitate learning across all classes
and adapt the GIoU metric for Non-Maximum Suppression
(NMS) for better post-processing. We show that our proposed model YOLOngv8 adapts the YOLOv8 model better for accurate object detection for the long-tailed iSAID
dataset.'
external_url: ''
code: 'https://github.com/salwaalkhatib/ultralytics'
paper: 'https://mbzuaiac-my.sharepoint.com/personal/mohamed_boudjoghra_mbzuai_ac_ae/_layouts/15/onedrive.aspx?id=%2Fpersonal%2Fmohamed%5Fboudjoghra%5Fmbzuai%5Fac%5Fae%2FDocuments%2FTechnical%20reports%2FCV703%5FProject%5FFinal%5FReport%20%283%29%2Epdf&parent=%2Fpersonal%2Fmohamed%5Fboudjoghra%5Fmbzuai%5Fac%5Fae%2FDocuments%2FTechnical%20reports&ga=1'
---