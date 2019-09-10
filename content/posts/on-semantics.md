+++
title = "On Semantics"
description = "Some thoughts about semantics"
tags = [
    "interoperability",
    "article-seed"
]
date = "2019-02-02"
categories = [
    "Article"
]
+++

## On Semantics

I'm a software engineer and is not uncommon for me to talk with colleagues about semantics.

We discuss semantics while clarifying a specification, or being precise about a new language or specific notation, also while writing a paper or a proposal. In my field, people commonly to argue that semantics will enable machines to make better use of the Web, and even -from time to time- some writers actively promote the use of data _with_ semantics instead of without.

When I hear those things, I tend to ask myself: It is correct to talk of data _with_ semantics? What is semantics after all?

Without expecting to define what semantics is, I'll try to write here some thoughts about the subject.

# Some history

We commonly describe Semantics as the study of meaning.

The word _Semantics_ derives from the following ancient Greek words:

* σημαντικός \(semantikos\), which relates to _meaning_.
* σημαίνω \(semaino\), which relates to signify, to indicate.
* σῆμα \(sema\), which refers to sign, mark or token.

To build up an idea about what _semantics_ means, it is important to distinguish at least between these three concepts: semantikos, semaino and sema.

# The triangle of meaning

According to the semiotic tradition, there is a fundamental distinction between symbols and the things to which those symbols are associated. For example, we can say that the word _salt shaker_ refers to an object that may contain salt. We know that we can use this object to stir salt, and we can distinguish it from the word since the word itself cannot be used to put salt on our food.

![](/rdfsemioticsusdyojo.gif)

The triangle of meaning \(also called the triangle of reference\) is a tool commonly used to study how symbols are related to the objects they represent. It classically concerns a triadic structure that comprises the symbol \(the expression or representation of an idea\), a conceptualization \(how someone abstracts it\) and a referent \(the thing or concept that people refer to\).

This triangle provides us with a clear insight into how representations, conceptualizations, and referents can be separated. In the broad sense, when we talk about representation, we refer to any symbol or group of symbols materialized in a medium, such as a written or spoken word, a drawing, corporal movements and so on. When we build up a representation, we intend to evoke in others and ourselves a conceptualization about a specific referent.

The notion of representation has been explored extensively through history, especially in the arts and philosophy. It is said that representation is something capable of bringing something to present again or to be recalled. A representation starts when a person decides that A is the representation of B and others accept that this relation holds. Ideally, a representation has properties or features that allow others to grasp an idea about what is represented, being always the representation only a picture or shadow of what will be recalled. The representation can look just like the described element or be an abstraction of it, an expression capable of evoking in our minds, elements previously perceived through our experience. Usually, the _meaning_ of one representation is established by social conventions that we use to figure out what to do when we perceive and recognize such representation.

To illustrate this, let's imagine that we have two persons, Alice and Bob, and a salt shaker in front of them. Alice can point to the salt shaker and make a statement about it, for instance, ask "can you lend me the salt shaker please?" to which Bob lends the salt shaker to Alice. We may point several implicit considerations that would turn this quotidian and straightforward act, into something interesting.

First, the notion of _representation_ of the salt shaker. In our example, the representation or symbol "salt shake" is uttered, perceived and interpreted by Bob, to be recognized as the object in front of him. This salt shaker could have been symbolized by other means, for example pointing to it with a finger or the word "that." The salt shaker lending operation only happened after the utterance of Alice is interpreted by Bob recalling some previous conceptualization in his mind, for example, his mental image of a salt shaker, probably different to the one reminded by Alice. Both, the perception of Alice and Bob constitute images of the salt shaker, not the salt shaker itself.

Secondly, Alice and Bob have their ideas about what a salt shaker is. The conceptualizations in their minds are evoked autonomously, and they will depend on the previous personal experiences and interactions that Alice and Bob had with the world, in the sum to their constitution \(i.e., biological, emotional\). Although these conceptualizations are independent and different, Alice and Bob intuitively may have a _compatible_ idea about what a "salt shaker" could be, probably an idea or _social convention_ that they learned previously through interactions with others. Along these conventions, Alice and Bob might also share thoughts about the laws of nature that govern the salt shaker, laws that can't necessarily be controlled by Alice or Bob, but can be described and agreed upon with the help of logic. For instance, it is possible for them to declare that if Alice puts the salt shaker on her pocket, Bob won't be able to put it in his pocket at the same time. In our example, we could say those implicit agreements based on _logic_ were used to materialize the act of lending the salt shaker.

Lastly, we have the _referent_, or to what we refer. A referent is something that various persons can conceptualize in their minds, while cannot be declared that the evoked conceptualizations will be the same for all of them. A referent is something that we can represent in multiple ways, none of them definitive.

# On coordinating symbols

The act of evoking conceptualizations in others is central in the act of expression and communication. Agents will try to find and select the symbols that evoke in the most precise way possible, suitable conceptualizations in others. In the case of humans, this process cannot be fully automatized, since humans interpret and recognize elements based on their own experiences which cannot be directly accessed or modified by other humans or machines.

Humans use _dialogue_ to align their communication systems with other peers naturally. An exchange that happens through a medium such as speech, gestures, writing a letter, and an online forum and so on. In this way, they collaboratively build new meanings of symbols, negotiate the word meanings and establish useful conventions about their shared world. They incrementally try to solve the gaps in their linguistic and representational systems, as well as expanding them.

People intuitively or consciously try to persist these conventions in time, expressing them through artifacts to be exchanged. These artifacts may go from word glossaries to exact mathematical models. In the field of Information Systems \(IS\), the representations are persisted digitally to be read by a machine. Conventions of our world are then commonly expressed using categories, classes, relations, individual entities, etc., and anything that is useful to reason, organize or to be manipulated by our machines.

We map these computer-based representations to programs which can replicate certain behaviors, just in the same way we align musical notes to the metallic pins of a cylinder, to reproduce sound in musical boxes. We arrange symbols in a program or automatically derive symbols through rules conveyed and understood by humans.

The process to establish and negotiate symbols is difficult to centralize, and at least for humans, there is no central control capable of determining which symbols should be used by every person. Although people can perform coordinated efforts to build up artifacts that reflect and communicate conventions about some shared world, we cannot do this process automatically. However, we can profit from systems \(i.e., artificial agents\) that help us to facilitate our agreement processes.

# The Uniform Resource Locator

In very general terms, we want Information Systems \(IS\) to count with the means of \(1\) evoking acceptable conceptualizations in humans and \(2\) symbols that trigger correct behaviors in each component of the IS.

This problem is naturally complicated because interpretations from person to person differ and also machines cannot interpret things as a human does. Despite these difficulties, many of the advances in IT allow us to improve the way we materialize and store representations, and how we identify \(or point to\) to multiple referents.

The most fundamental mechanism to point referents is the URL, a universal point to which we can attach representations. By exposing URLs, people can exchange different representations to be consumed by people, while keeping a ubiquitous symbol to be interpreted unambiguously by machines.

This mechanism is so powerful, that allows us, only by composing URLs, to build up new tailored representations and more impressively set up hyperlinks to explore what we call the Web.

# The Semantic Web duality

Approximately ten years after inventing the Web, Tim Berners Lee coined the term Semantic Web to refer to a web of data to be processed by machines, one in which much of the _meaning_ is machine-readable.

But can _meaning_ be machine-readable? Can computers conceptualize symbols in a way we do?

My personal opinion is that computers cannot. For me, they are just tools, only one materialization of human abstraction. Two computers might trigger similar behavior when processing a symbol, but the meaning of those symbols has more to do with humans and semantics.

Individually of my view, there is no problem with that. If these machines are instead sentient entities, aliens or any  species capable of writing interpreting symbols like a human, it is still desirable  to diminish the gap between the intended and evoked interpretations, so we can communicate.

With the advent of the Internet, new challenges arise, having computers able of processing representations ubiquitously referenced by URLs. We face new possibilities in the context of human communication which are not yet fully understood. On the other hand, this is a problem humans  face for millenia. People continually diminish this gap by evolving their spoken grammar, writing capabilities, artistic depictions or any other medium.

I think that one of the tasks of the ones who study semantics or preservation of meaning is to figure out better ways to diminish the gap between evoked and the intended interpretations, for machines, but more importantly, for human agents their ultimate users.

![What a computer was](/what-a-computer-was.png)

# On Agreements

But how distinct peers come into agreements? We can understand the process of reaching agreements as a natural process where humans try to diminish their interpretation gaps using language and exchanging representations.

These agreements can only happen when peers express features that are recognizable by others, using different syntax and languages to reach descriptions precise enough to support future dialogues and interactions.

If we want IS to aid us into reach those agreements effectively, we need to support the exchange of multiple description mechanisms, in the context of the Semantic Web, at least natural, controlled and/or formal languages.

