# Community Structure in Networks

In complex networks, a network is said to have community structure if the nodes of the
network can be grouped into groups of nodes with dense connections internally, and sparser
connections between groups.

This program implements an algorithm for detecting community structures in a network.

The program receives two command-line arguments. The 1st is an input filename, and the 2nd is an
output filename. The input of your program is a network (a graph), and the output is a list
of groups (the division).

The input and output files are both binary files consisting only of integers.

Input File:

    The first value represents the number of nodes in the network.
    The second value represents the number of edges of the first node, i.e., k1. It is followed by
    the k1 indices of its neighbors, in increasing order.
    The next value is k2, followed by the k2 indices of the neighbors of the second node, then k3
    and its k3 neighbors, and so on until the last node.

Output File:

    The first value represents the number of groups in the division.
    The second value represents the number of nodes in the first group, followed by the indices
    of the nodes in the group, in increasing order.
    The next value is the number of nodes in the second group, followed by the indices of the
    nodes in group, then the number of nodes and indices of nodes in the third group, and so
    on until the last group.
    
    
full details in sp_project.pdf
