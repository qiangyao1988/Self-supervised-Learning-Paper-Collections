# Self-supervised Learning Paper Collections
 This repo lists recent self-supervised learning papers and their github pages. 

## General 
- **A Theoretical Analysis of Contrastive Unsupervised Representation Learning**
[[Paper]](https://arxiv.org/pdf/1902.09229.pdf)<br>
Descrption: This paper formalizes the notion of semantic similarity by introducing latent classes. Similar pairs are assumed to be drawn from the same latent class. A downstream task is comprised of a subset of these latent classes.

- **Predicting What You Already Know Helps: Provable Self-Supervised Learning**
[[Paper]](https://arxiv.org/pdf/2008.01064.pdf)<br>
Descrption: This paper proposes a mechanism based on approximate conditional independence (ACI) to explain why solving pretext tasks created from known information can learn representations that provably reduce downstream sample complexity.

- **Self-Supervised Learning for Large-Scale Unsupervised Image Clustering**
[[Paper]](https://arxiv.org/pdf/2008.10312.pdf)
[[Code]](https://github.com/Randl/kmeans_selfsuper)<br>
Descrption: This paper proposes an additional way of evaluating self-supervised learning: training a clustering algorithm on extracted features in an unsupervised manner. The authors also show that self-supervised learning provides a strong baseline for unsupervised computer vision and mentions some possible direction for the current self-supervised methods performance improvement.

- **Self-supervised Visual Feature Learning with Deep Neural Networks A Survey**
[[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9086055&casa_token=lpa6IChv6PcAAAAA:2cLIsBwmEtpF2gxKT6iWZ39s68I1D8SBxKo-tk3GWtRqy31Dv4IlHSIHozhkb1kiiXeJ7nrB&tag=1)<br>

- **Towards Good Practices in Self-supervised Representation Learning**
[[Paper]](https://sslneuips20.github.io/files/CameraReadys%203-77/35/CameraReady/neurips_2020.pdf)<br>
Descrption: This paper presents several efficient practises in SSL. e.g., nonlinear projection head, strong data augmentation, and negative samples.

- **Understanding Contrastive Representation Learning through Alignment and Uniformity on the Hypersphere**
[[Paper]](https://arxiv.org/pdf/2005.10242.pdf)
[[Code]](https://ssnl.github.io/hypersphere/)<br>
Descrption: This paper identifies alignment (closeness) of features from positive parits and uniformity of the induced distribution of the features on the hypersphere are two key propoerties in contrastive loss. The authors popose quantifiable metrics to evaluate the representation quality for these two kinds of features. 

- **Understanding Self-supervised Learning with Dual Deep Networks**
[[Paper]](https://arxiv.org/pdf/2010.00578.pdf)<br>
Descrption: 

- **Understanding self-supervised learning using controlled datasets with known structure**
[[Paper]](https://sslneuips20.github.io/files/CameraReadys%203-77/64/CameraReady/Understanding_self_supervised_learning.pdf)<br>
Descrption: 

- **What Makes for Good Views for Contrastive Learning?**
[[Paper]](https://arxiv.org/pdf/2005.10243.pdf)
[[Code]](https://hobbitlong.github.io/InfoMin/)<br>
Descrption: This paper first demonstrates that optimal views for contrastive representation learning are task-dependent Then the authors anlyse an "InfoMin princple", which means a godd set of views are those that share the minimal information necessary to perform well at the downstream task. 


## Computer Vision

- **Adversarial Self-Supervised Contrastive Learning**
[[Paper]](https://arxiv.org/pdf/2006.07589.pdf)<br>
Descrption: 

- **A critical analysis of self-supervision, or what we can learn from a single image**
[[Paper]](https://arxiv.org/pdf/1904.13132.pdf)<br>
Descrption: 

 - **A Multi-view Perspective of Self-supervised Learning**
[[Paper]](https://arxiv.org/pdf/2003.00877.pdf)<br>
Descrption: 

- **A Simple Framework for Contrastive Learning of Visual Representations**
[[Paper]](https://arxiv.org/pdf/2002.05709.pdf)
[[Code]](https://github.com/google-research/simclr)<br>
Descrption: This paper introduces a simple framework for contrastive learning of visual representations named SimCLR. It makes several contributions for cintrastive learning: (1) data augnentations play a citical role; (2) inroducecing a learnable nonlinear transformation; (3) demonstrating contrastive learning benifites from larger batch sizes and more training steps.

- **Big Self-Supervised Models are Strong Semi-Supervised Learners**
[[Paper]](https://arxiv.org/pdf/2006.10029v1.pdf)
[[Code]](https://github.com/google-research/simclr)<br>
Descrption: The proposed semi-supervised learning framework comprises three steps: (1) unsupervised or self-supervised pretraining, (2) supervised fine-tuning, and (3) distillation using unlabeled data.

- **Bootstrap Your Own Latent A New Approach to Self-Supervised Learning**
[[Paper]](https://arxiv.org/pdf/2006.07733.pdf)
[[Code]](https://github.com/deepmind/deepmind-research/tree/master/byol)<br>
Descrption: 

- **Contrast and Classify: Alternate Training for Robust VQA** 
[[Paper]](https://arxiv.org/pdf/2010.06087.pdf)<br>
Descrption: 

- **Contrastive Learning with Hard Negative Samples**
[[Paper]](https://arxiv.org/pdf/2010.04592.pdf)<br>
Descrption: 

- **Contrastive Learning with Adversarial Examples**
[[Paper]](https://arxiv.org/pdf/2010.12050.pdf)<br>
Descrption: 

- **Domain Generalization by Solving Jigsaw Puzzles**
[[Paper]](https://arxiv.org/pdf/1903.06864.pdf)
[[Code]](https://github.com/fmcarlucci/JigenDG)<br>
Descrption: 

- **Evaluation of Out-of-Distribution Detection Performance of Self-Supervised Learning in a Controllable Environment**
[[Paper]](https://arxiv.org/pdf/2011.13120.pdf)<br>
Descrption: 


- **MixCo: -Mix: A Strategy for Regularizing Contrastive Representation Learning **
[[Paper]](https://arxiv.org/pdf/2010.08887.pdfm)<br>
Descrption: 



- **MixCo: Mix-up Contrastive Learning for Visual Representation **
[[Paper]](https://arxiv.org/pdf/2010.06300.pdf)<br>
Descrption: 



- **Momentum Contrast for Unsupervised Visual Representation Learning**
[[Paper]](https://arxiv.org/pdf/1911.05722.pdf)
[[Code]](https://github.com/facebookresearch/moco)<br>
Descrption: 

- **Prototypical Contrastive Learning of Unsupervised Representations**
[[Paper]](https://arxiv.org/pdf/2005.04966.pdf)<br>
Descrption: 

- **SelfMatch: Combining Contrastive Self-Supervision and Consistency for Semi-Supervised Learning**
[[Paper]](https://arxiv.org/pdf/2101.06480.pdf)<br>
Descrption: 


- **Self-Supervised Domain Adaptation with Consistency Training**
[[Paper]](https://arxiv.org/pdf/2010.07539.pdf)
[[Code]](https://github.com/Jiaolong/ss-da-consistency)<br>
Descrption: This paper adds a consistency loss based on mutual information theory to the main taks loss and pretext loss in a domain adaption tasks. 

- **Self-supervised Domain Adaptation for Computer Vision Tasks**
[[Paper]](https://arxiv.org/pdf/1907.10915.pdf)<br>
Descrption: 

- **Semi-supervised Domain Adaptation via Minimax Entropy**
[[Paper]](https://arxiv.org/pdf/1904.06487.pdf)<br>
Descrption: 

- **Self-supervised Domain Adaptation for Computer Vision Tasks**
[[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8883232)<br>
Descrption: 

- **Self-supervised Label Augmentation via Input Transformations**
[[Paper]](https://arxiv.org/pdf/1910.05872.pdf)<br>
Descrption: 


- **Self-Supervised Learning of Pretext-Invariant Representations**
[[Paper]](https://arxiv.org/pdf/1912.01991.pdf)<br>
Descrption: PIRL learns representations that are invariant to the transformation t and retain semantic information.

- **S4L: Self-Supervised Semi-Supervised Learning**
[[Paper]](https://openaccess.thecvf.com/content_ICCV_2019/papers/Zhai_S4L_Self-Supervised_Semi-Supervised_Learning_ICCV_2019_paper.pdf)<br>
Descrption: 

- **Self-supervised Representation Learning with Relative Predictive Coding**
[[Paper]](https://openreview.net/pdf?id=068E_JSq9O)<br>
Descrption: PIRL learns representations that are invariant to the transformation t and retain semantic information.




- **Towards Good Practices in Self-supervised Representation Learning**
[[Paper]](https://arxiv.org/pdf/2012.00868.pdf)<br>
Descrption: 

- **Universal Domain Adaptation through Self-Supervision**
[[Paper]](https://arxiv.org/pdf/2002.07953.pdf)
[[Code]](https://github.com/VisionLearningGroup/DANCE)<br>
Descrption: This paper proposed two novel self-supervised techniques, such as neighborhood clustering and entropy separation, dealing with arbitory category shift in domain adaptation tasks. 

- **Unsupervised Domain Adaptation through Self-Supervision**
[[Paper]](https://arxiv.org/pdf/1909.11825.pdf)<br>
Descrption: 

- **Unsupervised Intra-domain Adaptation for Semantic Segmentation through Self-Supervision**
[[Paper]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Pan_Unsupervised_Intra-Domain_Adaptation_for_Semantic_Segmentation_Through_Self-Supervision_CVPR_2020_paper.pdf)
[[Code]](https://github.com/feipan664/IntraDA)<br>
Descrption: This paper applied self-supervised technique to minimize both inter-domain and intra-domain gap simultaneously for domain adaptation tasks in semantic segmentation.

- **Virtual Adversarial Training: A Regularization Method for Supervised and Semi-Supervised Learning**
[[Paper]](https://arxiv.org/pdf/1704.03976.pdf)<br>
Descrption: 


## Natural Language Processing

- **Cross-Domain Sentiment Classification With In-domain Contrastive Learning** 
[[Paper]](https://arxiv.org/pdf/2012.02943.pdf)<br>
Descrption: This paper applies two data augmentation methods, i.e., synonym subtituion and back translation, to define pretext taks in contrastive learning. 

- **Evaluating Models’ Local Decision Boundaries via Contrast Sets** 
[[Paper]](https://arxiv.org/pdf/2004.02709.pdf) 
[[Code]](https://allennlp.org/contrast-sets)<br>
Descrption: Contrast sets provide a local view of a model's decision boundary, which can be used to more accurately evaluate a model's true linguistic capabilities. This paper proposed a new annotation paradigm for NLP to generate contrast samples. 

- **Self-Supervised Dialogue Learning** 
[[Paper]](https://arxiv.org/pdf/1907.00448.pdf)<br>
Descrption: 

- **Self-Supervised Learning for Contextualized Extractive Summarization** 
[[Paper]](https://www.aclweb.org/anthology/P19-1214.pdf)<br>
Descrption: 


## Others
- **Contrastive Multi-View Representation Learning on Graphs**
[[Paper]](https://arxiv.org/pdf/2006.05582.pdf)<br>
Descrption: This paper applis self-supervised approach to learn contrasting sturctural views of graphs. The authors mention contrasting encodings form first-order neighbors and a graph conffusion is more effective than multi-scale encodings in some graph classiification benchmarks. 

- **Federated Self-Supervised Learning of Multi-Sensor Representations for Embedded Intelligence**
[[Paper]](https://arxiv.org/pdf/2007.13018.pdf)<br>
Descrption: 


## Blogs 
- **Self-Supervised Representation Learning**
[[Link]](https://lilianweng.github.io/lil-log/2019/11/10/self-supervised-learning.html)

- **Contrastive Learning**
[[Link]](https://github.com/HobbitLong/PyContrast)
