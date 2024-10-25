---
title: Untitled
date: 2024-10-16 15:51:00
lastmod: 2024-10-16 15:51:00
categories: 
tags: 
aliases: 
share: false 
---

# Rust Execution Engine

#### Grammar Construction

We use [[Pest]] to construct a grammar that describes primarily formulas and terms. Formulas are compound expressions nested between an equal sign and parentheses | commas | custom functions. Terms are [[Atomic]] cells 

### Some questions:
1. How should we use the [[Pest|pest]] file?
	1. Constructing a grammar
	