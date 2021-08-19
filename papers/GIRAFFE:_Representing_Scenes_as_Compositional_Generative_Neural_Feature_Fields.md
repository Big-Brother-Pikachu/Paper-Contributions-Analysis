[**GIRAFFE: Representing Scenes as Compositional Generative Neural Feature Fields**](https://github.com/Big-Brother-Pikachu/Paper-Contributions-Analysis#7-giraffe-representing-scenes-as-compositional-generative-neural-feature-fields)

# Contributions in my words

1. They proposed a controllable image synthesis pipeline called GIRAFFE, which can be trained from raw image collections.
2. They modeled scenes as compositions of objects and represented each object using a separate feature field. They used volumn and neural rendering procedure to differentially render images from this representation. An adversarial framework is used to train the whole network.
3. Experiment results demonstrate that this framework can learn disentangled scene representations and allow for controllable image synthesis. It can generate images with better quality and a higher disentanglement degree than previous work with fewer parameters.

# Contributions they claim

1. In this work, we introduce GIRAFFE, a novel method for generating scenes in a controllable and photorealistic manner while training from raw unstructured image collections. Our key insight is twofold: First, incorporating a compositional 3D scene representation directly into the generative model leads to more controllable image synthesis. Second, combining this explicit 3D representation with a neural rendering pipeline results in faster inference and more realistic images. 
2. We represent scenes as compositional generative neural feature fields. We volume render the scene to a feature image of relatively low resolution to save time and computation. A neural renderer processes these feature images and outputs the final renderings. This way, our approach achieves high-quality images and scales to real-world scenes. We find that our method allows for controllable image synthesis of single-object as well as multi-object scenes when trained on raw unstructured image collections.

# Contributions in my words modified

1. They proposed a controllable image synthesis pipeline called GIRAFFE, which can be trained from raw image collections.
2. They modeled scenes as compositions of objects and represented each object using a separate feature field. They used volumn and neural rendering procedure to differentially render images from this representation. An adversarial framework is used to train the whole network. **The intuition behind these designs are: a compositional representation can lead to more controllable image synthesis and a mixed rendering pipline can result in faster inference and more realistic images.**
3. Experiment results demonstrate that this framework can learn disentangled scene representations and allow for controllable image synthesis **in complex real-world scenes**. It can generate images with better quality and a higher disentanglement degree than previous work with fewer parameters.