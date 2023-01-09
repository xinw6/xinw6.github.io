---
title: "Visual descriptor extraction from patent figure captions: a case study of data efficiency between BiLSTM and transformer"
collection: publications
permalink: /publication/visual
excerpt: Technical drawings used for illustrating designs are ubiquitous in patent documents, especially design patents. Different from natural images, these drawings are usually made using black strokes with little color information, making it challenging for models trained on natural images to recognize objects. To facilitate indexing and searching, we propose an effective and efficient visual descriptor model that extracts object names and aspects from patent captions to annotate benchmark patent figure datasets. We compared two state-of-the-art named entity recognition (NER) models and found that with a limited number of annotated samples, the BiLSTM-CRF model outperforms the Transformer model by a significant margin, achieving an overall F1=96.60%. We further conducted a data efficiency study by varying the number of training samples and found that BiLSTM consistently beats the transformer model on our task. The proposed model is used to annotate a benchmark patent figure dataset.
date: 2022-06-20
venue: 'Proceedings of the 22nd ACM/IEEE Joint Conference on Digital Libraries'
paperurl: ''
citation: 'Xin Wei, Jian Wu, Kehinde Ajayi, Diane Oyen. &quot; Visual descriptor extraction from patent figure captions: a case study of data efficiency between BiLSTM and transformer.&quot; <i>Proceedings of the 22nd ACM/IEEE Joint Conference on Digital Libraries</i>, 2022.'
---
