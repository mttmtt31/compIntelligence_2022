---
title: Lab1 - Set Covering
author: Francesco Capuano (s295366), Matteo Matteotti (s294552)
date: today
---

# Lab1 - Set Covering
This repo contains the solution to the first laboratory of the 2022/2023 Computational Intelligence course called **Set Covering**. The problem specifications can be found [at this link](https://github.com/squillero/computational-intelligence/blob/master/2022-23/lab1_set-covering.ipynb)

## Authors
The contributors of this repo are:
* Francesco Capuano, s295366 
* Matteo Matteotti, s294552  

## Sources 
Part of the code was reproduced from what seen in class, especially from the solution to the [3x3 puzzle problem](https://github.com/squillero/computational-intelligence/blob/master/2022-23/8-puzzle.ipynb).

## Methodology
To solve the problem, we turned the unhashable class `MultiSet()` into a custom hashable class called `SuperSet()`, defined stemming from the dict subclass `Counter()`. 
This was coupled with a variable called `tuples_seen` which tracked the 'visited' notes.

## Results