---
layout: post
title: What is an Enumerator?
date: 2025-12-13
description: And why is this blog titled so?
tags: TCS computability
categories: 
---

In theoretical computer science, an [enumerator](https://en.wikipedia.org/wiki/Enumerator_(computer_science)) is a type of [Turing machine](https://en.wikipedia.org/wiki/Turing_machine) that generates (or "enumerates") a list of strings. Unlike a standard Turing machine that takes an input and produces an output, an enumerator does not take any input; instead, it produces an infinite sequence of strings, one after another, on its output tape. This process continues indefinitely, and the strings generated can be thought of as being "enumerated" in a specific order. It turns out that while enumerators and Turing machines are seemingly different in their operations, they are equivalent in terms of the languages they can recognize. Specifically, a language is Turing-recognizable (or as some people call it, recursively enumerable) if and only if there exists an enumerator that can enumerate all the strings in that language.

This blog is titled "Enumerator" because, much like an enumerator Turing machine, I aim to generate and output a continuous stream of ideas, insights, and knowledge through my posts. Just as an enumerator systematically does computation to produce strings from a (Turing-recognizable) language, I intend to systematically explore various topics in CS/Math/ML/Stats/other fields, and output my ideas/thoughts on them for readers to consume.

Also, on a historical note, in the early 20th century, Hilbert sought to answer the [Entscheidungsproblem](https://en.wikipedia.org/wiki/Entscheidungsproblem) by asking whether there exists a mechanical procedure/Algorithm/Turing machine that can determine the truth or falsity of any mathematical statement, from the axioms. The motivation was that, if there indeed existed such a Turing machine, it could be used to *enumerate* all true mathematical statements. Unfortunately, the Entscheidungsproblem was later shown to be unsolvable independently by [Alonzo Church](https://en.wikipedia.org/wiki/Alonzo_Church) and [Alan Turing](https://en.wikipedia.org/wiki/Alan_Turing) in the 1930s, through the concepts of [lambda calculus](https://en.wikipedia.org/wiki/Lambda_calculus) and Turing machines, respectively. However, these foundational ideas formalized the notion of computation, marked the beginning of modern computer science, and laid the groundwork for the development of all computing systems and algorithms that we use today. 

My hope is that this blog can serve as a tiny step towards that impossible grand vision, by outputting a stream of true and interesting statements in the realm of TCS and related fields. While we may not be able to enumerate all true mathematical statements ([Gödel's incompleteness theorems](https://en.wikipedia.org/wiki/G%C3%B6del%27s_incompleteness_theorems)), we can certainly strive to explore and understand the vast landscape of knowledge that lies within the realm of computation and the span of our lives. What better way to do that than through a blog named "Enumerator"!

