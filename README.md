# On the Use of Early Fusion Operators on Heterogeneous Graph Neural Networks for One-Class Learning

- Marcos Paulo Silva Gôlo (ICMC/USP) | marcosgolo@usp.br
- Marcelo Isaias de Moraes Junior (ICMC/USP) | marcelo.junior@usp.br
- Rudinei Goularte (UFMS) | rudinei@icmc.usp.br
- Ricardo Marcacini (ICMC/USP) | ricardo.marcacini@icmc.usp.br

# Citing:

If you use any part of this code or research in your research, please cite it using the following BibTex entry
```latex
@inproceedings{ref:Golo2023,
  title={On the Use of Early Fusion Operators on Heterogeneous Graph Neural Networks for One-Class Learning},
  author={G{\^o}lo, Marcos and Moraes Junior, Marcelo and Goularte, Rudinei and Marcacini, Ricardo},
  booktitle={Proceedings of the Brazilian Symposium on Multimedia and the Web},
  address = {Ribeirão Preto, São Paulo, Brazil},
  year={2023},
  publisher = {ACM}
}
```

# Abstract
Multimodal data fusion generates robust and unified representations considering supplementary and complementary information from different modalities, such as audio, image, and text. Different strategies for data fusion have been explored for decades, from simple concatenation-based strategies of the modalities' features to the use of vector fusion operators (sum, average, subtraction, multiplication, etc.) between feature vectors in latent spaces of each modality. However, existing studies do not investigate multimodal fusion operators for heterogeneous graphs, which are powerful representations for modeling real-world data through a powerful structure that considers the different relations between different node types. Those representations are suited for important multimedia-related tasks, such as classification, recommendation, summarization, web sensing, and content-based retrieval. This paper presents a Graph Neural Network (GNN) method for heterogeneous graphs that explores different types of early fusion operators to deal with multiple modalities. Moreover, we evaluated the proposal's performance with different early fusion operators considering one-class learning, a popular learning approach for real-world applications. A statistical analysis of the experimental results shows that early fusion operators improve the f1-Score when considering GNNs from heterogeneous graphs. We highlight the subtraction, multiplication, and minimum operators outperforming the other operators. Thus, we argue that our early-fusion operators' proposal in heterogeneous graph neural networks leads to improved performance and is also a competitive alternative to the well-often-used concatenation technique or costly hand-based approaches of combining different modalities.

# Datasets

- **Fake News** : https://github.com/GoloMarcos/FKTC.git

- **Recommender Systems** : https://github.com/GoloMarcos/One-Class-Recommendation-GNNLinkPrediciton.git

- **Music** : : https://github.com/AngeloMendes/Unsupervised-Heterogeneous-GraphNeural-Network-for-Hit-Song-Prediction-through-One-Class-Learning.git

- **Event** : https://github.com/joaopedromattos/GNEE


| Datasets | Nodes | Edges | Nodes with initial features 
| :---: | :---: | :---: | :---: |
| Fake News | 10348 | 318411 | 2064 |
| Rec. Sys. | 8774 | 30471 | 2397 | 
| Music | 2125 | 5243 | 1529 | 
| Event | 579 | 803 | 96 | 

# Proposal
![Proposal](/images/pipeline.png)

# Results
![Results](/images/results.png)

# TSNE on FCN
![TSNE](/images/tsne.png)
