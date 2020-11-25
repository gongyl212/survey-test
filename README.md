@@ -4,33 +4,56 @@ GNN: graph neural network
Contributed by ?.

## [Content](#content)
<table>
<tr><td colspan="2"><a href="#survey-papers"><a href="">1. Survey</a></td></tr> 
<tr><td colspan="2"><a href="#models">2. Models</a></td></tr>
<tr>
    <td>&emsp;<a href="#basic-models">2.1 Basic Models</a></td>
    <td>&emsp;<a href="#graph-types">2.2 Graph Types</a></td>
</tr>
<tr>
    <td>&emsp;<a href="#pooling-methods">2.3 Pooling Methods</a></td>
    <td>&emsp;<a href="#analysis">2.4 Analysis</a></td>
</tr>
<tr>
    <td>&emsp;<a href="#efficiency">2.5 Efficiency</a></td>
    <td>&emsp;</td>
</tr>
<tr><td colspan="2"><a href="#applications">3. Applications</a></td></tr> 
<tr>
    <td>&emsp;<a href="#physics">3.1 Physics</a></td>
    <td>&emsp;<a href="#chemistry-and-biology">3.2 Chemistry and Biology</a></td>
</tr> 
<tr>
    <td>&emsp;<a href="#knowledge-graph">3.3 Knowledge Graph</a></td>
    <td>&emsp;<a href="#recommender-systems">3.4 Recommender Systems</a></td>
</tr>
<tr>
    <td>&emsp;<a href="#computer-vision">3.5 Computer Vision</a></td>
    <td>&emsp;<a href="#natural-language-processing">3.6 Natural Language Processing</a></td>
</tr> 
<tr>
    <td>&emsp;<a href="#generation">3.7 Generation</a></td>
    <td>&emsp;<a href="#combinatorial-optimization">3.8 Combinatorial Optimization</a></td>
</tr> 
<tr>
    <td>&emsp;<a href="#adversarial-attack">3.9 Adversarial Attack</a></td>
    <td>&emsp;<a href="#graph-clustering">3.10 Graph Clustering</a></td>
</tr>
<tr>
    <td>&emsp;<a href="#graph-classification">3.11 Graph Classification</a></td>
    <td>&emsp;<a href="#reinforcement-learning">3.12 Reinforcement Learning</a></td>
</tr>
<tr>
    <td>&emsp;<a href="#traffic-network">3.13 Traffic Network</a></td>
    <td>&emsp;<a href="#few-shot-and-zero-shot-learning">3.14 Few-shot and Zero-shot Learning</a></td>
</tr>
<tr>
    <td>&emsp;<a href="#program-representation">3.15 Program Representation</a></td>
    <td>&emsp;<a href="#social-network">3.16 Social Network</a></td>
</tr> 
</table>

## [Survey papers](#content)

## Auto-encoders
#### Stacked Auto-encoders

1. **Modularity based community detection with deep learning**
*L. Yang, X. Cao, D. He, C. Wang, X. Wang, and W. Zhang* IJCA 2016. [paper](https://www.ijcai.org/Proceedings/16/Papers/321.pdf)

-1. **Interaction Networks for Learning about Objects, Relations and Physics**
*Peter Battaglia, Razvan Pascanu, Matthew Lai, Danilo Rezende, Koray Kavukcuoglu* NIPS 2016. [paper](https://arxiv.org/pdf/1612.00222.pdf)

1. **Interaction Networks for Learning about Objects, Relations and Physics.**
*Peter Battaglia, Razvan Pascanu, Matthew Lai, Danilo Rezende, Koray Kavukcuoglu.* NIPS 2016. [paper](https://arxiv.org/pdf/1612.00222.pdf)

1. **Graph Neural Networks: A Review of Methods and Applications.**
*Jie Zhou, Ganqu Cui, Zhengyan Zhang, Cheng Yang, Zhiyuan Liu, Maosong Sun.* 2018. [paper](https://arxiv.org/pdf/1812.08434.pdf)

1. **Deep Graph Infomax.** ICLR 2019. [paper](https://openreview.net/pdf?id=rklz9iAcKQ)

    *Petar Veličković, William Fedus, William L. Hamilton, Pietro Liò, Yoshua Bengio, R Devon Hjelm.*

1. **Combining Neural Networks with Personalized PageRank for Classification on Graphs.** ICLR 2019. [paper](https://arxiv.org/pdf/1810.05997.pdf)
    
    *Johannes Klicpera, Aleksandar Bojchevski, Stephan Günnemann.*

#### Stacked Auto-encoders


#### Sparse Auto-encoders


#### Denoising Auto-encoders


#### Variational Auto-encoders


1. **Interaction Networks for Learning about Objects, Relations and Physics**
*Peter W. Battaglia, Razvan Pascanu, Matthew Lai, Danilo Rezende, Koray Kavukcuoglu* NIPS 2016. [paper](https://arxiv.org/pdf/1612.00222.pdf)
*Peter Battaglia, Razvan Pascanu, Matthew Lai, Danilo Rezende, Koray Kavukcuoglu* NIPS 2016. [paper](https://arxiv.org/pdf/1612.00222.pdf)

1. **A Compositional Object-Based Approach to Learning Physical Dynamics**
*Michael B. Chang, Tomer Ullman, Antonio Torralba, Joshua B. Tenenbaum* ICLR 2017. [paper](https://arxiv.org/pdf/1612.00341.pdf)

1. **Visual Interaction Networks: Learning a Physics Simulator from Video** 
*Nicholas Watters, Andrea Tacchetti, Théophane Weber, Razvan Pascanu, Peter Battaglia, Daniel Zoran* NIPS 2017. [paper](http://papers.nips.cc/paper/7040-visual-interaction-networks-learning-a-physics-simulator-from-video.pdf)

1. **Relational neural expectation maximization: Unsupervised discovery of objects and their interactions**
*Sjoerd van Steenkiste, Michael Chang, Klaus Greff, Jürgen Schmidhuber* ICLR 2018. [paper](https://arxiv.org/pdf/1802.10353.pdf)

1. **Graph networks as learnable physics engines for inference and control**
*Alvaro Sanchez-Gonzalez, Nicolas Heess, Jost Tobias Springenberg, Josh Merel, Martin Riedmiller, Raia Hadsell, Peter Battaglia* ICML 2018. [paper](https://arxiv.org/pdf/1806.01242.pdf)
