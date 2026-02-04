---
title: "Iterator Pattern"
excerpt: "Traverse elements of a collection without exposing its underlying representation."
collection: reading
type: chapter
date: 2024-12-05
book: design-pattern
layout: chapter
chapter_number: 8
tags:
  - design-patterns
  - behavioral-patterns
---

Iterator is a behavioral design pattern that lets you traverse elements of a collection without exposing its underlying representation (list, stack, tree, etc.).

## Scenario

Collections are one of the most used data types in programming. Nonetheless, a collection is just a container for a group of objects.

![collection traversal](https://hackmd.io/_uploads/HyqkXZAmke.png)

Adding more and more traversal algorithms to the collection gradually blurs its primary responsibility, which is efficient data storage.

![iterator](https://hackmd.io/_uploads/B18X7-C71e.png)

without iterator pattern:

A position:
- plan1: next is B
- plan2: next is C

with iterator pattern:
- plan1: A->B->C->...
- plan2: A->C->...

## Structure

![structure](https://hackmd.io/_uploads/r1l6Q-AmJl.png)

## Case Study

https://refactoring.guru/design-patterns/iterator/cpp/example
