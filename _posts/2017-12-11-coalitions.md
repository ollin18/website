---
title: "Mexican Senate Coalitions"
categories:
  - Senate
tags:
  - dynamics senate mexico mexican coalition vote bill
last_modified_at: 2017-12-11T16:55:37-04:00
---
# Coalitions in the Mexican Senate
### In this post I'm going to talk about how the current mexican senators are colluded with each other in a complex network point of view.

A very hot topic in complex networks is community detection which is basically finding groups of nodes that are densely connected. I described this
as *hot* becase it's not a closed problem and new detection algorithms are released constantly, in a future post I will discuss this data set with my own algorithm but in this one we are going to talk about assortativity mixing.

Assortativity mixing is the tendency of vertices to connect to others that are alike it in some way, this
is also called homophily which is clearer to understand as it resembles the predilection of agents to connect to their equals.
To measure this we need some definitions first:

> **Community**:
>
> A group of nodes within a network that are tightly connected to eachother and weakly connected to the rest of the network.

This tells us that those nodes must be close
$\alpha$

> Let *c_in* be the number of links between pair of nodes that

When it comes to merely topological assortativity the most common one is by degree
correlation and it has been long studied. In general a network displays degree corre-
lations if the number of links between the high and low degree nodes is systematically
different from what is expected by chance when the high degree vertices will be
preferentially attached to other high degree vertices and the analogous way fot the low
degree we’ll say that the network presents assortativity mixing by degree but if the high
degree vertices tend to connect to low degree ones and vice versa we’ll have disassorta-
tive mixing by degree. Several social network present assortativity mixing.

In thist case we're going to use a different kind of assortativity, by properities. This means that
a pair of nodes tends to connect between them if they have certain similarity by a property or metadata.

Assortativity is important because it meas
