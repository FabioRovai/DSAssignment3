# Assignment 3

https://colab.research.google.com/drive/15ERdBmS_iGzXOaknpv5ZpCwhf2nIkDEt?usp=sharing


1. Find a dataset.

Used a dataset of genetic mutations.


2. Pick some variables and visualise as a 2D plot using PCA. Does there appear to be clear groups?

Yes.

3. Run K-Means and visualise the results. Experiment with some of the things below. It may be that you iterate between this and step 4 a few times, investigating how your clusters are and updating your parameters / dataset.

K means shows 5 distincts groups
 
4. Investigate the examples in your clusters, do they seem to have coherent differences? If so, can you characterise them? You can try the methods below.

If the clusters seem to have no patterns, can you think why this might be, considering your data, and its representation/features?

Nucleotide is present in all 5 clusters, where it had predominant value (except for cluster 4).
polyphen_sort and sift_sort are inverted (except for cluster 5).
Residue / Position is about a third of nucleotide.
