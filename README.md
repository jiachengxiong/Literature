**GNN in Drug Discovery**
====  
This is a collection of recent parpers of graph neural network applied in drug discovery


# Contents
- [Review](#Review)
- [Articles](#Articles)
  - [Unsupervised Learning](#Unsupervised)
  - [Property Prediction](#Properties)
      - [Small Molecular](#Small_Molecular)
      - [Protien](#Protien)
  - [Chemical Reaction Prediction](#Reaction)
      - [Prediction of General Chemical Reaction](#General)
      - [Prediction of Specific Types of Chemical Reactions](#Specific)
      - [Prediction of Retrosynthesis ](#Retros)
  - [Molecule Generation](#Generation)
      - [Based on GAN](#GAN)
      - [Based on VAE](#VAE)
      - [Based on Autoregression](#Autoregression)
      - [Based on Invertible Flow](#Flow)
      - [Based on Chemical Reaction](#Reaction)
   - [Interaction & Association Prediction](#Interaction)
      - [Drug-Target Interaction](#DTI)
      - [Drug-Drug Interaction](#DDI)
      - [Protien-Protein Interaction](#PPI)
      - [Solute-Solvent Interaction](#SSI)
      - [RNA-Protein Interaction](#RPI)
      - [Disease-lncRNA Association](#DlA)
      - [Drug-miRNA Association](#DmA)
      - [Disease-Gene Association](#DGA)

<a name="Review" />

# Review
1. **Graph convolutional networks for computational drug development and discovery.** *BRIEF BIOINFORM.* ***2019.*** [Link](https://academic.oup.com/bib/advance-article/doi/10.1093/bib/bbz042/5498046)
<a name="Articles" />

# Articles

<a name="Unsupervised" />

## Unsupervised Learning
1. **Strategies For Pre-training Graph Neural Networks.** *ICLR.* ***2020.*** [Link](https://arxiv.org/pdf/1905.12265.pdf)

<a name="Properties" />

## Prediction of Molecular Properties
<a name="Small_Molecular" />

### Small Molecular

1. **Convolutional networks on graphs for learning molecular fingerprints.** *NIPS.* ***2015***. [Link](https://papers.nips.cc/paper/5954-convolutional-networks-on-graphs-for-learning-molecular-fingerprints.pdf)

1. **Molecular graph convolutions: moving beyond fingerprints.** *J. Comput.-Aided Mol. Des.* ***2016***. [Link](https://link.springer.com/article/10.1007%2Fs10822-016-9938-8)

1. **Neural message passing for quantum chemistry.** JMLR. ***2017.*** [Link](https://arxiv.org/pdf/1704.01212.pdf)

1. **Deeply learning molecular structure-property relationships using attention- and gate-augmented graph convolutional network.** *arXiv.* ***2018.*** [Link](https://arxiv.org/pdf/1805.10988.pdf)

1. **Edge attention-based multi-relational graph convolutional networks.** *arXiv.* ***2018.*** [Link](https://arxiv.org/abs/1802.04944)

1. **Graph warp module an auxiliary module for boosting the power of graph neural networks in molecular graph analysis.** *arXiv.* ***2019.*** [Link](https://arxiv.xilesou.top/pdf/1902.01020.pdf)

1. **Analyzing Learned Molecular Representations for Property Prediction.** *J CHEM INF MODEL* ***2019.*** [Link](https://pubs.acs.org/doi/abs/10.1021/acs.jcim.9b00237)

1. **Graph networks as a universal machine learning framework for molecules and crystals.** *CHEM MATER.* ***2019.*** [Link](https://pubs.acs.org/doi/abs/10.1021/acs.chemmater.9b01294)

1. **Molecular activity prediction using graph convolutional deep neural network considering distance on a molecular graph.** *aRxiv.* ***2019.*** [Link](https://arxiv.xilesou.top/pdf/1907.01103.pdf)

1. **Multitask learning on graph neural networks applied to molecular property predictions.** *aRxiv.* ***2019.*** [Link](https://arxiv.xilesou.top/pdf/1910.13124.pdf)

1. **Pushing the boundaries of molecular representation for drug discovery with the graph attention mechanism.** *J MED CHEM.* ***2019.*** [Link](https://pubs.acs.org/doi/abs/10.1021/acs.jmedchem.9b00959)

2. **Molecular geometry prediction using a deep generative graph neural network.** *Sci Rep.* ***2019.*** [Link](https://www.nature.xilesou.top/articles/s41598-019-56773-5)

3. **Practical high-quality electrostatic potential surfaces for drug.** *J MED CHEM.* ***2019.*** [Link](https://pubs.acs.org/doi/abs/10.1021/acs.jmedchem.9b01129)

1. **Building attention and edge message passing neural networks for bioactivity and physical–chemical property prediction.** *J CHEMINFORMATICS.* ***2020.*** [Link](https://link.springer.xilesou.top/article/10.1186/s13321-019-0407-y)

1. **A deep learning approach to antibiotic discovery.** *CELL.* ***2020*** [Link](https://www.sciencedirect.com/science/article/pii/S0092867420301021)
<a name="Protien" />

### Protien

1. **Structural learning of proteins using graph convolutional neural networks.** *bioRxiv.* ***2019.*** [Link](https://www.biorxiv.org/content/biorxiv/early/2019/04/16/610444.full.pdf)

<a name="Reaction" />

## Chemical Reaction Prediction
<a name="General" />

### Prediction of General Chemical Reaction
1. **Predicting organic reaction outcomes with weisfeiler-lehman network.** *NIPS.* ***2017.*** [Link](https://papers.nips.cc/paper/6854-predicting-organic-reaction-outcomes-with-weisfeiler-lehman-network.pdf)

2. **A graph-convolutional neural network model for the prediction of chemical reactivity.** *CHEM SCI.* ***2019.*** [Link](https://pubsrsc.xilesou.top/lv/content/articlehtml/2019/sc/c8sc04228d)

3. **Graph transformation policy network for chemical reaction prediction.** *KDD.* ***2019.*** [Link](https://dl.acm.org/doi/abs/10.1145/3292500.3330958)

4. **Integrating deep neural networks and symbolic inference for organic reactivity prediction.** *chemArix.* ***2020.*** [Link](https://chemrxiv.org/articles/Integrating_Deep_Neural_Networks_and_Symbolic_Inference_for_Organic_Reactivity_Prediction/11659563)
<a name="Specific" />

### Prediction of Specific Types of Chemical Reactions
1. **Rapid and accurate prediction of pka values of C–H acids using graph convolutional neural networks.** *JACS.* ***2019.*** [Link](https://pubs.acs.org/doi/abs/10.1021/jacs.9b05895)

<a name="Retros" />

### Prediction of Retrosynthesis
1.  **Interpretable retrosynthesis prediction in two steps.** *ChemRxiv.* ***2020.***  [Link](https://chemrxiv.org/articles/Interpretable_Retrosynthesis_Prediction_in_Two_Steps/11869692)

<a name="Generation" />

## Molecule Generation
<a name="GAN" />


### Based on GAN
1. **MolGAN: An implicit generative model for small molecular graphs.** *aRxiv.* ***2018.*** [Link](https://arxiv.xilesou.top/pdf/1805.11973.pdf%20http://arxiv.org/abs/1805.11973.pdf)

<a name="VAE" />

### Based on VAE
1. **Graphvae: Towards generation of small graphs using variational autoencoders.** *ICANN.* ***2018.*** [Link](https://arxiv.xilesou.top/pdf/1802.03480.pdf)

3. **Junction tree variational autoencoder for molecular graph generation.** *PMLR.* ***2018.*** [Link](http://proceedings.mlr.press/v80/jin18a/jin18a.pdf)

2. **Efficient learning of non-autoregressive graph variational autoencoders for molecular graph generation.** *J CHEMINFORMATICS.* ***2019.*** [Link](https://jcheminf.biomedcentral.com/track/pdf/10.1186/s13321-019-0396-x)

5. **Hierarchical graph-to-graph translation for molecules.** *aRxiv.* ***2019.*** [Link](https://arxiv.org/pdf/1907.11223.pdf)

5. **Learning Multimodal Graph-to-graph Translation For Molecular Optimization.** *ICLR.* ***2019.*** [Link](https://arxiv.xilesou.top/pdf/1812.01070.pdf)

4. **Core: Automatic molecule optimization using copy & refine strategy.** *AAAI.* ***2020.*** [Link](https://arxiv.xilesou.top/pdf/1912.05910.pdf)

<a name="Autoregression" />

### Based on Autoregression

1. **Graph convolutional policy network for goal-directed molecular graph generation.** *NIPS.* ***2018.*** [Link](http://papers.nips.cc/paper/7877-graph-convolutional-policy-network-for-goal-directed-molecular-graph-generation.pdf)

2. **Multi-objective de novo drug design with conditional graph generative model.** *J CHEMINFORMATICS.* ***2018.*** [Link](https://link.springer.com/article/10.1186/s13321-018-0287-6#author-information)

3. **MolecularRNN: Generating realistic molecular graphs with optimized properties.** *aRxiv.* ***2019.*** [Link](https://arxiv.xilesou.top/pdf/1905.13372.pdf)


<a name="Flow" />

### Based on Invertible Flow
1. **GraphNVP:An invertible flow model for generating molecular graphs.** *aRxiv.* ***2019.*** [Link](https://arxiv.xilesou.top/pdf/1905.11600.pdf)

<a name="Reaction" />

### Based on Chemical Reaction

1. **A model to search for synthesizable molecules.** *NIPS.* ***2019.*** [Link](http://papers.nips.cc/paper/9007-a-model-to-search-for-synthesizable-molecules.pdf)
<a name="Interaction" />

## Interaction & Association Prediction
<a name="DTI" />


### Drug-Target Interaction
1. **Atomic convolutional networks for predicting protein-ligand binding affinity.** *aRxiv.* ***2017.*** [Link](https://arxiv.xilesou.top/pdf/1703.10603.pdf)

2. **PotentialNet for molecular property prediction.** *ACS CENTRAL SCI.* ***2018.*** [Link](https://pubs.acs.org/doi/abs/10.1021/acscentsci.8b00507)

4. **Interpretable drug target prediction using deep neural representation.** *IJCAI.* ***2018.*** [Link](https://astro.temple.edu/~tua87106/ijcai_dti.pdf)

3. **Compound-protein interaction prediction with end-to-end learning of neural networks for graphs and sequences.** *BIOINFORMATICS.* ***2019.*** [Link](https://academic.oup.com/bioinformatics/article/35/2/309/5050020)

4. **GraphDTA: Prediction of drug target binding affinity using graph neural networks.** *bioRxiv .* ***2019.*** [Link](https://www.biorxiv.org/content/10.1101/684662v1.full.pdf)

5. **Graph convolutional neural networks for predicting drug-target interactions.** *J CHEM INF MODEL.* ***2019.*** [Link](https://pubs.acs.org/doi/abs/10.1021/acs.jcim.9b00628)

6. **Predicting drug−target interaction using a novel graph neural network with 3d structure-embedded graph representation.** *J CHEM INF MODEL.* ***2019.*** [Link](https://pubs.acs.org/doi/abs/10.1021/acs.jcim.9b00387)

7. **AGL-Score: Algebraic graph learning score for protein−ligand binding scoring, ranking, docking, and screening.** *J CHEM INF MODEL.* ***2019.*** [Link](https://pubs.acs.org/doi/10.1021/acs.jcim.9b00334)

7. **Target identiﬁcation among known drugs by deep learning from heterogeneous networks.** *CHEM SCI.* ***2020.*** [Link](https://pubsrsc.xilesou.top/en/content/articlehtml/2020/sc/c9sc04336e)

<a name="DDI" />

### Drug-Drug Interaction
1. **Enhancing drug-drug interaction extraction from texts by molecular structure information.** *aRxiv.* ***2018.*** [Link](https://arxiv.xilesou.top/pdf/1805.05593.pdf)

2. **MR-GNN: Multi-resolution and dual graph neural network for predicting structured entity interactions.** *aRxiv.* ***2018.*** [Link](https://arxiv.xilesou.top/pdf/1905.09558.pdf)

3. **Drug similarity integration through attentive multi-view graph auto-encoders.** *aRxiv.* ***2018.*** [Link](https://arxiv.xilesou.top/pdf/1804.10850.pdf)

4. **Modeling polypharmacy side effects with graph convolutional networks.** *BIOINFORMATICS.* ***2018.*** [Link](https://academic.oup.com/bioinformatics/article/34/13/i457/5045770)

5. **GENN: Predicting correlated drug-drug interactions with graph energy neural networks.** *aRxiv.* ***2019.*** [Link](https://arxiv.xilesou.top/pdf/1910.02107.pdf)

6. **Tri-graph information propagation for polypharmacy side effect prediction.** *aRxiv.* ***2019.*** [Link](https://arxiv.xilesou.top/pdf/2001.10516.pdf)

<a name="PPI" />

### Protien-Protein Interaction
1. **Protein interface prediction using graph convolutional networks.** *NIPS.* ***2017.*** [Link](http://papers.nips.cc/paper/7231-protein-interface-prediction-using-graph-convolutional-networks.pdf)

<a name="SSI" />

### Solute-Solvent Interaction
1. **Chemically interpretable graph interaction network for prediction of pharmacokinetic properties of drug-like molecules.** *chemRxiv.* ***2020.*** [Link](https://chemrxiv.org/articles/Chemically_Interpretable_Graph_Interaction_Network_for_Prediction_of_Pharmacokinetic_Properties_of_Drug-like_Molecules/10282346)

<a name="RPI" />

### RNA-Protein Interaction
1. **Graph neural representational learning of RNA secondary structures for predicting RNA-protein interactions.** *bioRxiv.* ***2020.*** [Link](https://www.biorxiv.org/content/10.1101/2020.02.11.931030v1.full.pdf)

<a name="DlA" />

### Disease-lncRNA Association
1. **Graph convolutional network and convolutional neural network based method for predicting lncRNA-disease associations.** *Cells.* ***2019.*** [Link](http://papers.nips.cc/paper/7231-protein-interface-prediction-using-graph-convolutional-networks.pdf)
<a name="DmA" />

### Drug-miRNA Association
1. **Graph convolution for predicting associations between miRNA and drug resistance.** *BIOINFORMATICS.* ***2020.*** [Link](https://academic.oup.com/bioinformatics/article/36/3/851/5545546)
<a name="DGA" />

### Disease-Gene Association
1. **GCN-MF: Disease-gene association identification by graph convolutional networks and matrix factorization.** *KDD.* ***2019.*** [Link](https://dl.acm.org/doi/abs/10.1145/3292500.3330912)



