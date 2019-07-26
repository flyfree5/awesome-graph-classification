# Awesome Graph Classification
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)
![GitHub stars](https://img.shields.io/github/stars/benedekrozemberczki/awesome-graph-embedding.svg?style=plastic)
![GitHub forks](https://img.shields.io/github/forks/benedekrozemberczki/awesome-graph-embedding.svg?color=blue&style=plastic)
![License](https://img.shields.io/github/license/benedekrozemberczki/awesome-graph-embedding.svg?color=blue&style=plastic)

A collection of graph classification methods, covering embedding, deep learning, graph kernel and factorization papers with reference implementations.

Relevant graph classification benchmark datasets are available [[here]](https://github.com/shiruipan/graph_datasets).

Similar collections about [community detection](https://github.com/benedekrozemberczki/awesome-community-detection), [classification/regression tree](https://github.com/benedekrozemberczki/awesome-decision-tree-papers) and [gradient boosting](https://github.com/benedekrozemberczki/awesome-gradient-boosting-papers) papers with implementations.

<p align="center">
  <img width="400" src="atlas.png">
</p>

##### Contents  

1. [Factorization](#factorization)  
2. [Spectral and Statistical Fingerprints](#spectral-and-statistical-fingerprints)
3. [Deep Learning](#deep-learning)  
4. [Graph Kernels](#graph-kernels)  

## Factorization
- **Learning Graph Representation via Frequent Subgraphs (SDM 2018)**
- *通过频繁子图学习图的表达*
  - Dang Nguyen, Wei Luo, Tu Dinh Nguyen, Svetha Venkatesh, Dinh Phung
  - [[Paper]](https://epubs.siam.org/doi/10.1137/1.9781611975321.35)
  - [[Python Reference]](https://github.com/nphdang/GE-FSG)

- **Anonymous Walk Embeddings (ICML 2018)**
- *随机游走embeding*
  - Sergey Ivanov and Evgeny Burnaev
  - [[Paper]](https://arxiv.org/pdf/1805.11921.pdf)
  - [[Python Reference]](https://github.com/nd7141/AWE)

- **Graph2vec (MLGWorkshop 2017)**
- *图转向量*
  - Annamalai Narayanan, Mahinthan Chandramohan, Lihui Chen, Yang Liu, and Santhoshkumar Saminathan
  - [[Paper]](https://arxiv.org/abs/1707.05005)
  - [[Python High Performance]](https://github.com/benedekrozemberczki/graph2vec)
  - [[Python Reference]](https://github.com/MLDroid/graph2vec_tf)

- **Subgraph2vec (MLGWorkshop 2016)**
- *子图转向量*
  - Annamalai Narayanan, Mahinthan Chandramohan, Lihui Chen, Yang Liu, and Santhoshkumar Saminathan
  - [[Paper]](https://arxiv.org/abs/1606.08928)
  - [[Python High Performance]](https://github.com/MLDroid/subgraph2vec_gensim)
  - [[Python Reference]](https://github.com/MLDroid/subgraph2vec_tf)

- **Rdf2Vec: RDF Graph Embeddings for Data Mining (ISWC 2016)**
- *RDF图转向量*
  - Petar Ristoski and Heiko Paulheim
  - [[Paper]](https://link.springer.com/chapter/10.1007/978-3-319-46523-4_30)
  - [[Python Reference]](https://github.com/airobert/RDF2VecAtWebScale)

- **Deep Graph Kernels (KDD 2015)**
- *深度图内核*
  - Pinar Yanardag and S.V.N. Vishwanathan
  - [[Paper]](https://dl.acm.org/citation.cfm?id=2783417)
  - [[Python Reference]](https://github.com/pankajk/Deep-Graph-Kernels)

## Spectral and Statistical Fingerprints

- **A Simple Yet Effective Baseline for Non-Attribute Graph Classification (ICLR RLPM 2019)**
- *一种简单有效的非特征图分类的baseline*
  - Chen Cai, Yusu Wang
  - [[Paper]](https://arxiv.org/abs/1811.03508)
  - [[Python Reference]](https://github.com/Chen-Cai-OSU/LDP)

- **NetLSD (KDD 2018)**
  - Anton Tsitsulin, Davide Mottin, Panagiotis Karras, Alex Bronstein, and Emmanuel Müller
  - [[Paper]](https://arxiv.org/abs/1805.10712)
  - [[Python Reference]](https://github.com/xgfs/NetLSD)

- **A Simple Baseline Algorithm for Graph Classification (Relational Representation Learning, NIPS 2018)**
- *图分类的一种简单baseline算法*
  - Nathan de Lara and Edouard Pineau
  - [[Paper]](https://arxiv.org/pdf/1810.09155.pdf)
  - [[Python Reference]](https://github.com/edouardpineau/A-simple-baseline-algorithm-for-graph-classification)

- **Multi-Graph Multi-Label Learning Based on Entropy (Entropy NIPS 2018)**
- *基于熵的多重图多标签学习*
  - Zixuan Zhu and Yuhai Zhao
  - [[Paper]](https://github.com/TonyZZX/MultiGraph_MultiLabel_Learning/blob/master/entropy-20-00245.pdf)
  - [[Python Reference]](https://github.com/TonyZZX/MultiGraph_MultiLabel_Learning)

- **Hunt For The Unique, Stable, Sparse And Fast Feature Learning On Graphs (NIPS 2017)**
- *搜寻唯一的稳定的稀疏的并且快速的特征学习基于图*
  - Saurabh Verma and Zhi-Li Zhang
  - [[Paper]](https://papers.nips.cc/paper/6614-hunt-for-the-unique-stable-sparse-and-fast-feature-learning-on-graphs.pdf)
  - [[Python Reference]](https://github.com/vermaMachineLearning/FGSD)

- **Joint Structure Feature Exploration and Regularization for Multi-Task Graph Classification (TKDE 2015)**
- *多任务图分类中的链接结构特征探索和规整化*
  - Shirui Pan, Jia Wu, Xingquan Zhuy, Chengqi Zhang, and Philip S. Yuz
  - [[Paper]](https://ieeexplore.ieee.org/document/7302040)
  - [[Java Reference]](https://github.com/shiruipan/MTG)

- **NetSimile: A Scalable Approach to Size-Independent Network Similarity (arXiv 2012)**
- *网络相似性：一种可扩展的方法对于自由尺寸的网络相似性*
  - Michele Berlingerio, Danai Koutra, Tina Eliassi-Rad, and Christos Faloutsos
  - [[Paper]](https://arxiv.org/abs/1209.2684)
  - [[Python]](https://github.com/kristyspatel/Netsimile)

## Deep Learning

- **Relational Pooling for Graph Representations (ICML 2019)**
- *图表达的相关性池化*
  - Ryan L. Murphy, Balasubramaniam Srinivasan, Vinayak Rao, Bruno Ribeiro
  - [[Paper]](https://arxiv.org/abs/1903.02541)
  - [[Python Reference]](https://github.com/PurdueMINDS/RelationalPooling)

- **Ego-CNN: Distributed, Egocentric Representations of Graphs for Detecting Critical Structure (ICML 2019)**
- *Ego-CNN：分布式，图中心表达方法为探查图的重要结构*
  - Ruo-Chun Tzeng, Shan-Hung Wu
  - [[Paper]](http://proceedings.mlr.press/v97/tzeng19a/tzeng19a.pdf)
  - [[Python Reference]](https://github.com/rutzeng/EgoCNN)

- **Self-Attention Graph Pooling (ICML 2019)**
- *图的自注意力池化*
  - Junhyun Lee, Inyeop Lee, Jaewoo Kang
  - [[Paper]](https://arxiv.org/abs/1904.08082)
  - [[Python Reference]](https://github.com/inyeoplee77/SAGPool)

- **Variational Recurrent Neural Networks for Graph Classification (ICLR 2019)**
- *基于图分类的变周期神经网络（VRNN）*
  - Edouard Pineau, Nathan de Lara
  - [[Paper]](https://arxiv.org/abs/1902.02721)
  - [[Python Reference]](https://github.com/edouardpineau/Variational-Recurrent-Neural-Networks-for-Graph-Classification)

- **Crystal Graph Neural Networks for Data Mining in Materials Science (Arxiv 2019)**
- *晶体图神经网络在材料科学中的应用*
  - Takenori Yamamoto
  - [[Paper]](https://storage.googleapis.com/rimcs_cgnn/cgnn_matsci_May_27_2019.pdf)
  - [[Python Reference]](https://github.com/Tony-Y/cgnn)

- **Explainability Techniques for Graph Convolutional Networks (ICML 2019 Workshop)**
- *图卷积神经网络的可扩展技术们*
  - Federico Baldassarre, Hossein Azizpour
  - [[Paper]](https://128.84.21.199/pdf/1905.13686.pdf)
  - [[Python Reference]](https://github.com/gn-exp/gn-exp)

- **Semi-Supervised Graph Classification: A Hierarchical Graph Perspective (WWW 2019)**
- *半监督图分类：一种分层图透视*
  - Jia Li, Yu Rong, Hong Cheng, Helen Meng, Wenbing Huang, and Junzhou Huang
  - [[Paper]](https://arxiv.org/pdf/1904.05003.pdf)
  - [[Python Reference]](https://github.com/benedekrozemberczki/SEAL-CI)

- **Capsule Graph Neural Network (ICLR 2019)**
- *胶囊图神经网络*
  - Zhang Xinyi and Lihui Chen
  - [[Paper]](https://openreview.net/forum?id=Byl8BnRcYm)
  - [[Python Reference]](https://github.com/benedekrozemberczki/CapsGNN)

- **How Powerful are Graph Neural Networks? (ICLR 2019)**
- *图神经网络有多强*
  - Keyulu Xu, Weihua Hu, Jure Leskovec, Stefanie Jegelka
  - [[Paper]](https://arxiv.org/abs/1810.00826)
  - [[Python Reference]](https://github.com/weihua916/powerful-gnns)

- **Weisfeiler and Leman Go Neural: Higher-order Graph Neural Networks (AAAI 2019)**
- *高阶图神经网络*
  - Christopher Morris, Martin Ritzert, Matthias Fey, William L. Hamilton, Jan Eric Lenssen, Gaurav Rattan, and Martin Grohe
  - [[Paper]](https://arxiv.org/pdf/1810.02244v2.pdf)
  - [[Python Reference]](https://github.com/k-gnn/k-gnn)

- **Capsule Neural Networks for Graph Classification using Explicit Tensorial Graph Representations (Arxiv 2019)**
- *图分类的胶囊神经网络用在直接张量的图表达上*
  - Marcelo Daniel Gutierrez Mallea, Peter Meltzer, and Peter J Bentley
  - [[Paper]](https://arxiv.org/pdf/1902.08399v1.pdf)
  - [[Python Reference]](https://github.com/BraintreeLtd/PatchyCapsules)
  
- **Mapping Images to Scene Graphs with Permutation-Invariant Structured Prediction (NIPS 2019)**
- *映射图片到场景图 用在 排列不变结构预测*
  - Roei Herzig, Moshiko Raboh, Gal Chechik, Jonathan Berant, Amir Globerson
  - [[Paper]](https://arxiv.org/abs/1802.05451)
  - [[Python Reference]](https://github.com/shikorab/SceneGraph)

- **Three-Dimensionally Embedded Graph Convolutional Network for Molecule Interpretation (Arxiv 2018)**
- *图神经网络3维embeding 对分子解释*
  - Hyeoncheol Cho and Insung. S. Choi
  - [[Paper]](https://arxiv.org/abs/1811.09794)
  - [[Python Reference]](https://github.com/blackmints/3DGCN)

- **Learning Graph-Level Representations with Recurrent Neural Networks (Arxiv 2018)**
- *利用循环神经网络学习图级别的表示*
  - Yu Jin and Joseph F. JaJa
  - [[Paper]](https://arxiv.org/pdf/1805.07683v4.pdf)
  - [[Python Reference]](https://github.com/yuj-umd/graphRNN)

- **Graph Capsule Convolutional Neural Networks (ICML 2018)**
- *图胶囊神经网络*
  - Saurabh Verma and Zhi-Li Zhang
  - [[Paper]](https://arxiv.org/abs/1805.08090)
  - [[Python Reference]](https://github.com/vermaMachineLearning/Graph-Capsule-CNN-Networks)

- **Graph Classification Using Structural Attention (KDD 2018)**
- *结构注意力模型用来图分类*
  - John Boaz Lee, Ryan Rossi, and Xiangnan Kong
  - [[Paper]](http://ryanrossi.com/pubs/KDD18-graph-attention-model.pdf)
  - [[Python Pytorch Reference]](https://github.com/benedekrozemberczki/GAM)

- **Graph Convolutional Policy Network for Goal-Directed Molecular Graph Generation (NIPS 2018)**
- *图卷积策略神经网络在目标导向的分子图生成中的应用*
  - Jiaxuan You, Bowen Liu, Rex Ying, Vijay Pande, and Jure Leskovec
  - [[Paper]](https://arxiv.org/abs/1806.02473)
  - [[Python Reference]](https://github.com/bowenliu16/rl_graph_generation)

- **Hierarchical Graph Representation Learning with Differentiable Pooling (NIPS 2018)**
  - Zhitao Ying, Jiaxuan You, Christopher Morris, Xiang Ren, Will Hamilton and Jure Leskovec
  - [[Paper]](http://papers.nips.cc/paper/7729-hierarchical-graph-representation-learning-with-differentiable-pooling.pdf)
  - [[Python Reference]](https://github.com/rusty1s/pytorch_geometric)

- **Contextual Graph Markov Model: A Deep and Generative Approach to Graph Processing (ICML 2018)**
  - Davide Bacciu, Federico Errica, and Alessio Micheli
  - [[Paper]](https://arxiv.org/pdf/1805.10636.pdf)
  - [[Python Reference]](https://github.com/diningphil/CGMM)

- **MolGAN: An Implicit Generative Model for Small Molecular Graphs (ICML 2018)**
  - Nicola De Cao and Thomas Kipf
  - [[Paper]](https://arxiv.org/pdf/1805.11973.pdf)
  - [[Python Reference]](https://github.com/nicola-decao/MolGAN)

- **Deeply Learning Molecular Structure-Property Relationships Using Graph Attention Neural Network (2018)**
  - Seongok Ryu, Jaechang Lim, and Woo Youn Kim    
  - [[Paper]](https://arxiv.org/abs/1805.10988)
  - [[Python Reference]](https://github.com/SeongokRyu/Molecular-GAT)

- **Compound-protein Interaction Prediction with End-to-end Learning of Neural Networks for Graphs and Sequences (Bioinformatics 2018)**
  - Masashi Tsubaki, Kentaro Tomii, and Jun Sese
  - [[Paper]](https://academic.oup.com/bioinformatics/article/35/2/309/5050020)
  - [[Python Reference]](https://github.com/masashitsubaki/CPI_prediction)
  - [[Python Reference]](https://github.com/masashitsubaki/GNN_molecules)
  - [[Python Alternative ]](https://github.com/xnuohz/GCNDTI)

- **Learning Graph Distances with Message Passing Neural Networks (ICPR 2018)**
  - Pau Riba, Andreas Fischer, Josep Llados, and Alicia Fornes
  - [[Paper]](https://ieeexplore.ieee.org/abstract/document/8545310)
  - [[Python Reference]](https://github.com/priba/siamese_ged)

- **Edge Attention-based Multi-Relational Graph Convolutional Networks (2018)**
  - Chao Shang, Qinqing Liu, Ko-Shin Chen, Jiangwen Sun, Jin Lu, Jinfeng Yi and Jinbo Bi  
  - [[Paper]](https://arxiv.org/abs/1802.04944v1)
  - [[Python Reference]](https://github.com/Luckick/EAGCN)

- **Commonsense Knowledge Aware Conversation Generation with Graph Attention (IJCAI-ECAI 2018)**
  - Hao Zhou, Tom Yang, Minlie Huang, Haizhou Zhao, Jingfang Xu and Xiaoyan Zhu
  - [[Paper]](http://coai.cs.tsinghua.edu.cn/hml/media/files/2018_commonsense_ZhouHao_3_TYVQ7Iq.pdf)
  - [[Python Reference]](https://github.com/tuxchow/ccm)

- **Residual Gated Graph ConvNets (ICLR 2018)**
  - Xavier Bresson and Thomas Laurent
  - [[Paper]](https://arxiv.org/pdf/1711.07553v2.pdf)
  - [[Python Pytorch Reference]](https://github.com/xbresson/spatial_graph_convnets)

- **An End-to-End Deep Learning Architecture for Graph Classification (AAAI 2018)**
  - Muhan Zhang, Zhicheng Cui, Marion Neumann and Yixin Chen
  - [[Paper]](https://www.cse.wustl.edu/~muhan/papers/AAAI_2018_DGCNN.pdf)
  - [[Python Tensorflow Reference]](https://github.com/muhanzhang/DGCNN)    
  - [[Python Pytorch Reference]](https://github.com/muhanzhang/pytorch_DGCNN)
  - [[MATLAB Reference]](https://github.com/muhanzhang/DGCNN)
  - [[Python Alternative]](https://github.com/leftthomas/DGCNN)
  - [[Python Alternative]](https://github.com/hitlic/DGCNN-tensorflow)

- **SGR: Self-Supervised Spectral Graph Representation Learning (KDD DLDay 2018)**
  - Anton Tsitsulin, Davide Mottin, Panagiotis Karra, Alex Bronstein and Emmanueal Müller
  - [[Paper]](https://arxiv.org/abs/1807.02839)
  - [[Python Reference]](http://mott.in/publications/others/sgr/)

- **Deep Learning with Topological Signatures (NIPS 2017)**
  - Christoph Hofer, Roland Kwitt, Marc Niethammer, and Andreas Uhl
  - [[paper]](https://arxiv.org/abs/1707.04041)
  - [[Python Reference]](https://github.com/c-hofer/nips2017)

- **Dynamic Edge-Conditioned Filters in Convolutional Neural Networks on Graphs (CVPR 2017)**
  - Martin Simonovsky and Nikos Komodakis
  - [[paper]](https://arxiv.org/pdf/1704.02901v3.pdf)
  - [[Python Reference]](https://github.com/mys007/ecc)

- **Deriving Neural Architectures from Sequence and Graph Kernels (ICML 2017)**
  - Tao Lei, Wengong Jin, Regina Barzilay, and Tommi Jaakkola
  - [[Paper]](https://arxiv.org/abs/1705.09037)
  - [[Python Reference]](https://github.com/taolei87/icml17_knn)

- **Protein Interface Prediction using Graph Convolutional Networks (NIPS 2017)**
  - Alex Fout, Jonathon Byrd, Basir Shariat and Asa Ben-Hur
  - [[Paper]](https://papers.nips.cc/paper/7231-protein-interface-prediction-using-graph-convolutional-networks)
  - [[Python Reference]](https://github.com/fouticus/pipgcn)

- **Graph Classification with 2D Convolutional Neural Networks (2017)**
  - Antoine J.-P. Tixier, Giannis Nikolentzos, Polykarpos Meladianos and Michalis Vazirgiannis
  - [[Paper]](https://arxiv.org/abs/1708.02218)
  - [[Python Reference]](https://github.com/Tixierae/graph_2D_CNN)

- **CayleyNets: Graph Convolutional Neural Networks with Complex Rational Spectral Filters (IEEE TSP 2017)**
  - Ron Levie, Federico Monti, Xavier Bresson, Michael M. Bronstein
  - [[Paper]](https://arxiv.org/pdf/1705.07664v2.pdf)
  - [[Python Reference]](https://github.com/fmonti/CayleyNet)

- **Semi-supervised Learning of Hierarchical Representations of Molecules Using Neural Message Passing (2017)**
  - Hai Nguyen, Shin-ichi Maeda, Kenta Oono
  - [[Paper]](https://arxiv.org/pdf/1711.10168.pdf)
  - [[Python Reference]](https://github.com/pfnet-research/hierarchical-molecular-learning)

- **Kernel Graph Convolutional Neural Networks (2017)**
  - Giannis Nikolentzos, Polykarpos Meladianos, Antoine Jean-Pierre Tixier, Konstantinos Skianis, Michalis Vazirgiannis
  - [[Paper]](https://arxiv.org/pdf/1710.10689.pdf)
  - [[Python Reference]](https://github.com/giannisnik/cnn-graph-classification)

- **Deep Topology Classification: A New Approach For Massive Graph Classification (IEEE Big Data 2016)**
  - Stephen Bonner, John Brennan, Georgios Theodoropoulos, Ibad Kureshi, Andrew Stephen McGough
  - [[Paper]](https://ieeexplore.ieee.org/document/7840988/)
  - [[Python Reference]](https://github.com/sbonner0/DeepTopologyClassification)

- **Learning Convolutional Neural Networks for Graphs (ICML 2016)**
  - Mathias Niepert, Mohamed Ahmed, Konstantin Kutzkov
  - [[Paper]](https://arxiv.org/abs/1605.05273)
  - [[Python Reference]](https://github.com/tvayer/PSCN)

- **Gated Graph Sequence Neural Networks (ICLR 2016)**
  - Yujia Li, Daniel Tarlow, Marc Brockschmidt, Richard Zemel
  - [[Paper]](https://arxiv.org/abs/1511.05493)
  - [[Python TensorFlow]](https://github.com/bdqnghi/ggnn.tensorflow)
  - [[Python PyTorch]](https://github.com/JamesChuanggg/ggnn.pytorch)
  - [[Python Reference]](https://github.com/YunjaeChoi/ggnnmols)

- **Convolutional Networks on Graphs for Learning Molecular Fingerprints (NIPS 2015)**
  - David Duvenaud, Dougal Maclaurin, Jorge Aguilera-Iparraguirre, Rafael Gómez-Bombarelli, Timothy Hirzel, Alán Aspuru-Guzik, and Ryan P. Adams
  - [[Paper]](https://papers.nips.cc/paper/5954-convolutional-networks-on-graphs-for-learning-molecular-fingerprints.pdf)
  - [[Python Reference]](https://github.com/fllinares/neural_fingerprints_tf)
  - [[Python Reference]](https://github.com/jacklin18/neural-fingerprint-in-GNN)
  - [[Python Reference]](https://github.com/HIPS/neural-fingerprint)
  - [[Python Reference]](https://github.com/debbiemarkslab/neural-fingerprint-theano)

## Graph Kernels
- **Message Passing Graph Kernels (2018)**
  - Giannis Nikolentzos, Michalis Vazirgiannis
  - [[Paper]](https://arxiv.org/pdf/1808.02510.pdf)
  - [[Python Reference]](https://github.com/giannisnik/message_passing_graph_kernels)

- **Matching Node Embeddings for Graph Similarity (AAAI 2017)**
  - Giannis Nikolentzos, Polykarpos Meladianos, and Michalis Vazirgiannis
  - [[Paper]](https://aaai.org/ocs/index.php/AAAI/AAAI17/paper/view/14494)

- **Global Weisfeiler-Lehman Graph Kernels (2017)**
  - Christopher Morris, Kristian Kersting and Petra Mutzel
  - [[Paper]](https://arxiv.org/pdf/1703.02379.pdf)
  - [[C++ Reference]](https://github.com/chrsmrrs/glocalwl)

- **On Valid Optimal Assignment Kernels and Applications to Graph Classification (2016)**
  - Nils Kriege, Pierre-Louis Giscard, Richard Wilson
  - [[Paper]](https://arxiv.org/pdf/1606.01141.pdf)
  - [[Java Reference]](https://github.com/nlskrg/optimal_assignment_kernels)

- **Efficient Comparison of Massive Graphs Through The Use Of ‘Graph Fingerprints’ (MLGWorkshop 2016)**
  - Stephen Bonner, John Brennan, and A. Stephen McGough
  - [[Paper]](http://dro.dur.ac.uk/19773/1/19773.pdf?DDD10+lzdh59+d700tmt)    
  - [[python Reference]](https://github.com/sbonner0/GraphFingerprintComparison)

- **The Multiscale Laplacian Graph Kernel (NIPS 2016)**
  - Risi Kondor and Horace Pan
  - [[Paper]](https://arxiv.org/abs/1603.06186)
  - [[C++ Reference]](https://github.com/horacepan/MLGkernel)

- **Faster Kernels for Graphs with Continuous Attributes (ICDM 2016)**
  - Christopher Morris, Nils M. Kriege, Kristian Kersting and Petra Mutzel
  - [[Paper]](https://arxiv.org/abs/1610.00064)
  - [[Python Reference]](https://github.com/chrsmrrs/hashgraphkernel)

- **Propagation Kernels: Efficient Graph Kernels From Propagated Information (Machine Learning 2016)**
  - Neumann, Marion and Garnett, Roman and Bauckhage, Christian and Kersting, Kristian
  - [[Paper]](https://link.springer.com/article/10.1007/s10994-015-5517-9)
  - [[Matlab Reference]](https://github.com/marionmari/propagation_kernels)

- **Halting Random Walk Kernels (NIPS 2015)**
  - Mahito Sugiyama and Karsten M. Borgward
  - [[Paper]](https://pdfs.semanticscholar.org/79ba/8bcfbf9496834fdc22a1f7c96d26d776cd6c.pdf)
  - [[C++ Reference]](https://github.com/BorgwardtLab/graph-kernels)

- **Scalable Kernels for Graphs with Continuous Attributes (NIPS 2013)**
  - Aasa Feragen, Niklas Kasenburg, Jens Petersen, Marleen de Bruijne and Karsten Borgwardt
  - [[Paper]](https://papers.nips.cc/paper/5155-scalable-kernels-for-graphs-with-continuous-attributes.pdf)

- **Subgraph Matching Kernels for Attributed Graphs (ICML 2012)**
  - Nils Kriege and Petra Mutzel
  - [[Paper]](https://arxiv.org/abs/1206.6483)
  - [[Python Reference]](https://github.com/mockingbird2/GraphKernelBenchmark)  

- **Nested Subtree Hash Kernels for Large-Scale Graph Classification over Streams (ICDM 2012)**
  - Bin Li, Xingquan Zhu, Lianhua Chi, Chengqi Zhang
  - [[Paper]](https://ieeexplore.ieee.org/document/6413884/)
  - [[Python Reference]](https://github.com/benedekrozemberczki/NestedSubtreeHash)  

- **Weisfeiler-Lehman Graph Kernels (JMLR 2011)**
  - Nino Shervashidze, Pascal Schweitzer, Erik Jan van Leeuwen, Kurt Mehlhorn, and Karsten M. Borgwardt
  - [[Paper]](http://www.jmlr.org/papers/volume12/shervashidze11a/shervashidze11a.pdf)
  - [[Python Reference]](https://github.com/jajupmochi/py-graph)
  - [[Python Reference]](https://github.com/deeplego/wl-graph-kernels)
  - [[C++ Reference]](https://github.com/BorgwardtLab/graph-kernels)  

- **Fast Neighborhood Subgraph Pairwise Distance Kernel (ICML 2010)**
  - Fabrizio Costa and Kurt De Grave
  - [[Paper]](https://icml.cc/Conferences/2010/papers/347.pdf)
  - [[C++ Reference]](www.bioinf.uni-freiburg.de/~costa/EDeNcpp.tgz)
  - [[Python Reference]](https://github.com/fabriziocosta/EDeN)

- **A Linear-time Graph Kernel (ICDM 2009)**
  - Shohei Hido and Hisashi Kashima
  - [[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=5360243)  
  - [[Python Reference]](https://github.com/hgascon/adagio)

- **Weisfeiler-Lehman Subtree Kernels (NIPS 2009)**
  - Nino Shervashidze, Pascal Schweitzer, Erik Jan van Leeuwen, Kurt Mehlhorn, and Karsten M. Borgwardt
  - [[Paper]](http://papers.nips.cc/paper/3813-fast-subtree-kernels-on-graphs.pdf)
  - [[Python Reference]](https://github.com/jajupmochi/py-graph)
  - [[Python Reference]](https://github.com/deeplego/wl-graph-kernels)
  - [[C++ Reference]](https://github.com/BorgwardtLab/graph-kernels)

- **Fast Computation of Graph Kernels (NIPS 2006)**
  - S. V. N. Vishwanathan, Karsten M. Borgwardt, and Nicol N. Schraudolph
  - [[Paper]](http://www.dbs.ifi.lmu.de/Publikationen/Papers/VisBorSch06.pdf)
  - [[Python Reference]](https://github.com/jajupmochi/py-graph)
  - [[C++ Reference]](https://github.com/BorgwardtLab/graph-kernels)

- **Shortest-Path Kernels on Graphs (ICDM 2005)**
  - Karsten M. Borgwardt and Hans-Peter Kriegel
  - [[Paper]](https://www.ethz.ch/content/dam/ethz/special-interest/bsse/borgwardt-lab/documents/papers/BorKri05.pdf)
  - [[C++ Reference]](https://github.com/KitwareMedical/ITKTubeTK)

- **Cyclic Pattern Kernels For Predictive Graph Mining (KDD 2004)**
  - Tamás Horváth, Thomas Gärtner, and Stefan Wrobel
  - [[Paper]](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.332.6158&rep=rep1&type=pdf)
  - [[Python Reference]](https://github.com/jajupmochi/py-graph)

- **Extensions of Marginalized Graph Kernels (ICML 2004)**
  - Pierre Mahe, Nobuhisa Ueda, Tatsuya Akutsu, Jean-Luc Perret, and Jean-Philippe Vert
  - [[Paper]](http://members.cbio.mines-paristech.fr/~jvert/publi/04icml/icmlMod.pdf)
  - [[Python Reference]](https://github.com/jajupmochi/py-graph)

- **Marginalized Kernels Between Labeled Graphs (ICML 2003)**
  - Hisashi Kashima, Koji Tsuda, and Akihiro Inokuchi
  - [[Paper]](https://pdfs.semanticscholar.org/2dfd/92c808487049ab4c9b45db77e9055b9da5a2.pdf)
  - [[Python Reference]](https://github.com/jajupmochi/py-graph)
