 # **Infinite Feature Selection: A Graph-based Feature Filtering Approach**
 **Giorgio Roffo, Simone Melzi, Member, IEEE, Umberto Castellani, Alessandro Vinciarelli, Member, IEEE and Marco Cristani, Member, IEEE**
 
 We propose a filtering feature selection framework that considers a subset of features as a path in a graph, where a node
 is a feature and an edge indicates pairwise (customizable) relations among features, dealing with relevance and redundancy principles.
 By two different interpretations (exploiting properties of power series of matrices and relying on Markov chains fundamentals) we can
 evaluate the values of paths (i.e., feature subsets) of arbitrary lengths, eventually go to infinite, from which we dub our framework
 Infinite Feature Selection (Inf-FS). Going to infinite allows to constrain the computational complexity of the selection process, and to
 rank the features in an elegant way, that is, considering the value of any path (subset) containing a particular feature. We also propose
 a simple unsupervised strategy to cut the ranking, so providing the subset of features to keep. In the experiments, we analyze diverse
 setups with heterogeneous features, for a total of 11 benchmarks, comparing against 18 widely-know yet effective comparative
 approaches. The results show that Inf-FS behaves better in almost any situation, that is, when the number of features to keep are fixed
 a priori, or when the decision of the subset cardinality is part of the process.

La propuesta se baso en ralizarlo en Google Colab trabajando con el dataset UCI Human Activity Recognition (HAR)
1. **Tipo:** Sensor (acelerómetro y giroscopio).
2. **Instancias:** 10,299.
3. **Características:** 561.
4. **Clases:** 6.
5. **Uso:** Util para probar técnicas como Inf-FS en señales temporales.
6. **Descarga:** https://archive.ics.uci.edu/ml/datasets/human+activity+recognition+using+smartphones
