[**NeRF: Representing Scenes as Neural Radiance Fields for View Synthesis**](https://github.com/Big-Brother-Pikachu/Paper-Contributions-Analysis#6-nerf-representing-scenes-as-neural-radiance-fields-for-view-synthesis)

# Contributions in my words

1. They proposed a new scene representation called neural radiance field scene representation, which maps each location and viewing direction to volume density and directional emitted color. They used a differential volumn rendering technology to synthesis images from this scene representation.
2. They used positional encoding and hierarchical sampling to improve the quality and this scene representation can be learned via backpropagation.
3. Experiment results demonstrate that this method outperforms prior work quantitatively and qualitatively with less computation cost. Ablation studies verify the design choices of this method.

# Contributions they claim

1. An approach for representing continuous scenes with complex geometry and materials as 5D neural radiance fields, parameterized as basic MLP networks.
2. A differentiable rendering procedure based on classical volume rendering techniques, which we use to optimize these representations from standard RGB images. This includes a hierarchical sampling strategy to allocate the MLP's capacity towards space with visible scene content.
3. A positional encoding to map each input 5D coordinate into a higher dimensional space, which enables us to successfully optimize neural radiance fields to represent high-frequency scene content.

# Contributions in my words modified

1. They proposed a new **continuous** scene representation called neural radiance field scene representation, which **is parameterized as basic MLP networks** and maps each location and viewing direction to volume density and directional emitted color. They used a differential volumn rendering technology to synthesis images from this scene representation.
2. They used positional encoding and hierarchical sampling to improve the quality and this scene representation can be learned via backpropagation **from standard RGB images**.
3. Experiment results demonstrate that this method outperforms prior work quantitatively and qualitatively with less computation cost. Ablation studies verify the design choices of this method.