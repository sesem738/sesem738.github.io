---
layout: page
title: Self Driving Car
description: 
img: assets/img/Polaris.jpg
importance: 1
category: Undergraduate Research
---

<div class="col-sm mt-3 mt-md-0">
        {% include video.html path="assets/video/IHMC Mechanical Engineering Internship Application.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true %}
    </div>

# Bridging the Gap in Autonomous Vehicle Object Detection: Introducing the Multimodal Fusion Detection System (MDFS)


## Introduction

In the pursuit of safe and efficient autonomous vehicles, object detection stands as a critical pillar. Accurate object detection is the cornerstone upon which safe path planning and decision-making are built. However, the challenge lies in finding the right balance between speed and accuracy in object detection models. Currently, there exists a gap between models that are fast but less accurate and those that are highly accurate but computationally intensive.

## The Need for Multimodal Fusion

Enter the Multimodal Fusion Detection System (MDFS), a groundbreaking approach to object detection in autonomous vehicles. MDFS leverages the strengths of two distinct sensor modalities to bridge the trade-off between performance and accuracy. It combines the speed of a fast image detection Convolutional Neural Network (CNN) model with the precision of LiDAR point cloud data through a decision tree approach.

## The Primary Objective

The primary objective of MDFS is clear: to provide a solution that marries the computational efficiency of a CNN model with the accuracy achieved by LiDAR point cloud data. By doing so, we aim to enable autonomous vehicles to navigate roadways more safely and effectively.

## Motivation for MDFS

The motivation for MDFS is rooted in the desire to reduce the computational complexity associated with traditional CNN-based object detection models. While CNNs are powerful, their computational demands can be substantial. MDFS seeks to optimize efficiency by extracting complementary features from the LiDAR point cloud data, thus achieving comparable detection accuracy without sacrificing performance.

## Impressive Results

The results of our research are compelling. MDFS outperforms the base CNN detection model by an impressive 3.7% in terms of accuracy. Notably, MDFS accomplishes this while operating at a speed of 10 Hz, making it suitable for real-time applications in autonomous vehicles.

## Embedded Device Compatibility

Practicality is a key consideration for any autonomous vehicle technology. MDFS is designed with this in mind, and it boasts a small memory footprint, making it suitable for deployment on embedded devices such as the Nvidia TX1.

## Conclusion

The Multimodal Fusion Detection System (MDFS) represents a significant leap forward in the field of autonomous vehicle object detection. By combining the speed of a fast image detection CNN with the accuracy of LiDAR point cloud data, we have successfully bridged the gap between performance and accuracy. Our results demonstrate the potential for safer and more efficient autonomous vehicles, setting the stage for a future where the roads are navigated with confidence and precision.
