# WTF-is-Deep-Learning
My notes, experiences, progress, and resources for building Deep Learning expertise and slaying grad school. \
Focal Topics: Machine Learning, Deep Learning, Computer Vision, Biomedical Imaging
<br><br>
**Plan for 2020**: Intensively read 6 papers a week (1 per day Mon to Sat, review on Sun), and submit notes for each of them. The 6 papers will be divided into 2 general categories: (1) Breadth - aimed at solidifying DL foundations (2) Depth - for advancing relevant expertise for current projects and my dissertation in general.
<br><br>
(Inspired by: [Patrick Liu](https://github.com/patrick-llgc/Learning-Deep-Learning))

### Contents
1. [Resources](#i-resources)
    * Meta-Learning - learning how to learn, effective research, process-focused incremental improvement
    * Papers - sources to keep up with literature
    * Courses - great beginner and PhD-level courses
    * Talks - seminars, conference talks, stand-alone lectures
2. [Paper Notes](#ii-paper-notes)
    - Weekly list of papers I read, notes on the, and publication info

### Search (Cmd-F)
**By Year** - 2002 to 2020 \
**By Conference** -
   e.g. CVPR, NIPS, MICCAI, ICLR, ICCV, ICML, ECCV \
**By Topic Category** -
   e.g. [Gml], [Opt], [Net], [Loc], [Uns], [Ano], [Vid]
   * [Gml] General ML (Thinking Frameworks, Theory, Math, 
   * [Opt] Training & Optimization
   * [Net] Networks (FeatEx Backbones, Modules, Aggregation Methods, Components, Analysis)
   * [Loc] Localization (Object Detection, Segmentation)
   * [Uns] Unsupervised Techniques (GAN, VAE, Self-Supervised, Contrastive)
   * [Ano] Annotation Reduction (Active/Transfer Learning, Semi/Weakly-Supervised)
   * [Vid] Video (Multi-Object Tracking, Temporal Features)

# I. Resources

### Meta-Learning 

Learning how to learn.
* Paper on How to Read a Paper [[pdf](/meta/how_to_read_a_paper.pdf)]
* Andrew Ng - Reading Research Papers & Career Advice [[vid](https://www.youtube.com/watch?v=733m6qBH-jI)]
* How to Release Research Code [[git](https://github.com/paperswithcode/releasing-research-code)]

### Papers

Primary
* Google Scholar - Follow Relevant Authors [[site](https://scholar.google.com/citations?hl=en&view_op=search_authors&mauthors=label:computer_vision)]
* ArXiV Preprints - Computer Vision [[site](https://arxiv.org/list/cs.CV/recent)]
* ArXiV Preprints - Organized-ish [[site](http://www.arxiv-sanity.com/)]
* Open Review [[site](https://openreview.net/)]
* Computer Vision Foundation Open Access [[site](http://openaccess.thecvf.com/menu.py)]
* All NIPS Proceedings [[site](https://papers.nips.cc/)]
* Papers With Code [[site](https://paperswithcode.com/)]

Community Discourse & Mentions
* r/MachineLearning Subreddit [[sub](https://www.reddit.com/r/MachineLearning/)]
* Twitter [[followlist](https://www.reddit.com/r/MachineLearning/comments/5jjzny/d_deep_learning_twitter_loop/)]

### Courses & Books

Fundamentals
* 🌟 All-in-one List of *Many* Topics [[repo](https://github.com/kmario23/deep-learning-drizzle)]
* MIT Patrick Winston - Classic Artifical Intelligence 2010 [[playlist](https://www.youtube.com/playlist?list=PLUl4u3cNGP63gFHB6xb-kVBiQHYe_4hSi)]
* ⭐ Stanford CS231n - CNNs for Visual Recognition [[site](http://cs231n.stanford.edu/)]
* Stanford Andrew Ng - Deep Learning Specialization [[coursera](https://www.coursera.org/specializations/deep-learning)]
* Geoffrey Hinton - NNs for Machine Learning [[playlist](https://www.youtube.com/watch?v=OVwEeSsSCHE&list=PLLssT5z_DsK_gyrQ_biidwvPYCRNGI3iv)]
* Columbia Andreas Mueller - Applied Machine Learning 2020 [[playlist](https://www.youtube.com/playlist?list=PL_pVmAaAnxIRnSw6wiCpSvshFyCREZmlM)]
* Carnegie Mellon University - Array of Deep Learning Courses 2020 [[playlists](https://www.youtube.com/channel/UC8hYZGEkI2dDO8scT8C5UQA/playlists)]

Specialized
* deeplearning.ai - AI for Medicine Specialization [[coursera](https://www.coursera.org/specializations/ai-for-medicine)]
* ⭐ Berkeley Pieter Abbeel - Deep Unsupervised Learning [[playlist](https://www.youtube.com/watch?v=V9Roouqfu-M&list=PLwRJQ4m4UJjPiJP3691u-qWwPGVKzSlNP)]

Books
* Dive into Deep Learning (w/PyTorch Implementations) [[site](http://d2l.ai/index.html)]


### Misc

Biomedical Topics
* Biomedical Image Segmentation Loss Functions in PyTorch [[repo](https://github.com/JunMa11/SegLoss)]
* Paper List on Uncertainty Theory and Applications in Medical Analysis [[repo](https://github.com/JunMa11/MedUncertainty)]


Conferences, Events, and Challenges
* Computer Vision Conferences [[site](http://conferences.visionbib.com/Iris-Conferences.html)]
* Biomedical Challenges [[site](https://grand-challenge.org/challenges/)]

# II. Paper Notes

Wish-List - 
Breadth: ML Perspectives
* [Hidden Technical Debt in Machine Learning Systems](https://papers.nips.cc/paper/5656-hidden-technical-debt-in-machine-learning-systems.pdf) [[TBP]()] <kbd>NIPS 2015</kbd>
* [Statistical Modeling: The Two Cultures](https://www.semanticscholar.org/paper/Statistical-Modeling%3A-The-Two-Cultures-Breiman/e5df6bc6da5653ad98e754b08f63326c2e52b372) [[TBP](papers/2002_stat_modeling_2cultures.md)] <kbd>2001</kbd>
* [A Few Useful Things to Know About Machine Learning](https://homes.cs.washington.edu/~pedrod/papers/cacm12.pdf) [[TBP](papers/2012_useful_things_about_ml.md)] <kbd>2012</kbd>
* [Measuring the tendency of CNNs to Learn Surface Statistical Regularities](https://arxiv.org/abs/1711.11561) <kbd>2017</kbd>
* [Investigating Human Priors for Playing Video Games](https://arxiv.org/abs/1802.10217) <kbd>ICLR 2018</kbd>

Architectures and Model Components
* [Batch Normalization: Accelerating DNN Training by Reducing Internal Covariate Shift](https://arxiv.org/abs/1502.03167) [[TBP]()]
* [EfficientNet: Rethinking Model Scaling for CNNs](https://arxiv.org/abs/1905.11946) [[TBP]()] <kbd>ICML 2019</kbd>
* [Selective Kernel Networks](https://arxiv.org/abs/1903.06586)
* [NCE: New Estimation Principle for Unnormalized Statistical Models](http://proceedings.mlr.press/v9/gutmann10a/gutmann10a.pdf) [[]()]

Breadth: Deep Learning Fundamental Concepts
* [Computing Receptive Fields of CNNs](https://distill.pub/2019/computing-receptive-fields/) [[TBP]()] <kbd>Distill 2019</kbd>
* [Why Momentum Really Works](https://distill.pub/2017/momentum/) [[TBP]()] <kbd>Distill 2017</kbd>
* [Visualizing Neural Networks with the Grand Tour](https://distill.pub/2020/grand-tour/) [[TBP]()] <kbd>Distill 2020</kbd>
* [The Building Blocks of Interpretability](https://distill.pub/2018/building-blocks/) [[TBP]()] <kbd>Distill 2018</kbd>

### Wk13 - 2020.10.20
Semi-Supervised Learning
* [(Topic) Null Space Deep Learning](https://docs.google.com/document/d/e/2PACX-1vTID-8qXRE4se-u_qtHYv017llQ140QyFigJb64WsJBLBRBFpbEoS07wphtW8d7FMtmfvx7AtqoEkCf/pub) [[Notes](https://docs.google.com/document/d/e/2PACX-1vTID-8qXRE4se-u_qtHYv017llQ140QyFigJb64WsJBLBRBFpbEoS07wphtW8d7FMtmfvx7AtqoEkCf/pub)]
* [Semi-supervised Machine Learning with MixMatch and Equivalence Classes](https://link.springer.com/chapter/10.1007/978-3-030-61166-8_12) [[Notes](https://docs.google.com/document/d/e/2PACX-1vTJY1VzWuhzb68JuS8SJwhEtaaNldCRb--Q6yyqB4gYqd4Rh9CEE254x-iiAD2OEFYAYTmGzAdFPUXd/pub)] <kbd>MICCAI 2020</kbd>
* [MixMatch: A Holistic Approach to Semi-Supervised Learning](https://arxiv.org/abs/1905.02249) [[Notes](https://docs.google.com/document/d/e/2PACX-1vRhkat4tAj1EY21Cmrab_dciZn4Y1JtedTgXdxojXTkW4nmm9TimoLxcUVXIoLH9UFJrIiyqGlyoSB7/pub)] <kbd>NIPS 2019</kbd>
* [Pi-Model: Ensembling for Semi-Supervised Learning](https://arxiv.org/abs/1610.02242) [[Notes](https://docs.google.com/document/d/e/2PACX-1vTWEr25XPcQfJ8ijvITZ8pwgGBbZ5pfb6Ueu_yKmWs_rX0yMpV4jr0vneIr1KjQaMQzJiGsqyImd2sJ/pub)] <kbd>ICLR 2017</kbd>
* [Distilling the Knowledge in a Neural Network](https://arxiv.org/abs/1503.02531) [[Notes](https://docs.google.com/document/d/e/2PACX-1vSgA_r5_o0NWELfuFwSFH550nammFsiU1wUb3TgIQnoUWtgcFt829fD0Rn9FUeSdy0bpsSKBpPYCviV/pub)] <kbd>NIPS 2014</kbd> 
* []() [[Notes]()] <kbd>MICCAI 2020</kbd>
* []() [[Notes]()] <kbd>MICCAI 2020</kbd>

### Wk12 - 2020.10.13
Biomedical Semi-Supervised Learning
* [Dual Teacher: Integrating Intra-Domain and Inter-Domain Teachers for Cardiac Segmentation](https://arxiv.org/abs/2007.06279) [[Notes](https://docs.google.com/document/d/e/2PACX-1vQvzHR-Rl3uLqi_Tj9geA6GxAYMNQvjTGracgcLIPw6wub18k95_bfpm85gw8O-Y4qcfcgUQs4IZvlo/pub)] <kbd>MICCAI 2020</kbd>
* [MMT-PSM: Deep Semi-supervised Knowledge Distillation for Overlapping Cervical Cell Instance Segmentation](https://arxiv.org/abs/2007.10787) [[Notes](https://docs.google.com/document/d/e/2PACX-1vRTLIAOY4MOvQKbBcrlIBkv_ODRe2WX_zJL_A37I2GXEjP04deP4E_iJQ21AOg0n5E5rhTH64InkfCb/pub)] <kbd>MICCAI 2020</kbd>
* [Semi-Supervised Brain Lesion Segmentation with an Adapted Mean Teacher Model](https://arxiv.org/abs/1903.01248) [[Notes](https://docs.google.com/document/d/e/2PACX-1vQh8aTva3601AlUjWD9WaxX6XPmehZFPILpaPfHqdRWLlLQTHqGY8CQoGkr51gQDwFplw4u4vxxTOvB/pub)] <kbd>IPMI 2019</kbd>

Noisy Labels
* [Confident Learning: Characterizing Label Errors: Confident Learning for Noisy-Labeled Image Segmentation](https://link.springer.com/chapter/10.1007%2F978-3-030-59710-8_70) [[Notes](https://docs.google.com/document/d/e/2PACX-1vQY4X3BFY47fDdL6DaY1C-8zKS-ZYYTMrxhNN-8QFBH5gcLl0CbnRqs4D7objlyekRozGaGId1188tO/pub)] <kbd>MICCAI 2020</kbd>

### Wk11 - 2020.08.31
Tracking
* [Detect to Track and Track to Detect](https://arxiv.org/abs/1710.03958) [[Notes](https://docs.google.com/document/d/e/2PACX-1vQSaMl00ZygtOFIs-52GTHxlnirvxNxCIb1LKp5naPwA6rDQ77MzA07HDi7pHEucEdMd5D1hVTxlDUR/pub)] <kbd>ICCV 2017</kbd>
* [SORT: Simple Online and Realtime Tracking](https://arxiv.org/abs/1602.00763) [[Notes](https://docs.google.com/document/d/e/2PACX-1vRfCLKnU5ykHa_gn6YWANxCSWjTtmhVA8Ox29oEu1pTnIJ3aUTkSKPaDVytb572hktPjheux8yYdFDD/pub)) <kbd>ICIP 2016</kbd>
* [DeepSORT: Simple Online and Realtime Tracking with a Deep Association Metric](https://arxiv.org/abs/1703.07402) [[Notes](https://docs.google.com/document/d/e/2PACX-1vTGD7l2kGYEIGy6CParXPcRVR6WZeVcACCiS-LtoEeqjvH7ip-3TdVcC4nPtmDf5Gurz0VknFtyW-u6/pub)] <kbd>ICIP 2017</kbd>

Localization Architectures
* [CIA-Net: Robust Nuclei Instance Segmentation with Contour-aware Information Aggregation](https://arxiv.org/abs/1903.05358) [[Notes](https://docs.google.com/document/d/e/2PACX-1vSjTm15SNsBZGrzNwiI5pY46frMhhHLNbUGJpkCPKAXW0k2JjaWyEc6Nuh5LA50zSwimb4iKQ8gX3jL/pub)] <kbd>IPMI 2019</kbd>
* [HRNet: Deep High-Resolution Representation Learning for Human Pose Estimation](https://arxiv.org/abs/1902.09212) [[Notes](https://docs.google.com/document/d/e/2PACX-1vRnByCt7RtzBq0h99oGvwRO6JI0MJJZaIjCPt60DxGtpZZILIErmIR3ZEGxicMmNuNK3dUf7xcab1CM/pub)] [[Talk](https://docs.google.com/document/d/e/2PACX-1vQWf9OgmIoicoWzuu4wElaJsmAo3Rs87-pY_f6nk-3ybQ_6O3GBWu8XQ8nGpAfKfkGNIQPd27lgihB_/pub)] <kbd>CVPR 2019</kbd>

Bloomberg - Foundations of Machine Learning
* [L1/2 Black Box Machine Learning](https://www.youtube.com/playlist?list=PLnZuxOufsXnvftwTB1HL6mel1V32w0ThI) [[Notes](https://drive.google.com/file/d/1sjycPqS2RsCtTIm9RGaooazd1fqC6Ozr/view?usp=sharing)] <kbd>2018</kbd>
* [L3 Introduction to Statistical Learning Theory](https://www.youtube.com/watch?v=rqJ8SrnmWu0&list=PLnZuxOufsXnvftwTB1HL6mel1V32w0ThI&index=4) [[Notes](https://drive.google.com/file/d/1m2oPuX_NPiXU-F9oZa473x6doOvTn9y9/view?usp=sharing)] <kbd>2018</kbd>

### Wk10 - 2020.08.17
*(reduced reading due to paper submission deadline)* <br>
Misc
* [Mixup: Beyond Empirical Risk Minimization](https://arxiv.org/abs/1710.09412) [[Notes](https://docs.google.com/document/d/e/2PACX-1vS2naSByqJpVY0qMLixlaexV0qRA0Kl7ptjb8NYZedQxwtOmPyCBpmL_mjX9AMVlx1-fg55NBDDvpTS/pub)] <kbd>ICML 2018</kbd>
* [Rethinking Pre-Training and Self-Training (Object Detection)](https://arxiv.org/abs/2006.06882) [[Notes](https://docs.google.com/document/d/e/2PACX-1vTCDEjFOU8kfxQFiB5spdPYBU_MxsUYiVUIQmK_4SCp48POcyoP7DifS5VuzhW0Y7ajD22vRHjUz78V/pub)] <kbd>2020</kbd>
* [CVPR'18 Interpretability Workshop](https://www.youtube.com/results?search_query=cvpr+2018+interpretability) [[Notes](https://drive.google.com/file/d/1KtKCxmw7-GvM7d8_kckxJNUk8hfWo28S/view?usp=sharing)] <kbd>Goodnotes</kbd>


### Wk9 - 2020.08.17
*(reduced reading due to paper submission deadline)* <br>
Biomedical Analysis + Limited Annotation Techniques
* [Extreme Consistency: Overcoming Annotation Scarcity and Domain Shifts](https://arxiv.org/abs/2004.11966) [[Notes](https://docs.google.com/document/d/e/2PACX-1vSptLgbssAUkyMjhh5KVkkMgIWmeSIlJ1Wz4GTW42_F4ldJd6Oj1RyOQj3IcKce5VBilXVcH9c70bNM/pub)] <kbd>2020</kbd>
* [Semi-Supervised Learning for Netowrk-Based Cardiac MR Segmentation](https://link.springer.com/chapter/10.1007/978-3-319-66185-8_29) [[Notes](https://docs.google.com/document/d/e/2PACX-1vR47l8m2ftyT4cDVBok3_FAKpkfr6RzbjqVizuUO3p_5L8Wzto1lJRvl1Nns6tbgDa3aYD9FaIlV7MY/pub)] <kbd>MICCAI 2017</kbd>
* [MoCo v2: Improved Baselines with Momentum Contrastive Learning](https://arxiv.org/abs/2003.04297) [[Notes](https://docs.google.com/document/d/e/2PACX-1vQ1ukREnWUyWWs32-ljY3XYMMNkstf9k_C3zwqUns3udc93jNfSUQU2Y-wYCeRdg5oJ8q9ZmtqEE6cb/pub)] <kbd>2020</kbd>

### Wk8 - 2020.08.10
*(reduced reading due to paper submission deadline)* <br>
Biomedical Segmentation/Classification + Limited Annotation Techniques
* [UA-MET: Uncertainty-aware Self-ensembling for SemiSup 3D Left Atrium Segmentation](https://arxiv.org/abs/1907.07034) [[Notes](https://docs.google.com/document/d/e/2PACX-1vQxSVM3qzF1GxtHy3VskCAWBf82SbaFflJvdlvG-RPDU_O3BGHwDDBrD22TUcl2lho9F3g98iCbcsVL/pub)] <kbd>MICCAI 2019</kbd>
* [SSL+Size-Regressor: Curriculum semi-supervised segmentation](https://arxiv.org/abs/1904.05236) [[Notes](https://docs.google.com/document/d/e/2PACX-1vTJKSorbQLN5QIZMSWgUrwIBYpFVVKLJ2SvxfgXZF6j9eYIsxC8VNMJNj1QZK_Z9aMJBLD63_gHTZ59/pub)] <kbd>MICCAI 2019</kbd>
* [MICCAI'19 Best Paper - Segmentation of the Prostate Clinical Target Volume in Ultrasound Images](https://www.sciencedirect.com/science/article/abs/pii/S1361841519300623?via%3Dihub) [[Notes](https://docs.google.com/document/d/e/2PACX-1vQ3-QN9qDZdxGzNGaR3eVEcku4JChUrv-s85ItknYT5ECEfQXw_WgwebvEHea55tDUNlBuOfv7r8ZnR/pub)] <kbd>MICCAI 2019</kbd>
* [An Active Learning Approach for Reducing Annotation Cost in Skin Lesion Analysis](https://arxiv.org/abs/1909.02344) [[Notes](https://docs.google.com/document/d/e/2PACX-1vQbES1uib9h7vhToUZWYAf74Sw70i9xWwFsXNYFDdy2Ho7O8uAoBqPaifbSAXgE9jkIBWJWpPePZB7G/pub)] <kbd>MIML 2019</kbd>

### Wk7 - 2020.08.03
Biomedical Segmentation + Limited Annotation Techniques
* [Suggestive Annotation of Brain Tumour Images with Gradient-guided Sampling](https://arxiv.org/abs/2006.14984) [[Notes](https://docs.google.com/document/d/e/2PACX-1vQ3SlVTLmWYZ2udV2psMwvlIexfrv33Br3NL6TUWcFJiK3HEGZlR5004iZV-E3Ww1XXIZBxbmSBh79m/pub)] <kbd>MICCAI 2020</kbd>
* [ISIC17 Winner: Improving Dermoscopic Image Segmentation w/Enhanced Conv-Deconv Nets](https://arxiv.org/abs/1709.09780) [[Notes](https://docs.google.com/document/d/e/2PACX-1vRX9cO_ZYqnjvcicx5gCWjA9HbekU5R68yVZdPR_YZ65kqNIA0l5wygt4kXuTfd79CP01gIICCnwM_7/pub)] <kbd>BHI Journal 2017</kbd>
* [DAML: Difficulty-aware Meta-learning for Rare Disease Diagnosis](https://arxiv.org/abs/1907.00354) [[Notes](https://docs.google.com/document/d/e/2PACX-1vTh0d6iF3GEEyFKk51EVm6WIV_UADYEm4x9Glwj9j1Iyl9I_qe2A4BzF9VMSPqFuvKVJty7SVtr6aNU/pub)] <kbd>MICCAI 2020</kbd>
* [Consistency-Based Semi-Supervised Active Learning: Towards Minimizing Labeling Cost](https://arxiv.org/abs/1910.07153) [[Notes](https://docs.google.com/document/d/e/2PACX-1vQFbjVytKWPjrmFEQh40qjTlgVBzhX-f-IObn2yA2DvS0gPqlJE5QUpZt92KqdxlevvkM8Ek_q0zFBP/pub)] <kbd>2020</kbd>

Free-Hand Notes on Segmentation Models and Training Tricks
* [5 BIBM 2019 Segmentation Papers](https://drive.google.com/file/d/1EYPLUgLK0cm7FjOFixLAg6JvjqM56D0g/view?usp=sharing) <kbd>Goodnotes</kbd>

### Wk6 - 2020.07.27
Biomedical Segmentation + Semi-Supervised Techniques
* [TCSM: Transformation Consistent Self-Ensembling Model for SemiSup Medical Segmentation](https://arxiv.org/abs/1903.00348) [[Notes](https://docs.google.com/document/d/e/2PACX-1vRafQh3tPlVVo4KLrhfuG-5rYFXClXzM1XcWrs3XplFZ1cmLfjpfaEIvPrAL-X9bNY47grovCdWY2eQ/pub)] <kbd>NNLS 2020</kbd>
* [HDenseUNet: Hybrid Densely Connected UNet for CT Liver and Tumor Segmentation](https://arxiv.org/abs/1709.07330) [[Notes](https://docs.google.com/document/d/e/2PACX-1vTRXJZhn2Jz8-HUufjhZZaNx9xfLgF6It_IND7pz12UfNx70Ju454oKhuzhsq-z5MaaIjqiOcz3Dtqo/pub)] <kbd>TMI 2018</kbd>

Classics
* [Curriculum Learning](https://ronan.collobert.com/pub/matos/2009_curriculum_icml.pdf) [[Notes](https://docs.google.com/document/d/e/2PACX-1vT9vGcYUxYV9weXLnfmJStsDKsTAzMEhCUlguczrP3ADMdP2d-P8h6E1JRXalfwG_q7RmelqHYA7p6Y/pub)] <kbd>ICML 2009</kbd>

### Wk5 - 2020.07.20
Biomedical Segmentation
* [Survey on Not-So-Supervised Biomedical Image Analysis Methods](https://arxiv.org/abs/1804.06353) [[Notes](https://docs.google.com/document/d/e/2PACX-1vTNAVhQ_9AAozTKfK5pNT_tL3dh-n_nup2DH-a_ISijEX4scmxviUf_LK-f6WZPhvR_CZUu_R2ivIKG/pub)] <kbd>MIA 2018</kbd>
* [Attention U-Net: Learning Where to Look for the Pancreas](https://arxiv.org/abs/1804.03999) [[Notes](https://docs.google.com/document/d/e/2PACX-1vQpK-Q8spAIy346TDsLQVIgtF59Plv1aqFA2wHMj17AUDAAXpVlmxrZ6xWkMx4OQBWkLHHJk_6enzG5/pub)] <kbd>MIDL 2018</kbd>
* [A New Ensemble Learning Framework for 3D Biomedical Image Segmentation](https://arxiv.org/abs/1812.03945) [[Notes](https://docs.google.com/document/d/e/2PACX-1vQsvNH53qejLk6p7ZOGH-9rx-JBLpIK0ooyzPPv5xf7iCiXzWUi9vDdcBK6VCvQ7YY3QicKS0yBv3xp/pub)] <kbd>AAAI 2018</kbd>
* [3D UNet: Learning Dense Volumetric Segmentation from Sparse Annotation](https://arxiv.org/abs/1606.06650) [[Notes](https://docs.google.com/document/d/e/2PACX-1vREDFzO_LbTAzI48jUSg0kwwjCMLaCgOTuQEeJTWMNzXsj-zbKwv1wzJBE1HivNFunK2dB1nie7eqcA/pub)] <kbd>MICCAI 2016</kbd>
* [DenseVoxNet: Automatic 3D Cardio MR Segmentation w/Densely-Connected Volumetric CNNs](https://arxiv.org/abs/1708.00573) [[Notes](https://docs.google.com/document/d/e/2PACX-1vTfLFFWjpy9JoRy_00PUHNLtExj48I6enj9-uGAp8oP7DOyeY2ok7NisD8S_WTtU_SEf1Y1WbTngB9p/pub)] <kbd>MICCAI 2017</kbd>
* [VoxResNet: Deep Voxelwise Residual Networks for Brain Segmentation from 3D MR Images](https://arxiv.org/abs/1608.05895) [[Notes](https://docs.google.com/document/d/e/2PACX-1vTfyqbwzbGVz8MhLwxfC80m0HS9uvX2TlceCwhDPwpxEKvaurZ5SaT5b0v84Ujt6FPmJzRhqVJ856b1/pub)] <kbd>JNeuroImage 2018</kbd>
* [2D Semi-Supervised Medical Image Segmentation via Learning Consistency under Transformations](https://arxiv.org/abs/1911.01218) [[Notes](https://docs.google.com/document/d/e/2PACX-1vST9F-ZTQO0mFV-sS6BRbGooAmqjaCVmpSfLTyE00taELDgI8YoSVhmzT3QmxCjc3kWUAVjRErYu1SQ/pub)] <kbd>MICCAI 2019</kbd>

### Wk4 - 2020.07.13
Depth: Recent Self-Supervised & Semi-Supervised Techniques
* [AMDIM: ALearning Representations by Maximizing Mutual Information Across Views](https://arxiv.org/abs/1906.00910) [[Notes](https://docs.google.com/document/d/e/2PACX-1vT7Gsd3Hp9RgNsJft-iRQQxBEoGCMKnHWXY0DtCSqDHR38EurpHECbGwqneFrXG3aCgr6Cssza2z8kB/pub)] <kbd>NIPS 2019</kbd>
* [PIRL: Self-Supervised Learning of Pretext-Invariant Representations](https://arxiv.org/abs/1912.01991) [[Notes](https://docs.google.com/document/d/e/2PACX-1vSsb9J2PUPIJWDJhWHC0pz-x4ddbJnN2IXnnlwkR9s6bABWtTe2u1xqM_z5vU2kM9ECueksVWPzoLvq/pub)] <kbd>CVPR 2020</kbd>
* [Virtual Adversarial Training: A Regularization ](https://arxiv.org/abs/1704.03976) [[Notes](https://docs.google.com/document/d/e/2PACX-1vQGMoYNBPHsMQkpmHOp6A1Gp-hdfEQF7e88QEUxeXXvSmo2EjMCDdMBWX1MWCyWgHAWvH9hXi5ZvzHH/pub)] <kbd>TPAMI 2018</kbd>

### Wk3 - 2020.07.06
Breadth: Segmentation
* [U-Net: Convolutional Networks for Biomedical Image Segmentation](https://arxiv.org/abs/1505.04597) [[Notes](https://docs.google.com/document/d/e/2PACX-1vQONhlttSJmabntPQdSQK82lcOqdLd2cGawQcIU2U4TutljBFwbzIqAbNu87PJsZDJ-Zb-c0CRKjsHA/pub)] <kbd>MICCAI 2015</kbd>
* [Segmentation Survey (cont.): Image Segmentation Using Deep Learning](https://arxiv.org/abs/2001.05566) [[Notes](https://docs.google.com/document/d/e/2PACX-1vTx0Wt6Tf4cqLLDKo47uCw9AugVEwG7x0YcH4IvCcTCVDM7stfp8BM2RZuaYbYkQ-z7on6uNBg7-bdx/pub)] <kbd>2020</kbd>
* [V-Net: Fully Convolutional Neural Networks for Volumetric Medical Image Segmentation](https://arxiv.org/abs/1606.04797) [[Notes](https://docs.google.com/document/d/e/2PACX-1vRZ_Twb9b7KY9avO4-uRs21JfGiYR5fKa6QzvJQuZOchYC4mbv2lyogI4iX0Im_Lem7rzGe1RJfvJ-e/pub)] <kbd>3DV 2016</kbd>

Depth: Recent Self-Supervised & Semi-Supervised Techniques
* [FixMatch: Simplifying Semi-Supervised Learning with Consistency and Confidence](https://arxiv.org/abs/2001.07685) [[Notes](https://docs.google.com/document/d/e/2PACX-1vSl0pBzwQE5UFluG5V_cT1kDh4QUVgBExxW_gfwz-HempGGTBocllDwQm7T3H8xmSSUtRCRAqEaJRCd/pub)] <kbd>2020</kbd>
* [Mean Teachers: Weight-Averaged Consistency Targets Improve SemiSL Results](https://arxiv.org/abs/1703.01780) [[Notes](https://docs.google.com/document/d/e/2PACX-1vRDDUqIBJsqA365PgPu3JeymLLeWbkIP8x0Xc_YopjqgyJAo6qeNuTV9o6RE6dzBrWdwr739IeXDB1J/pub)] <kbd>NIPS 2017</kbd>
* [CPC: Representation Learning with Contrastive Predictive Coding](https://arxiv.org/abs/1807.03748) [[Notes](https://docs.google.com/document/d/e/2PACX-1vRR9Euw9K7IP2D8Og_QSNj5Imn4tkxo96-0O2uXV0d_SVNlDQsOvnlhDHtc1l1GqqXxG125w03npOvT/pub)] <kbd>2018</kbd>

### Wk2 - 2020.06.29
Breadth: Faster Training and Segmentation
* [Large Scale Distributed Deep Networks](https://papers.nips.cc/paper/4687-large-scale-distributed-deep-networks) [[Notes](https://docs.google.com/document/d/e/2PACX-1vQWAXjGUkP1XXVsCw5QxFRw7nSG96ypaA2Je_VCUGdmvddqraAmyn0fCsUTCO4fKCEFY-KUy6APLJbE/pub)] <kbd>NIPS 2012</kbd>
* [Segmentation Survey: Image Segmentation Using Deep Learning](https://arxiv.org/abs/2001.05566) [[Notes](https://docs.google.com/document/d/e/2PACX-1vTx0Wt6Tf4cqLLDKo47uCw9AugVEwG7x0YcH4IvCcTCVDM7stfp8BM2RZuaYbYkQ-z7on6uNBg7-bdx/pub)] <kbd>2020</kbd>

Depth: Recent Self-Supervised Techniques
* [RotNet'18: Unsupervised Representation Learning by Predicting Image Rotations](https://arxiv.org/abs/1803.07728) [[Notes](https://docs.google.com/document/d/e/2PACX-1vTs6ZgjAhNHocztgGIp9pW-4fJdcov1HvzqrX2b8KkGG1AE8uwBwB3nkCIGHxI_v8qvVRZhoz_dsZeA/pub)] <kbd>ICLR 2018</kbd>
* [SimClr: A Simple Framework for Contrastive Learning of Visual Representations](https://arxiv.org/abs/2002.05709) [[Notes](https://docs.google.com/document/d/e/2PACX-1vQfMcTFad1_TorKNQYhE2M7CE9XgLAQwuPLvJdXcXmPxZ7EaRbhcXisT_nG0alpke8nd6O3Xua-or6E/pub)] <kbd>2020</kbd>
* [SimClr2: Big Self-Supervised Models are Strong Semi-Supervised Learners](https://arxiv.org/abs/2006.10029) [[Notes](https://docs.google.com/document/d/e/2PACX-1vQjvgDpS65W6SbvSXyB5I0D7Z4p97bfjdAHLEa_cs6-505wctWSYEtOKr72FS8XrWWwozfx3sD-jTFc/pub)] <kbd>2020</kbd>
* [MoCo: Momentum Contrast for Unsupervised Visual Representation Learning](https://arxiv.org/abs/1911.05722) [[Notes](https://docs.google.com/document/d/e/2PACX-1vQs6jb-aWYj3M5AD3TmFgOQmtZUzUP9cJVBWFxxEUjiQFS3Sf62kpK4o3sk-KHiqSdaXSN4j5MGq61i/pub)] <kbd>CVPR 2020</kbd>

### Wk1 - 2020.06.22
Breadth: Classics on Network Components
* [PReLu: Delving Deep into Rectifiers: Surpassing Humans on ImageNet](https://arxiv.org/abs/1502.01852) [[Notes](https://docs.google.com/document/d/e/2PACX-1vRqOwLjzuJ8ZKJUv7EhMS7yh4aGf2-mebJrzYst33eOrpRGt-ap__btUpOwhv0iZvelbIPSgAFIFhZ_/pub)] <kbd>ICCV 2015</kbd>
* [Network in Network](https://arxiv.org/abs/1312.4400) [[Notes](https://docs.google.com/document/d/e/2PACX-1vQ4TFpOLHDiMtjfQdmf-XB5_hMkOHlJRe-s45veXK89fsVecz8ub2e5m7UAhcyQod5JbTIzdXFyw4Mj/pub)] <kbd>ICLR 2014</kbd>
* [ResNeXt: Aggregated Residual Transformations for DNNs](https://arxiv.org/abs/1611.05431) [[Notes](https://docs.google.com/document/d/e/2PACX-1vRb2gGDAC2GEicocasLbDZ8MohQRXuqR49Xqyz8P9hWGWw06LApyQ6TX2vaMQw1fyRgN3K7fheHMz1Y/pub)] <kbd>CVPR 2017</kbd>

Depth: Effective Training
* [Bag of Tricks for Image Classification](https://arxiv.org/abs/1812.01187) [[Notes](https://docs.google.com/document/d/e/2PACX-1vSoh0y7XiaE7EWYvT1a_aUUFpIJ0FIrm1h0zGKQBq5RyQno7b3Wg-crOsMgppYCIXi4fM-b2k6v-JHe/pub)] <kbd>CVPR 2019</kbd> 
* [Don't Decay the Learning Rate, Increase the Batch Size](https://arxiv.org/abs/1711.00489) [[Notes](https://docs.google.com/document/d/e/2PACX-1vRhMhpCevNtp3-D8J28Uo47DWj2_i_pP-imYT5vfPqpy0N0Bj2opEduvm3lQiB_ZhplwafqseTQqZUq/pub)] <kbd>ICLR 2018</kbd> 
* [Four Things Everyone Should Know to Improve Batch Normalization](https://arxiv.org/abs/1906.03548) [[Notes](https://docs.google.com/document/d/e/2PACX-1vQ_IX5oi94F7dCDkcsYexACrD2Wxbl08vbHqCr0KIsA6tyNuyNcl-169bo-pa3RtTZ1HRAUQ68Mmdon/pub)] <kbd>ICLR 2020</kbd>

### Wk0 - 2020.06.15
(Trial Run) Test and improve the process.
* [How to Read a Paper](http://blizzard.cs.uwaterloo.ca/keshav/home/Papers/data/07/paper-reading.pdf) [[Notes](https://docs.google.com/document/d/e/2PACX-1vRF38E2y_akvL4NKcfXzoeiPSYz3_73xSIuOk_YGCvjSmMWUcSLzZMa91jgdZc-B-AqkfpT6G6D_BbO/pub)] <kbd>2016</kbd>
* [DLA: Deep Layer Aggregation](https://arxiv.org/abs/1707.06484) [[Notes]()] <kbd>CVPR 2018</kbd>
* [DenseNet: Densely Connected Convolutional Networks](https://arxiv.org/abs/1608.06993) [[Notes](https://docs.google.com/document/d/e/2PACX-1vT41lqeRvSWQdN7Qjc55WheEVzWYINBjNuugH3VVgwXA-HRUW8zhQYBJTdVt51LU5WjI4qHT4iQpihQ/pub)] <kbd>CVPR 2017</kbd>

