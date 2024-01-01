# [DocLLM: A layout-aware generative language model for multimodal document understanding](https://github.com/dswang2011/DocLLM/blob/main/DocLLLM_preprint.pdf)
*(arxiv version is under review)*

Dongsheng Wang, Natraj Raman, Mathieu Sibue, Zhiqiang Ma, Petr Babkin, Simerjot Kaur, Yulong Pei, Armineh Nourbakhsh, Xiaomo Liu


## Introduction 

Enterprise documents such as forms, invoices, receipts, reports, contracts, and other similar records, often carry rich semantics at the intersection of textual and spatial modalities. The visual cues offered by their complex layouts play a crucial role in comprehending these documents effectively. In this paper, we present \docllm, a lightweight extension to traditional large language models (LLMs) for reasoning over visual documents, taking into account both textual semantics and spatial layout. Our model differs from existing multimodal LLMs by avoiding expensive image encoders and focuses exclusively on bounding box information to incorporate the spatial layout structure. Specifically, the cross-alignment between text and spatial modalities is captured by decomposing the attention mechanism in classical transformers to a set of disentangled matrices. Furthermore, we devise a pre-training objective that learns to infill text segments. This approach allows us to address irregular layouts and heterogeneous content frequently encountered in visual documents. The pre-trained model is fine-tuned using a large-scale instruction dataset, covering four core document intelligence tasks. We demonstrate that our solution outperforms SotA LLMs on 14 out of 16 datasets across all tasks, and generalizes well to 4 out of 5 previously unseen datasets.

<p align="center">
  <img align="middle" width="800" src="overview.png"/>
</p>

## Acknowledgments
This paper was prepared for information purposes by the [Artificial Intelligence Research group of JPMorgan Chase \& Co and its affiliates (“JP Morgan”)](https://www.jpmorgan.com/technology/artificial-intelligence), and is not a product of the Research Department of JP Morgan.  J.P. Morgan makes no representation and warranty whatsoever and disclaims all liability for the completeness, accuracy or reliability of the information contained herein. This document is not intended as investment research or investment advice, or a recommendation, offer or solicitation for the purchase or sale of any security, financial instrument, financial product or service, or to be used in any way for evaluating the merits of participating in any transaction, and shall not constitute a solicitation under any jurisdiction or to any person, if such solicitation under such jurisdiction or to such person would be unlawful. © 2023 JP Morgan Chase \& Co. All rights reserved.

## BibTeX citation:
@misc{2023,
      title={DocLLM: A Layout-Aware Generative Language Model for Multimodal Document Understanding}, 
      author={Dongsheng Wang, Natraj Raman, Mathieu Sibue, Zhiqiang Ma, Petr Babkin, Simerjot Kaur, Yulong Pei, Armineh Nourbakhsh, Xiaomo Liu},
      year={2023},
      Month={December},
      institute={JPMorgan AI Research}
}
