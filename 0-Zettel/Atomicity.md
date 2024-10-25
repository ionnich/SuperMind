---
title: Atomicity
date: 2024-10-25 09:56:00
lastmod: 2024-10-25 10:08:03
categories:
  - Theory
tags: 
aliases: 
share: false
---

# Atomicity


This feels like a term I deeply care about when designing systems.

Atomic means a --something-- cannot be splittable into smaller pieces. To me this sounds like designing structs, classes, functions such that, when used in higher contexts, appear singular in function and absolutely either execute or fail. This is important because when systems get overly complex, it is invaluable to have absolute constructs to rely on. If your functions are atomic


> *Atomic in programming refers to an assembly language instruction ATOMIC...* 
> *n programming ATOMIC refers to a group of assembly instructions that form a single uninterruptable unit instruction*

> In programming, an atomic action is one that effectively happens all at once. An atomic action cannot stop in the middle: it either happens completely, or it doesn't happen at all. No side effects of an atomic action are visible until the action is complete.

