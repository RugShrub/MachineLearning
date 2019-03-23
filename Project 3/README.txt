Code was ran using Weka.
Databases at : https://github.com/RugShrub/MachineLearning


Weka>Explore>preprocess>Open File choose website.arff or wine.arff


K-means: Cluster>Clusterer>weka>clusterers>SimpleKMeans, change the numClusters

EM: Cluster>Clusterer>weka>clusterers>EM, change the numClusters

For Dimensionality Reducer: preprocess>filter>unspervised>attribute and select function

For Information Gain: preprocess>filter>supervised>attribute>attributeSelection
evaluator: infoGainedAttributeEvaluator
search: ranker


For ICA Kurtosis calculation: python kurtosis_calculator <dataset>.arff
