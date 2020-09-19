+++
title = "Interoperability on Information Systems"
description = "Description"
tags = [
    "interoperability",
    "glossary"
]
date = "2012-04-04"
categories = [
    "Vocab"
]
+++

## Interoperability on Information Systems

Within the IS context, we refer to *Interoperability* to the ability of two or more peers to interact by exchanging information to express and interpret data accurately enough to produce the expected results. 

The first step is to create explicit artifacts that enable data transformations or data mediation mappings between data sources and destinations to share information between distinct systems. 

The community should agree on these explicit artifacts; otherwise, they don't share meaning.

To reach acceptable interoperability levels is a significant concern to the IS field. Lots of efforts go into obtaining acceptable degrees of interoperability between systems. 

One interoperability level is the so-called *syntactic interoperability*, which refers to establishing the necessary symbols to exchange a representation without losing structure. 

Examples may go from the standardization of the ASCII code to the HTML markup language, sets of symbols used to build protocols intended for broad audiences.

If the syntax used by the sender is different than the one used by the receiver, then a translation or mapping mechanism can be applied. For example, one can use a library to translate from an RDF XML serialization into RDF JSON and vice-versa. If an accurate translation of syntaxes is possible, we say that systems can interoperate at the syntactic level.

Syntactical interoperability is a requirement to reach other levels of interoperability, such as *semantic interoperability*. Semantic interoperability refers to reducing gaps in interpretation between peers.

Peers can achieve this using shared reference models, such as schemas, vocabularies, or ontologies. However, having a reference model that contains all the representations of every concept conceivable is generally considered impossible; but we still can build up acceptable agreements for some context.
