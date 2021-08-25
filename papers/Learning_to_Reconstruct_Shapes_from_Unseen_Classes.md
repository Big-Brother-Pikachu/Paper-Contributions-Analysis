[**Learning to Reconstruct Shapes from Unseen Classes**](https://github.com/Big-Brother-Pikachu/Paper-Contributions-Analysis#10-learning-to-reconstruct-shapes-from-unseen-classes)

# Contributions in my words

1. They proposed a framework to reconstruct 3D shapes from single 2D images. They divide the framework into three learnable modules and claim the generalization ability of each module, which enables the framework to reconstruct shapes from unseen classes. Spherical maps and three geometric projection processes are used to regularize the framework.
2. Experiment results demonstrate the effectiveness of this method and verify the generalization ability of each module by comparing several baselines.

# Contributions they claim

1. We emphasize the task of generalizable single-image 3D shape reconstruction. 
2. We propose to disentangle geometric projections from shape reconstruction, and include spherical maps with differentiable, deterministic projections in an integrated neural model. 
3. We demonstrate that the resulting model achieves state-of-the-art performance on single-image 3D shape reconstruction for objects within and outside training classes.

# Contributions in my words modified

1. They proposed a framework to reconstruct 3D shapes from single 2D images. They **disentangled geometric projections from shape reconstruction** and divided the framework into three learnable **modularized** modules, which enables the framework to reconstruct shapes from unseen classes. Spherical maps and differentiable geometric projections are used to regularize the framework.
2. Experiment results demonstrate the effectiveness of this method **on objects within and outside training classes** and verify the generalization ability of each module by comparing several baselines.