# Creating-RegionProposalNetwork-Applying-NonMaxSuppression
Code outlines RPN creation with NMS integration for Feature Pyramid Network (FPN). Functions manipulate bounding boxes and a custom layer processes RPN-generated proposals. Finally, custom Keras layer generates target data for object detection training.

This code outlines the step-by-step creation of a Region Proposal Network (RPN) and the application of Non-Maximum Suppression (NMS) to integrate it into a Feature Pyramid Network (FPN). In detail, it defines functions for working with bounding boxes and introduces a custom Keras layer. This layer's primary purpose is to process proposals generated by the RPN, which is a fundamental component in object detection pipelines. The RPN generates potential regions (proposals) where objects might be located. The custom layer then processes these proposals, aligning them for use within the broader context of a Feature Pyramid Network (FPN). 

In the final section of the code, a custom Keras layer takes proposals and ground-truth information and generates target ROIs, class IDs, bounding box refinement deltas, and masks for training object detection models. It is a crucial component in the training process of models such as Mask-RCNN.
