+++
title = "Semantics between PODs"
description = "developer rant"
tags = [
    "ML",
    "Data cleaning",
    "Mappings",
    "article-seed"
]
date = "2020-01-22"
categories = [
    "Article"
]
+++
 ## So many schemas

In the ML context, we put considerable effort into cleaning, transforming, and making sense of the data captured or exchanged between different systems. We prefer data with structure, and we want to be able to understand that structure. 

Some data comes from APIs using vocabularies or schemas that allow us to make sense of the data. But to a certain extent, we still need to spend considerable effort into understanding the models underneath. Each organization described their data differently, with different intended meanings forcing us to code the necessary mappings and transformations to accomplish our task.

I believe that Machine learning can help to make the data-processing tasks easier. We should be able to ask our systems for mappings or explanations of the data that suits our understanding. 

And also diminish our suffering and time spent in transforming data from one form into another.

 ### Emergent Semantics

We understand Emergent Semantics (ES) as a self-organizing process, in which agreements on the interpretation of data are established locally, following an incremental, bottom-up approach. The idea of emergent semantics is not new, and it refers to how multiple computer agents can reach acceptable degrees of interoperability through self-organizing processes.

The key lies in the interaction of the agents. We can identify the agents, and we can observe the data that they exchange. We have a context; we have access to the schemas used. All the data is there, so let's use it.

How about automatically building up structure, extracting facts, and building mappings directly from the data exchanged between systems?
How to do this without explicitly writing ontologies or schemas?

I believe that the current ML techniques might play a significant role here. 

Also, I think it's a subject of importance, mainly because society is increasingly towards decentralization, unveiling new challenges related to interoperability as environments become more diverse and heterogeneous.
