---
title: "UniMelb at SemEval-2019 Task 12: Multi-model combination for toponym resolution"
collection: publications
permalink: /publication/2019-semeval-toponym
year: 2019
date: 2019-06-06
venue: 'Proceedings of the 13th International Workshop on Semantic Evaluation (SemEval)'
paperurl: 'https://aclanthology.org/S19-2231.pdf'
author: '<b>Haonan Li</b>, Minghan Wang, Maria Vasardani, Martin Tomko, Timothy Baldwin'
---

```
@inproceedings{li2019unimelb,
  title={UniMelb at SemEval-2019 Task 12: Multi-model combination for toponym resolution},
  author={Li, Haonan and Wang, Minghan and Baldwin, Timothy and Tomko, Martin and Vasardani, Maria},
  booktitle={Proceedings of the 13th International Workshop on Semantic Evaluation},
  pages={1313--1318},
  year={2019}
}
```

## Abstract
This paper describes our submission to
SemEval-2019 Task 12 on toponym resolution in scientific papers. We train separate NER models for toponym detection over text extracted from tables vs. text from the body of the paper, and train another auxiliary model to eliminate mis-detected toponyms. For toponym disambiguation, we use an SVM classifier with hand-engineered features. Our best model achieved a strict micro-F1 score of 80.92% and overlap micro-F1 score of 86.88% in the toponym detection subtask, ranking 2nd out of 8 teams on F1 score. For toponym disambiguation and end-to-end resolution, we officially ranked 2nd and 3rd, respectively.
