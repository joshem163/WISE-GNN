# WISE-GNN
![FrameWork-1](https://github.com/joshem163/WISE-GNN/assets/133717791/89269231-6105-4529-bdb1-9cbc59695eb3)


# Overview

Wise-GNN is an innovative machine learning model for Graph representation learning that utilizes a  novel approach named "Wise Embeddings", effectively integrating local topological information and positional information in the doamin feature spaces,to improve the performance of existing GNN models. This repository contains the code for the Wise-GNN paper. 
# Requirements
Wise-GNN depends on the followings:
1. Pytorch
2. Pyflagser
3. networkx 3.1
4. ogb 1.3.6
5. sklearn 1.3.0
6. torch_geometric 2.4.0
7. natsort 8.4.0
   
The code is implemented in python 3.11.4. 
# Datasets
In this study,  ten benchmark datasets have been utilized, comprising three homophilic, two OGBN, and five heterophilic datasets. The link to access these datasets is provided below:

[CORA](https://linqs-data.soe.ucsc.edu/public/datasets/cora/cora.zip) 

[CITESEER](https://linqs-data.soe.ucsc.edu/public/datasets/citeseer-doc-classification/citeseer-doc-classification.zip)

[PUBMED](https://linqs-data.soe.ucsc.edu/public/datasets/pubmed-diabetes/pubmed-diabetes.zip)

[WebKB](https://github.com/bingzhewei/geom-gcn/tree/master/new_data)

[Wiki](https://github.com/benedekrozemberczki/MUSAE/tree/master/input)

# Runing the  Experiments
1. Execute all cell of notebook to run the experiment:
2. The code has the ability to download and preprocess the dataset by itself. The dataset will be stored in the same directory.
3. Make sure to maintain the sequential order of execution as specified in the code.
4. Follow the prompts or instructions provided by the code to proceed with the experiment. 


