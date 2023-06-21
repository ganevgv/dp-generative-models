# Differentially Private (tabular) Generative Models Papers with Code


## Copulas
* DPCopula | [Differentially Private Synthesization of Multi-Dimensional Data using Copula Functions](http://www.openproceedings.org/EDBT/2014/paper_74.pdf) (Li et al., 2014) | [code](https://github.com/Emory-AIMS/DPCopula)
* dpc | [Differentially Private Release of High-Dimensional Datasets using the Gaussian Copula](https://arxiv.org/abs/1902.01499) (Asghar et al., 2020)
* Copula-Shirley | [Growing Synthetic Data Through Differentially-Private Vine Copulas](https://petsymposium.org/2021/files/papers/issue3/popets-2021-0040.pdf) (Gambs et al., 2021) | [code](https://github.com/alxxrg/copula-shirley) | [video](https://www.youtube.com/watch?v=pYSA0bmhloQ)


## Marginals
* DPSyn | [DPSyn: Experiences in the NIST Differential Privacy Data Synthesis Challenges](https://arxiv.org/abs/2106.12949) (Li et al., 2021) | [code](https://github.com/usnistgov/PrivacyEngCollabSpace/tree/master/tools/de-identification/Differential-Privacy-Synthetic-Data-Challenge-Algorithms/DPSyn) [code_1](https://github.com/agl-c/deid2_dpsyn)
* PrivSyn | [PrivSyn: Differentially Private Data Synthesis](https://arxiv.org/abs/2012.15128) (Zhang et al., 2021)


## Graphical Models
* PrivBayes | [PrivBayes: Private Data Release via Bayesian Networks](https://dl.acm.org/doi/abs/10.1145/3134428) (Zhang et al., 2017) | [code (C++)](https://sourceforge.net/projects/privbayes/), [reimplementation (Python)](https://github.com/DataResponsibly/DataSynthesizer/blob/master/DataSynthesizer/lib/PrivBayes.py)
* PrivMN | [Differentially Private High-Dimensional Data Publication via Markov Network](https://www.researchgate.net/publication/334758350_Differentially_Private_High-Dimensional_Data_Publication_via_Markov_Network) (Zhang et al., 2019)
* MST | [Winning the NIST Contest: A Scalable and General Approach to Differentially Private Synthetic Data](https://arxiv.org/abs/2108.04978) (McKenna et al., 2021) | [code](https://github.com/ryan112358/private-pgm/blob/master/mechanisms/mst.py)
* PrivMRF | [Data Synthesis via Differentially Private Markov Random Fields](http://www.vldb.org/pvldb/vol14/p2190-cai.pdf) (Cai et al., 2021) | [code](https://github.com/caicre/PrivMRF)
* dpart | [dpart: Differentially Private Autoregressive Tabular, a General Framework for Synthetic Data Generation](https://arxiv.org/abs/2207.05810) (Mahiou et al., 2022) | [code](https://github.com/hazy/dpart)


## VAEs
* DPGM | [Differentially Private Mixture of Generative Neural Networks](https://arxiv.org/abs/1709.04514) (Acs et al., 2017) 
* DP-SYN | [Privacy Preserving Synthetic Data Release Using Deep Learning](https://www.researchgate.net/publication/330460051_Privacy_Preserving_Synthetic_Data_Release_Using_Deep_Learning) (Abay et al., 2018)
* P3GM | [P3GM: Private High-Dimensional Data Release via Privacy Preserving Phased Generative Model](https://arxiv.org/abs/2006.12101v4) (Takagi et al., 2021) | [code](https://github.com/tsubasat/P3GM)


## GANs
* DPGAN | [Differentially Private Generative Adversarial Network](https://arxiv.org/abs/1802.06739) (Xie et al., 2018) | [code](https://github.com/illidanlab/dpgan)
* PATE-GAN | [PATE-GAN: Generating Synthetic Data with Differential Privacy Guarantees](https://openreview.net/forum?id=S1zk9iRqF7) (Jordon et al., 2019) | [code](https://bitbucket.org/mvdschaar/mlforhealthlabpub/src/0b0190bcd38a76c405c805f1ca774971fcd85233/alg/pategan/), [code_1](https://github.com/vanderschaarlab/mlforhealthlabpub/tree/main/alg/pategan)
* dp-GAN-TSCD | [Diﬀerentially Private Generative Adversarial Networks for Time Series, Continuous, and Discrete Open Data](https://arxiv.org/abs/1901.02477) (Frigerio et al., 2019) | [code](https://github.com/Lory94/dp-GAN)
* SPRINT-gan | [Privacy-Preserving Generative Deep Neural Networks Support Clinical Data Sharing](https://www.biorxiv.org/content/10.1101/159756v5) (Beaulieu-Jones et al., 2019) | [code](https://github.com/greenelab/SPRINT_gan)
* DPautoGAN | [Differentially Private Synthetic Mixed-Type Data Generation For Unsupervised Learning](https://arxiv.org/abs/1912.03250) (Tantipongpipat et al., 2021) | [code](https://github.com/DPautoGAN/DPautoGAN)
* G-PATE | [G-PATE: Scalable Differentially Private Data Generator via Private Aggregation of Teacher Discriminators](https://openreview.net/forum?id=_CmrI7UrmCl) (Long et al., 2021) | [code](https://github.com/AI-secure/G-PATE)


## Other Approaches
* RON-Gauss | [RON-Gauss: Enhancing Utility in Non-Interactive Private Data Release](https://arxiv.org/abs/1709.00054) (Chanyaswad et al., 2019) | [code](https://github.com/inspire-group/RON-Gauss)
* FEM | [New Oracle-Efficient Algorithms for Private Synthetic Data Release](https://arxiv.org/abs/2007.05453) (Vietri et al., 2020) | [code](https://github.com/giusevtr/fem)
* RAP | [Differentially Private Query Release Through Adaptive Projection](https://arxiv.org/abs/2103.06641) (Aydore et al., 2021) | [code](https://github.com/amazon-research/relaxed-adaptive-projection)
* Kamino | [Kamino: Constraint-Aware Differentially Private Data Synthesis](https://arxiv.org/abs/2012.15713) (Ge et al., 2021) | [code](https://github.com/cgebest/kamino)
* PEP, GEM | [Iterative Methods for Private Synthetic Data: Unifying Framework and New Methods](https://arxiv.org/abs/2106.07153) (Liu et al., 2021) | [code](https://github.com/terranceliu/iterative-dp), [code_1](https://github.com/terranceliu/dp-query-release)
* AIM | [AIM: An Adaptive and Iterative Mechanism for Differentially Private Synthetic Data](https://arxiv.org/abs/2201.12677) (McKenna et al., 2022) | [code](https://github.com/ryan112358/private-pgm/blob/master/mechanisms/aim.py)
* RAP++ | [Private Synthetic Data for Multitask Learning and Marginal Queries](https://arxiv.org/abs/2209.07400) (Vietri et al., 2022)



## Other NIST Differential Privacy Challenges Solutions
* DP-WGAN | Differentially Private Dataset Release using Wasserstein GANs (Alzantot et al., 2019) | [code](https://github.com/nesl/nist_differential_privacy_synthetic_data_challenge)
* DPFieldGroups | Differential Privacy Synthetic Data Challenge Algorithm (Gardner, 2019) | [code](https://github.com/usnistgov/PrivacyEngCollabSpace/tree/master/tools/de-identification/Differential-Privacy-Synthetic-Data-Challenge-Algorithms/DPFieldGroups)


## Other Data Domains
* GANobfuscator | [GANobfuscator: Mitigating Information Leakage Under GAN via Differential Privacy](https://ieeexplore.ieee.org/document/8636556) (Xu et al., 2019)
* DP-CGAN | [DP-CGAN: Differentially Private Synthetic Data and Label Generation](https://arxiv.org/abs/2001.09700) (Torkzadehmahani et al., 2019) | [code](https://github.com/reihaneh-torkzadehmahani/DP-CGAN)
* GS-WGAN | [GS-WGAN: A Gradient-Sanitized Approach for Learning Differentially Private Generators](https://arxiv.org/abs/2006.08265) (Chen et al., 2020) | [code](https://github.com/DingfanChen/GS-WGAN)
* DPDoppelGANger | [Using GANs for Sharing Networked Time Series Data: Challenges, Initial Promise, and Open Questions](https://arxiv.org/abs/1909.13403) (Lin et al., 2020) | [code](https://github.com/fjxmlzn/DoppelGANger)
* DP-Sinkhorn | [Don't Generate Me: Training Differentially Private Generative Models with Sinkhorn Divergence](https://arxiv.org/abs/2111.01177) (Cao et al., 2021) 


## Non Peer-Reviewed Models
* dp-GAN | [Differentially Private Releasing via Deep Generative Model (Technical Report)](https://arxiv.org/abs/1801.01594) (Zhang et al., 2018) | [code](https://github.com/alps-lab/dpgan)
* DP-AuGM, DP-VaeGM | [Differentially Private Data Generative Models](https://arxiv.org/abs/1812.02274) (Chen et al., 2018) 
