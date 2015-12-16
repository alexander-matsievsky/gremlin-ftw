# gremlin-ftw
Gremlin For The Web!

## Intro

## Goals

This booklet pursuits two main goals:

1. to give the readers a deep, "close to the metal" understanding of the Gremlin stack of technologies, with a special attention to the theory;

2. to provide a viable practical implementation of Gremlin for the web browsers.

## Approach


## Table of contents

This booklet consists of three chapters, each building upon the results and insights of the previous one.

1. `jQuemlin`. Or *Why bother with this new unfamiliar thing?*
    
    In its time, `jQuery` created a mini-revolution in the web browser. A decade has passed since 2006, and nowadays it is a lingua franca of DOM traversal and manipulation familiar to most web developers. The library popularized declarative APIs for these operations.
    In this chapter we'll exploit this familiarity. Let's treat the DOM as a graph database! An ad-hoc graph computing library `jQuemlin` will be implemented to provide the solutions to common problems in a side-by-side comparison with `jQuery`. We'll exceed the expectations by elegantly solving problems `jQuery` can not. (Notice: incapability here means the lack of straightforward and idiomatic solution due to its assumptions and limitations and, more so, its DOM foundation.)
    We'll also try to extract the essential machinery of our library and lay the ground for its formalization.
     
2. `IndexedGDB`, `Gremlin` & `Grenda`. Or *How to get my hands on it? How to wrap my brain around it??*

    In contrast to the immediate practicality of the previous chapter, this one might seem a little detached and theoretical.
    We'll build three software artifacts.
    
    `IndexedGDB` -- graph database built atop of `IndexedDB`; 
    `Gremlin` -- implementation of Gremlin graph computing framework for the web browsers; 
    `Grenda` -- dataviz graphical component supporting graph rendering to `HTML`, `SVG` and `Canvas` of the web browsers. 

3. `circuitry`. Or *What exciting new prospects does it bring?*
