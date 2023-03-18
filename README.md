# Awesome-Colorful Large Language Model [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of Large Language Model ➕ Vision/Speech/Robotic.

**CONTENTS**

- [VISION](#vision)
  - [Image Language Model](#image-language-model)
    - [Reading List](#reading-list)
  - [Video Language Model](#video-language-model)
    - [Reading List](#reading-list-1)
    - [Pretraining Tasks](#pretraining-tasks)
    - [Datasets](#datasets)
  - [Tutorials](#tutorials)
  - [Other Curated Lists](#other-curated-lists)
- [SPEECH](#speech)
  - [Other Curated Lists](#other-curated-lists-1)
- [ROBOTIC](#robotic)
  - [Other Curated Lists](#other-curated-lists-2)
- [Related](#related)

## VISION

### Image Language Model

#### Reading List

| Paper                                                                                                  | Base Language Model      | Code                                                               | Publication | Preprint                                    | Affiliation |
| ------------------------------------------------------------------------------------------------------ | ------------------------ | ------------------------------------------------------------------ | ----------- | ------------------------------------------- | ----------- |
| ViperGPT: Visual Inference via Python Execution for Reasoning                                          | Codex                    | [ViperGPT](https://github.com/cvlab-columbia/viper)                   |             | [2303.08128](https://arxiv.org/abs/2303.08128) | Columbia    |
| ChatGPT Asks, BLIP-2 Answers: Automatic Questioning Towards Enriched Visual Descriptions               | ChatGPT, Flan-T5 (BLIP2) | [ChatCaptioner](https://github.com/Vision-CAIR/ChatCaptioner)         |             | [2303.06594](https://arxiv.org/abs/2303.06594) | KAUST       |
| Visual ChatGPT: Talking, Drawing and Editing with Visual Foundation Models                             | ChatGPT                  | [Visual ChatGPT](https://github.com/microsoft/visual-chatgpt)         |             | [2303.04671](https://arxiv.org/abs/2303.04671) | Microsoft   |
| PaLM-E: An Embodied Multimodal Language Model                                                          | PaLM                     |                                                                    |             | [2303.03378](https://arxiv.org/abs/2303.03378) | Google      |
| Language Is Not All You Need: Aligning Perception with Language Models                                 | Magneto                  | [KOSMOS-1](https://github.com/microsoft/unilm)                        |             | [2302.14045](https://arxiv.org/abs/2302.14045) | Microsoft   |
| BLIP-2: Bootstrapping Language-Image Pre-training with Frozen Image Encoders and Large Language Models | Flan-T5                  | [BLIP2](https://github.com/salesforce/LAVIS/tree/main/projects/blip2) |             | [2301.12597](https://arxiv.org/abs/2301.12597) | Salesforce  |
| Language Models are General-Purpose Interfaces                                                         | DeepNorm                 | [METALM](https://github.com/microsoft/unilm)                          |             | [2206.06336](https://arxiv.org/abs/2206.06336) | Microsoft   |
| Flamingo: a Visual Language Model for Few-Shot Learning                                                | Chinchilla               | [Flamingo](https://github.com/lucidrains/flamingo-pytorch)            | NIPS 2022   | [2204.14198](https://arxiv.org/abs/2204.14198) | DeepMind    |
| Learning Transferable Visual Models From Natural Language Supervision                                  | Bert                     | [CLIP](https://github.com/openai/CLIP)                                | ICML 2021   | [2103.00020](https://arxiv.org/abs/2103.00020) | OpenAI      |

### Video Language Model

#### Reading List

| Paper                                                                                                                    | Base Language Model | Code                                                                                                     | Publication         | Preprint                                    | Affiliation |
| ------------------------------------------------------------------------------------------------------------------------ | ------------------- | -------------------------------------------------------------------------------------------------------- | ------------------- | ------------------------------------------- | ----------- |
| Vid2Seq: Large-Scale Pretraining of a Visual Language Model for Dense Video Captioning                                   | T5                  | [Vid2Seq](https://github.com/google-research/scenic/tree/main/scenic/projects/vid2seq)                      |                     | [2302.14115](https://arxiv.org/abs/2302.14115) | Google      |
| HiTeA: Hierarchical Temporal-Aware Video-Language Pre-training                                                           | Bert                |                                                                                                          |                     | [2212.14546](https://arxiv.org/abs/2212.14546) | Alibaba     |
| VindLU: A Recipe for Effective Video-and-Language Pretraining                                                            | Bert                | [VindLU](https://github.com/klauscc/VindLU)                                                                 |                     | [2212.05051](https://arxiv.org/abs/2212.05051) | UNC         |
| SMAUG: Sparse Masked Autoencoder for Efficient Video-Language Pre-training                                               | Bert                |                                                                                                          |                     | [2211.11446](https://arxiv.org/abs/2211.11446) | UW          |
| CLOP: Video-and-Language Pre-Training with Knowledge Regularizations                                                     | Roberta             |                                                                                                          | MM 2022             | [2211.03314](https://arxiv.org/abs/2211.03314) | Baidu       |
| OmniVL: One Foundation Model for Image-Language and Video-Language Tasks                                                 | Bert                |                                                                                                          | NIPS 2022           | [2209.07526](https://arxiv.org/abs/2209.07526) | Microsoft   |
| Clover: Towards A Unified Video-Language Alignment and Fusion Model                                                      | Bert                | [Clover](https://github.com/LeeYN-43/Clover)                                                                |                     | [2207.07885](https://arxiv.org/abs/2207.07885) | Bytedance   |
| LAVENDER: Unifying Video-Language Understanding as Masked Language Modeling                                              | Bert-like           | [LAVENDER](https://github.com/microsoft/LAVENDER)                                                           | CVPR 2023           | [2206.07160](https://arxiv.org/abs/2206.07160) | Microsoft   |
| Revealing Single Frame Bias for Video-and-Language Learning                                                              | Bert                | [Singularity](https://github.com/jayleicn/singularity)                                                      |                     | [2206.03428](https://arxiv.org/abs/2206.03428) | UNC         |
| Flamingo: a Visual Language Model for Few-Shot Learning                                                                  | Chinchilla          | [Flamingo](https://github.com/lucidrains/flamingo-pytorch)                                                  | NIPS 2022           | [2204.14198](https://arxiv.org/abs/2204.14198) | DeepMind    |
| All in One: Exploring Unified Video-Language Pre-training                                                                | Bert-like           | [All-In-One](https://github.com/showlab/all-in-one)                                                         | CVPR 2023           | [2203.07303](https://arxiv.org/abs/2203.07303) | NUS         |
| End-to-end Generative Pretraining for Multimodal Video Captioning                                                        | Bert+GPT2           |                                                                                                          | CVPR 2022           | [2201.08264](https://arxiv.org/abs/2201.08264) | Google      |
| Align and Prompt: Video-and-Language Pre-training with Entity Prompts                                                    | Bert-like           | [ALPRO](https://github.com/salesforce/ALPRO)                                                                | CVPR 2022           | [2112.09583](https://arxiv.org/abs/2112.09583) | Salesforce  |
| VIOLET : End-to-End Video-Language Transformers with Masked Visual-token Modeling <space> [V2](https://arxiv.org/pdf/2209.01540.pdf) | Bert                | [VIOLET](https://github.com/tsujuifu/pytorch_violet)                                                        |                     | [2111.12681](https://arxiv.org/abs/2111.12681) | Microsoft   |
| VideoCLIP: Contrastive Pre-training for Zero-shot Video-Text Understanding                                               | Bert                | [VideoCLIP](https://github.com/facebookresearch/fairseq/tree/main/examples/MMPT)                            | EMNLP 2021          | [2109.14084](https://arxiv.org/abs/2109.14084) | Facebook    |
| MERLOT: Multimodal Neural Script Knowledge Models <space> [V2](https://arxiv.org/abs/2201.02639)                                     | Roberta             | [MERLOT](https://github.com/rowanz/merlot)                                                                  | NIPS 2021           | [2106.02636](https://arxiv.org/abs/2106.02636) | AI2         |
| VLM: Task-agnostic Video-Language Model Pre-training for Video Understanding                                             | Bert                | [VLP](https://github.com/facebookresearch/fairseq/blob/main/examples/MMPT/README.md)                        | ACL Findings 2021   | [2105.09996](https://arxiv.org/abs/2105.09996) | Facebook    |
| VATT: Transformers for Multimodal Self-Supervised Learning from Raw Video, Audio and Text                                | Bert-like           |                                                                                                          | NIPS 2021           | [2104.11178](https://arxiv.org/abs/2104.11178) | Google      |
| CLIP4Clip: An Empirical Study of CLIP for End to End Video Clip Retrieval                                                | Bert-like           | [CLIP4Clip](https://github.com/ArrowLuo/CLIP4Clip)                                                          | Neurocomputing 2022 | [2104.08860](https://arxiv.org/abs/2104.08860) | Microsoft   |
| Frozen in Time: A Joint Video and Image Encoder for End-to-End Retrieval                                                 | Bert                | [Frozen](https://github.com/m-bain/frozen-in-time)                                                          | ICCV 2021           | [2104.00650](https://arxiv.org/abs/2104.00650) | Oxford      |
| Less is More: CLIPBERT for Video-and-Language Learning via Sparse Sampling                                               | Bert                | [ClipBert](https://github.com/jayleicn/ClipBERT)                                                            | CVPR 2021           | [2102.06183](https://arxiv.org/abs/2102.06183) | Microsoft   |
| ActBERT: Learning Global-Local Video-Text Representations                                                                | Bert                | [ActBert](https://github.com/PaddlePaddle/PaddleVideo/blob/develop/docs/en/model_zoo/multimodal/actbert.md) | CVPR 2020           | [2011.07231](https://arxiv.org/abs/2011.07231) | Baidu       |
| Video Understanding as Machine Translation                                                                               | T5                  |                                                                                                          |                     | [2006.07203](https://arxiv.org/abs/2006.07203) | Facebook    |
| HERO: Hierarchical Encoder for Video+Language Omni-representation Pre-training                                           | Bert                | [HERO](https://github.com/linjieli222/HERO)                                                                 | EMNLP 2020          | [2005.00200](https://arxiv.org/abs/2005.00200) | Microsoft   |
| UniVL: A Unified Video and Language Pre-Training Model for Multimodal Understanding and Generation                       | Bert                | [UniVL](https://github.com/microsoft/UniVL)                                                                 |                     | [2002.06353](https://arxiv.org/abs/2002.06353) | Microsoft   |
| Learning Video Representations using Contrastive Bidirectional Transformer                                               | Bert                |                                                                                                          |                     | [1906.05743](https://arxiv.org/abs/1906.05743) | Google      |
| VideoBERT: A Joint Model for Video and Language Representation Learning                                                  | Bert                | [VideoBert (non-official)](https://github.com/ammesatyajit/VideoBERT)                                       | ICCV 2019           | [1904.01766](https://arxiv.org/abs/1904.01766) | Google      |

#### Pretraining Tasks

<details><summary>Commmonly Used Pretraining Tasks</summary>

- Masked Language Modeling (MLM)
- Causal Language Modeling (LM)
- Masked Vision Modeling (MLM)
  - Vision = Frame
  - Vision = Patch
  - VIsion = Object
- Video Language Matching (VLM)
- Video Language Contrastive (VLC)

</details>

#### Datasets

<details><summary>Commmonly Used Video Corpus for Pretraining</summary>

| Paper                                                                                        | Video Clips | Duration | Sentences | Domain      | Download Link                                              |
| -------------------------------------------------------------------------------------------- | ----------- | -------- | --------- | ----------- | ---------------------------------------------------------- |
| Frozen in Time: A Joint Video and Image Encoder for End-to-End Retrieval                     | 2.5M        | 18s      | 2.5M      | open        | [WebVid-2M](https://github.com/m-bain/webvid)                 |
| Howto100m: Learning a text-video embedding by watching hundred million narrated video clips  | 136M        | 4s       | 136M      | instruction | [HowTo100M](https://www.di.ens.fr/willow/research/howto100m/) |
| Merlot: Multimodal neural script knowledge models. Advances in Neural Information Processing | 6M          | -20m     | ~720M     | open        | [YT-Temporal-180M](https://rowanzellers.com/merlot/)          |

</details>

<details><summary>Commmonly Used Downsteam Tasks</summary>

| **Task**          | **Paper**                                                                                                         | **Download Link**                                                                                                     | **Publication** |
| ----------------------- | ----------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------- | --------------------- |
| **Retrieval**     | **Collecting Highly Parallel Data for Paraphrase Evaluation**                                                     | [MSVD](https://www.cs.utexas.edu/users/ml/clamp/videoDescription/)                                                             | **ACL 2011**    |
| **Retrieval**     | **A Dataset for Movie Description**                                                                               | [LSMDC](https://sites.google.com/site/describingmovies/download)                                                               | **CVPR 2015**   |
| **Retrieval**     | **MSR-VTT: A Large Video Description Dataset for Bridging Video and Language**                                    | [MSR-VTT](https://www.robots.ox.ac.uk/~maxbain/frozen-in-time/data/MSRVTT.zip)                                                 | **CVPR 2016**   |
| **Retrieval**     | **Localizing Moments in Video with Natural Language**                                                             | [DiDeMo](https://github.com/LisaAnne/LocalizingMoments)                                                                        | **ICCV 2017**   |
| **Retrieval**     | **Dense-Captioning Events in Videos**                                                                             | [ActivityNet Caption](https://cs.stanford.edu/people/ranjaykrishna/densevid/)                                                  | **ICCV 2017**   |
| **Retrieval**     | **Towards Automatic Learning of Procedures from Web Instructional Videos**                                        | [YouCook2](http://youcook2.eecs.umich.edu/download)                                                                            | **AAAI 2018**   |
| **OE QA**         | **TGIF-QA: Toward Spatio-Temporal Reasoning in Visual Question Answering**                                        | [TGIF-Frame](https://github.com/YunseokJANG/tgif-qa/tree/cvpr2017/dataset)                                                     | **CVPR 2017**   |
| **OE QA**         | **A dataset and exploration of models for understanding video data through fill-in-the-blank question-answering** | [LSMDC-FiB](https://github.com/yj-yu/lsmdc)                                                                                    | **CVPR 2017**   |
| **OE QA**         | **Video Question Answering via Gradually Refined Attention over Appearance and Motion**                           | [MSRVTT-QA](https://github.com/xudejing/video-question-answering),[MSVD-QA](https://github.com/xudejing/video-question-answering) | **MM 2017**     |
| **OE QA**         | **ActivityNet-QA: A Dataset for Understanding Complex Web Videos via Question Answering**                         | [ActivityNet-QA](https://github.com/MILVLG/activitynet-qa)                                                                     | **AAAI 2019**   |
| **MC QA**         | **Learning Language-Visual Embedding for Movie Understanding with Natural-Language**                              | [LSMDC-MC](https://github.com/yj-yu/lsmdc)                                                                                     |                       |
| **MC  QA**        | **TGIF-QA: Toward Spatio-Temporal Reasoning in Visual Question Answering**                                        | [TGIF-Action, TGIF-Transition](https://github.com/YunseokJANG/tgif-qa/tree/cvpr2017/dataset)                                   | **CVPR 2017**   |
| **MC QA**         | **A Joint Sequence Fusion Model for Video Question Answering and Retrieval**                                      | [MSRVTT-MC](https://github.com/yj-yu/lsmdc)                                                                                    | **ECCV 2018**   |
| **Caption**       | **Collecting Highly Parallel Data for Paraphrase Evaluation**                                                     | [MSVD](https://www.cs.utexas.edu/users/ml/clamp/videoDescription/)                                                             | **ACL 2011**    |
| **Caption**       | **MSR-VTT: A Large Video Description Dataset for Bridging Video and Language**                                    | [MSR-VTT](https://www.robots.ox.ac.uk/~maxbain/frozen-in-time/data/MSRVTT.zip)                                                 | **CVPR 2016**   |
| **Dense Caption** | **Dense-Captioning Events in Videos**                                                                             | [ActivityNet Caption](https://cs.stanford.edu/people/ranjaykrishna/densevid/)                                                  | **ICCV 2017**   |
| **Dense Caption** | **Towards Automatic Learning of Procedures from Web Instructional Videos**                                        | [YouCook2](http://youcook2.eecs.umich.edu/download)                                                                            | **AAAI 2018**   |
| **Dense Caption** | **Multimodal Pretraining for Dense Video Captioning**                                                             | [ViTT](https://github.com/google-research-datasets/Video-Timeline-Tags-ViTT)                                                   | **AACL 2020**   |

</details>

### Tutorials

- [[CVPR2022 Tutorial] Recent Advances in Vision-and-Language Pre-training](https://vlp-tutorial.github.io/)

### Other Curated Lists

- [LLM-in-Vision](https://github.com/DirtyHarryLYL/LLM-in-Vision)
- [Awesome-Vision-and-Language](https://github.com/sangminwoo/awesome-vision-and-language#survey)

## Speech

### Other Curated Lists

- [Audio-AI-Timeline](https://github.com/archinetai/audio-ai-timeline)

## Robotic

### Other Curated Lists

- [Awesome-LLM-Robotics](https://github.com/GT-RIPL/Awesome-LLM-Robotics)
- [Awesome-Robotics](https://github.com/ahundt/awesome-robotics)

## Related

- [Awesome-Multimodal-Research](https://github.com/Eurus-Holmes/Awesome-Multimodal-Research)
- [Awesome-Multimodal-ML](https://github.com/pliang279/awesome-multimodal-ml)

## Contributing

Please freely create [pull request](https://github.com/patrick-tssn/Awesome-Colorful-LLM/pulls) or drop me an [email](flagwyx@gmail.com)