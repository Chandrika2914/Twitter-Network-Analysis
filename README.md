# Twitter Network Analysis — Stanford Network Analysis Project
This project is developed completely in Python to analyze Twitter data from the Stanford Network Analysis Project (SNAP).
The main goal is to analyze and create Ego Networks — visualizing and understanding how users are connected and how information flows in a social network.

## Overview
The project explores a Twitter dataset to understand the connectivity and influence among users using key graph theory concepts such as:
- Degree Centrality
- Closeness Centrality
- Betweenness Centrality
    ### Ego Networks
        An Ego Network consists of:
        A focal node (ego node)
        The nodes directly connected to it (alters)
        And the connections among those alters (if any)
This type of analysis helps visualize and quantify how central or influential a user is within a network.

## Pipeline
- Download the Dataset: Obtain the Twitter dataset from the Stanford Network Analysis Project (SNAP)
- Load the Dataset:Use Python libraries such as pandas and networkx to load and preprocess the data.
- Compute Centrality Measures

    -   Degree Centrality: Measures the number of direct connections a node has.
    -   Closeness Centrality: Indicates how close a node is to all other nodes in the network.
    -   Betweenness Centrality: Shows how often a node appears on the shortest paths between other nodes.
- Build Ego Networks: Construct and visualize ego networks for selected nodes to study their local influence and structure.