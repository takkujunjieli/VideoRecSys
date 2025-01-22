# VideoRecSys
This is a recommendation system built for an online streaming platform.

## Configuration
* Java 8
* Scala 2.11
* Python 3.6+
* TensorFlow 2.0+

## Start
Run "RecSysServer" file and check locally with `http://localhost:6010/`

## Data
An open source database contains over 2 million movie collections and relevant user data[MovieLens](https://grouplens.org/datasets/movielens/)

## Architecture Design
![alt text](https://github.com/wzhe06/SparrowRecSys/raw/master/docs/sparrowrecsysarch.png)

## Model involved
* Word2vec (Item2vec)
* DeepWalk (Random Walk based Graph Embedding)
* Embedding MLP
* Wide&Deep
* Nerual CF
* Two Towers
* DeepFM
* DIN(Deep Interest Network)

