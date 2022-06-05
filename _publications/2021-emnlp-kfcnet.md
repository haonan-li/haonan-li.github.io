---
title: "KFCNet: Knowledge Filtering and Contrastive Learning for Generative Commonsense Reasoning"
collection: publications
permalink: /publication/2021-emnlp-kfcnet
year: 2021
date: 2021-10-16
venue: 'Findings of the Association for Computational Linguistics (EMNLP)'
paperurl: 'https://aclanthology.org/2021.findings-emnlp.249/'
author: '<b>Haonan Li</b>, Yeyun Gong, Jian Jiao, Ruofei Zhang, Timothy Baldwin, Nan Duan'
---

```
@inproceedings{li-etal-2021-kfcnet-knowledge,
    title = "{KFCN}et: Knowledge Filtering and Contrastive Learning for Generative Commonsense Reasoning",
    author = "Li, Haonan  and
      Gong, Yeyun  and
      Jiao, Jian  and
      Zhang, Ruofei  and
      Baldwin, Timothy  and
      Duan, Nan",
    booktitle = "Findings of the Association for Computational Linguistics: EMNLP 2021",
    month = nov,
    year = "2021",
    address = "Punta Cana, Dominican Republic",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2021.findings-emnlp.249",
    doi = "10.18653/v1/2021.findings-emnlp.249",
    pages = "2918--2928",
}
```

## Abstract
Pre-trained language models have led to substantial gains over a broad range of natural language processing (NLP) tasks, but have been shown to have limitations for natural language generation tasks with high-quality requirements on the output, such as commonsense generation and ad keyword generation. In this work, we present a novel Knowledge Filtering and Contrastive learning Network (KFCNet) which references external knowledge and achieves better generation performance. Specifically, we propose a BERT-based filter model to remove low-quality candidates, and apply contrastive learning separately to each of the encoder and decoder, within a general encoder{--}decoder architecture. The encoder contrastive module helps to capture global target semantics during encoding, and the decoder contrastive module enhances the utility of retrieved prototypes while learning general features. Extensive experiments on the CommonGen benchmark show that our model outperforms the previous state of the art by a large margin: +6.6 points (42.5 vs. 35.9) for BLEU-4, +3.7 points (33.3 vs. 29.6) for SPICE, and +1.3 points (18.3 vs. 17.0) for CIDEr. We further verify the effectiveness of the proposed contrastive module on ad keyword generation, and show that our model has potential commercial value.
