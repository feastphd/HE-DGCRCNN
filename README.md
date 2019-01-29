# HE-DGCRCNN

Functions of each file:

 - Preprocess dataset RCV1 to get each class ID, words ID and coresponding embeddings: rcv1_unzip.py, rcv1_processer.py
 - Compute elastic distance (classes' similarity): make_edgelist.py, make_sim.py
 - Represent each sample (passage) by using GCNs and reorder neighbors to extract long distance information: make_data.py
 - Skip noise samples, generate relevant labels and weights according to classes' similarity: make_labels.py
 - Train and test models: code2.py 
 

# License

These codes can be used for research purposes only.

If you use these codes for research purposes, you should cite the aforementioned papers in any resulting publication and appropriately credit it.
