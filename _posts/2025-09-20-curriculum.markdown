---
layout: post
title:  "Curriculum Learning"
date:   2025-09-20 21:03:03 -0700
categories: [blog]
---
## Polydactyly

How many genetic mutations are necessary to cause the growth of an extra finger?  This question was posed to me by a colleague (and member of our discussion group), Ben Kovitz.  Considering the complexity of a finger, it becomes somewhat startling that such a change could ever occur.  But it can occur spontaneously, and only requires a single nucleotide change.

How is this possible?  The answer, of course, is that our genetic code is highly modular and hierarchical.  Functional units, such as the code necessary to create a digit, are reused often.  This code is built to make use of smaller units that are reused multiple times within a single finger, and so forth.

This feature is both a result of the evolutionary process and a key to its success.  In a complex, adaptive system, the earliest functional units are reused and adapted whenever possible.  This is just a simple corollary of evolutionary pressure, but the implications are enormous.  Imagine that each cell in the human body had its own unique genetic code.  Not only would the genome be incredibly unwieldy, but mutations would lead to unnoticeable changes in the organism.  The compression, through hierarchy and reuse, of our genome is what allows for meaningful adaptation.

## Foundation models as complex adaptive systems

The typical approach to LLM pretraining forces a model to "understand" the structure (i.e., predict the next words) of a large corpus of unrelated and unfiltered text.  Through this process, these models learn enough of human reasoning patterns to mimic their application in a wide variety of settings, to surprising success.  We've seen hints that models have far more parameters then necessary, and struggle to successfully transfer reasoning patterns from one domain to another, related one.  This process of generalization or abstraction is an innate skill of humans, and one of our greatest strengths.

How can we instill these characteristics in LLMs, ideally improving their capabilities and stabilities as collaborators?  It turns out that we already have an approach for doing this with humans.  

## Education
As a former teacher, there's a clear difference in outcomes when course material is packaged in a structured, hierarchical fashion, rather than as a series of unconnected facts.  Can we force this same process with LLMs?

One reasonable first pass seems to combine a curriculum learning approach that leverages existing human developmental curricula.  This approach could be combined with various techniques for slowly expanding the breadth of model parameters.  Modules that converge early on simple tasks could be semi-frozen, and then available for reuse as the model grows and engages in more sophisticated challenges.  A detailed technical sketch of one possible method will be the topic of a later post.


