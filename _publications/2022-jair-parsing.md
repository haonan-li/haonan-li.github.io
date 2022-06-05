---
title: "Neural character-level syntactic parsing for Chinese"
collection: publications
permalink: /publication/2022-jair-parsing
year: 2022
date: 2022-1-31
venue: 'Proceedings of the Thirty-Second AAAI Conference on Artificial Intelligence (AAAI)'
paperurl: 'https://dl.acm.org/doi/pdf/10.1613/jair.1.13052'
author: 'Zuchao Li, Junru Zhou, Hai Zhao, Zhisong Zhang, <b>Haonan Li</b>, Yuqi Ju'
---


```
@article{li2022neural,
  title={Neural Character-Level Syntactic Parsing for Chinese},
  author={Li, Zuchao and Zhou, Junru and Zhao, Hai and Zhang, Zhisong and Li, Haonan and Ju, Yuqi},
  journal={Journal of Artificial Intelligence Research},
  volume={73},
  pages={461--509},
  year={2022}
}
```

## Abstract
In this work, we explore character-level neural syntactic parsing for Chinese with two typical syntactic formalisms: the constituent formalism and a dependency formalism based on a newly released character-level dependency treebank. Prior works in Chinese parsing have struggled with whether to define words when modeling character interactions. We choose to integrate full character-level syntactic dependency relationships using neural rep- resentations from character embeddings and richer linguistic syntactic information from human-annotated character-level Parts-Of-Speech and dependency labels. This has the potential to better understand the deeper structure of Chinese sentences and provides a better structural formalism for avoiding unnecessary structural ambiguities. Specifically, we first compare two different character-level syntax annotation styles: constituency and dependency. Then, we discuss two key problems for character-level parsing: (1) how to combine constituent and dependency syntactic structure in full character-level trees and (2) how to convert from character-level to word-level for both constituent and dependency trees. In addition, we also explore several other key parsing aspects, including different character-level dependency annotations and joint learning of Parts-Of-Speech and syntac- tic parsing. Finally, we evaluate our models on the Chinese Penn Treebank (CTB) and our published Shanghai Jiao Tong University Chinese Character Dependency Treebank (SCDT). The results show the effectiveness of our model on both constituent and depen- dency parsing. We further provide empirical analysis and suggest several directions for future study.
