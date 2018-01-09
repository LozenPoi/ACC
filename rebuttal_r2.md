We would like to thank all the reviewers for theirs helpful comments.
Here we would like to clarify some issues upon our submission in round 2.

1. The statement over "the reason SSD is favored over Faster-RCNN" is based on our analyze on the structural design of the inference network, where Faster-RCNN crops subregions from the feature map for object classification. The quantitative impact of SSD for better scene understand over object classification is described in the paper "SSD: Single Shot MultiBox Detector".

Following changes would be revealed in camera-ready revision:

1. All statement describing "instance-level object detection" would changed to "object detection".
2. All statement describing "distance estimation" would changed to "depth estimation" to improve the terminology consistency.
3. The statement on learning rate would changed as: "We use initial learning rates of 0.0005 with a multi-factor learning rate scheduler for gradient update with SGD-based learning. The learning rate decreases at the rate of 0.5 at epoch 80/160/240, respectively."
4. 
