**What exactly is the Dirichlet Multinomial Model?** 🤔

Dirichlet Multinomial Mixtures (DMM) is simply a probabilistic method for the clustering of community data. It is an infinite mixture model, which means that the method can infer the optimal number of community types. Before going deep into the understanding of how a DMM works, let us first see the basic issues of clustering and later acknowledge how can a DMM cater to these issues! There might arise several issues while clustering text data and below listed are few important ones:
1. Setting of the **number of clusters**
2. Ability to work with **high-dimensional data**
3. **Interpretability** of results
4. **Scalability** to large datasets
 
🤔So, one might think while measures like the Term Frequency-Inverse Document Frequency (TF-IDF) might solve some of them, they cannot work well in the short text setting as most words only occur once in each short text. Other clustering methods like Gaussian Mixture Model, Affinity Propagation, and Spectral clustering cannot solve the issues broadly because they are not scalable with high-dimensional and large-volume data like texts. Furthermore, while models such as Vector Space Model which is used mainly to represent the texts, the sparse and high-dimensional vectors will result in a waste of both memory and computation time. Many such models are failing to cope with the challenges posed by text-clustering. One way to solve the challenges is to use a DMM(Dirichlet Multinomial Mixture model)

❗**A Dirichlet Multinomial Mixture (DMM) model** or in short a **DMM** is a probabilistic generative model for documents and assumes the below while the generative process-
..* that the documents are generated by a mixture model 
..* there is a one-to-one correspondence between mixture components and clusters. 
So, when generating document d, DMM first selects a mixture component (cluster) k according to the mixture weights (weights of clusters), _P(z = k)_. Then document d is generated by the selected mixture component (cluster) from the probability distribution _P(d|z = k)_.  Thus we can characterize the likelihood of document d with the sum of the total probability over all clusters:

![likelihood_DMM](https://github.com/UmaGunturi/awesome-ai-ml-dl/blob/master/formulae/likehood_DMM.png)

Here, K is the number of mixture components (clusters). Now, the problem becomes how to define _P(d|z = k)_ and _P(z = k)_. DMM makes the Naive Bayes assumption that the words in a document are generated independently when the document’s cluster label k is known, and the probability of a word is independent of its position within the document. Then the probability of document d generated by cluster k can be derived as follows:

![DMM_formula](https://github.com/UmaGunturi/awesome-ai-ml-dl/blob/master/formulae/DMM_formula.png)

**Was all this mathematics so hard to process?**
⭐Here is an easy to understand graphical model of GMM!!
   ![DMM_graphical_view](https://github.com/UmaGunturi/awesome-ai-ml-dl/blob/master/formulae/dmm_graphical_view.png)

💡Another model derived from DMM is GSDMM as mentioned in [paper](http://dbgroup.cs.tsinghua.edu.cn/wangjy/papers/KDD14-GSDMM.pdf):
      In this excellent short text clustering problem, they estimate the mixture component (cluster) z for each document d and introduce a GSDMM algorithm. To the best of my knowledge, this is one of the best attempts made to use DMM in text clustering. They found that GSDMM has the following nice properties: 
1) GSDMM can infer the number of clusters automatically; 
2) GSDMM has a clear way to balance the completeness and homogeneity of the clustering results;
3) GSDMM is fast to converge;
4) Unlike the Vector Space Model (VSM)-based approaches, GSDMM can cope with the sparse and high-dimensional problem of short texts; 
5) Like Topic Models, GSDMM can also obtain the representative words of each cluster.

❓**Are there any exisiting implementations of GSDMM?**

The possible implementations of the collapsed Gibbs Sampling algorithm for Dirichlet Multinomial Mixture model (GSDMM):
Paper Link: http://dbgroup.cs.tsinghua.edu.cn/wangjy/papers/KDD14-GSDMM.pdf  
Java Source Code: https://github.com/WHUIR/GSDMM  
Available Python Implementation: https://github.com/jrmazarura/GPM  

💡Some details about the Python Implementation:
GPyM_TM is a python package that is primarily used to perform text clustering. This library provides two models - GSDMM (It is Dirichlet Multinomial Model) and GPM (It is a Poisson Model). Topic modeling is one of the applications that can be achieved by text clustering.

❓What does this package do?

GSDMM.DMM() is a function that takes two mandatory input parameters - corpus and number of clusters desired by us. Other optional input parameters are confidence parameters in the Dirichlet Multinomial Model, number of Gibbs Sampler iterations.Few outputs of GSDMM.DMM()that can prove to be useful is:

1. *Theta* - It provides the probability distributions of different roles for a given user. This distribution is based on the content of the user given as input. The number of roles is equal to the number of clusters we have specified in the input arguments of GSDMM.DMM().
2. *The Size of finalAssignments vector*- denotes the optimal number of clusters that GSDMM has found for our data.
3. *Selected_theta* - It provides the probability distributions of different roles for a given user but the number of roles is equal to the optimal number of clusters GSDMM() has found out.



❌Disclaimer: This list is not intended to be exhaustive, nor to cover every single topic related to DMM. There are plenty of amazing resources available and this is rather a pick of the most recent impactful works in the past few years  mostly influenced by what I read. Here are a few picks for you:

🌍**Useful References**

📌https://www.kdd.org/kdd2016/papers/files/rpp0617-yinAemb.pdf  
📌https://www.cs.cmu.edu/~knigam/papers/multinomial-aaaiws98.pdf  
📌https://github.com/jackyin12/GSDMM  
📌http://keg.cs.tsinghua.edu.cn/jietang/publications/KDD15-Han-Tang-Prob-Community-Role.pdf  
📌https://link.springer.com/article/10.1023/A:1007692713085  
📌https://www.jstor.org/stable/2982840?origin=crossref  







