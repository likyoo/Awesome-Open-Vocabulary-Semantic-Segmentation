# Awesome-Open-Vocabulary-Semantic-Segmentation

**If you find this project helpful, please consider giving it a star ⭐.**

## Contents
<!-- vim-markdown-toc GitLab -->

* [Open-Vocabulary Semantic Segmentation](#Open-Vocabulary-Semantic-Segmentation) (mainly updated by [@tbh3223](https://github.com/tbh3223))
  * [Fully-supervised Methods](#Fully-Supervised-Open-Vocabulary-Semantic-Segmentation)
  * [Weakly-supervised Methods](#Weakly-Supervised-Open-Vocabulary-Semantic-Segmentation)
  * [Training-free Methods](#Training-Free-Open-Vocabulary-Semantic-Segmentation)
  * [Others](#Others)

* [Zero-shot Semantic Segmentation](#Zero-Shot-Semantic-Segmentation) (mainly updated by [@tbh3223](https://github.com/tbh3223))
  
* [Referring-Image-Segmentation](#Referring-Image-Segmentation) (mainly updated by [@ghost-000](https://github.com/ghost-000))
  * [Fully-Supervised Methods](#Fully-Supervised-Referring-Image-Segmentation)
  * [Weakly-Supervised Methods](#Weakly-Supervised-Referring-Image-Segmentation)
* [Open-Vocabulary Object Detection](#Open-Vocabulary-Object-Detection)  (mainly updated by [@tbh3223](https://github.com/tbh3223))
* [Universal Semantic Segmentation](#Universal-Semantic-Segmentation)  (mainly updated by [@tbh3223](https://github.com/tbh3223))
* [Other Related Work](#Other-Related-Work)
* [Related Survey](#Related-Survey)

<!-- vim-markdown-toc -->

## Open-Vocabulary Semantic Segmentation


### Fully-Supervised Open-Vocabulary Semantic Segmentation
The model is trained on fully-supervised semantic segmentation datasets with pixel-level annotations (e.g., COCO Stuff dataset).

1. <span id = "1001">**[LSeg]**</span> | **ICLR'22** | Language-driven Semantic Segmentation | [`[pdf]`](https://arxiv.org/abs/2201.03546) | [`[code]`](https://github.com/isl-org/lang-seg)
2. <span id = "1002">**[OpenSeg]**</span> | **ECCV'22** | Scaling Open-vocabulary Image Segmentation with Image-level Labels | [`[pdf]`](https://arxiv.org/abs/2112.12143) | [`[code]`](https://github.com/tensorflow/tpu/tree/641c1ac6e26ed788327b973582cbfa297d7d31e7/models/official/detection/projects/openseg)
3. <span id = "1003">**[Xu et al.]**</span> | **ECCV'22** | A Simple Baseline for Open-Vocabulary Semantic Segmentation with Pre-trained Vision-language Model | [`[pdf]`](https://arxiv.org/abs/2112.14757) | [`[code]`](https://github.com/MendelXu/zsseg.baseline)
4. <span id = "1003">**[SegCLIP]**</span> | **ICML'23** | SegCLIP: Patch Aggregation with Learnable Centers for Open-Vocabulary Semantic Segmentation | [`[pdf]`](https://arxiv.org/abs/2211.14813) | [`[code]`](https://github.com/ArrowLuo/SegCLIP)
5. <span id = "1003">**[MaskCLIP]**</span> | **ICML'23** | Open-Vocabulary Universal Image Segmentation with MaskCLIP | [`[pdf]`](https://arxiv.org/abs/2208.08984v2) | [`[code]`](https://github.com/mlpc-ucsd/MaskCLIP)
6. <span id = "1003">**[OVSeg]**</span> | **CVPR'23** | Open-Vocabulary Semantic Segmentation with Mask-adapted CLIP | [`[pdf]`](https://arxiv.org/abs/2210.04150) | [`[code]`](https://github.com/facebookresearch/ov-seg)
7. <span id = "1003">**[X-Decoder]**</span> | **CVPR'23** | Generalized Decoding for Pixel, Image, and Language | [`[pdf]`](https://arxiv.org/abs/2212.11270) | [`[code]`](https://github.com/microsoft/X-Decoder)
8. <span id = "1003">**[SAN]**</span> | **CVPR'23(Highlight)** | Side Adapter Network for Open-Vocabulary Semantic Segmentation | [`[pdf]`](https://arxiv.org/abs/2302.12242) | [`[code]`](https://github.com/MendelXu/SAN)
9. <span id = "1003">**[SAN]**</span> | **TAPMI'23** | SAN: Side Adapter Network for Open-vocabulary Semantic Segmentation | [`[pdf]`](https://ieeexplore.ieee.org/abstract/document/10238837) | [`[code]`](https://github.com/MendelXu/SAN)
10. <span id = "1003">**[ODISE]**</span> | **CVPR'23** | Open-Vocabulary Panoptic Segmentation with Text-to-Image Diffusion Models | [`[pdf]`](https://arxiv.org/abs/2303.04803) | [`[code]`](https://github.com/NVlabs/ODISE)
11. <span id = "1003">**[FreeSeg]**</span> | **CVPR'23** | FreeSeg: Unified, Universal and Open-Vocabulary Image Segmentation | [`[pdf]`](https://arxiv.org/abs/2303.17225) | [`[code]`](https://github.com/bytedance/FreeSeg)
13. <span id = "1003">**[OpenSeeD]**</span> | **ICCV'23** | A Simple Framework for Open-Vocabulary Segmentation and Detection | [`[pdf]`](https://arxiv.org/abs/2303.08131) | [`[code]`](https://github.com/IDEA-Research/OpenSeeD)
14. <span id = "1003">**[GKC]**</span> | **ICCV'23** | Global Knowledge Calibration for Fast Open-Vocabulary Segmentation | [`[pdf]`](https://arxiv.org/pdf/2303.09181)
15. <span id = "1003">**[OPSNet]**</span> | **ICCV'23** | Open-vocabulary Panoptic Segmentation with Embedding Modulation | [`[pdf]`](https://arxiv.org/abs/2303.11324) | [`[code]`](https://github.com/XavierCHEN34/OPSNet)
16. <span id = "2005">**[MasQCLIP]**</span> | **ICCV'23** | MasQCLIP for Open-Vocabulary Universal Image Segmentation | [`[pdf]`](https://openaccess.thecvf.com/content/ICCV2023/html/Xu_MasQCLIP_for_Open-Vocabulary_Universal_Image_Segmentation_ICCV_2023_paper.html)
17. <span id = "2005">**[DeOP]**</span> | **ICCV'23** | Open Vocabulary Semantic Segmentation with Decoupled One-Pass Network | [`[pdf]`](https://arxiv.org/abs/2304.01198) | [`[code]`](https://github.com/CongHan0808/DeOP)
18. <span id = "2005">**[Li et al.]**</span> | **ICCV'23** | Open-vocabulary Object Segmentation with Diffusion Models | [`[pdf]`](https://openaccess.thecvf.com/content/ICCV2023/html/Li_Open-vocabulary_Object_Segmentation_with_Diffusion_Models_ICCV_2023_paper.html) | [`[code]`](https://github.com/Lipurple/Grounded-Diffusion)
19. <span id = "1003">**[HIPIE]**</span> | **NeurIPS'23** | Hierarchical Open-vocabulary Universal Image Segmentation | [`[pdf]`](https://arxiv.org/abs/2307.00764) | [`[code]`](https://github.com/berkeley-hipie/HIPIE)
20. <span id = "1003">**[FC-CLIP]**</span> | **NeurIPS'23** | Convolutions Die Hard: Open-Vocabulary Segmentation with Single Frozen Convolutional CLIP | [`[pdf]`](https://arxiv.org/abs/2308.02487) | [`[code]`](https://github.com/bytedance/fc-clip)
21. <span id = "1003">**[MAFT]**</span> | **NeurIPS'23** | Learning Mask-aware CLIP Representations for Zero-Shot Segmentation | [`[pdf]`](https://arxiv.org/abs/2310.00240) | [`[code]`](https://github.com/jiaosiyu1999/MAFT)
22. <span id = "1003">**[ADA]**</span> | **NeurIPS'23** | Open-Vocabulary Semantic Segmentation via Attribute Decomposition-Aggregation | [`[pdf]`](https://arxiv.org/abs/2309.00096)
23. <span id = "1003">**[Dao et al]**</span> | **TMM** | Class Enhancement Losses with Pseudo Labels for Open-Vocabulary Semantic Segmentation | [`[pdf]`](https://ieeexplore.ieee.org/abstract/document/10306291)
24. <span id = "1003">**[SELF-SEG]**</span> | **Arixv'23.12** | Self-Guided Open-Vocabulary Semantic Segmentation | [`[pdf]`](https://arxiv.org/abs/2312.04539) 
25. <span id = "1003">**[OpenSD]**</span> | **Arixv'23.12** | OpenSD: Unified Open-Vocabulary Segmentation and Detection | [`[pdf]`](https://arxiv.org/abs/2312.06703) | [`[code]`](https://github.com/strongwolf/OpenSD)
26. <span id = "1003">**[RENOVATE]**</span> | **Arixv'24.03** | Renovating Names in Open-Vocabulary Segmentation Benchmarks | [`[pdf]`](https://arxiv.org/abs/2403.09593) 
27. <span id = "1003">**[DreamCLIP]**</span> | **ECCV'24** | DreamLIP: Language-Image Pre-training with Long Captions | [`[pdf]`](https://arxiv.org/abs/2403.17007) | [`[code]`](https://github.com/zyf0619sjtu/DreamLIP)
28. <span id = "1003">**[CAT-Seg]**</span> | **CVPR'24** | CAT-Seg : Cost Aggregation for Open-Vocabulary Semantic Segmentation | [`[pdf]`](https://arxiv.org/abs/2303.11797) | [`[code]`](https://github.com/KU-CVLAB/CAT-Seg)
29. <span id = "1003">**[SED]**</span> | **CVPR'24** | SED: A Simple Encoder-Decoder for Open-Vocabulary Semantic Segmentation | [`[pdf]`](https://arxiv.org/abs/2311.15537) | [`[code]`](https://github.com/xb534/SED)
30. <span id = "1003">**[SCAN]**</span> | **CVPR'24** | Open-Vocabulary Segmentation with Semantic-Assisted Calibration | [`[pdf]`](https://arxiv.org/abs/2312.04089) | [`[code]`](https://github.com/workforai/SCAN)
31. <span id = "1003">**[OpenTrans]**</span> | **CVPR'24** | Transferable and Principled Efficiency for Open-Vocabulary Segmentation | [`[pdf]`](https://arxiv.org/abs/2404.07448) | [`[code]`](https://github.com/Xujxyang/OpenTrans))
32. <span id = "1003">**[H-CLIP]**</span> | **Arixv'24.05** | Parameter-efficient Fine-tuning in Hyperspherical Space for Open-vocabulary Semantic Segmentation | [`[pdf]`](https://arxiv.org/pdf/2405.18840)
33. <span id = "1003">**[OpenDAS]**</span> | **Arixv'24.05** | OpenDAS: Domain Adaptation for Open-Vocabulary Segmentation | [`[pdf]`](https://arxiv.org/pdf/2405.20141)
34. <span id = "1003">**[USE]**</span> | **CVPR'24** | USE: Universal Segment Embeddings for Open-Vocabulary Image Segmentation | [`[pdf]`](https://openaccess.thecvf.com/content/CVPR2024/papers/Wang_USE_Universal_Segment_Embeddings_for_Open-Vocabulary_Image_Segmentation_CVPR_2024_paper.pdf)
35. <span id = "1003">**[EBSeg]**</span> | **CVPR'24** | Open-Vocabulary Semantic Segmentation with Image Embedding Balancing | [`[pdf]`](https://arxiv.org/pdf/2406.09829) | [`[code]`](https://github.com/slonetime/EBSeg))
36. <span id = "1003">**[MAFT+]**</span> | **ECCV'24** | Collaborative Vision-Text Representation Optimizing for Open-Vocabulary Segmentation | [`[pdf]`](https://arxiv.org/pdf/2408.00744) | [`[code]`](https://github.com/jiaosiyu1999/MAFT-Plus.git))
37. <span id = "1003">**[R-Adapter]**</span> | **ECCV'24** | Efficient and Versatile Robust Fine-Tuning of Zero-shot Models | [`[pdf]`](https://arxiv.org/pdf/2408.05749) | [`[code]`](https://cvlab.postech.ac.kr/research/R-Adapter))
38. <span id = "1003">**[MROVSeg]**</span> | **Arixv'24.08** | MROVSeg: Breaking the Resolution Curse of Vision-Language Models in Open-Vocabulary Semantic Segmentation | [`[pdf]`](https://arxiv.org/pdf/2408.14776)
39. <span id = "1003">**[FrozenSeg]**</span> | **Arixv'24.09** | FrozenSeg: Harmonizing Frozen Foundation Models for Open-Vocabulary Segmentation | [`[pdf]`](https://arxiv.org/pdf/2409.03525) | [`[code]`](https://github.com/chenxi52/FrozenSeg)



### Weakly-Supervised Open-Vocabulary Semantic Segmentation
[**text-supervised/language-supervised**] The model is trained on weakly supervised datasets with only image-level annotations/captions (e.g., CC12M dataset). 

1. <span id = "2001">**[GroupViT]**</span> | **CVPR'22** | GroupViT: Semantic Segmentation Emerges from Text Supervision | [`[pdf]`](https://arxiv.org/abs/2202.11094) | [`[code]`](https://github.com/NVlabs/GroupViT)
2. <span id = "2002">**[ViL-Seg]**</span> | **ECCV'22** | Open-world Semantic Segmentation via Contrasting and Clustering Vision-Language Embedding | [`[pdf]`](https://arxiv.org/abs/2207.08455)
3. <span id = "2003">**[MaskCLIP+]**</span> | **ECCV'22(Oral)** | Extract Free Dense Labels from CLIP | [`[pdf]`](https://arxiv.org/abs/2112.01071)  | [`[code]`](https://github.com/chongzhou96/MaskCLIP)
4. <span id = "2006">**[ViewCo]**</span> | **ICLR'23** | Viewco: Discovering Text-supervised Segmentation Masks via Multi-view Semantic Consistency | [`[pdf]`](https://arxiv.org/abs/2302.10307)
5. <span id = "2004">**[SegCLIP]**</span> | **ICML'23** | SegCLIP: Patch Aggregation with Learnable Centers for Open-Vocabulary Semantic Segmentation | [`[pdf]`](https://arxiv.org/abs/2211.14813) | [`[code]`](https://github.com/ArrowLuo/SegCLIP)
6. <span id = "2005">**[CLIP-S4]**</span> | **CVPR'23** | CLIP-S4: Language-Guided Self-Supervised Semantic Segmentation | [`[pdf]`](https://arxiv.org/abs/2305.01040)
7. <span id = "2005">**[PACL]**</span> | **CVPR'23** | Open Vocabulary Semantic Segmentation with Patch Aligned Contrastive Learning | [`[pdf]`](https://arxiv.org/abs/2212.04994)
8. <span id = "2005">**[OVSegmentor]**</span> | **CVPR'23** | Learning Open-vocabulary Semantic Segmentation Models From Natural Language Supervision | [`[pdf]`](https://arxiv.org/abs/2301.09121) | [`[code]`](https://github.com/Jazzcharles/OVSegmentor)
9. <span id = "2005">**[SimSeg]**</span> | **CVPR'23** | A Simple Framework for Text-Supervised Semantic Segmentation | [`[pdf]`](https://openaccess.thecvf.com/content/CVPR2023/html/Yi_A_Simple_Framework_for_Text-Supervised_Semantic_Segmentation_CVPR_2023_paper.html) | [`[code]`](https://github.com/muyangyi/SimSeg)
10. <span id = "2005">**[TCL]**</span> | **CVPR'23** | Learning to Generate Text-grounded Mask for Open-world Semantic Segmentation from Only Image-Text Pairs | [`[pdf]`](https://arxiv.org/abs/2212.00785) | [`[code]`](https://github.com/kakaobrain/tcl)
11. <span id = "2005">**[SimCon]**</span> | **Arxiv'23.02** | SimCon Loss with Multiple Views for Text Supervised Semantic Segmentation | [`[pdf]`](https://browse.arxiv.org/abs/2302.03432)
12. <span id = "2005">**[Zhang et al.]**</span> | **Arxiv'23.04** | Associating Spatially-Consistent Grouping with Text-supervised Semantic Segmentation | [`[pdf]`](https://arxiv.org/abs/2304.01114)
13. <span id = "2005">**[ZeroSeg]**</span> | **ICCV'23** | Exploring Open-Vocabulary Semantic Segmentation from CLIP Vision Encoder Distillation Only | [`[pdf]`](https://openaccess.thecvf.com/content/ICCV2023/html/Chen_Exploring_Open-Vocabulary_Semantic_Segmentation_from_CLIP_Vision_Encoder_Distillation_Only_ICCV_2023_paper.html)
14. <span id = "2005">**[CLIPpy]**</span> | **ICCV'23** | Perceptual Grouping in Contrastive Vision-Language Models | [`[pdf]`](https://arxiv.org/abs/2210.09996)
15. <span id = "2005">**[MixReorg]**</span> | **ICCV'23** | MixReorg: Cross-Modal Mixed Patch Reorganization is a Good Mask Learner for Open-World Semantic Segmentation | [`[pdf]`](https://arxiv.org/abs/2308.04829)
16. <span id = "2005">**[CoCu]**</span> | **NeurIPS'23** | Bridging Semantic Gaps for Language-Supervised Semantic Segmentation | [`[pdf]`](https://arxiv.org/abs/2309.13505) | [`[code]`](https://github.com/xing0047/CoCu)
17. <span id = "2005">**[PGSeg]**</span> | **NeurIPS'23** | Uncovering Prototypical Knowledge for Weakly Open-Vocabulary Semantic Segmentation | [`[pdf]`](https://arxiv.org/abs/2310.19001) | [`[code]`](https://github.com/Ferenas/PGSeg)
18. <span id = "2005">**[SAM-CLIP]**</span> | **Arixv'23.10** | SAM-CLIP: Merging Vision Foundation Models towards Semantic and Spatial Understanding | [`[pdf]`](https://arxiv.org/abs/2310.15308)
19. <span id = "2005">**[CLIP-DINOiser]**</span> | **Arixv'23.12** | CLIP-DINOiser: Teaching CLIP a few DINO tricks | [`[pdf]`](https://arxiv.org/abs/2312.12359) | [`[code]`](https://github.com/wysoczanska/clip_dinoiser)
20. <span id = "2005">**[TagAlign]**</span> | **Arixv'23.12** | TagAlign: Improving Vision-Language Alignment with Multi-Tag Classification | [`[pdf]`](https://arxiv.org/abs/2312.14149) | [`[code]`](https://github.com/Qinying-Liu/TagAlign)
21. <span id = "2005">**[S-Seg]**</span> | **Arixv'24.01** | Exploring Simple Open-Vocabulary Semantic Segmentation | [`[pdf]`](https://arxiv.org/abs/2401.12217) | [`[code]`](https://github.com/zlai0/S-Seg)
22. <span id = "2005">**[CLIPSelf]**</span> | **ICLR'24(Spotlight)** | CLIPSelf: Vision Transformer Distills Itself for Open-Vocabulary Dense Prediction | [`[pdf]`](https://arxiv.org/abs/2310.01403) | [`[code]`](https://github.com/wusize/CLIPSelf)
23. <span id = "2005">**[Uni-OVSeg]**</span> | **Arixv'24.02** | Open-Vocabulary Segmentation with Unpaired Mask-Text Supervision | [`[pdf]`](https://arxiv.org/abs/2402.08960) | [`[code]`](https://github.com/DerrickWang005/Uni-OVSeg.pytorch)
24. <span id = "2005">**[MGCA]**</span> | **Arixv'24.03** | Multi-Grained Cross-modal Alignment for Learning Open-vocabulary Semantic Segmentation from Text Supervision | [`[pdf]`](https://arxiv.org/abs/2403.03707)
25. <span id = "2005">**[TTD]**</span> | **Arixv'24.04** | TTD: Text-Tag Self-Distillation Enhancing Image-Text Alignment in CLIP to Alleviate Single Tag Bias | [`[pdf]`](https://arxiv.org/abs/2404.00384)  | [`[code]`](https://github.com/shjo-april/TTD)
26. <span id = "2005">**[CoDe]**</span> | **CVPR'24** | Image-Text Co-Decomposition for Text-Supervised Semantic Segmentation | [`[pdf]`](https://arxiv.org/abs/2404.04231)
27. <span id = "2005">**[LLM-Supervision]**</span> | **Arixv'24.03** | Training-Free Semantic Segmentation via LLM-Supervision | [`[pdf]`](https://arxiv.org/pdf/2404.00701)
28. <span id = "2005">**[ProxyCLIP]**</span> | **ECCV'24** | ProxyCLIP: Proxy Attention Improves CLIP for Open-Vocabulary Segmentation | [`[pdf]`](https://arxiv.org/pdf/2408.04883) | [`[code]`](https://github.com/mc-lan/ProxyCLIP)



### Training-Free Open-Vocabulary Semantic Segmentation
The model is modified from the off-the-shelf large models (e.g., CLIP, Diffusion models) without an additional training phase. **Note that**, the large models have already been trained with some datasets (e.g., image-caption datasets). 

1. <span id = "3001">**[MaskCLIP]**</span> | **ECCV'22(Oral)** | Extract Free Dense Labels from CLIP | [`[pdf]`](https://arxiv.org/abs/2112.01071)  | [`[code]`](https://github.com/chongzhou96/MaskCLIP)
2. <span id = "3001">**[ReCo]**</span> | **NeurIPS'22** | ReCo: Retrieve and Co-segment for Zero-shot Transfer | [`[pdf]`](https://arxiv.org/abs/2206.07045)  | [`[code]`](https://github.com/NoelShin/reco) 
3. <span id = "3001">**[CLIP Surgery]**</span> | **Arxiv'23.04** | CLIP Surgery for Better Explainability with Enhancement in Open-Vocabulary Tasks | [`[pdf]`](https://arxiv.org/abs/2304.05653) | [`[code]`](https://github.com/xmed-lab/CLIP_Surgery)
4. <span id = "3001">**[OVDiff]**</span> | **Arxiv'23.06** | Diffusion Models for Zero-Shot Open-Vocabulary Segmentation | [`[pdf]`](https://arxiv.org/abs/2306.09316)
5. <span id = "3001">**[DiffSegmenter]**</span> | **Arxiv'23.09** | Diffusion Model is Secretly a Training-free Open Vocabulary Semantic Segmenter | [`[pdf]`](https://arxiv.org/abs/2309.02773) | [`[code]`](https://github.com/VCG-team/DiffSegmenter)
6. <span id = "3001">**[IPSeg]**</span> | **IJCV'24** | Towards Training-free Open-world Segmentation via Image Prompting Foundation Models | [`[pdf]`](https://arxiv.org/abs/2310.10912)
7. <span id = "3001">**[SCLIP]**</span> | **Arxiv'23.12** | SCLIP: Rethinking Self-Attention for Dense Vision-Language Inference | [`[pdf]`](https://arxiv.org/abs/2312.01597)
8. <span id = "3001">**[GEM]**</span> | **CVPR'24** | Grounding Everything: Emerging Localization Properties in Vision-Language Transformers | [`[pdf]`](https://arxiv.org/abs/2312.00878) | [`[code]`](https://github.com/WalBouss/GEM)
9. <span id = "3001">**[CLIP-DIY]**</span> | **WACV'24** | CLIP-DIY: CLIP Dense Inference Yields Open-Vocabulary Semantic Segmentation For-Free | [`[pdf]`](https://arxiv.org/abs/2309.14289)
10. <span id = "3001">**[FOSSIL]**</span> | **WACV'24** | FOSSIL: Free Open-Vocabulary Semantic Segmentation through Synthetic References Retrieval | [`[pdf]`](https://openaccess.thecvf.com/content/WACV2024/html/Barsellotti_FOSSIL_Free_Open-Vocabulary_Semantic_Segmentation_Through_Synthetic_References_Retrieval_WACV_2024_paper.html)
11. <span id = "3001">**[TagCLIP]**</span> | **AAAI'24** | TagCLIP: A Local-to-Global Framework to Enhance Open-VocabularyMulti-Label Classification of CLIP Without Training | [`[pdf]`](https://arxiv.org/abs/2312.12828) | [`[code]`](https://github.com/linyq2117/TagCLIP)
12. <span id = "3001">**[EmerDiff]**</span> | **ICLR'24** | EmerDiff: Emerging Pixel-level Semantic Knowledge in Diffusion Models | [`[pdf]`](https://arxiv.org/abs/2401.11739) | [`[code]`](https://github.com/linyq2117/TagCLIP) 
13. <span id = "3001">**[FreeSeg-Diff]**</span> | **Arxiv'24.03** | FreeSeg-Diff: Training-Free Open-Vocabulary Segmentation with Diffusion Models | [`[pdf]`](https://arxiv.org/abs/2403.20105) | [`[code]`](https://bcorrad.github.io/freesegdiff/)
14. <span id = "3001">**[MaskDiffusion]**</span> | **Arxiv'24.03** | MaskDiffusion: Exploiting Pre-trained Diffusion Models for Semantic Segmentation | [`[pdf]`](https://arxiv.org/abs/2403.11194) | [`[code]`](https://github.com/Valkyrja3607/MaskDiffusion)
15. <span id = "3001">**[TAG]**</span> | **Arxiv'24.03** | TAG: Guidance-free Open-Vocabulary Semantic Segmentation | [`[pdf]`](https://arxiv.org/abs/2403.11197) | [`[code]`](https://github.com/Valkyrja3607/TAG)
16. <span id = "3001">**[Sun et al.]**</span> | **Arxiv'24.04** | Training-Free Semantic Segmentation via LLM-Supervision | [`[pdf]`](https://arxiv.org/abs/2404.00701)
17. <span id = "3001">**[NACLIP]**</span> | **Arxiv'24.04** | Pay Attention to Your Neighbours: Training-Free Open-Vocabulary Semantic Segmentation| [`[pdf]`](https://arxiv.org/abs/2404.08181) | [`[code]`](https://github.com/sinahmr/NACLIP)
18. <span id = "3001">**[PnP-OVSS]**</span> | **CVPR'24** | Emergent Open-Vocabulary Semantic Segmentation from Off-the-shelf Vision-Language Models | [`[pdf]`](https://arxiv.org/abs/2311.17095)  | [`[code]`](https://github.com/letitiabanana/PnP-OVSS)
19. <span id = "3001">**[CaR]**</span> | **CVPR'24** | CLIP as RNN: Segment Countless Visual Concepts without Training Endeavor | [`[pdf]`](https://arxiv.org/abs/2312.07661) | [`[code]`](https://github.com/kevin-ssy/CLIP_as_RNN)
20. <span id = "3001">**[Wang et al.]**</span> | **CVPR'24** | Image-to-Image Matching via Foundation Models: A New Perspective for Open-Vocabulary Semantic Segmentation | [`[pdf]`](https://arxiv.org/abs/2404.00262) | [`[code]`](https://github.com/072jiajia/image-text-co-decomposition)
21. <span id = "3001">**[FreeDA]**</span> | **CVPR'24** | Training-Free Open-Vocabulary Segmentation with Offline Diffusion-Augmented Prototype Generation| [`[pdf]`](https://arxiv.org/abs/2404.06542) | [`[code]`](https://aimagelab.github.io/freeda/)
22. <span id = "3001">**[Yang et al.]**</span> | **Arxiv'24.05** | Tuning-free Universally-Supervised Semantic Segmentation | [`[pdf]`](https://arxiv.org/pdf/2405.14294)
23. <span id = "3001">**[CLIPTrase]**</span> | **ECCV'24** | Explore the Potential of CLIP for Training-Free Open Vocabulary Semantic Segmentation | [`[pdf]`](https://arxiv.org/pdf/2407.08268) | [`[code]`](https://github.com/leaves162/CLIPtrase)
24. <span id = "3001">**[ClearCLIP]**</span> | **ECCV'24** | ClearCLIP: Decomposing CLIP Representations for Dense Vision-Language Inference | [`[pdf]`](https://arxiv.org/pdf/2407.12442) | [`[code]`](https://github.com/mc-lan/ClearCLIP)
25. <span id = "2005">**[ProxyCLIP]**</span> | **ECCV'24** | ProxyCLIP: Proxy Attention Improves CLIP for Open-Vocabulary Segmentation | [`[pdf]`](https://arxiv.org/pdf/2408.04883) | [`[code]`](https://github.com/mc-lan/ProxyCLIP)
26. <span id = "2005">**[LaVG]**</span> | **ECCV'24** | In Defense of Lazy Visual Grounding for Open-Vocabulary Semantic Segmentation | [`[pdf]`](https://arxiv.org/pdf/2408.04961) | [`[code]`](https://github.com/dahyun-kang/lavg)
27. <span id = "3001">**[SegEarth-OV]**</span> | **Arxiv'24.10** | SegEarth-OV: Towards Traning-Free Open-Vocabulary Segmentation for Remote Sensing Images | [`[pdf]`](https://arxiv.org/abs/2410.01768) | [`[code]`](https://github.com/likyoo/SegEarth-OV)

  

### Others

1. <span id = "4001">**[EntitySeg]**</span> | **Arxiv'23.11** | Rethinking Evaluation Metrics of Open-Vocabulary Segmentation | [`[pdf]`](https://arxiv.org/abs/2311.03352)  | [`[code]`](https://github.com/qqlu/Entity/tree/main)

## Zero-Shot Semantic Segmentation
Different from open-vocabulary segmentation (cross-dataset),  zero-shot methods split each dataset to seen classes and unseen classes.

1. <span id = "1001">**[ZegFormer]**</span> | **CVPR'22** | ZegFormer: Decoupling Zero-Shot Semantic Segmentation | [`[pdf]`](https://arxiv.org/abs/2112.07910) | [`[code]`](https://github.com/dingjiansw101/ZegFormer)
2. <span id = "1002">**[Xu et al.]**</span> | **ECCV'22** | A Simple Baseline for Open-Vocabulary Semantic Segmentation with Pre-trained Vision-language Model | [`[pdf]`](https://arxiv.org/abs/2112.14757) | [`[code]`](https://github.com/MendelXu/zsseg.baseline)
3. <span id = "1003">**[ZegCLIP]**</span> | **CVPR'23** | ZegCLIP: Towards Adapting CLIP for Zero-shot Semantic Segmentation | [`[pdf]`](https://arxiv.org/abs/2212.03588) | [`[code]`](https://github.com/ZiqinZhou66/ZegCLIP)
4. <span id = "1004">**[PADing]**</span> | **CVPR'23** | Primitive Generation and Semantic-related Alignment for Universal Zero-Shot Segmentation | [`[pdf]`](https://arxiv.org/abs/2306.11087) | [`[code]`](https://github.com/heshuting555/PADing)
5. <span id = "1005">**[DeOP]**</span> | **ICCV'23** | Open Vocabulary Semantic Segmentation with Decoupled One-Pass Network | [`[pdf]`](https://arxiv.org/abs/2304.01198) | [`[code]`](https://github.com/CongHan0808/DeOP)
6. <span id = "1006">**[SPT]**</span> | **AAAI'24** | Spectral Prompt Tuning: Unveiling Unseen Classes for Zero-Shot Semantic Segmentation | [`[pdf]`](https://arxiv.org/abs/2312.12754) | [`[code]`](https://github.com/clearxu/SPT)
7. <span id = "1006">**[Chen et al.]**</span> | **Arxiv'24.02** | Generalizable Semantic Vision Query Generation for Zero-shot Panoptic and Semantic Segmentation | [`[pdf]`](https://arxiv.org/abs/2402.13697) 
8. <span id = "1006">**[LDVC]**</span> | **Arxiv'24.03** | Language-Driven Visual Consensus for Zero-Shot Semantic Segmentation | [`[pdf]`](https://arxiv.org/abs/2403.08426) 
9. <span id = "1006">**[OTSeg]**</span> | **Arxiv'24.03** | OTSeg: Multi-prompt Sinkhorn Attention for Zero-Shot Semantic Segmentation | [`[pdf]`](https://arxiv.org/abs/2403.14183) 
10. <span id = "1006">**[Cascade-CLIP]**</span> | **ICML'24** | Cascade-CLIP: Cascaded Vision-Language Embeddings Alignment for Zero-Shot Semantic Segmentation | [`[pdf]`](https://arxiv.org/abs/2406.00670) | [`[code]`](https://github.com/HVision-NKU/Cascade-CLIP)
11. <span id = "1006">**[SimZSS]**</span> | **Arxiv'24.07** | A Simple Framework for Open-Vocabulary Zero-Shot Segmentation | [`[pdf]`](https://arxiv.org/pdf/2406.16085)
12. <span id = "1006">**[CaR]**</span> | **CVPR'24** | CLIP as RNN: Segment Countless Visual Concepts without Training Endeavor | [`[pdf]`](https://arxiv.org/pdf/2312.07661) | [`[code]`](https://github.com/kevin-ssy/CLIP_as_RNN)

## Referring Image Segmentation

### Fully-Supervised Referring Image Segmentation

1. <span id = "3001">**[CARIS]**</span> | **ACM MM'23** | CARIS: Context-Aware Referring Image Segmentation | [`[pdf]`](https://dl.acm.org/doi/abs/10.1145/3581783.3612117) | [`[code]`](https://github.com/lsa1997/CARIS)
2. <span id = "3001">**[BKINet]**</span> | **TMM'23** | Bilateral Knowledge Interaction Network for Referring Image Segmentation | [`[pdf]`](https://ieeexplore.ieee.org/abstract/document/10227590) | [`[code]`](https://github.com/dhding/BKINet)
3. <span id = "3001">**[Group-RES]**</span> | **ICCV'23** | Advancing Referring Expression Segmentation Beyond Single Image | [`[pdf]`](https://arxiv.org/abs/2305.12452) | [`[code]`](https://github.com/yixuan730/group-res)
4. <span id = "3001">**[RIS-DMMI]**</span> | **ICCV'23** | Beyond One-to-One: Rethinking the Referring Image Segmentation | [`[pdf]`](https://arxiv.org/abs/2308.13853) | [`[code]`](https://github.com/toggle1995/RIS-DMMI)
5. <span id = "3001">**[ETRIS]**</span> | **ICCV'23** | Bridging Vision and Language Encoders: Parameter-Efficient Tuning for Referring Image Segmentation | [`[pdf]`](https://arxiv.org/pdf/2307.11545.pdf) | [`[code]`](https://github.com/kkakkkka/ETRIS)
6. <span id = "4001">**[SEEM]**</span> | **ArXiv'23.04** | Segment Everything Everywhere All at Once | [`[pdf]`](https://arxiv.org/pdf/2304.06718.pdf) | [`[code]`](https://github.com/UX-Decoder/Segment-Everything-Everywhere-All-At-Once)

 ### Weakly-Supervised Referring Image Segmentation
 1. <span id = "3001">**[Strudel et al.]**</span> | **ArXiv'22.05** | Weakly-supervised segmentation of referring expressions | [`[pdf]`](https://arxiv.org/pdf/2205.04725)
 2. <span id = "3001">**[Kim et al.]**</span> | **ICCV'23** | Shatter and Gather: Learning Referring Image Segmentation with Text Supervision | [`[pdf]`](https://arxiv.org/abs/2308.15512) | [`[code]`](https://github.com/kdwonn/SaG)
 3. <span id = "3001">**[TRIS]**</span> | **ICCV'23** | Referring Image Segmentation Using Text Supervision | [`[pdf]`](https://arxiv.org/abs/2308.14575) | [`[code]`](https://github.com/fawnliu/TRIS)
 4. <span id = "3001">**[Jungbeom Lee et al.]**</span> | **ICCV'23** | Weakly Supervised Referring Image Segmentation with Intra-Chunk and Inter-Chunk Consistency | [`[pdf]`](https://openaccess.thecvf.com/content/ICCV2023/papers/Lee_Weakly_Supervised_Referring_Image_Segmentation_with_Intra-Chunk_and_Inter-Chunk_Consistency_ICCV_2023_paper.pdf) 
 5. <span id = "3001">**[PPT]**</span> | **CVPR'24** | Curriculum Point Prompting for Weakly-Supervised Referring Segmentation | [`[pdf]`](https://arxiv.org/pdf/2404.11998) 

## Open-Vocabulary Object Detection

1. <span id = "3001">**[RO-ViT]**</span> | **CVPR'23(Highlight)** | Region-Aware Pretraining for Open-Vocabulary Object Detection with Vision Transformers | [`[pdf]`](https://arxiv.org/abs/2305.07011) | [`[code]`](https://github.com/mcahny/rovit)
2. <span id = "3001">**[CAT]**</span> | **CVPR'23** | CAT: LoCalization and IdentificAtion Cascade Detection Transformer for Open-World Object Detection | [`[pdf]`](https://arxiv.org/abs/2301.01970) | [`[code]`](https://github.com/xiaomabufei/CAT)
3. <span id = "3001">**[DetCLIPv2]**</span> | **CVPR'23** | DetCLIPv2: Scalable Open-Vocabulary Object Detection Pre-training via Word-Region Alignment | [`[pdf]`](https://arxiv.org/abs/2304.04514) 
4. <span id = "3001">**[CondHead]**</span> | **CVPR'23** | Learning to Detect and Segment for Open Vocabulary Object Detection | [`[pdf]`](https://arxiv.org/abs/2212.12130)
5. <span id = "3001">**[CORA]**</span> | **CVPR'23** | CORA: Adapting CLIP for Open-Vocabulary Detection with Region Prompting and Anchor Pre-Matching | [`[pdf]`](https://arxiv.org/abs/2303.13076)  | [`[code]`](https://github.com/tgxs002/CORA)
6. <span id = "3001">**[ovdet]**</span> | **CVPR'23** | Aligning Bag of Regions for Open-Vocabulary Object Detection | [`[pdf]`](https://arxiv.org/abs/2302.13996)  | [`[code]`](https://github.com/wusize/ovdet)
7. <span id = "3001">**[OADP]**</span> | **CVPR'23** | Object-Aware Distillation Pyramid for Open-Vocabulary Object Detection | [`[pdf]`](https://arxiv.org/abs/2303.05892)  | [`[code]`](https://github.com/LutingWang/OADP)
8. <span id = "3001">**[F-VLM]**</span> | **ICLR'23** | F-VLM: Open-Vocabulary Object Detection upon Frozen Vision and Language Models | [`[pdf]`](https://arxiv.org/abs/2209.15639)  | [`[code]`](https://github.com/google-research/google-research/tree/master/fvlm)
9. <span id = "3001">**[mm-ovod]**</span> | **ICML 2023** | Multi-Modal Classifiers for Open-Vocabulary Object Detection | [`[pdf]`](https://arxiv.org/abs/2306.05493)  | [`[code]`](https://github.com/prannaykaul/mm-ovod)
10. <span id = "3001">**[SGDN]**</span> | **Arxiv'23.07** | Open-Vocabulary Object Detection via Scene Graph Discovery | [`[pdf]`](https://arxiv.org/abs/2307.03339)
11. <span id = "3001">**[MMC-Det]**</span> | **Arxiv'23.08** | Exploring Multi-Modal Contextual Knowledge for Open-Vocabulary Object Detection | [`[pdf]`](https://arxiv.org/abs/2308.15846) 
12. <span id = "3001">**[SAS-Det]**</span> | **CVPR'24** | Taming Self-Training for Open-Vocabulary Object Detection | [`[pdf]`](https://arxiv.org/abs/2308.06412) | [`[code]`](https://github.com/xiaofeng94/SAS-Det)
13. <span id = "3001">**[DITO]**</span> | **Arxiv'23.09** | Detection-Oriented Image-Text Pretraining for Open-Vocabulary Detection | [`[pdf]`](https://arxiv.org/pdf/2310.00161v1.pdf) | [`[code]`](https://github.com/google-research/google-research/tree/master/fvlm/dito)
14. <span id = "3001">**[EdaDet]**</span> | **ICCV'23** | EdaDet: Open-Vocabulary Object Detection Using Early Dense Alignment | [`[pdf]`](https://arxiv.org/abs/2309.01151)  | [`[code]`](https://chengshiest.github.io/edadet/)
15. <span id = "3001">**[LP-OVOD]**</span> | **WACV'24** | LP-OVOD: Open-Vocabulary Object Detection by Linear Probing | [`[pdf]`](https://arxiv.org/abs/2310.17109) | [`[code]`](https://github.com/wysoczanska/clip-diy)
16. <span id = "3001">**[DST-Det]**</span> | **Arxiv'23.10** | DST-Det: Simple Dynamic Self-Training for Open-Vocabulary Object Detection | [`[pdf]`](https://arxiv.org/abs/2310.01393)  | [`[code]`](https://github.com/xushilin1/dst-det)
17. <span id = "3001">**[CoDet]**</span> | **NeurIPS'23** | CoDet: Co-Occurrence Guided Region-Word Alignment for Open-Vocabulary Object Detection | [`[pdf]`](https://arxiv.org/abs/2310.16667) | [`[code]`](https://github.com/CVMI-Lab/CoDet)
18. <span id = "3001">**[PLAC]**</span> | **Arxiv'23.12** | Learning Pseudo-Labeler beyond Noun Concepts for Open-Vocabulary Object Detection | [`[pdf]`](https://arxiv.org/pdf/2312.02103.pdf)
19. <span id = "3001">**[Sambor]**</span> | **Arxiv'23.12** | Boosting Segment Anything Model Towards Open-Vocabulary Learning | [`[pdf]`](https://arxiv.org/pdf/2312.03628.pdf) | [`[code]`](https://github.com/ucas-vg/Sambor)
20. <span id = "3001">**[DVDet]**</span> | **ICLR'24** | LLMs Meet VLMs: Boost Open Vocabulary Object Detection with Fine-grained Descriptors | [`[pdf]`](https://arxiv.org/pdf/2402.04630.pdf)
21. <span id = "3001">**[DetCLIPv3]**</span> | **CVPR'24** | DetCLIPv3: Towards Versatile Generative Open-vocabulary Object Detection | [`[pdf]`](https://arxiv.org/pdf/2404.09216)
22. <span id = "3001">**[AggDet]**</span> | **Arxiv'24.04** | Training-free Boost for Open-Vocabulary Object Detection with Confidence Aggregation | [`[pdf]`](https://arxiv.org/pdf/2404.08603)
23. <span id = "3001">**[RALF]**</span> | **CVPR'24** | Retrieval-Augmented Open-Vocabulary Object Detection | [`[pdf]`](https://arxiv.org/pdf/2404.05687) | [`[code]`](https://github.com/mlvlab/RALF)
24. <span id = "3001">**[Chhipa et al.]**</span> | **Arxiv'24.06** | Investigating Robustness of Open-Vocabulary Foundation Object Detectors under Distribution Shifts | [`[pdf]`](https://arxiv.org/pdf/2405.14874)
25. <span id = "3001">**[SHiNe]**</span> | **CVPR'24(Highlight)** | SHiNe: Semantic Hierarchy Nexus for Open-vocabulary Object Detection | [`[pdf]`](https://arxiv.org/pdf/2405.10053) | [`[code]`](https://github.com/naver/shine)
26. <span id = "3001">**[RTGen]**</span> | **Arxiv'24.06** | RTGen: Generating Region-Text Pairs for Open-Vocabulary Object Detection | [`[pdf]`](https://arxiv.org/pdf/2405.19854) | [`[code]`](https://github.com/seermer/RTGen)
27. <span id = "3001">**[LBP]**</span> | **CVPR'24** | Learning Background Prompts to Discover Implicit Knowledge for Open Vocabulary Object Detection | [`[pdf]`](https://arxiv.org/pdf/2406.00510)
28. <span id = "3001">**[YOLO-World]**</span> | **CVPR'24** | Real-Time Open-Vocabulary Object Detection | [`[pdf]`](https://arxiv.org/pdf/2401.17270) | [`[code]`](https://github.com/AILab-CVC/YOLO-World)
29. <span id = "3001">**[OV-DINO]**</span> | **Arxiv'24.07** | Unified Open-Vocabulary Detection with Language-Aware Selective Fusion | [`[pdf]`](https://arxiv.org/pdf/2407.07844) | [`[code]`](https://github.com/Atten4Vis/LWDETR)
30. <span id = "3001">**[OVLW-DETR]**</span> | **Arxiv'24.07** | OVLW-DETR: Open-Vocabulary Light-Weighted Detection Transformer | [`[pdf]`](https://arxiv.org/pdf/2407.10655) | [`[code]`](https://github.com/wanghao9610/OV-DINO)
31. <span id = "3001">**[LaMI-DETR]**</span> | **ECCV'24** | LaMI-DETR: Open-Vocabulary Detection with Language Model Instruction | [`[pdf]`](https://arxiv.org/pdf/2407.11335) | [`[code]`](https://github.com/eternaldolphin/LaMI-DETR)
32. <span id = "3001">**[MarvelOVD]**</span> | **ECCV'24** | MarvelOVD: Marrying Object Recognition and Vision-Language Models for Robust Open-Vocabulary Object Detection | [`[pdf]`](https://arxiv.org/pdf/2407.21465) | [`[code]`](https://github.com/wkfdb/MarvelOVD)




## Universal Semantic Segmentation

1. <span id = "3001">**[Semantic-SAM]**</span> | **ECCV'24** | Semantic-SAM: Segment and Recognize Anything at Any Granularity | [`[pdf]`](https://arxiv.org/pdf/2307.04767.pdf) | [`[code]`](https://github.com/UX-Decoder/Semantic-SAM)
2. <span id = "3001">**[Open-Vocabulary SAM]**</span> | **ECCV'24** | Open-Vocabulary SAM: Segment and Recognize Twenty-thousand Classes Interactively | [`[pdf]`](https://arxiv.org/pdf/2401.02955.pdf) | [`[code]`](https://github.com/HarborYuan/ovsam)
3. <span id = "3001">**[OMG-Seg]**</span> | **CVPR'24** | OMG-Seg: Is One Model Good Enough For All Segmentation? | [`[pdf]`](https://arxiv.org/pdf/2401.10229.pdf) | [`[code]`](https://github.com/lxtGH/OMG-Seg)

## Other Related Work

1. <span id = "3001">**[DENOISER]**</span> | **Arxiv'24.04** | DENOISER: Rethinking the Robustness for Open-Vocabulary Action Recognition | [`[pdf]`](https://arxiv.org/pdf/2404.14890)
2. <span id = "3001">**[O2V-mapping]**</span> | **Arxiv'24.04** | O2V-Mapping: Online Open-Vocabulary Mapping with Neural Implicit Representation | [`[pdf]`](https://arxiv.org/pdf/2404.06836)
3. <span id = "3001">**[CMD-SE]**</span> | **CVPR'24** | Exploring the Potential of Large Foundation Models for Open-Vocabulary HOI Detection | [`[pdf]`](https://arxiv.org/pdf/2404.06194)
4. <span id = "3001">**[FG-CLIP]**</span> | **CBMI'24** | Is CLIP the main roadblock for fine-grained open-world perception? | [`[pdf]`](https://arxiv.org/pdf/2404.03539) | [`[code]`](https://github.com/lorebianchi98/FG-CLIP)
5. <span id = "3001">**[NegPrompt]**</span> | **CVPR'24** | Learning Transferable Negative Prompts for Out-of-Distribution Detection | [`[pdf]`](https://arxiv.org/pdf/2404.03248) | [`[code]`](https://github.com/mala-lab/negprompt)
6. <span id = "3001">**[OVFoodSeg]**</span> | **CVPR'24** | OVFoodSeg: Elevating Open-Vocabulary Food Image Segmentation via Image-Informed Textual Representation | [`[pdf]`](https://arxiv.org/pdf/2404.01409)
7. <span id = "3001">**[Fed-MP]**</span> | **NAACL'24** | Open-Vocabulary Federated Learning with Multimodal Prototyping | [`[pdf]`](https://arxiv.org/pdf/2404.01232)
8. <span id = "3001">**[PSALM]**</span> | **ECCV'24** | PSALM: Pixelwise SegmentAtion with Large Multi-Modal Model | [`[pdf]`](https://arxiv.org/pdf/2403.14598) | [`[code]`](https://github.com/zamling/PSALM)
9. <span id = "3001">**[OVAM]**</span> | **Arxiv'24.03** | Open-Vocabulary Attention Maps with Token Optimization for Semantic Segmentation in Diffusion Models | [`[pdf]`](https://arxiv.org/pdf/2403.14291)
10. <span id = "3001">**[CLIP-VIS]**</span> | **Arxiv'24.06** | CLIP-VIS: Adapting CLIP for Open-Vocabulary Video Instance Segmentation | [`[pdf]`](https://arxiv.org/pdf/2403.12455)
11. <span id = "3001">**[RoboHop]**</span> | **ICRA'24** | RoboHop: Segment-based Topological Map Representation for Open-World Visual Navigation | [`[pdf]`](https://oravus.github.io/RoboHop/data/RoboHop_Garg2024_compressed_v3.pdf)
12. <span id = "3001">**[Rein]**</span> | **CVPR'24** | Stronger, Fewer, & Superior: Harnessing Vision Foundation Models for Domain Generalized Semantic Segmentation | [`[pdf]`](https://arxiv.org/pdf/2312.04265) | [`[code]`](https://github.com/w1oves/Rein)
13. <span id = "3001">**[OVMR]**</span> | **CVPR'24** | OVMR: Open-Vocabulary Recognition with Multi-Modal References | [`[pdf]`](https://arxiv.org/pdf/2406.04675) | [`[code]`](https://github.com/Zehong-Ma/OVMR)
14. <span id = "3001">**[PartCLIPSeg]**</span> | **Arxiv'24.06** | Understanding Multi-Granularity for Open-Vocabulary Part Segmentation | [`[pdf]`](https://arxiv.org/pdf/2406.11384) | [`[code]`](https://github.com/kaist-cvml-lab/part-clipseg)
15. <span id = "3001">**[GBC]**</span> | **Arxiv'24.07** | Graph-Based Captioning: Enhancing Visual Descriptions by Interconnecting Region Captions | [`[pdf]`](https://arxiv.org/pdf/2407.06723)
16. <span id = "3001">**[TCC]**</span> | **Arxiv'24.07** | A Study of Test-time Contrastive Concepts for Open-world, Open-vocabulary Semantic Segmentation | [`[pdf]`](https://arxiv.org/pdf/2407.05061)
17. <span id = "3001">**[OPS]**</span> | **ECCV'24** | Open Panoramic Segmentation | [`[pdf]`](https://arxiv.org/pdf/2407.02685) | [`[code]`](https://github.com/JunweiZheng93/OPS)
18. <span id = "3001">**[Yu et al.]**</span> | **Arxiv'24.07** | PanopticRecon: Leverage Open-vocabulary Instance Segmentation for Zero-shot Panoptic Reconstruction | [`[pdf]`](https://arxiv.org/pdf/2407.01349)
19. <span id = "3001">**[Oryon]**</span> | **CVPR'24(Highlight)** | Oryon: Open-Vocabulary Object 6D Pose Estimation | [`[pdf]`](https://arxiv.org/pdf/2312.00690) | [`[code]`](https://github.com/jcorsetti/oryon)
20. <span id = "3001">**[GLIS]**</span> | **ECCV'24** | Global-Local Collaborative Inference with LLM for Lidar-Based Open-Vocabulary Detection | [`[pdf]`](https://arxiv.org/pdf/2407.08931) | [`[code]`](https://github.com/GradiusTwinbee/GLIS)
21. <span id = "3001">**[OVExp]**</span> | **Arxiv'24.07** | OVExp: Open Vocabulary Exploration for Object-Oriented Navigation | [`[pdf]`](https://arxiv.org/pdf/2407.09016) | [`[code]`](https://github.com/OpenRobotLab/OVExp)
22. <span id = "3001">**[OV-MLVC]**</span> | **Arxiv'24.07** | Open Vocabulary Multi-Label Video Classification | [`[pdf]`](https://arxiv.org/pdf/2407.09073v1)
23. <span id = "3001">**[DART]**</span> | **Arxiv'24.07** | An automated end-to-end object detection pipeline with data Diversification, open-vocabulary bounding box Annotation, pseudo-label Review, and model Training | [`[pdf]`](https://arxiv.org/pdf/2407.09174) | [`[code]`](https://github.com/chen-xin-94/DART)
24. <span id = "3001">**[NOVIC]**</span> | **Arxiv'24.07** | Unconstrained Open Vocabulary Image Classification: Zero-Shot Transfer from Text to Image via CLIP Inversion | [`[pdf]`](https://www.arxiv.org/pdf/2407.11211)
25. <span id = "3001">**[CerberusDet]**</span> | **Arxiv'24.07** | CerberusDet: Unified Multi-Task Object Detection | [`[pdf]`](https://arxiv.org/pdf/2407.12632)
26. <span id = "3001">**[GGSD]**</span> | **Arxiv'24.07** | Open Vocabulary 3D Scene Understanding via Geometry Guided Self-Distillation | [`[pdf]`](https://arxiv.org/pdf/2407.13362) | [`[code]`](https://github.com/Wang-pengfei/GGSD)
27. <span id = "3001">**[Diff2Scene]**</span> | **ECCV'24** | Open-Vocabulary 3D Semantic Segmentation with Text-to-Image Diffusion Models | [`[pdf]`](https://arxiv.org/pdf/2407.13642)
28. <span id = "3001">**[SegPoint]**</span> | **ECCV'24** | SegPoint: Segment Any Point Cloud via Large Language Model | [`[pdf]`](https://arxiv.org/pdf/2407.13761) | [`[code]`](https://heshuting555.github.io/SegPoint/)
29. <span id = "3001">**[LangOcc]**</span> | **Arxiv'24.07** | LangOcc: Self-Supervised Open Vocabulary Occupancy Estimation via Volume Rendering | [`[pdf]`](https://arxiv.org/pdf/2407.17310)
30. <span id = "3001">**[OVR]**</span> | **Arxiv'24.07** | A Dataset for Open Vocabulary Temporal Repetition Counting in Videos | [`[pdf]`](https://arxiv.org/pdf/2407.17085) | [`[code]`](https://sites.google.com/view/openvocabreps/)
31. <span id = "3001">**[SAM-CP]**</span> | **Arxiv'24.07** | SAM-CP: Marrying SAM with Composable Prompts for Versatile Segmentation | [`[pdf]`](https://arxiv.org/pdf/2407.16682) | [`[code]`](https://github.com/ucas-vg/SAM-CP)
32. <span id = "3001">**[OV-AVSS]**</span> | **ACM MM'24(Oral)** | Open-Vocabulary Audio-Visual Semantic Segmentation | [`[pdf]`](https://arxiv.org/pdf/2407.21721) | [`[code]`](https://github.com/ruohaoguo/ovavss)
33. <span id = "3001">**[Open3DRF]**</span> | **Arxiv'24.08** | Rethinking Open-Vocabulary Segmentation of Radiance Fields in 3D Space | [`[pdf]`](https://arxiv.org/pdf/2408.07416) | [`[code]`](https://github.com/hyunji12/Open3DRF/tree/main)
34. <span id = "3001">**[OVA-DETR]**</span> | **Arxiv'24.08** | OVA-DETR: Open Vocabulary Aerial Object Detection Using Image-Text Alignment and Fusion | [`[pdf]`](https://www.arxiv.org/pdf/2408.12246) | [`[code]`](https://github.com/GT-Wei/OVA-DETR)
35. <span id = "3001">**[OVAL]**</span> | **Arxiv'24.08** | Open-vocabulary Temporal Action Localization using VLMs | [`[pdf]`](https://arxiv.org/pdf/2408.17422) | [`[code]`](https://microsoft.github.io/VLM-Video-Action-Localization/)
36. <span id = "3001">**[EMPOWER]**</span> | **IROS'24** | EMPOWER: Embodied Multi-role Open-vocabulary Planning with Online Grounding and Execution | [`[pdf]`](https://arxiv.org/pdf/2408.17379) | [`[code]`](https://lab-rococo-sapienza.github.io/empower/)





## Related Survey

1. Towards Open Vocabulary Learning: A Survey | [`[pdf]`](https://arxiv.org/abs/2306.15880)
2. A Survey on Open-Vocabulary Detection and Segmentation: Past, Present, and Future | [`[pdf]`](https://arxiv.org/abs/2307.09220)

 


## Feedback

If you have any suggestions or find missing papers, please don't hesitate to contact me via [tbh3223@mail.ustc.edu.cn](mailto:tbh3223@mail.ustc.edu.cn) or [lydyc@mail.ustc.edu.cn](mailto:lydyc@mail.ustc.edu.cn).

