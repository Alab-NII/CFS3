# CFS3

The Communicative-Function-labeled Semantic Scholar Sentence Dataset (CFS3) is a distantly-labeled dataset that includes 100,016 sentences with 77 communicative-function labels.  
All sentences are derived from [S2ORC](https://github.com/allenai/s2orc).

If you find this useful, please cite [our work](https://aclanthology.org/2022.sdp-1.7/).

#### citation

```
@inproceedings{sugimoto-aizawa-2022-incorporating,
    title = "Incorporating the Rhetoric of Scientific Language into Sentence Embeddings using Phrase-guided Distant Supervision and Metric Learning",
    author = "Sugimoto, Kaito  and
      Aizawa, Akiko",
    booktitle = "Proceedings of the Third Workshop on Scholarly Document Processing",
    month = oct,
    year = "2022",
    address = "Gyeongju, Republic of Korea",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2022.sdp-1.7",
    pages = "54--68",
    abstract = "Communicative functions are an important rhetorical feature of scientific writing. Sentence embeddings that contain such features are highly valuable for the argumentative analysis of scientific documents, with applications in document alignment, recommendation, and academic writing assistance. Moreover, embeddings can provide a possible solution to the open-set problem, where models need to generalize to new communicative functions unseen at training time. However, existing sentence representation models are not suited for detecting functional similarity since they only consider lexical or semantic similarities. To remedy this, we propose a combined approach of distant supervision and metric learning to make a representation model more aware of the functional part of a sentence. We first leverage an existing academic phrase database to label sentences automatically with their functions. Then, we train an embedding model to capture similarities and dissimilarities from a rhetorical perspective. The experimental results demonstrate that the embeddings obtained from our model are more advantageous than existing models when retrieving functionally similar sentences. We also provide an extensive analysis of the performance differences between five metric learning objectives, revealing that traditional methods (e.g., softmax cross-entropy loss and triplet loss) outperform state-of-the-art techniques.",
}
```

---

Each label number corresponds to a total of 80 different functional classes included in one of the links below (accessed Nov. 2021).

- https://www.phrasebank.manchester.ac.uk/introducing-work/ (label: 01 ~ 17)
- https://www.phrasebank.manchester.ac.uk/referring-to-sources/ (label: 18 ~ 32)
- https://www.phrasebank.manchester.ac.uk/describing-methods/ (label: 33 ~ 46)
- https://www.phrasebank.manchester.ac.uk/reporting-results/ (label: 47 ~ 60)
- https://www.phrasebank.manchester.ac.uk/discussing-findings/ (label: 61 ~ 72)
- https://www.phrasebank.manchester.ac.uk/writing-conclusions/ (label: 73 ~ 80)

## Label Distribution

Labels `15`, `29`, and `39` are assigned to no sentence.

| label | CFS3 | CFS3_train | CFS3_valid |
|:--:|--:|--:|--:|
| 01 | 5212 | 4170 | 1042 |
| 02 | 520 | 416 | 104 |
| 03 | 334 | 267 | 67 |
| 04 | 5165 | 4132 | 1033 |
| 05 | 726 | 581 | 145 |
| 06 | 283 | 226 | 57 |
| 07 | 140 | 112 | 28 |
| 08 | 541 | 433 | 108 |
| 09 | 981 | 785 | 196 |
| 10 | 4101 | 3281 | 820 |
| 11 | 1735 | 1388 | 347 |
| 12 | 1339 | 1071 | 268 |
| 13 | 300 | 240 | 60 |
| 14 | 1102 | 882 | 220 |
| 15 | 0 | 0 | 0 |
| 16 | 142 | 114 | 28 |
| 17 | 493 | 394 | 99 |
| 18 | 73 | 58 | 15 |
| 19 | 134 | 107 | 27 |
| 20 | 172 | 138 | 34 |
| 21 | 211 | 169 | 42 |
| 22 | 10686 | 8549 | 2137 |
| 23 | 10 | 8 | 2 |
| 24 | 59 | 47 | 12 |
| 25 | 184 | 147 | 37 |
| 26 | 107 | 86 | 21 |
| 27 | 4 | 3 | 1 |
| 28 | 68 | 54 | 14 |
| 29 | 0 | 0 | 0 |
| 30 | 245 | 196 | 49 |
| 31 | 2 | 2 | 0 |
| 32 | 526 | 421 | 105 |
| 33 | 1694 | 1355 | 339 |
| 34 | 4394 | 3515 | 879 |
| 35 | 340 | 272 | 68 |
| 36 | 2950 | 2360 | 590 |
| 37 | 1774 | 1419 | 355 |
| 38 | 823 | 658 | 165 |
| 39 | 0 | 0 | 0 |
| 40 | 426 | 341 | 85 |
| 41 | 257 | 206 | 51 |
| 42 | 69 | 55 | 14 |
| 43 | 71 | 57 | 14 |
| 44 | 160 | 128 | 32 |
| 45 | 1988 | 1590 | 398 |
| 46 | 49 | 39 | 10 |
| 47 | 699 | 559 | 140 |
| 48 | 11873 | 9498 | 2375 |
| 49 | 2404 | 1923 | 481 |
| 50 | 1033 | 826 | 207 |
| 51 | 1642 | 1314 | 328 |
| 52 | 9 | 7 | 2 |
| 53 | 203 | 162 | 41 |
| 54 | 139 | 111 | 28 |
| 55 | 66 | 53 | 13 |
| 56 | 12 | 10 | 2 |
| 57 | 42 | 34 | 8 |
| 58 | 6 | 5 | 1 |
| 59 | 91 | 73 | 18 |
| 60 | 416 | 333 | 83 |
| 61 | 776 | 621 | 155 |
| 62 | 114 | 91 | 23 |
| 63 | 3096 | 2477 | 619 |
| 64 | 543 | 434 | 109 |
| 65 | 5463 | 4370 | 1093 |
| 66 | 982 | 786 | 196 |
| 67 | 3800 | 3040 | 760 |
| 68 | 1254 | 1003 | 251 |
| 69 | 746 | 597 | 149 |
| 70 | 121 | 97 | 24 |
| 71 | 23 | 18 | 5 |
| 72 | 628 | 502 | 126 |
| 73 | 3243 | 2594 | 649 |
| 74 | 447 | 358 | 89 |
| 75 | 1460 | 1168 | 292 |
| 76 | 2805 | 2244 | 561 |
| 77 | 2091 | 1673 | 418 |
| 78 | 169 | 135 | 34 |
| 79 | 2466 | 1973 | 493 |
| 80 | 564 | 451 | 113 |

## License

CC BY-NC 4.0
