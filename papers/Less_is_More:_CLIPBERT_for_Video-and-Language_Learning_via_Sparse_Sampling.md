[**Less is More: CLIPBERT for Video-and-Language Learning via Sparse Sampling**](https://github.com/Big-Brother-Pikachu/Paper-Contributions-Analysis#5-less-is-more-clipbert-for-video-and-language-learning-via-sparse-sampling)

# Contributions in my words

1. They proposed a new framework for video-and-language learning called ClipBERT, which enables end-to-end learning from video frame pixels and raw text tokens, instead of from offline-extracted single-modality features. They proposed to use sparse sampling strategy to reduce the resulting increased computation cost.
2. Experiment results show that this framework can achieve state-of-the-art performance on text-to-video retrieval task and video question answering task on several datasets.
3. Meticulous studies are conducted to analyze the impact of different components in the framework on efficiency and effectiveness.

# Contributions they claim

1. We propose CLIPBERT, a new end-to-end learning framework for video+language tasks. Experiments show that CLIPBERT achieves superior (or on par) performance than existing methods across diverse video-text tasks, where the average video length ranges from a few seconds to three minutes. 
2. Our work suggests “less is more”: the proposed end-to-end training strategy with a single or a few (less) sparsely sampled clips is often more accurate than traditional approaches that employ densely extracted video features.
3. We demonstrate that image-text pre-training benefits video-text tasks. We also provide comprehensive ablation studies to reveal the key factors that lead to the success of CLIPBERT, in hope of inspiring more future work.

# Contributions in my words modified

1. They proposed a new framework for video-and-language learning called ClipBERT, which enables end-to-end learning from video frame pixels and raw text tokens, instead of from offline-extracted single-modality features. They proposed to use sparse sampling strategy to reduce the resulting increased computation cost.
2. Experiment results show that this framework can achieve state-of-the-art performance on text-to-video retrieval task and video question answering task on several video-and-language datasets **of different video length ranges**.
3. Meticulous studies are conducted to analyze the impact of different components in the framework on efficiency and effectiveness. **They demonstrate that sparse sampling strategy and image-text pre-training benefit video-text tasks.**