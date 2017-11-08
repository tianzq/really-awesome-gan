# really-awesome-gan
A list of papers and other resources on Generative Adversarial (Neural) Networks.
This site is maintained by Holger Caesar.
To complement or correct it, please contact me at holger-at-it-caesar.com or visit [it-caesar.com](http://www.it-caesar.com). Also checkout [really-awesome-semantic-segmentation](https://github.com/nightrome/really-awesome-semantic-segmentation) and our [COCO-Stuff dataset](https://github.com/nightrome/cocostuff).

**Announcement:** Starting from September 1 we are organizing the public [COCO 2017 Stuff Segmentation Challenge](http://cocodataset.org). Please consider participating. Winners will be announced at the [Joint COCO and Places Recognition](https://places-coco2017.github.io/) workshop at ICCV 2017.

## Contents
- [Recommendations](#recommendations)
- [Workshops](#workshops)
- [Tutorials & Workshops & Blogs](#tutorials--workshops--blogs)
- [Videos](#videos)
- [Code](#code)
- [Papers](#papers)
  - [Overview](#overview)
  - [Theory & Machine Learning](#theory--machine-learning)
  - [Applied Vision](#applied-vision)
  - [Applied Other](#applied-other)
  - [Humor](#humor)
  
## Recommendations
<ul>
<li>Beyond Face Rotation: Global and Local Perception GAN for Photorealistic and Identity Preserving Frontal View Synthesis <a href="https://arxiv.org/abs/1704.04086">[arXiv]</a> 
<img src="http://it-caesar.com/github/beyond-face-rotation.png" alt="Beyond face rotation"></li>

<li>Pose Guided Person Image Generation <a href="https://arxiv.org/abs/1705.09368">[arXiv]</a> 
<img src="http://it-caesar.com/github/pose-guided-person.png" alt="Pose guided person"></li>

<li>Unpaired Image-to-Image Translation using Cycle-Consistent Adversarial Networks <a href="https://arxiv.org/abs/1703.10593">[arXiv]</a>  
<img src="http://it-caesar.com/github/cycle-gan.png" alt="Cycle GAN"></li>
</ul>

# Tutorials & Workshops & Blogs
- Columbia Advanced Machine Learning Seminar
  - New Progress on GAN Theory and Practice [[Blog]](https://casmls.github.io/general/2017/04/13/gan.html)
  - Implicit Generative Models — What are you GAN-na do? [[Blog]](https://casmls.github.io/general/2017/05/24/ligm.html)
- How to Train a GAN? Tips and tricks to make GANs work [[Blog]](https://github.com/soumith/ganhacks)
- NIPS 2016 Tutorial: Generative Adversarial Networks [[arXiv]](https://arxiv.org/abs/1701.00160)
- NIPS 2016 Workshop on Adversarial Training [[Web]](https://sites.google.com/site/nips2016adversarial/) [[Blog]](http://www.inference.vc/my-summary-of-adversarial-training-nips-workshop/)
- On the intuition behind deep learning & GANs — towards a fundamental understanding [[Blog]](https://blog.waya.ai/introduction-to-gans-a-boxing-match-b-w-neural-nets-b4e5319cc935)
- OpenAI - Generative Models [[Blog]](https://openai.com/blog/generative-models/)
- SimGANs - a game changer in unsupervised learning, self driving cars, and more [[Blog]](https://blog.waya.ai/simgans-applied-to-autonomous-driving-5a8c6676e36b)

# Videos
- Generative Adversarial Networks by Ian Goodfellow [[Video]](https://channel9.msdn.com/Events/Neural-Information-Processing-Systems-Conference/Neural-Information-Processing-Systems-Conference-NIPS-2016/Generative-Adversarial-Networks)
- Tutorial on Generative Adversarial Networks by Mark Chang [[Video]](https://www.youtube.com/playlist?list=PLeeHDpwX2Kj5Ugx6c9EfDLDojuQxnmxmU)

# Code
- Cleverhans: A library for benchmarking vulnerability to adversarial examples [[Code]](https://github.com/openai/cleverhans) [[Blog]](http://cleverhans.io/)
- Generative Adversarial Networks (GANs) in 50 lines of code (PyTorch) [[Blog]](https://medium.com/@devnag/generative-adversarial-networks-gans-in-50-lines-of-code-pytorch-e81b79659e3f) [[Code]](https://github.com/devnag/pytorch-generative-adversarial-networks)
- Generative Models: Collection of generative models, e.g. GAN, VAE in Pytorch and Tensorflow [[Code]](https://github.com/wiseodd/generative-models)

# Papers
## Overview
- Generative Adversarial Networks: An Overview [[arXiv]](https://arxiv.org/abs/1710.07035)

## Theory & Machine Learning
- A Classification-Based Perspective on GAN Distributions [[arXiv]](https://arxiv.org/abs/1711.00970)
- A Connection between Generative Adversarial Networks, Inverse Reinforcement Learning, and Energy-Based Models [[arXiv]](https://arxiv.org/abs/1611.03852)
- A General Retraining Framework for Scalable Adversarial Classification [[Paper]](https://c4209155-a-62cb3a1a-s-sites.googlegroups.com/site/nips2016adversarial/WAT16_paper_2.pdf)
- Activation Maximization Generative Adversarial Nets [[arXiv]](https://arxiv.org/abs/1703.02000)
- AdaGAN: Boosting Generative Models [[arXiv]](https://arxiv.org/abs/1701.02386)
- Adversarial Autoencoders [[arXiv]](https://arxiv.org/abs/1511.05644)
- Adversarial Discriminative Domain Adaptation [[arXiv]](https://arxiv.org/abs/1702.05464)
- Adversarial Generator-Encoder Networks [[arXiv]](https://arxiv.org/pdf/1704.02304.pdf)
- Adversarial Feature Learning [[arXiv]](https://arxiv.org/abs/1605.09782) [[Code]](https://github.com/wiseodd/generative-models)
- Adversarially Learned Inference [[arXiv]](https://arxiv.org/abs/1606.00704) [[Code]](https://github.com/wiseodd/generative-models)
- AE-GAN: adversarial eliminating with GAN [[arXiv]](https://arxiv.org/abs/1707.05474)
- An Adversarial Regularisation for Semi-Supervised Training of Structured Output Neural Networks [[arXiv]](https://arxiv.org/abs/1702.02382)
- APE-GAN: Adversarial Perturbation Elimination with GAN [[arXiv]](https://arxiv.org/abs/1707.05474)
- Associative Adversarial Networks [[arXiv]](https://arxiv.org/abs/1611.06953)
- Autoencoding beyond pixels using a learned similarity metric [[arXiv]](https://arxiv.org/abs/1512.09300)
- Bayesian Conditional Generative Adverserial Networks [[arXiv]](https://arxiv.org/abs/1706.05477)
- Bayesian GAN [[arXiv]](https://arxiv.org/abs/1705.09558)
- BEGAN: Boundary Equilibrium Generative Adversarial Networks [[Paper]](https://c4209155-a-62cb3a1a-s-sites.googlegroups.com/site/nips2016adversarial/WAT16_paper_4.pdf) [[arXiv]](https://arxiv.org/abs/1703.10717) [[Code]](https://github.com/wiseodd/generative-models)
- Binary Generative Adversarial Networks for Image Retrieval [[arXiv]](https://arxiv.org/abs/1708.04150)
- Boundary-Seeking Generative Adversarial Networks [[arXiv]](https://arxiv.org/abs/1702.08431) [[Code]](https://github.com/wiseodd/generative-models)
- CausalGAN: Learning Causal Implicit Generative Models with Adversarial Training [[arXiv]](https://arxiv.org/abs/1709.02023)
- Class-Splitting Generative Adversarial Networks [[arXiv]](https://arxiv.org/abs/1709.07359)
- Comparison of Maximum Likelihood and GAN-based training of Real NVPs [[arXiv]](https://arxiv.org/abs/1705.05263)
- Conditional CycleGAN for Attribute Guided Face Image Generation [[arXiv]](https://arxiv.org/abs/1705.09966)
- Conditional Generative Adversarial Nets [[arXiv]](https://arxiv.org/abs/1411.1784) [[Code]](https://github.com/wiseodd/generative-models)
- Connecting Generative Adversarial Networks and Actor-Critic Methods [[Paper]](https://c4209155-a-62cb3a1a-s-sites.googlegroups.com/site/nips2016adversarial/WAT16_paper_1.pdf)
- Continual Learning in Generative Adversarial Nets [[arXiv]](https://arxiv.org/abs/1705.08395)
- C-RNN-GAN: Continuous recurrent neural networks with adversarial training [[arXiv]](https://arxiv.org/abs/1611.09904)
- CM-GANs: Cross-modal Generative Adversarial Networks for Common Representation Learning [[arXiv]](https://arxiv.org/abs/1710.05106)
- Cooperative Training of Descriptor and Generator Networks [[arXiv]](https://arxiv.org/abs/1609.09408)
- Coupled Generative Adversarial Networks [[arXiv]](https://arxiv.org/abs/1606.07536) [[Code]](https://github.com/wiseodd/generative-models)
- Dualing GANs [[arXiv]](https://arxiv.org/abs/1706.06216)
- Deep and Hierarchical Implicit Models [[arXiv]](https://arxiv.org/abs/1702.08896)
- Energy-based Generative Adversarial Network [[arXiv]](https://arxiv.org/abs/1609.03126) [[Code]](https://github.com/wiseodd/generative-models)
- Explaining and Harnessing Adversarial Examples [[arXiv]](https://arxiv.org/abs/1412.6572)
- Flow-GAN: Bridging implicit and prescribed learning in generative models [[arXiv]](https://arxiv.org/abs/1705.08868)
- f-GAN: Training Generative Neural Samplers using Variational Divergence Minimization [[arXiv]](https://arxiv.org/abs/1606.00709) [[Code]](https://github.com/wiseodd/generative-models)
- Gang of GANs: Generative Adversarial Networks with Maximum Margin Ranking [[arXiv]](https://arxiv.org/abs/1704.04865)
- Generalization and Equilibrium in Generative Adversarial Nets (GANs) [[arXiv]](https://arxiv.org/abs/1703.00573)
- Generating images with recurrent adversarial networks [[arXiv]](https://arxiv.org/abs/1602.05110)
- Generative Adversarial Networks [[arXiv]](https://arxiv.org/abs/1406.2661) [[Code]](https://github.com/goodfeli/adversarial) [[Code]](https://github.com/wiseodd/generative-models)
- Generative Adversarial Networks as Variational Training of Energy Based Models [[arXiv]](https://arxiv.org/abs/1611.01799)
- Generative Adversarial Networks with Inverse Transformation Unit [[arXiv]](https://arxiv.org/abs/1709.09354)
- Generative Adversarial Parallelization [[arXiv]](https://arxiv.org/abs/1612.04021) [[Code]](https://github.com/wiseodd/generative-models)
- Generative Adversarial Residual Pairwise Networks for One Shot Learning [[arXiv]](https://arxiv.org/abs/1703.08033)
- Generative Adversarial Structured Networks [[Paper]](https://c4209155-a-62cb3a1a-s-sites.googlegroups.com/site/nips2016adversarial/WAT16_paper_14.pdf)
- Generative Cooperative Net for Image Generation and Data Augmentation [[arXiv]](https://arxiv.org/abs/1705.02887)
- Generative Moment Matching Networks [[arXiv]](https://arxiv.org/abs/1502.02761) [[Code]](https://github.com/yujiali/gmmn)
- Generative Semantic Manipulation with Contrasting GAN [[arXiv]](https://arxiv.org/abs/1708.00315)
- Geometric GAN [[arXiv]](https://arxiv.org/abs/1705.02894)
- Good Semi-supervised Learning that Requires a Bad GAN [[arXiv]](https://arxiv.org/abs/1705.09783)
- Gradient descent GAN optimization is locally stable [[arXiv]](https://arxiv.org/abs/1706.04156)
- How to Train Your DRAGAN [[arXiv]](https://arxiv.org/abs/1705.07215)
- Image Quality Assessment Techniques Show Improved Training and Evaluation of Autoencoder Generative Adversarial Networks [[arXiv]](https://arxiv.org/abs/1708.02237)
- Improved Semi-supervised Learning with GANs using Manifold Invariances [[arXiv]](https://arxiv.org/abs/1705.08850)
- Improved Techniques for Training GANs [[arXiv]](https://arxiv.org/abs/1606.03498) [[Code]](https://github.com/openai/improved-gan)
- Improved Training of Wasserstein GANs [[arXiv]](https://arxiv.org/abs/1704.00028) [[Code]](https://github.com/wiseodd/generative-models)
- InfoGAN: Interpretable Representation Learning by Information Maximizing Generative Adversarial Nets [[arXiv]](https://arxiv.org/abs/1606.03657) [[Code]](https://github.com/wiseodd/generative-models)
- Inverting The Generator Of A Generative Adversarial Network [[Paper]](https://c4209155-a-62cb3a1a-s-sites.googlegroups.com/site/nips2016adversarial/WAT16_paper_9.pdf)
- It Takes (Only) Two: Adversarial Generator-Encoder Networks [[arXiv]](https://arxiv.org/abs/1704.02304)
- KGAN: How to Break The Minimax Game in GAN [[arXiv]](https://arxiv.org/abs/1711.01744)
- Learning in Implicit Generative Models [[Paper]](https://c4209155-a-62cb3a1a-s-sites.googlegroups.com/site/nips2016adversarial/WAT16_paper_10.pdf)
- Learning Loss for Knowledge Distillation with Conditional Adversarial Networks [[arXiv]](https://arxiv.org/abs/1709.00513)
- Learning to Discover Cross-Domain Relations with Generative Adversarial Networks [[arXiv]](https://arxiv.org/abs/1703.05192) [[Code]](https://github.com/wiseodd/generative-models)
- Learning Texture Manifolds with the Periodic Spatial GAN [[arXiv]](https://arxiv.org/abs/1705.06566)
- Least Squares Generative Adversarial Networks [[arXiv]](https://arxiv.org/abs/1611.04076) [[Code]](https://github.com/wiseodd/generative-models)
- Linking Generative Adversarial Learning and Binary Classification [[arXiv]](https://arxiv.org/abs/1709.01509)
- Loss-Sensitive Generative Adversarial Networks on Lipschitz Densities [[arXiv]](https://arxiv.org/abs/1701.06264)
- LR-GAN: Layered Recursive Generative Adversarial Networks for Image Generation [[arXiv]](https://arxiv.org/abs/1703.01560)
- MAGAN: Margin Adaptation for Generative Adversarial Networks [[arXiv]](https://arxiv.org/abs/1704.03817) [[Code]](https://github.com/wiseodd/generative-models)
- Maximum-Likelihood Augmented Discrete Generative Adversarial Networks [[arXiv]](https://arxiv.org/abs/1702.07983)
- McGan: Mean and Covariance Feature Matching GAN [[arXiv]](https://arxiv.org/abs/1702.08398)
- Message Passing Multi-Agent GANs [[arXiv]](https://arxiv.org/abs/1612.01294)
- MMD GAN: Towards Deeper Understanding of Moment Matching Network [[arXiv]](https://arxiv.org/abs/1705.08584)
- Mode Regularized Generative Adversarial Networks [[arXiv]](https://arxiv.org/abs/1612.02136) [[Code]](https://github.com/wiseodd/generative-models)
- Multi-Agent Diverse Generative Adversarial Networks [[arXiv]](https://arxiv.org/abs/1704.02906)
- Multi-Generator Gernerative Adversarial Nets [[arXiv]](https://arxiv.org/abs/1708.02556)
- Objective-Reinforced Generative Adversarial Networks (ORGAN) for Sequence Generation Models [[arXiv]](https://arxiv.org/abs/1705.10843)
- On Convergence and Stability of GANs [[arXiv]](https://arxiv.org/abs/1705.07215)
- On the effect of Batch Normalization and Weight Normalization in Generative Adversarial Networks [[arXiv]](https://arxiv.org/abs/1704.03971)
- On the Quantitative Analysis of Decoder-Based Generative Models [[arXiv]](https://arxiv.org/abs/1611.04273)
- Optimizing the Latent Space of Generative Networks [[arXiv]](https://arxiv.org/abs/1707.05776)
- Parametrizing filters of a CNN with a GAN [[arXiv]](https://arxiv.org/abs/1710.11386)
- PixelGAN Autoencoders [[arXiv]](https://arxiv.org/abs/1706.00531)
- SegAN: Adversarial Network with Multi-scale L1 Loss for Medical Image Segmentation [[arXiv]](https://arxiv.org/abs/1706.01805)
- SeqGAN: Sequence Generative Adversarial Nets with Policy Gradient [[arXiv]](https://arxiv.org/abs/1609.05473)
- Simple Black-Box Adversarial Perturbations for Deep Networks [[Paper]](https://c4209155-a-62cb3a1a-s-sites.googlegroups.com/site/nips2016adversarial/WAT16_paper_11.pdf)
- Softmax GAN [[arXiv]](https://arxiv.org/abs/1704.06191)
- Stabilizing Training of Generative Adversarial Networks through Regularization [[arXiv]](https://arxiv.org/abs/1705.09367)
- Stacked Generative Adversarial Networks [[arXiv]](https://arxiv.org/abs/1612.04357)
- Statistics of Deep Generated Images [[arXiv]](https://arxiv.org/abs/1708.02688)
- Structured Generative Adversarial Networks [[arXiv]](https://arxiv.org/abs/1711.00889)
- Tensorizing Generative Adversarial Nets [[arXiv]](https://arxiv.org/abs/1710.10772)
- The Cramer Distance as a Solution to Biased Wasserstein Gradients [[arXiv]](https://arxiv.org/abs/1705.10743)
- Towards Understanding Adversarial Learning for Joint Distribution Matching [[arXiv]](https://arxiv.org/abs/1709.01215)
- Training generative neural networks via Maximum Mean Discrepancy optimization [[arXiv]](https://arxiv.org/abs/1505.03906)
- Triple Generative Adversarial Nets [[arXiv]](https://arxiv.org/abs/1703.02291)
- Unrolled Generative Adversarial Networks [[arXiv]](https://arxiv.org/abs/1611.02163)
- Unsupervised Representation Learning with Deep Convolutional Generative Adversarial Networks [[arXiv]](https://arxiv.org/abs/1511.06434) [[Code]](https://github.com/Newmu/dcgan_code) [[Code]](https://github.com/pytorch/examples/tree/master/dcgan) [[Code]](https://github.com/carpedm20/DCGAN-tensorflow) [[Code]](https://github.com/soumith/dcgan.torch) [[Code]](https://github.com/jacobgil/keras-dcgan)
- Wasserstein GAN [[arXiv]](https://arxiv.org/abs/1701.07875) [[Code]](https://github.com/martinarjovsky/WassersteinGAN) [[Code]](https://github.com/wiseodd/generative-models)

## Applied Vision
- 3D Object Reconstruction from a Single Depth View with Adversarial Learning [[arXiv]](https://arxiv.org/abs/1708.07969)
- 3D Shape Induction from 2D Views of Multiple Objects [[arXiv]](https://arxiv.org/abs/1612.05872)
- A step towards procedural terrain generation with GANs [[arXiv]](https://arxiv.org/abs/1707.03383) [[Code]](https://github.com/christopher-beckham/gan-heightmaps)
- Abnormal Event Detection in Videos using Generative Adversarial Nets [[arXiv]](https://arxiv.org/abs/1708.09644)
- Adversarial Generation of Training Examples for Vehicle License Plate Recognition [[arXiv]](https://arxiv.org/abs/1707.03124)
- Adversarial nets with perceptual losses for text-to-image synthesis [[arXiv]](https://arxiv.org/abs/1708.09321)
- Adversarial Networks for Spatial Context-Aware Spectral Image Reconstruction from RGB [[arXiv]](https://arxiv.org/abs/1709.00265)
- Adversarial Networks for the Detection of Aggressive Prostate Cancer [[arXiv]](https://arxiv.org/abs/1702.08014)
- Adversarial PoseNet: A Structure-aware Convolutional Network for Human Pose Estimation [[arXiv]](https://arxiv.org/pdf/1705.00389.pdf)
- Adversarial Training For Sketch Retrieval [[arXiv]](https://arxiv.org/abs/1607.02748)
- Aesthetic-Driven Image Enhancement by Adversarial Learning [[arXiv]](https://arxiv.org/abs/1707.05251)
- Age Progression / Regression by Conditional Adversarial Autoencoder [[arXiv]](https://arxiv.org/abs/1702.08423)
- AlignGAN: Learning to Align Cross-Domain Images with Conditional Generative Adversarial Networks [[arXiv]](https://arxiv.org/abs/1707.01400)
- Amortised MAP Inference for Image Super-resolution [[arXiv]](https://arxiv.org/abs/1610.04490)
- A Novel Approach to Artistic Textual Visualization via GAN [[arXiv]](https://arxiv.org/abs/1710.10553)
- Anti-Makeup: Learning A Bi-Level Adversarial Network for Makeup-Invariant Face Verification [[arXiv]](https://arxiv.org/abs/1709.03654)
- ARIGAN: Synthetic Arabidopsis Plants using Generative Adversarial Network [[arXiv]](https://arxiv.org/abs/1709.00938)
- ArtGAN: Artwork Synthesis with Conditional Categorial GANs [[arXiv]](https://arxiv.org/abs/1702.03410)
- Artificial Generation of Big Data for Improving Image Classification: A Generative Adversarial Network Approach on SAR Data [[arXiv]](https://arxiv.org/abs/1711.02010)
- Auto-Encoder Guided GAN for Chinese Calligraphy Synthesis [[arXiv]](https://arxiv.org/abs/1706.08789)
- Auto-painter: Cartoon Image Generation from Sketch by Using Conditional Generative Adversarial Networks [[arXiv]](https://arxiv.org/abs/1705.01908)
- Automatic Liver Segmentation Using an Adversarial Image-to-Image Network [[arXiv]](https://arxiv.org/abs/1707.08037)
- Beyond Face Rotation: Global and Local Perception GAN for Photorealistic and Identity Preserving Frontal View Synthesis [[arXiv]](https://arxiv.org/abs/1704.04086)
- CAN: Creative Adversarial Networks Generating “Art” by Learning About Styles and Deviating from Style Norms [[arXiv]](https://arxiv.org/abs/1706.07068)
- Compressed Sensing MRI Reconstruction with Cyclic Loss in Generative Adversarial Networks [[arXiv]](https://arxiv.org/abs/1709.00753)
- Conditional Adversarial Network for Semantic Segmentation of Brain Tumor [[arXiv]](https://arxiv.org/abs/1708.05227)
- Conditional generative adversarial nets for convolutional face generation [[Paper]](http://www.foldl.me/uploads/2015/conditional-gans-face-generation/paper.pdf)
- Conditional Image Synthesis with Auxiliary Classifier GANs [[Paper]](https://c4209155-a-62cb3a1a-s-sites.googlegroups.com/site/nips2016adversarial/WAT16_paper_7.pdf) [[arXiv]](https://arxiv.org/abs/1610.09585) [[Code]](https://github.com/wiseodd/generative-models)
- Contextual RNN-GANs for Abstract Reasoning Diagram Generation [[arXiv]](https://arxiv.org/abs/1609.09444)
- Controllable Generative Adversarial Network [[arXiv]](https://arxiv.org/abs/1708.00598)
- Creatism: A deep-learning photographer capable of creating professional work [[arXiv]](https://arxiv.org/abs/1707.03491)
- Crossing Nets: Combining GANs and VAEs with a Shared Latent Space for Hand Pose Estimation [[arXiv]](https://arxiv.org/abs/1702.03431)
- CVAE-GAN: Fine-Grained Image Generation through Asymmetric Training [[arXiv]](https://arxiv.org/abs/1703.10155)
- Data Augmentation in Classification using GAN [[arXiv]](https://arxiv.org/abs/1711.00648)
- Deep Generative Adversarial Compression Artifact Removal [[arXiv]](https://arxiv.org/abs/1704.02518)
- Deep Generative Adversarial Networks for Compressed Sensing (GANCS) Automates MRI [[arXiv]](https://arxiv.org/abs/1706.00051)
- Deep Generative Adversarial Neural Networks for Realistic Prostate Lesion MRI Synthesis [[arXiv]](https://arxiv.org/abs/1708.00129)
- Deep Generative Image Models using a Laplacian Pyramid of Adversarial Networks [[arXiv]](https://arxiv.org/abs/1506.05751) [[Code]](https://github.com/facebook/eyescream) [[Blog]](http://soumith.ch/eyescream/)
- Deep multi-scale video prediction beyond mean square error [[arXiv]](https://arxiv.org/abs/1511.05440) [[Code]](https://github.com/dyelax/Adversarial_Video_Generation)
- Deep Unsupervised Representation Learning for Remote Sensing Images [[arXiv]](https://arxiv.org/abs/1612.08879)
- DeLiGAN : Generative Adversarial Networks for Diverse and Limited Data [[arXiv]](https://arxiv.org/abs/1706.02071)
- Depth Structure Preserving Scene Image Generation [[arXiv]](https://arxiv.org/abs/1706.00212)
- DualGAN: Unsupervised Dual Learning for Image-to-Image Translation [[arXiv]](https://arxiv.org/abs/1704.02510) [[Code]](https://github.com/wiseodd/generative-models)
- Dual Motion GAN for Future-Flow Embedded Video Prediction [[arXiv]](https://arxiv.org/abs/1708.00284)
- ExprGAN: Facial Expression Editing with Controllable Expression Intensity [[arXiv]](https://arxiv.org/abs/1709.03842)
- Face Aging With Conditional Generative Adversarial Networks [[arXiv]](https://arxiv.org/abs/1702.01983)
- Face Transfer with Generative Adversarial Network [[arXiv]](https://arxiv.org/abs/1710.06090)
- Filmy Cloud Removal on Satellite Imagery with Multispectral Conditional Generative Adversarial Nets [[arXiv]](https://arxiv.org/abs/1710.04835)
- Freehand Ultrasound Image Simulation with Spatially-Conditioned Generative Adversarial Networks [[arXiv]](https://arxiv.org/abs/1707.05392)
- From source to target and back: symmetric bi-directional adaptive GAN [[arXiv]](https://arxiv.org/abs/1705.08824)
- Full Resolution Image Compression with Recurrent Neural Networks [[arXiv]](https://arxiv.org/abs/1608.05148)
- GANs for Biological Image Synthesis [[arXiv]](https://arxiv.org/abs/1708.04692)
- GeneGAN: Learning Object Transfiguration and Attribute Subspace from Unpaired Data [[arXiv]](https://arxiv.org/abs/1705.04932) [[Code]](https://github.com/Prinsphield/GeneGAN)
- Generate Identity-Preserving Faces by Generative Adversarial Networks [[arXiv]](https://arxiv.org/abs/1706.03227)
- Generate To Adapt: Aligning Domains using Generative Adversarial Networks [[arXiv]](https://arxiv.org/abs/1704.01705)
- Generative Adversarial Models for People Attribute Recognition in Surveillance [[arXiv]](https://arxiv.org/abs/1707.02240)
- Generative Adversarial Network based on Resnet for Conditional Image Restoration [[arxiv]](https://arxiv.org/abs/1707.04881)
- Generative Adversarial Network-based Synthesis of Visible Faces from Polarimetric Thermal Faces [[arXiv]](https://arxiv.org/abs/1708.02681)
- Generative Adversarial Networks for Multimodal Representation Learning in Video Hyperlinking [[arXiv]](https://arxiv.org/abs/1705.05103)
- Generative Adversarial Text to Image Synthesis [[arXiv]](https://arxiv.org/abs/1605.05396) [[Code]](https://github.com/paarthneekhara/text-to-image)
- Generative Visual Manipulation on the Natural Image Manifold [[Project]](http://www.eecs.berkeley.edu/~junyanz/projects/gvm/) [[Youtube]](https://youtu.be/9c4z6YsBGQ0) [[Paper]](https://arxiv.org/abs/1609.03552) [[Code]](https://github.com/junyanz/iGAN)
- GP-GAN: Gender Preserving GAN for Synthesizing Faces from Landmarks [[arXiv]](https://arxiv.org/abs/1710.00962)
- GP-GAN: Towards Realistic High-Resolution Image Blending [[arXiv]](https://arxiv.org/abs/1703.07195)
- Guiding InfoGAN with Semi-Supervision [[arXiv]](https://arxiv.org/abs/1707.04487)
- How to Fool Radiologists with Generative Adversarial Networks? A Visual Turing Test for Lung Cancer Diagnosis [[arXiv]](https://arxiv.org/abs/1710.09762)
- Hierarchical Detail Enhancing Mesh-Based Shape Generation with 3D Generative Adversarial Network [[arXiv]](https://arxiv.org/abs/1709.07581)
- High-Quality Face Image SR Using Conditional Generative Adversarial Networks [[arXiv]](https://arxiv.org/abs/1707.00737)
- High-Quality Facial Photo-Sketch Synthesis Using Multi-Adversarial Networks [[arXiv]](https://arxiv.org/abs/1710.10182)
- Image De-raining Using a Conditional Generative Adversarial Network [[arXiv]](https://arxiv.org/abs/1701.05957)
- Image Generation and Editing with Variational Info Generative Adversarial Networks [[arXiv]](https://arxiv.org/abs/1701.04568)
- Image-to-Image Translation with Conditional Adversarial Networks [[arXiv]](https://arxiv.org/abs/1611.07004) [[Code]](https://github.com/phillipi/pix2pix)
- Improved Adversarial Systems for 3D Object Generation and Reconstruction [[arXiv]](https://arxiv.org/abs/1707.09557) [[Code]](https://github.com/EdwardSmith1884/3D-IWGAN)
- Improving Heterogeneous Face Recognition with Conditional Adversarial Networks [[arXiv]](https://arxiv.org/abs/1709.02848)
- Improving image generative models with human interactions [[arXiv]](https://arxiv.org/abs/1709.10459)
- Imitating Driver Behavior with Generative Adversarial Networks [[arXiv]](https://arxiv.org/abs/1701.06699)
- Interactive 3D Modeling with a Generative Adversarial Network [[arXiv]](https://arxiv.org/abs/1706.05170)
- Intraoperative Organ Motion Models with an Ensemble of Conditional Generative Adversarial Networks [[arXiv]](https://arxiv.org/abs/1709.02255)
- Invertible Conditional GANs for image editing [[arXiv]](https://arxiv.org/abs/1611.06355) [[Paper]](https://c4209155-a-62cb3a1a-s-sites.googlegroups.com/site/nips2016adversarial/WAT16_paper_8.pdf)
- Label Denoising Adversarial Network (LDAN) for Inverse Lighting of Face Images [[arXiv]](https://arxiv.org/abs/1709.01993)
- Learning a Driving Simulator [[arXiv]](https://arxiv.org/abs/1608.01230)
- Learning a Generative Adversarial Network for High Resolution Artwork Synthesis [[arXiv]](https://arxiv.org/abs/1708.09533)
- Learning a Probabilistic Latent Space of Object Shapes via 3D Generative-Adversarial Modeling [[arXiv]](https://arxiv.org/abs/1610.07584)
- Learning from Simulated and Unsupervised Images through Adversarial Training [[arXiv]](https://arxiv.org/abs/1612.07828)
- Learning to Discover Cross-Domain Relations with Generative Adversarial Networks [[arXiv]](https://arxiv.org/abs/1703.05192)
- Learning to Generate Chairs with Generative Adversarial Nets [[arXiv]](https://arxiv.org/abs/1705.10413)
- Learning to Generate Time-Lapse Videos Using Multi-Stage Dynamic Generative Adversarial Networks [[arXiv]](https://arxiv.org/abs/1709.07592)
- Low Dose CT Image Denoising Using a Generative Adversarial Network with Wasserstein Distance and Perceptual Loss [[arXiv]](https://arxiv.org/abs/1708.00961)
- MARTA GANs: Unsupervised Representation Learning for Remote Sensing Image Classification [[arXiv]](https://arxiv.org/abs/1612.08879)
- Megapixel Size Image Creation using Generative Adversarial Networks [[arXiv]](https://arxiv.org/abs/1706.00082)
- Microscopy Cell Segmentation via Adversarial Neural Networks [[arXiv]](https://arxiv.org/abs/1709.05860)
- MoCoGAN: Decomposing Motion and Content for Video Generation [[arXiv]](https://arxiv.org/abs/1707.04993)
- Multi-view Generative Adversarial Networks [[Paper]](https://c4209155-a-62cb3a1a-s-sites.googlegroups.com/site/nips2016adversarial/WAT16_paper_13.pdf)
- Neural Photo Editing with Introspective Adversarial Networks [[Paper]](https://c4209155-a-62cb3a1a-s-sites.googlegroups.com/site/nips2016adversarial/WAT16_paper_15.pdf) [[arXiv]](https://arxiv.org/abs/1609.07093)
- Neural Stain-Style Transfer Learning using GAN for Histopathological Images [[arXiv]](https://arxiv.org/abs/1710.08543)
- Outline Colorization through Tandem Adversarial Networks [[arXiv]](https://arxiv.org/abs/1704.08834)
- Perceptual Adversarial Networks for Image-to-Image Transformation [[arXiv]](https://arxiv.org/abs/1706.09138)
- Perceptual Generative Adversarial Networks for Small Object Detection [[arXiv]](https://arxiv.org/abs/1706.05274)
- Photo-Realistic Single Image Super-Resolution Using a Generative Adversarial Network [[arXiv]](https://arxiv.org/abs/1609.04802)
- Pose Guided Person Image Generation [[arXiv]](https://arxiv.org/abs/1705.09368)
- Precomputed Real-Time Texture Synthesis with Markovian Generative Adversarial Networks [[arXiv]](https://arxiv.org/abs/1604.04382)
- Recurrent Topic-Transition GAN for Visual Paragraph Generation [[arXiv]](https://arxiv.org/abs/1703.07022)
- RenderGAN: Generating Realistic Labeled Data [[arXiv]](https://arxiv.org/abs/1611.01331)
- Representation Learning and Adversarial Generation of 3D Point Clouds [[arXiv]](https://arxiv.org/abs/1707.02392)
- Retinal Vasculature Segmentation Using Local Saliency Maps and Generative Adversarial Networks For Image Super Resolution [[arXiv]](https://arxiv.org/abs/1710.04783)
- Retinal Vessel Segmentation in Fundoscopic Images with Generative Adversarial Networks [[arXiv]](https://arxiv.org/abs/1706.09318)
- SAD-GAN: Synthetic Autonomous Driving using Generative Adversarial Networks [[arXiv]](https://arxiv.org/abs/1611.08788)
- SalGAN: Visual Saliency Prediction with Generative Adversarial Networks [[arXiv]](https://arxiv.org/abs/1701.01081v2)
- SegAN: Adversarial Network with Multi-scale L1 Loss for Medical Image Segmentation [[arXiv]](https://arxiv.org/abs/1706.01805)
- SeGAN: Segmenting and Generating the Invisible [[arXiv]](https://arxiv.org/abs/1703.10239)
- Semantic Image Inpainting with Deep Generative Models [[arXiv]](https://arxiv.org/abs/1607.07539)
- Semantic Image Synthesis via Adversarial Learning [[arXiv]](https://arxiv.org/abs/1707.06873)
- Semantic Segmentation using Adversarial Networks [[arXiv]](https://arxiv.org/abs/1611.08408)
- Semantically Decomposing the Latent Spaces of Generative Adversarial Networks [[arXiv]](https://arxiv.org/abs/1705.07904)
- Semi-Latent GAN: Learning to generate and modify facial images from attributes [[arXiv]](https://arxiv.org/abs/1704.02166)
- Semi-Supervised Learning with Context-Conditional Generative Adversarial Networks [[arXiv]](https://arxiv.org/abs/1611.06430)
- Sharpness-aware Low dose CT denoising using conditional generative adversarial network [[arXiv]](https://arxiv.org/abs/1708.06453)
- Simultaneously Color-Depth Super-Resolution with Conditional Generative Adversarial Network [[arXiv]](https://arxiv.org/abs/1708.09105)
- Socially-compliant Navigation through Raw Depth Inputs with Generative Adversarial Imitation Learning [[arXiv]](https://arxiv.org/abs/1710.02543)
- StackGAN: Text to Photo-realistic Image Synthesis with Stacked Generative Adversarial Networks [[arXiv]](https://arxiv.org/abs/1612.03242)
- StackGAN++: Realistic Image Synthesis with Stacked Generative Adversarial Networks [[arXiv]](https://arxiv.org/abs/1710.10916)
- Style Transfer for Sketches with Enhanced Residual U-net and Auxiliary Classifier GAN [[arXiv]](https://arxiv.org/abs/1706.03319)
- Supervised Adversarial Networks for Image Saliency Detection [[arXiv]](https://arxiv.org/abs/1704.07242)
- Synthesis of Positron Emission Tomography (PET) Images via Multi-channel Generative Adversarial Networks (GANs) [[arXiv]](https://arxiv.org/abs/1707.09747)
- Synthesizing Filamentary Structured Images with GANs [[arXiv]](https://arxiv.org/abs/1706.02185)
- Synthetic Iris Presentation Attack using iDCGAN [[arXiv]](https://arxiv.org/abs/1710.10565)
- Synthetic Medical Images from Dual Generative Adversarial Networks [[arXiv]](https://arxiv.org/abs/1709.01872)
- TAC-GAN - Text Conditioned Auxiliary Classifier Generative Adversarial Network [[arXiv]](https://arxiv.org/abs/1703.06412)
- Temporal Generative Adversarial Nets with Singular Value Clipping [[arXiv]](https://arxiv.org/abs/1611.06624)
- TextureGAN: Controlling Deep Image Synthesis with Texture Patches [[arXiv]](https://arxiv.org/abs/1706.02823)
- Texture Synthesis with Spatial Generative Adversarial Networks [[arXiv]](https://arxiv.org/abs/1611.08207v3) [[Code]](https://github.com/ubergmann/spatial_gan)
- The Conditional Analogy GAN: Swapping Fashion Articles on People Images [[arXiv]](https://arxiv.org/abs/1709.04695)
- Towards Adversarial Retinal Image Synthesis [[arXiv]](https://arxiv.org/abs/1701.08974) [[Code]](https://github.com/costapt/vess2ret) [[Demo]](http://vess2ret.inesctec.pt/retina)
- Towards Diverse and Natural Image Descriptions via a Conditional GAN [[arXiv]](https://arxiv.org/abs/1703.06029)
- Towards the Automatic Anime Characters Creation with Generative Adversarial Networks [[arXiv]](https://arxiv.org/abs/1708.05509)
- Unlabeled Samples Generated by GAN Improve the Person Re-identification Baseline in vitro [[arXiv]](https://arxiv.org/abs/1701.07717)
- Unpaired Image-to-Image Translation using Cycle-Consistent Adversarial Networks [[arXiv]](https://arxiv.org/abs/1703.10593)
- Unsupervised and Semi-supervised Learning with Categorical Generative Adversarial Networks [[arXiv]](https://arxiv.org/abs/1511.06390)
- Unsupervised Anomaly Detection with Generative Adversarial Networks to Guide Marker Discovery [[arXiv]](https://arxiv.org/abs/1703.05921)
- Unsupervised Cross-Domain Image Generation [[arXiv]](https://arxiv.org/abs/1611.02200)
- Unsupervised Diverse Colorization via Generative Adversarial Networks [[arXiv]](https://arxiv.org/abs/1702.06674)
- Unsupervised Pixel–Level Domain Adaptation with Generative Adversarial Networks [[arXiv]](https://arxiv.org/abs/1612.05424)
- Unsupervised Visual Attribute Transfer with Reconfigurable Generative Adversarial Networks [[arXiv]](https://arxiv.org/abs/1707.09798)
- VIGAN: Missing View Imputation with Generative Adversarial Networks [[arXiv]](https://arxiv.org/abs/1708.06724)
- WaterGAN: Unsupervised Generative Network to Enable Real-time Color Correction of Monocular Underwater Images [[arXiv]](https://arxiv.org/abs/1702.07392)
- Weakly Supervised Generative Adversarial Networks for 3D Reconstruction [[arXiv]](https://arxiv.org/abs/1705.10904)

## Applied Other
- Adversarial Generation of Natural Language [[arXiv]](https://arxiv.org/abs/1705.10929)
- Adversarial Ranking for Language Generation [[arXiv]](https://arxiv.org/abs/1705.11001)
- Adversarial Training Methods for Semi-Supervised Text Classification [[arXiv]](https://arxiv.org/abs/1605.07725) [[Paper]](https://c4209155-a-62cb3a1a-s-sites.googlegroups.com/site/nips2016adversarial/WAT16_paper_12.pdf)
- A Generative Model for Volume Rendering [[arXiv]](A Generative Model for Volume Rendering)
- ChemGAN challenge for drug discovery: can AI reproduce natural chemical diversity? [[arXiv]](https://arxiv.org/abs/1708.08227)
- Generating Adversarial Malware Examples for Black-Box Attacks Based on GAN [[arXiv]](https://arxiv.org/abs/1702.05983)
- Generating Multi-label Discrete Electronic Health Records using Generative Adversarial Networks [[arXiv]](https://arxiv.org/abs/1703.06490)
- Language Generation with Recurrent Generative Adversarial Networks without Pre-training [[arXiv]](https://arxiv.org/abs/1706.01399)
- Learning to Protect Communications with Adversarial Neural Cryptography [[arXiv]](https://arxiv.org/abs/1610.06918) [[Blog]](https://blog.acolyer.org/2017/02/10/learning-to-protect-communications-with-adversarial-neural-cryptography/)
- Long Text Generation via Adversarial Training with Leaked Information [[arXiv]](https://arxiv.org/abs/1709.08624)
- MidiNet: A Convolutional Generative Adversarial Network for Symbolic-domain Music Generation using 1D and 2D Conditions [[arXiv]](https://arxiv.org/abs/1703.10847)
- MuseGAN: Symbolic-domain Music Generation and Accompaniment with Multi-track Sequential Generative Adversarial Networks [[arXiv]](https://arxiv.org/abs/1709.06298)
- Reconstruction of three-dimensional porous media using generative adversarial neural networks [[arXiv]](https://arxiv.org/abs/1704.03225) [[Code]](https://github.com/LukasMosser/PorousMediaGan)
- SEGAN: Speech Enhancement Generative Adversarial Network [[arXiv]](https://arxiv.org/abs/1703.09452)
- Semi-supervised Learning of Compact Document Representations with Deep Networks [[Paper]](http://www.cs.nyu.edu/~ranzato/publications/ranzato-icml08.pdf)
- SSGAN: Secure Steganography Based on Generative Adversarial Networks [[arXiv]](https://arxiv.org/abs/1707.01613)
- Steganographic Generative Adversarial Networks [[arXiv]](https://arxiv.org/abs/1703.05502)
- Towards Grounding Conceptual Spaces in Neural Representations [[arXiv]](https://arxiv.org/abs/1706.04825)

## Humor
- Stopping GAN Violence: Generative Unadversarial Networks [[arXiv]](https://arxiv.org/abs/1703.02528)
