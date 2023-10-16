# Let's understand an author's papers over time!

## Introduction

This project aims to understand an author's papers over time. 
We will be using the [Semantic Scholar](https://www.semanticscholar.org/) API to curate author details and papers for all authors considered for this project.
More specifically we will look into a few authors from different stages of their career and see how their papers have evolved over time. 

## Data Curation

We scrape Semantic Scholar for the author's papers (use the author's Semantic Scholar ID to get the author details).

## Data Analysis

### Standard t-SNE

For early researchers, t-SNE does not seem to be able to capture any interesting trends about evolution of work and research topics.



## Conclusion

## Limitations

### Data Curation

Let's go over some of the limitations in the curation pipeline:

- We are limited by what Semantic Scholar has on the author. This could mean a lag behind a paper showing up online in some form to existing on S2, or we could also have papers erraneously attributed to the author. Jimmy needed merging from multiple Jimmy's.


- Some of the textual contents of papers have not been scraped by S2, primarily because of conference/journal gating. In these cases, we would miss both the abstract and the full text of the paper and as a result any artefacts that we would have extracted from the text.