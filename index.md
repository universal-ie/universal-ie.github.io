---
title: Unified Structure Generation for Universal Information Extraction
---

## News
- [2022.04.27] **NEW!!!** [Submission website](https://aistudio.baidu.com/aistudio/competition/detail/161/0/submit-result) for UIE@CCKS2022 competition is open, welcome to submit your solutions!
- [2022.04.21] Our [code](https://github.com/universal-ie/UIE) are public released.
- [2022.04.12] Launch [universal information extraction competition](https://aistudio.baidu.com/aistudio/competition/detail/161/0/introduction) [@CCKS2022](http://sigkg.cn/ccks2022/?page_id=22).
- [2022.02.24] UIE accepted by ACL 2022, long paper.

## Unified Structure Generation for Universal Information Extraction
![UIE](/img/UIE.png "UIE")
Information extraction suffers from its varying targets, heterogeneous structures, and demand-specific schemas. In this paper, we propose a unified text-to-structure generation framework, namely UIE, which can universally model different IE tasks, adaptively generate targeted structures, and collaboratively learn general IE abilities from different knowledge sources. Specifically, UIE uniformly encodes different extraction structures via a structured extraction language, adaptively generates target extractions via a schema-based prompt mechanism – structural schema instructor, and captures the common IE abilities via a large-scale pretrained text-to-structure model. Experiments show that UIE achieved the state-of-the-art performance on 4 IE tasks, 13 datasets, and on all supervised, low-resource, and few-shot settings for a wide range of entity, relation, event and sentiment extraction tasks and their unification. These results verified the effectiveness, universality, and transferability of UIE.

You can find code at [Github](https://github.com/universal-ie/UIE) and the pre-trained models as following CAS Cloud Box/Google Drive links.

uie-en-base [[CAS Cloud Box]](https://pan.cstcloud.cn/s/w2hTaHYaRWw) [[Google Drive]](https://drive.google.com/file/d/12Dkh6KLDPvXrkQ1I-1xLqODQSYjkwnvs/view) [[Huggingface]](https://huggingface.co/luyaojie/uie-base-en)

uie-en-large [[CAS Cloud Box]](https://pan.cstcloud.cn/s/2vrXYBVTbk) [[Google Drive]](https://drive.google.com/file/d/15OFkWw8kJA1k2g_zehZ0pxcjTABY2iF1/view) [[Huggingface]](https://huggingface.co/luyaojie/uie-large-en)

## Publications
- **Unified Structure Generation for Universal Information Extraction**. Yaojie Lu, Qing Liu, Dai Dai, Xinyan Xiao, Hongyu Lin, Xianpei Han, Le Sun and Hua Wu. ACL 2022. [[link]](https://aclanthology.org/2022.acl-long.395/) [[arxiv]](https://arxiv.org/abs/2203.12277) [[Code in PyTorch]](https://github.com/universal-ie/UIE) [[Code in Paddle]](https://github.com/PaddlePaddle/PaddleNLP/tree/develop/examples/information_extraction/DuUIE)

## Competition
- **Universal Information Extraction @CCKS 2022** [[website]](https://aistudio.baidu.com/aistudio/competition/detail/161/0/introduction) [[Baseline in Paddle]](https://github.com/PaddlePaddle/PaddleNLP/tree/develop/examples/information_extraction/DuUIE)

## Other Implementations
- [PaddlePaddle] **UIE-Pointer: A pointer-based solution for universal information extraction** [[link](https://github.com/PaddlePaddle/PaddleNLP/tree/develop/model_zoo/uie)] \\
This is a pointer-based solution for universal information extraction implemented by Baidu and ISCAS.
This implementation is with the same intuition as UIE, but it replaces the T5-based generation model with an ERNIE-based pointer model and further fine-tunes on public available IE datasets.

-------------
*Last updated: Sep 23rd, 2022*

[![Day/Overall](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Funiversal-ie.github.io&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=hits&edge_flat=true)](https://hits.seeyoufarm.com)
