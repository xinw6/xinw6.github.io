---
title: "Visual descriptor extraction from patent figure captions: a case study of data efficiency between BiLSTM and transformer"
collection: publications
permalink: /publication/visual
excerpt: Technical drawings used for illustrating designs are ubiquitous in patent documents, especially design patents. Different from natural
images, these drawings are usually made using black strokes with little color information, making it challenging for models trained on natural images to recognize objects. To facilitate indexing and searching, we propose an effective and efficient visual descriptor model that extracts object names and aspects from patent captions
to annotate benchmark patent figure datasets. We compared two state-of-the-art named entity recognition (NER) models and found that with a limited number of annotated samples, the BiLSTM-CRF model outperforms the Transformer model by a significant margin, achieving an overall F1=96.60%. We further conducted a data efficiency study by varying the number of training samples and found that BiLSTM consistently beats the transformer model on our task. The proposed model is used to annotate a benchmark patent figure dataset.
date: 2022-06-20
venue: 'Proceedings of the 22nd ACM/IEEE Joint Conference on Digital Libraries'
paperurl: ''
citation: 'Pengzhan Zhou, Xin Wei, Cong Wang, Yuanyuan Yang. &quot; Explore Truthful Incentives for Tasks with Heterogenous Levels of Difficulty in the Sharing Economy.&quot; <i>International Joint Conferences on Artificial Intelligence (IJCAI)</i>, 2019.'
---
Incentives are explored in the sharing economy to inspire users for better resource allocation. Previous works build a budget feasible incentive mechanism to learn users' cost distribution. However, they only consider a special case that all tasks are considered as the same. The general problem asks for finding a solution when the cost for different tasks varies. In this paper, we investigate this general problem by considering a system with k levels of difficulty. We present two incentivizing strategies for offline and online implementation, and formally derive the ratio of utility between them in different scenarios. We propose a regret minimizing mechanism to decide incentives by dynamically adjusting budget assignment and learning from users' cost distributions. Our experiment demonstrates utility improvement about 7 times and time saving of 54% to meet a utility objective compared to the previous works.

[Download paper here](https://www.ijcai.org/proceedings/2019/0094.pdf)

Pengzhan Zhou, Xin Wei, Cong Wang, Yuanyuan Yang. "Paper Explore Truthful Incentives for Tasks with Heterogenous Levels of Difficulty in the Sharing Economy." <i>International Joint Conferences on Artificial Intelligence (IJCAI)</i>. Macau, 2019.
