# A title

Contributed by XX, XX and XX.

## [Content](#content)
<table>
<tr><td colspan="2"><a href="#ch1">1. Introduction</a></td></tr> 
<tr><td colspan="2"><a href="#ch3">3. COMMUNITY DETECTION WITH PROBABILISTIC GRAPHICAL MODEL</a></td></tr> 
<tr>
    <td>&emsp;&ensp;<a href="#DGM">3.1 Directed Graphical Models</a></td>
</tr> 
<tr>
    <td>&emsp;&ensp;<a href="#UGM">3.2 Undirected Graphical Mode</a></td>
</tr> 
<tr>
    <td>&emsp;&ensp;<a href="#DMUM">3.3 Integrating Directed and Undirected Models</a></td>
</tr>
<tr><td colspan="2"><a href="#ch4">4. COMMUNITY DETECTION WITH DEEP LEARNING</a></td></tr> 
<tr>
    <td>&emsp;&ensp;<a href="#AE">4.1 Auto-encoder-based Methods</a></td>
</tr> 
<tr>
    <td>&emsp;&ensp;<a href="#GAN">4.2 Generative Adversarial Network-based Methods</a></td>
</tr> 
<tr>
    <td>&emsp;&ensp;<a href="#Graph-Convolutional-Network-based-Methods">4.3 Graph Convolutional Network-based Methods</a></td>
</tr> 
<tr>
    <td>&emsp;&ensp;<a href="#GCNUGM">4.4 Integrating Graph Convolutional Network and Undirected Graphical Models</a></td>
</tr>
</table>

## [COMMUNITY DETECTION WITH DEEP LEARNING](#content)
## [Auto-encoder-based Methods](#content)
#### Stacked Auto-encoders

1. **Network embedding for community detection in attributed networks.** ACM TKDD 2020. [paper](https://dl.acm.org/doi/10.1145/3385415)

     *Heli Sun, Fang He, Jianbin Huang, Yizhou Sun, Yang Li, Chenyu Wang, Liang He, Zhongbin Sun, Xiaolin Jia*
     
1. **High-performance community detection in social networks using a deep transitive autoencoder.** Inf. Sci 2019. [paper](https://linkinghub.elsevier.com/retrieve/pii/S0020025519303251)

     *Ying Xie, Xinmei Wang, Dan Jiang, Rongbin Xu*
     
1. **A distributed overlapping community detection model for large graphs using autoencoder.** Future Gener. Comput. Syst. 2019. [paper](https://linkinghub.elsevier.com/retrieve/pii/S0167739X17327863)

     *Vandana Bhatia, Rinkle Rani*

1. **Incorporating network structure with node contents for community detection on large networks using deep learning.** Neurocomputing 2018. [paper](https://linkinghub.elsevier.com/retrieve/pii/S0925231218300985)

     *Jinxin Cao, Di Jin, Liang Yang, Jianwu Dang*

1. **Autoencoder based community detection with adaptive integration of network topology and node contents.** KSEM 2018. [paper](http://link.springer.com/10.1007/978-3-319-99247-1_16)

     *Jinxin Cao, Di Jin, Jianwu Dang*
    
1. **Using deep learning for community discovery in social networks.** ICTAI 2017. [paper](https://ieeexplore.ieee.org/document/8371938)

     *Di Jin, Meng Ge, Zhixuan Li, Wenhuan Lu, Dongxiao He, Françoise Fogelman-Soulié*
  
1. **Modularity based community detection with deep learning.** IJCAI 2016. [paper](https://www.ijcai.org/Proceedings/16/Papers/321.pdf)

     *Liang Yang, Xiaochun Cao, Dongxiao He, Chuan Wang, Xiao Wang, Weixiong Zhang*
    
#### Sparse Auto-encoders
     
1. **Stacked autoencoderbased community detection method via an ensemble clustering framework.** Inf. Sci 2020. [paper](https://www.sciencedirect.com/science/article/pii/S002002552030270X)

     *Rongbin Xu, Yan Che, Xinmei Wang, Jianxiong Hu, Ying Xie*
     
1. **Dfuzzy: a deep learning-based fuzzy clustering model for large graphs.** Knowl. Inf. Syst. 2018. [paper](https://link.springer.com/article/10.1007/s10115-018-1156-3)

     *Vandana Bhatia, Rinkle Rani*
 
1. **Learning deep representations for graph clustering.** AAAI 2014. [paper](https://dl.acm.org/doi/10.5555/2893873.2894074)
 
     *Fei Tian, Bin Gao, Qing Cui, Enhong Chen, Tie-Yan Liu*
    
#### Denoising Auto-encoders

1. **MGAE: marginalized graph autoencoder for graph clustering.** CIKM 2017. [paper](https://dl.acm.org/doi/10.1145/3132847.3132967)

     *Chun Wang, Shirui Pan, Guodong Long, Xingquan Zhu, Jing Jiang*
     
1. **Graph clustering with dynamic embedding.** CoRR 2017. [paper](https://arxiv.org/abs/1712.08249)

     *Carl Yang, Mengxiong Liu, Zongyi Wang, Liyuan Liu, Jiawei Han*
     
#### Variational Auto-encoders

1. **Network-specific variational auto-encoder for embedding in attribute networks.** IJCAI 2019. [paper](https://www.ijcai.org/Proceedings/2019/370)

     *Di Jin, Bingyi Li, Pengfei Jiao, Dongxiao He, Weixiong Zhang*
     
1. **Optimizing variational graph autoencoder for community detection.** BigData 2019. [paper](https://ieeexplore.ieee.org/document/9006123/)

     *Jun Jin Choong, Xin Liu, Tsuyoshi Murata*
     
1. **Learning community structure with variational autoencoder.** ICDM 2018. [paper](https://ieeexplore.ieee.org/document/8594831)

     *Jun Jin Choong, Xin Liu, Tsuyoshi Murata*

1. **Adversarially regularized graph autoencoder for graph embedding.** IJCAI 2018. [paper](https://www.ijcai.org/Proceedings/2018/362)

     *Shirui Pan, Ruiqi Hu, Guodong Long, Jing Jiang, Lina Yao, Chengqi Zhang*

## [Generative Adversarial Network-based Methods](#content)

1. **MEGAN: A generative adversarial network for multi-view network embedding.** IJCAI 2019. [paper](https://www.ijcai.org/Proceedings/2019/489)
     
     *Yiwei Sun, Suhang Wang, Tsung-Yu Hsieh, Xianfeng Tang, Vasant G. Honavar*
     
1. **JANE: jointly adversarial network embedding.** IJCAI 2020. [paper](https://www.ijcai.org/Proceedings/2020/192)
     
     *Liang Yang, Yuexue Wang, Junhua Gu, Chuan Wang, Xiaochun Cao, Yuanfang Guo*
     
1. **Adversarial attack on community detection by hiding individuals.** WWW 2020. [paper](https://dl.acm.org/doi/10.1145/3366423.3380171)
     
     *Jia Li, Honglei Zhang, Zhichao Han, Yu Rong, Hong Cheng, Junzhou Huang*
     
1. **SEAL: learning heuristics for community detection with generative adversarial networks.** SIGKDD 2020. [paper](https://dl.acm.org/doi/10.1145/3394486.3403154)
     
     *Yao Zhang, Yun Xiong, Yun Ye, Tengfei Liu, Weiqiang Wang, Yangyong Zhu, Philip S. Yu*
     
1. **GANE: A generative adversarial network embedding.** . IEEE Trans. Neural Networks Learn. Syst. 2020. [paper](https://ieeexplore.ieee.org/document/8758400/)
     
     *Huiting Hong, Xin Li, Mingzhong Wang*
     
1. **Progan: Network embedding via proximity generative adversarial network.** SIGKDD 2019. [paper](https://dl.acm.org/doi/10.1145/3292500.3330866)
     
     *Hongchang Gao, Jian Pei, Heng Huang*
     
1. **Communitygan: Community detection with generative adversarial nets.** WWW 2019. [paper](https://dl.acm.org/doi/10.1145/3308558.3313564)
     
     *Yuting Jia, Qinqin Zhang, Weinan Zhang, Xinbing Wang*
     
1. **Generative adversarial nets.** NIPS 2014. [paper](https://proceedings.neurips.cc/paper/2014/hash/5ca3e9b122f61f8f06494c97b1afccf3-Abstract.html)
     
     *Ian J. Goodfellow, Jean Pouget-Abadie, Mehdi Mirza, Bing Xu, David Warde-Farley, Sherjil Ozair, Aaron C. Courville, Yoshua Bengio*
     
1. **Adversarial mutual information learning for network embedding.** IJCAI 2020. [paper](https://www.ijcai.org/Proceedings/2020/459)
     
     *Dongxiao He, Lu Zhai, Zhigang Li, Di Jin, Liang Yang, Yuxiao Huang, Philip S. Yu*

## [Graph Convolutional Network-based Methods](#content)

1. **Semi-supervised classification with graph convolutional networks.** ICLR (Poster) 2017. [paper](https://openreview.net/forum?id=SJU4ayYgl)
     
     *Thomas N. Kipf, Max Welling*
     
1. **Community detection via joint graph convolutional network embedding in attribute network.**  ICANN (Workshop) 2019. [paper](https://link.springer.com/chapter/10.1007%2F978-3-030-30493-5_55)
     
     *Di Jin, Bingyi Li, Pengfei Jiao, Dongxiao He, Hongyu Shan*
     
1. **Graph convolutional networks meet markov random fields: Semi-supervised community detection in attribute networks.**  AAAI 2019. [paper](https://ojs.aaai.org//index.php/AAAI/article/view/3780)
     
     *Di Jin, Ziyang Liu, Weihao Li, Dongxiao He, Weixiong Zhang*
     
1. **Heterogeneous graph convolutional networks for temporal community detection.** CoRR 2019. [paper](https://arxiv.org/abs/1909.10248)
     
     *Yaping Zheng, Shiyi Chen, Xiaofeng Zhang, Di Wang*
     
1. **GMNN: graph markov neural networks.** ICML 2019:. [paper](http://proceedings.mlr.press/v97/qu19a.html)
     
     *Meng Qu, Yoshua Bengio, Jian Tang*
     
1. **Community-centric graph convolutional network for unsupervised community detection.** IJCAI 2020. [paper](https://www.ijcai.org/Proceedings/2020/486)
     
     *Dongxiao He, Yue Song, Di Jin, Zhiyong Feng, Binbin Zhang, Zhizhi Yu, Weixiong Zhang*



## [Integrating Graph Convolutional Network and Undirected Graphical Models](#content)

1. **GMNN: graph markov neural networks.** ICML 2019:. [paper](http://proceedings.mlr.press/v97/qu19a.html)
     
     *Meng Qu, Yoshua Bengio, Jian Tang*
     
1. **Graph convolutional networks meet markov random fields: Semi-supervised community detection in attribute networks.**  AAAI 2019. [paper](https://ojs.aaai.org//index.php/AAAI/article/view/3780)
     
     *Di Jin, Ziyang Liu, Weihao Li, Dongxiao He, Weixiong Zhang*
     
1. **A view of the em algorithm that justifies incremental, sparse, and other variants.** Learning in Graphical Models  1998. [paper](https://link.springer.com/chapter/10.1007%2F978-94-011-5014-9_12)
     
     *Radford M. Neal, Geoffrey E. Hinton*
     
1. **Conditional random field enhanced graph convolutional neural networks.** KDD 2019. [paper](https://dl.acm.org/doi/10.1145/3292500.3330888)
     
     *Hongchang Gao, Jian Pei, Heng Huang*



















 
