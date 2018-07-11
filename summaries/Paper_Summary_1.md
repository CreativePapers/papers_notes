# Unsupervised Domain Adaptation for Automatic Estimation of Cardiothoracic Ratio

* Link to paper: [https://arxiv.org/pdf/1807.03434.pdf](https://arxiv.org/pdf/1807.03434.pdf)
* Paper Accepted: MICCAI 2018

----

## Summary 

This paper presents an approach to unsupervised domain adaptation for the task of CTR estimation that is based on the intuition that prediction masks should be domain independent. Using an adversarial training approach, they show
that they can predict cardiomegaly from a dataset without segmentation annotations. The paper further illustrates how the  approach can be adapted for semi-supervised learning.

Network Diagram:
Illustration of the architecture. In our proposed adversarial training procedure, the segmentor produces segmentations for the input images and the discriminator attempts to distinguish these predictions from ground truth annotations. A post-processing step (bottom part of figure) is used to predict cardiomegaly based on the predicted lung segmentation masks.

<img src="/summaries/images/network_diagram.png" width="800" /> ![](https://github.com/CreativePapers/papers_notes/tree/master/summaries/images/network_diagram.png)



Traditional CNNs:
- ResNet18 has been used as a backbone architecture .
- The discriminator is a standard ResNet classifier and the segmentor is inspired by the Fully Convolutional Network (FCN) , but uses an output stride of 16,
- Provided the predicted labels for the two lungs, the CTR is calculated in a post-processing step.

