# Small-LexNormViHSD
The Small-LexNormViHSD dataset is used for lexical normalization on Vietnamese social media text.

This dataset contains 2,181 annotated comments from the [ViHSD dataset](https://github.com/sonlam1102/vihsd), which is used for hate speech detection on social network sites.
Label: input (non-standard sentence), output(standard sentence)

To understand more about the dataset, please read this paper: [Automatic Textual Normalization for Hate Speech Detection](https://link.springer.com/chapter/10.1007/978-3-031-64779-6_1)

Please cite the following paper if you use this dataset: 

```
@InProceedings{10.1007/978-3-031-64779-6_1,
author="Nguyen, Anh Thi-Hoang
and Nguyen, Dung Ha
and Nguyen, Nguyet Thi
and Ho, Khanh Thanh-Duy
and Nguyen, Kiet Van",
editor="Abraham, Ajith
and Bajaj, Anu
and Hanne, Thomas
and Siarry, Patrick",
title="Automatic Textual Normalization for Hate Speech Detection",
booktitle="Intelligent Systems Design and Applications",
year="2024",
publisher="Springer Nature Switzerland",
address="Cham",
pages="1--12",
abstract="Social media data is a valuable resource for research, yet it contains a wide range of non-standard words (NSW). These irregularities hinder the effective operation of NLP tools. Current state-of-the-art methods for the Vietnamese language address this issue as a problem of lexical normalization, involving the creation of manual rules or the implementation of multi-staged deep learning frameworks, which necessitate extensive efforts to craft intricate rules. In contrast, our approach is straightforward, employing solely a sequence-to-sequence (Seq2Seq) model. In this research, we provide a dataset for textual normalization, comprising 2,181 human-annotated comments with an inter-annotator agreement of 0.9014. By leveraging the Seq2Seq model for textual normalization, our results reveal that the accuracy achieved falls slightly short of 70{\%}. Nevertheless, textual normalization enhances the accuracy of the Hate Speech Detection (HSD) task by approximately 2{\%}, demonstrating its potential to improve the performance of complex NLP tasks. Our dataset is accessible for research purposes (Github: https://github.com/AnhHoang0529/Small-LexNormViHSD).",
isbn="978-3-031-64779-6"
}
```
