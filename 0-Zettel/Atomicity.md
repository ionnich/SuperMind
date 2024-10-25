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

Atomic means a --something-- cannot be splittable into smaller pieces. To me this sounds like designing structs, classes, functions such that, when used in higher contexts, appear singular in function and absolutely either execute or fail.


> *Atomic in programming refers to an assembly language instruction ATOMIC...* 
> *n programming ATOMIC refers to a group of assembly instructions that form a single uninterruptable unit instruction*

