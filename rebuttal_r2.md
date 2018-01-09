We would like to thank all the reviewers for theirs helpful comments.
Here we would like to clarify some issues addressed in the reviews upon our submission in round 2.

(1) The statement over "the reason SSD is favored over Faster-RCNN" is based on our analysis on the structural design of the inference network, where Faster-RCNN must crop subregions from the feature map for object detection. The quantitative impact of SSD for better scene understanding over object detection is described in the paper "SSD: Single Shot MultiBox Detector".

(2) The statement "our replication of Stuffnet" means that we use the existing implementation by the original authors and train it on Cityscapes.

(3) The "reduced PSPNet" means ...

(4) There are two reasons why we don't compare with Blitznet. First, the pulication date of Blitznet is too late, considering our period of work and the first round submission date. It might also not make sense to readers if our experiment/comparison is not based on current well-known and highly-achieved methods. Second, in this paper, we want to emphasize that our proposed multi-task method can have very close and even better performance on each task, compared to each corresponding single-task approach.

Following changes would be revealed in camera-ready revision:

1. All statement describing "instance-level object detection" would changed to "object detection".
2. All statement describing "distance estimation" would changed to "depth estimation" to improve the terminology consistency.
3. The statement on learning rate would changed as: "We use initial learning rates of 0.0005 with a multi-factor learning rate scheduler for gradient update with SGD-based learning. The learning rate decreases at the rate of 0.5 at epoch 80/160/240, respectively."
4. The statement "Performing pixel-wise softmax at the input image scale would consume a large computational runtime and memory footprint, which is unnecessary and ineffective" will be changed to "... footprint, which is currently not satisfactory nor efficient for real-time applications" to make words precise.
5. We will add one sentence to each (2) and (3) to make clarifications.
