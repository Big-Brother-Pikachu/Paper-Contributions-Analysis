[**Knowledge Evolution in Neural Networks**](https://github.com/Big-Brother-Pikachu/Paper-Contributions-Analysis#9-knowledge-evolution-in-neural-networks)

# Contributions in my words

1. They proposed Knowledge Evolution(KE) approach designed for learning without the burden for data collection. They split a dense network into fit and reset hypotheses which are trained with different training regime.
2. Experiment results demonstrate the effectiveness of KE on classification and metric learning tasks when trained with small datasets. Ablation studies verify the intutions behind the design.

# Contributions they claim

1. A training approach, knowledge evolution (KE), that boosts the performance of deep networks on relatively small datasets (Sec. 3.1). We evaluate KE using both classification (Sec. 4.1) and metric learning (Sec. 4.2) tasks. KE achieves SOTA results.
2. A network splitting technique, KELS, which learns a slim network automatically while training a deep network (Sec. 3.2). KELS supports a large spectrum of CNNs and introduces neither hyperparameters nor regularization terms. Our ablation studies (Sec. 5) demonstrate how KELS reduces inference cost significantly.

# Contributions in my words modified

1. They proposed Knowledge Evolution(KE) approach designed for learning without the burden for data collection. They split a dense network into fit and reset hypotheses which are trained with different training regime.
2. **They proposed a network splitting technique, kernel-level convolutional-aware splitting(KELS), to reduce inference cost.**
3. Experiment results demonstrate the effectiveness of KE on classification and metric learning tasks when trained with small datasets. Ablation studies verify the intutions behind the design **and the effect of KELS on reducing inference cost**.