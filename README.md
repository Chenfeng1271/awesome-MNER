# <p align=center> Awesome Multimodal Named Entity Recognition 🎶📜</p>

<div align=center>

A collection of resources on multimodal named entity recognition.
 
</div>

## <span id="head-content"> *Content* </span>
* - [ ] [1. Description](#head1)
* - [ ] [2. Topic Order](#head2)
  * - [ ] [👑 Dataset](#head-dataset)
* - [ ] [3. Chronological Order](#head3)
  * - [ ] [Survey](#head-Survey)
  * - [ ] [2020](#head-2020)
  * - [ ] [2021](#head-2021)
  * - [ ] [2022](#head-2022)

* - [ ] [4. Courses](#head4)

* [*Contact Me*](#head5)

## <span id="head1"> *1.Description* </span>

>🐌 Markdown Format:
>
> * (Conference/Journal Year) **Title**, First Author et al. [[Paper](URL)] [[Code](URL)] [[Project](URL)] <br/>
> * (Conference/Journal Year) [💬Topic] **Title**, First Author et al. [[Paper](URL)] [[Code](URL)] [[Project](URL)]
>     * (Optional) ```🌱``` or ```📌 ```
>     * (Optional) 🚀 or 👑 or 📚

* ```🌱: Novel idea```
* ```📌: The first...```
* 🚀: State-of-the-Art
* 👑: Novel dataset/model
* 📚：Downstream Tasks 

## <span id="head2"> *2. Topic Order* </span>
* <span id="head-dataset"> **👑 Dataset**  </span>
    * (AAAI 2017) **Adaptive Co-attention Network for Named Entity Recognition in Tweets** [[paper](https://ojs.aaai.org/index.php/AAAI/article/view/11962)]
    * (ACL 2018) **Visual Attention Model for Name Tagging in Multimodal Social Media** [[paper](https://aclanthology.org/P18-1185.pdf)]

## <span id="head3"> *3. Chronological Order* </span>
* <span id="head-2020"> **2020**  </span>
    * (ACL 2020) **Improving Multimodal Named Entity Recognition via Entity Span Detection with Unified Multimodal Transformer** [[paper](https://aclanthology.org/2020.acl-main.306.pdf)]
    * (ACL 2020) **RIVA: A Pre-trained Tweet Multimodal Model Based on Text-image Relation for Multimodal NER** [[paper](https://aclanthology.org/2020.coling-main.168/)]

* <span id="head-2021"> **2021**  </span>

    * (AAAI 2021) **Multi-modal Graph Fusion for Named Entity Recognition with Targeted Visual Guidance** [[paper](https://ojs.aaai.org/index.php/AAAI/article/view/17687)]
    * (AAAI 2021) **RpBERT: A Text-image Relation Propagation-based BERT Model for Multimodal NER** [[paper](https://arxiv.org/abs/2102.02967)]  [[code](https://github.com/Multimodal-NER/RpBERT)]
    * (EMNLP 2021) **Can images help recognize entities? A study of the role of images for Multimodal NER** [[paper](https://arxiv.org/abs/2010.12712)] [[code](https://github.com/RiTUAL-UH/multimodal_NER)]

* <span id="head-2022"> **2022**  </span>

    * (CVPR 2022) **Flat Multi-modal Interaction Transformer for Named Entity Recognition** [[paper](https://arxiv.org/abs/2208.11039)]
        * 📌 1st interpolating FLAT with MNER
        * 🚀  SOTA on Twitter15 with Bert_base_uncased but code is unavailable
    * (NAACL Findings 2022) **Good Visual Guidance Makes A Better Extractor: Hierarchical Visual Prefix for Multimodal Entity and Relation Extraction** [[paper](https://aclanthology.org/2022.findings-naacl.121/)] [[code](https://github.com/zjunlp/HVPNeT)]
        * 📌 code using refined Twitter15 dataset
    * (WSDM 2022) **MAF: A General Matching and Alignment Framework for Multimodal Named Entity Recognition** [[paper](https://arxiv.org/abs/2010.05379)] [[code](https://github.com/xubodhu/MAF)]
    * (SIGIR 2022) **Hybrid Transformer with Multi-level Fusion for Multimodal Knowledge Graph Completion** [[paper](https://arxiv.org/abs/2205.02357)] [[paper](https://github.com/zjunlp/MKGformer)]
        * 📌 1st fully Transformer structure
        * 🚀 SOTA on Twitter17 using Bert_base_uncased but only implement on Twitter17 
    * (NAACL 2022) **ITA: Image-Text Alignments for Multi-Modal Named Entity Recognition** [[paper](https://arxiv.org/abs/2112.06482)] [[code](https://github.com/Alibaba-NLP/KB-NER)]
        * 📌  Roberta_large as backbone provides powerful improvements
        * 🌱  Using OCR ect without directly using images
    * (MM 2022) **Query Prior Matters: A MRC Framework for Multimodal Named Entity Recognition** [[paper](https://dl.acm.org/doi/abs/10.1145/3503161.3548427)]
        * 🌱  1st MRC based framework for MNER
    * (SIGIR 2022) **Learning from Different text-image Pairs: A Relation-enhanced Graph Convolutional Network for Multimodal NER** [[paper](https://dl.acm.org/doi/abs/10.1145/3503161.3548228)]
        * 📌 Trustworthy performance by reimplementation
    * (ICME 2022) **CAT-MNER: Multimodal Named Entity Recognition with Knowledge-Refined Cross-Modal Attention** [[paper](https://ieeexplore.ieee.org/document/9859972)]
        * 🚀  SOTA on Twitter15 and Twitter17 with Roberta_large
        * 📌  Require 8 V100 GPU
    * (DSAA 2022) **PromptMNER: Prompt-Based Entity-Related Visual Clue Extraction and Integration for Multimodal Named Entity Recognition** [[paper](https://link.springer.com/chapter/10.1007/978-3-031-00129-1_24)]
        * 🚀  SOTA on Twitter15 and Twitter17 with Roberta_large
        * 📌  Require 8 V100 GPU
        * 🌱 Prompt-based
        
    * （arxiv 2022） **Multi-Granularity Cross-Modality Representation Learning for Named Entity Recognition on Social Media** [[paper](https://arxiv.org/abs/2210.14163)] [[code](https://github.com/LiuPeiP-CS/IIE4MNER)]

  
