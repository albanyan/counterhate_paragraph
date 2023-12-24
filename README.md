# Finding Authentic Counterhate Arguments

This repository contains the corpus and code of the [EMNLP_23](https://2023.emnlp.org/) paper "Finding Authentic Counterhate Arguments: A Case Study with Public Figures". Authors: Abdullah Albanyan, Ahmed Hassan, and Eduardo Blanco.
<br />
<!--[[paper link](https://ojs.aaai.org/index.php/AAAI/article/view/21284)]
[[supplementary materials](/Docs/hate-twitter-supplemental.pdf)]-->

## Introduction
In this work, we propose a methodology that assures the authenticity of the argument and its specificity to the individual of interest. We show that finding arguments in online articles is an efficient alternative to counterhate generation approaches that may hallucinate unsupported arguments.

## Example

We target authentic counterhate arguments that address the specific hateful claims, as exemplified in the bottom two arguments in the following figure: 

<p align="center">
<img  src="Docs/figs/tweet1.png" width=70% height=70%>
</p>

Hateful tweet (top) and three replies with counterhate arguments. Previous work targets synthetic counterhate arguments that tend to be generic (first counterhate argument). In this paper, we find authentic counterhate arguments that address the hateful claims in the tweet at hand (2nd and 3rd counterhate arguments).


## Citation

```
@inproceedings{albanyan-etal-2023-finding,
    title = "Finding Authentic Counterhate Arguments: A Case Study with Public Figures",
    author = "Albanyan, Abdullah  and
      Hassan, Ahmed  and
      Blanco, Eduardo",
    editor = "Bouamor, Houda  and
      Pino, Juan  and
      Bali, Kalika",
    booktitle = "Proceedings of the 2023 Conference on Empirical Methods in Natural Language Processing",
    month = dec,
    year = "2023",
    address = "Singapore",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2023.emnlp-main.855",
    doi = "10.18653/v1/2023.emnlp-main.855",
    pages = "13862--13876",
    abstract = "We explore authentic counterhate arguments for online hateful content toward individuals. Previous efforts are limited to counterhate to fight against hateful content toward groups. Thus, we present a corpus of 54,816 hateful tweet-paragraph pairs, where the paragraphs are candidate counterhate arguments. The counterhate arguments are retrieved from 2,500 online articles from multiple sources. We propose a methodology that assures the authenticity of the counter argument and its specificity to the individual of interest. We show that finding arguments in online articles is an efficient alternative to counterhate generation approaches that may hallucinate unsupported arguments. We also present linguistic insights on the language used in counterhate arguments. Experimental results show promising results. It is more challenging, however, to identify counterhate arguments for hateful content toward individuals not included in the training set.",
}
```
