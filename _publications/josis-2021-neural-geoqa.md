---
title: "Neural Factoid Geospatial Question Answering"
collection: publications
permalink: /publication/josis-2021-neural-geoqa
date: 2021-12-24
venue: 'Journal of Spatial Information Science'
paperurl: 'https://josis.org/index.php/josis/article/view/159'
---

```
@article{li2021neural,
  title={Neural factoid geospatial question answering},
  author={Li, Haonan and Hamzei, Ehsan and Majic, Ivan and Hua, Hua and Renz, Jochen and Tomko, Martin and Vasardani, Maria and Winter, Stephan and Baldwin, Timothy},
  journal={Journal of Spatial Information Science},
  number={23},
  pages={65--90},
  year={2021}
}
```

## Abstract
Existing question answering systems struggle to answer factoid questions when geospatial information is involved. This is because most systems cannot accurately detect the geospatial semantic elements from the natural language questions, or capture the semantic relationships between those elements. In this paper, we propose a geospatial semantic encoding schema and a semantic graph representation which captures the semantic relations and dependencies in geospatial questions. We demonstrate that our proposed graph representation approach aids in the translation from natural language to a formal, executable expression in a query language. To decrease the need for people to provide explanatory information as part of their question and make the translation fully automatic, we treat the semantic encoding of the question as a sequential tagging task, and the graph generation of the query as a semantic dependency parsing task. We apply neural network approaches to automatically encode the geospatial questions into spatial semantic graph representations. Compared with current template-based approaches, our method generalises to a broader range of questions, including those with complex syntax and semantics. Our proposed approach achieves better results on GeoData201 than existing methods.
