# A Multi-Expert Deep Learning Framework with LLM-Guided Arbitration for Multimodal Histopathology Prediction

- #### Authors</ins>: Shyam Sundar Debsarkar \& Surya Prasath 
- #### Journal : Computerized Medical Imaging and Graphics
- #### Doi: https://doi.org/10.1016/j.compmedimag.2026.102704


## Abstract

Recent advances in deep learning have significantly improved the accuracy of computational pathology; however conventional model ensembling strategies often lack adaptability and interpretability hindering the clinical adaptability. While multiple artificial intelligence (AI) expert models can provide complementary perspectives, simply aggregating their outputs is often insufficient for handling inter-model disagreement and delivering interpretable decisions. To address these challenges, we propose a novel multi-expert framework that integrates diverse vision-based predictors and a clinical feature-based model, with a large language model (LLM) acting as an intelligent arbitrator. By leveraging the contextual reasoning and explanation capabilities of LLMs, our architecture dynamically synthesizes insights from both imaging and clinical data, resolving model conflicts, and providing transparent, rational decisions. We validate our approach on two cancer histopathology datasets, namely the HMU-GC-HE-30K which is a gastric cancer dataset containing pathology images only, and the BCNB which is a breast cancer biopsy dataset that is multimodal - contains pathology imaging and clinical information. Our proposed multi-expert, LLM arbitrated framework (MELLMA) outperforms convolutional neural networks (CNNs), and transformers, which are currently the de facto and state-of-the-art classification ensemble models, with better overall results. We test different LLMs as arbitrators, namely LLaMA, GPT variants, and Mistral. Further, our proposed framework outperforms strong single-agent CNN/ViT baselines on the datasets, and ablations show that learned per-agent trust materially improves the arbitrator’s decisions without altering prompts or data. These experimental results demonstrate that LLM-guided arbitration consistently provides more robust and explainable performance than individual models, conventional ensembling with majority vote, uniform average, and meta-learners. The results obtained highlight the promise of LLM-driven arbitration for building transparent and extensible AI systems in digital pathology.

## Dataset Guide
### Gastric Cancer Histopathology Tissue Image Dataset (GCHTID):-
**HMU-GC-HE-30K** : [Download Link](https://doi.org/10.6084/m9.figshare.25954813)

### Early Breast Cancer Core-Needle Biopsy WSI (BCNB):-
**BCNB**: [Download Link](https://bupt-ai-cz.github.io/BCNB/)
