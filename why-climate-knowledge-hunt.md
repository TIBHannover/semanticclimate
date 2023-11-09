---
title: Why are we running this hackathon?
date: 2023-04-18
summary: Steps in processing a climate chapter
author: Peter Murray-Rust
tags:
  - climate-knowledge-hunt
  - hackathon
---
The UN's IPCC AR6 report is probably the most important global document of this century. It gives
* the scientific basis of climate change
* its current and predicted effects
* how we can reduce the  harmful ones (mitigation)
* how we can adapt to them (adaptation)
As citizens of this planet we must learn as mush as we can and take responsible action.
## Interpreting the report
The report is about 10,000 pages, very dense, and written for specialists and politicians to read, *and
agree*. It's the basis of government policies and every word has been carefully drafted. Think of it as a
contract between nations.
It is primarily written for policy makers, not general citizens, and their language is jargon-rich (
because they must be precise) and full of statements based on evidence. This makes casual reading hard.
We believe it's essential to make this report accessible to citizens, and we believe our approach can
be used by committed high-school students (think Greta Thunberg!). We are not climate scientists so we are
not adding material, but rather providing reading and comprehension aids. We make the reports semantic.
# semantic climate reports
The reports (ca 10,000 pages) are published in English and formatted in PDF. This makes it almost impossible to re-use (edit, translate hyperlink, etc.). Blind readers or non-anglophones (except in a few translations) will find it almost impossible. So we are making this semantic - machine-interpretable. Semantic means that machines can understand the structure of  the documents and can add meaning to parts. (This is not AI - we'll come to that later.)
We therefore transform the PDF into HTML, deduce the structure (chapters, tables, captions, etc.) and give the (sub)sections identifiers.
We can then add human meaning using ontologies (dictionaries), especially as jargon- and abbreviation busters. (e.g. "GHG", "AR6/WGII",
"nitrous oxide", "palaeoarctic zone").
We can also split the reports into smaller chunks and filter those with a common theme (e.g. "oceans", "SouthAsia", "cities"). To do this
we provide Open Source tools which anyone can use and also modify.
Note that the semantic process is completely transparent and understandable. Unlike AI/ML (which is often a black box), semantics can be designed
and manipulated at all levels of granularity.
# Why not use AI/LLMs, etc.?
There's no doubt that LLMs will transform how we manage information and transform it into communal knowledge and decision making. But it's at an early stage and errors are frequent. (ChatGPT told PMR that he had studied at the University of Chicago!). LLMs are not transparent - where did it get that info? - and so they aren't reliable. Accuracy and traceability are *essential* if our semantic version is going to be valuable.
Also the LLMs are run by closed, opaque companies. They almost certainly build in inequity (e.g. Anglophone, GlobalNorth), and without governance their motivation can't be trusted. So we believe that it will be better to build public Open LLMs, and semantic climate can be a useful input into that. (We can discuss at the hackathon!)