---
title: "Deep Learning-based Object Detection in Industrial Production"
collection: projects
type: " National Natural Science Foundation of China"
permalink: /projects/object-detection
venue: " Hunan University"
date: 2021-10-01
location: "Changsha, China"
---

The project aims to apply deep learning-based object detection to the industrial production of cylindrical lenses.

Background
======
Computer vision technology has been applied in the field of cylindrical lens manufacturing. Some production lines use template matching techniques for the positioning and recognition of lens particles. However, template matching methods rely on stable lighting conditions and single-feature targets, and they require searching through the sliding window method, which leads to a significant amount of computational redundancy and poor robustness. To address these issues, deep learning-based object detection algorithms offer more solutions for industrial positioning and detection.

Methods
======
* Building upon the original YOLOX-nano algorithm, we further decoupled the detection head and introduced an attention mechanism to suppress noise.
* During the training process, we employed α-SIoU Loss as the bounding box loss function and divided the training into two stages to enhance its performance while eliminating the need for non-maximum suppression.

Responsibilities
======
* I employed the NCC template matching algorithm to capture images of workpieces in different models and various environments, followed by dataset annotation using image labeling software, thereby constructing a dataset for cylindrical lens.
* I proposed a method for further decoupling YOLOX , which is also the most impactful improvement in terms of increasing the mean average precision (mAP).
* Some ablation experiments were conducted.

<font style="color: Brown;">This work has been submitted to the journal "Engineering Applications of Artificial Intelligence." Stay tuned for updates!</font>
