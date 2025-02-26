# playervectors-ai
Clustering and predicting PlayerVectors using Machine Learning and Deep Learning algorithms.

## Player Vectors
Player Vectors summarise the playing styles of individual football players.

#### Install Player Vectors

I implemented the entire concept of Player Vectors.
You can install my **`Player Vector`** package via pip:

```bash
pip install playervectors
```

## Cluster Player Vectors using t-SNE

![image](res/playervector_cluster_tsne.png)


## Predicting Player positions using Player Vectors

Used Classification Models:

* K Nearest Neighbour Classifier
* Suppor-Vector Classifier
* Decission Tree Classifier
* Random Forest Classifier
* Gradient Boosted Decission Tree Classifier
* Multilayer Perceptron

### Accurcay scores
![image](res/clf_accuracy.png)

### Confusion matrices of classifiers
![image](res/clf_confusion_matrix.png)

## Citations

```bibtex
@article{ecmlpkdd2019,
  title     = {Player Vectors: Characterizing Soccer Players’
Playing Style from Match Event Streams},
  author    = {Tom Decroos, Jesse Davis},
  journal   = {ecmlpkdd2019},
  year      = {2019},
}
```