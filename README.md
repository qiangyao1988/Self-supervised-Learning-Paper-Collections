# Self-supervised Learning Paper Collections
 This repo lists recent self-supervised learning papers and their github pages. 
 
## General 
- **A Theoretical Analysis of Contrastive Unsupervised Representation Learning**
[[Paper]](https://arxiv.org/pdf/1902.09229.pdf)<br>

- **What Makes for Good Views for Contrastive Learning?**
[[Paper]](https://arxiv.org/pdf/2005.10243.pdf)
[[Code]](https://hobbitlong.github.io/InfoMin/)<br>
Descrption: This paper first demonstrates that optimal views for contrastive representation learning are task-dependent Then the authors anlyse an "InfoMin princple", which means a godd set of views are those that share the minimal information necessary to perform well at the downstream task. 

- **Understanding Contrastive Representation Learning through Alignment and Uniformity on the Hypersphere**
[[Paper]](https://arxiv.org/pdf/2005.10242.pdf)
[[Code]](https://ssnl.github.io/hypersphere/)<br>
Descrption: This paper identifies alignment (closeness) of features from positive parits and uniformity of the induced distribution of the features on the hypersphere are two key propoerties in contrastive loss. The authors popose quantifiable metrics to evaluate the representation quality for these two kinds of features. 

- **Towards Good Practices in Self-supervised Representation Learning**
[[Paper]](https://sslneuips20.github.io/files/CameraReadys%203-77/35/CameraReady/neurips_2020.pdf)<br>
Descrption: This paper presents several efficient practises in SSL. e.g., nonlinear projection head, strong data augmentation, and negative samples.


## Computer Vision
- **A Simple Framework for Contrastive Learning of Visual Representations**
[[Paper]](https://arxiv.org/pdf/2002.05709.pdf)
[[Code]](https://github.com/google-research/simclr)<br>
Descrption: This paper introduces a simple framework for contrastive learning of visual representations named SimCLR. It makes several contributions for cintrastive learning: (1) data augnentations play a citical role; (2) inroducecing a learnable nonlinear transformation; (3) demonstrating contrastive learning benifites from larger batch sizes and more training steps.

- **Self-Supervised Domain Adaptation with Consistency Training**
[[Paper]](https://arxiv.org/pdf/2010.07539.pdf)
[[Code]](https://github.com/Jiaolong/ss-da-consistency)<br>
Descrption: This paper adds a consistency loss based on mutual information theory to the main taks loss and pretext loss in a domain adaption tasks. 

- **Unsupervised Domain Adaptation through Self-Supervision**
[[Paper]](https://arxiv.org/pdf/1909.11825.pdf)<br>
Descrption: 

- **Self-supervised Domain Adaptation for Computer Vision Tasks**
[[Paper]](https://arxiv.org/pdf/1907.10915.pdf)<br>
Descrption: 

- **Universal Domain Adaptation through Self-Supervision**
[[Paper]](https://arxiv.org/pdf/2002.07953.pdf)
[[Code]](https://github.com/VisionLearningGroup/DANCE)<br>
Descrption: This paper proposed two novel self-supervised techniques, such as neighborhood clustering and entropy separation, dealing with arbitory category shift in domain adaptation tasks. 

- **Unsupervised Intra-domain Adaptation for Semantic Segmentation through Self-Supervision**
[[Paper]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Pan_Unsupervised_Intra-Domain_Adaptation_for_Semantic_Segmentation_Through_Self-Supervision_CVPR_2020_paper.pdf)
[[Code]](https://github.com/feipan664/IntraDA)<br>
Descrption: This paper applied self-supervised technique to minimize both inter-domain and intra-domain gap simultaneously for domain adaptation tasks in semantic segmentation. 

## Natural Language Processing
- **Evaluating Models’ Local Decision Boundaries via Contrast Sets** 
[[Paper]](https://arxiv.org/pdf/2004.02709.pdf) 
[[Code]](https://allennlp.org/contrast-sets)<br>
Descrption: Contrast sets provide a local view of a model's decision boundary, which can be used to more accurately evaluate a model's true linguistic capabilities. This paper proposed a new annotation paradigm for NLP to generate contrast samples. 

- **Cross-Domain Sentiment Classification With In-domain Contrastive Learning** 
[[Paper]](https://arxiv.org/pdf/2012.02943.pdf)<br>
Descrption: This paper applies two data augmentation methods, i.e., synonym subtituion and back translation, to define pretext taks in contrastive learning. 

- **Contrast and Classify: Alternate Training for Robust VQA** 
[[Paper]](https://arxiv.org/pdf/2010.06087.pdf)<br>
Descrption: 

## Others
- **Contrastive Multi-View Representation Learning on Graphs**
[[Paper]](https://arxiv.org/pdf/2006.05582.pdf)<br>
Descrption: This paper applis self-supervised approach to learn contrasting sturctural views of graphs. The authors mention contrasting encodings form first-order neighbors and a graph conffusion is more effective than multi-scale encodings in some graph classiification benchmarks. 

## Blogs 
- **Self-Supervised Representation Learning**
[[Link]](https://lilianweng.github.io/lil-log/2019/11/10/self-supervised-learning.html)

- **Contrastive Learning**
[[Link]](https://github.com/HobbitLong/PyContrast)
