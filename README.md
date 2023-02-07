# Improving-Temporal-Graph-Network-Messaging

## Research Abstract
Graph Representation Learning can be used to encode a graph structure to better accomplish tasks such as link prediction and node classification. In dynamic networks, the networks change over time, and so this requires additional adaptation. In Rossi et al.’s Temporal Graph Network algorithm (2020), each node has memory to store edge and node changes that affect it as the network evolves. In this work, improvements to the message function are explored, particularly to share messages to a node's neighbourhood so as to take into account neighbourhood changes when making predictions. The neighbourhood sample types considered are uniform, highest degree, and most recent. The adapted Temporal Graph Network algorithm is then tested on the bipartite dynamic network Wikipedia and unipartite dynamic network Social Evolution for link prediction. Results for the proposed variants show very small inconsistent improvements for both networks with comparable runtime to the original Temporal Graph Network algorithm. The number of neighbours selected did not seem to affect the variant’s performance, but the best neighbourhood sample varied according to the network, perhaps reflecting their very different structure. Future work will consider additional dynamic network data with similar structure to Wikipedia and Social Evolution respectively to explore whether the neighbourhood sample pattern persists. As well, further variants would be tested, considering different choices for the embedding method, the number of neighbourhood nodes to be sampled, and which neighbourhood to consider.

This research project was presented at multiple conferences, notably the 2022 Annual Meeting of the Institute for Operations Research and the Management Sciences. I also won 1st place in the Poster Competition of Western University's Inspiring Diversity in STEM Conference in Spring 2022. The winning project had their abstracts published in the Conference Abstract Issue of the Undergraduate Research in Natural and Clinical Science and Technology (URNCST) Journal. It can be viewed at the following link: https://doi.org/10.26685/urncst.386.

Note the code will soon be shared to this pubic repository.

## Research Poster
![Poster](https://github.com/celestejasmine/Improving-Temporal-Graph-Network-Messaging/blob/main/TGN%20Research%20Poster%20Image.png)
