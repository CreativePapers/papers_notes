# Unsupervised Domain Adaptation for Automatic Estimation of Cardiothoracic Ratio

* Link to paper: [https://arxiv.org/pdf/1807.03434.pdf](https://arxiv.org/pdf/1807.03434.pdf)
* Paper Accepted: MICCAI 2018

----

## Summary 

This paper presents an approach to unsupervised domain adaptation for the task of CTR estimation that is based on the intuition that prediction masks should be domain independent. Using an adversarial training approach, they show
that they can predict cardiomegaly from a dataset without segmentation annotations. The paper further illustrates how the  approach can be adapted for semi-supervised learning.

Network Diagram:
<img src="https://github.com/CreativePapers/papers_notes/tree/master/summaries/images/network_diagram.png" width=800 /> ![](https://github.com/CreativePapers/papers_notes/tree/master/summaries/images/network_diagram.png)

Traditional CNNs:
- Stacked fully connected conv layers
- 
- 

The way to increase accuracy is to go deeper and wider. But:
- increases memory and computation (linear increase in filters lead to quadradic increase in compute)
- needs more data
- 

GoogLeNet
- 
12x less parameters than AlexNet. Lower memory use, lower power use. More accurate than AlexNet. 1.5 billion add/mul;tiply.
- 2x less computation wrt AlexNet

Inspiration







