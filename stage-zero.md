**The Curse of Dimensionality: A Haunting Challenge for Cancer Research**

Author (@slack): Leticia Villadangos (@leticia)



 

The term "Curse of Dimensionality" refers to the numerous difficulties and complexities that come up while organizing and interpreting data in high-dimensional spaces (Coelho _et al._, 2023). Within the area of cancer research, this problem may difficult the inference of cancer classification models, encouraging the search for solutions.

 

**The Peculiarity of Cancer Gene Expression Data**

Genetic changes cause normal human cells to gradually change into malignant derivatives, a process known as carcinogenesis. After deoxyribonucleic acid (DNA) damage is induced, normal cells change their metabolism becoming cancerous transformed cells. After this point, proliferation is uncontrolled until forming a tumor mass. Cancerous cells may invade other adjacent or distant tissues through the new vessels formed to grow and form a new secondary tumor (Guamán-Ortiz, 2019).

![Diagram of cancer development](https://github.com/lvillad/hbinternship/blob/main/Imagen1.png?raw=true)

**Figure 1.** Schematic representation of cancer development (Guamán-Ortiz, 2019).

Certain genes that are expressed differently in various tumor types can be found using gene expression microarrays, which have been shown to be useful for classifying various cancer types. However, gene expression data sets are complex and often include thousands of attributes (genes) and a small number of examples (patients), which makes the creation of cancer classification models difficult. Additionally, there is a substantial component of noise in these samples, resulting from numerous sources of variation affecting expression measurements (Mramor _et al._, 2005).

 

**Conquering the Curse of Dimensionality in Gene Expression Cancer Diagnosis**

To overcome the curse of dimensionality, the prevailing modelling approaches include gene filtering and gene subset selection (Mramor _et al._, 2005). For instance, in Khan et al.'s work, genes with low expression values were disregarded throughout the data set to categorize four types of children malignancies. Subsequently, 3750 feed-forward neural networks were trained on different gene subsets found using principal component analysis (PCA), a dimensionality reduction method (Armstrong _et al._, 2022).

The resulting networks were then examined for the most informative genes, yielding a subset of 96 genes whose expression clearly distinguished between different cancer types when multidimensional scaling was applied (Khan _et al._, 2001).

More recent approaches to overcome the curse of dimensionality include more aspects to take care of such as gene-gene interactions (Chattopadhyay y Lu, 2019). Nonetheless, gene expression data sets of different tumor types have been proven to be very useful in modern medicine and may probably continue to be so.

 

**Conclusion**

Creating cancer classification models can include challenges that may hinder their clinical application. However, multiple methods are being developed to overcome this issue, an encouraging fact that may impact the realm of oncology.

 

**References**

Armstrong, G., Rahman, G., Martino, C., McDonald, D., Gonzalez, A., Mishne, G. y Knight, R. (2022). Applications and Comparison of Dimensionality Reduction Methods for Microbiome Data_. Frontiers in Bioinformatics_, 2: 821861. doi: 10.3389/fbinf.2022.821861.

Chattopadhyay, A. y Lu, T. (2019). Gene-gene interaction: the curse of dimensionality_. Annals of Translational Medicine_, 7(24): 813. doi: 10.21037/atm.2019.12.87.

Coelho, D., Madureira, A., Pereira, I. y Gonçalves, R. (2023). A Review on Dimensionality Reduction for Machine Learning. Abraham, A., Bajaj, A., Gandhi, N., Madureira, A.M. y Kahraman, C., eds. , pp. 287–296.

Guamán-Ortiz, L.M. (2019). From Mutagenesis to Metastasis: A General Description of Cancer Development.

Khan, J., Wei, J.S., Ringnér, M., Saal, L.H., Ladanyi, M., Westermann, F., Berthold, F., Schwab, M., Antonescu, C.R., Peterson, C. y Meltzer, P.S. (2001). Classification and diagnostic prediction of cancers using gene expression profiling and artificial neural networks_. Nature Medicine_, 7(6): 673–679. doi: 10.1038/89044.

Mramor, M., Leban, G., Demšar, J. y Zupan, B. (2005). Conquering the Curse of Dimensionality in Gene Expression Cancer Diagnosis: Tough Problem, Simple Models. Miksch, S., Hunter, J. y Keravnou, E.T., eds. , pp. 514–523.

<!--StartFragment--> <!--EndFragment-->
