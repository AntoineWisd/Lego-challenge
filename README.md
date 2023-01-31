# Lego-challenge - Presentation / Preliminary work

## Introduction:

In this presentation, we will describe our approach for detecting Sybil addresses on the Ethereum blockchain using autonomous Legos. These Legos are packaged algorithms that can be run individually in batch mode or combined into pipelines for closer to real-time execution. We will describe the different Legos that we have designed for detecting Sybil addresses, as well as how we have combined them into a global detection pipeline.

## Overall approach:

Our overall approach for detecting Sybil addresses involves using a combination of different methods to evaluate Ethereum addresses. These methods include analyzing the address's age, the number of transactions made, related addresses, transaction patterns, address centrality in the transaction network and cluster analysis.

## Legos:

A) Address age: This Lego takes in an Ethereum address and checks for how long it has been in use. It can have a configuration parameter for a minimum duration for the address to be considered valid.

B) Number of transactions: This Lego takes in an Ethereum address and checks how many transactions it has made. It can have a configuration parameter for a minimum number of transactions for the address to be considered valid.

C) Related addresses: This Lego takes in an Ethereum address and checks how many other addresses have had interactions with it. It can have a configuration parameter for a minimum number of addresses and a rule for these addresses (e.g. only outgoing transactions, or only addresses that themselves have had interactions with a certain number of other addresses).

D) Transaction patterns: This Lego takes in an Ethereum address and uses pattern recognition algorithms to detect suspicious patterns in the address's transactions.

E) Address centrality: This Lego takes in an Ethereum address and uses centrality methods to evaluate its centrality in the transaction network.

F) Cluster analysis: This Lego takes in an Ethereum address and uses cluster analysis techniques to identify groups of addresses that appear to be connected to each other.

## Detection pipeline:

We have combined these different Legos into a global detection pipeline using classifiers such as RandomForestClassifier, SVM, XGBoost, etc. We have also combined the results of multiple classifiers for improved performance.

## Conclusion:

This is our approach for detecting Sybil addresses on the Ethereum blockchain using autonomous Legos. We have described the different Legos that we have designed for evaluating Ethereum addresses, as well as how we have combined them into a global detection pipeline. We believe that this approach can be used to improve the security of blockchain-based systems.
