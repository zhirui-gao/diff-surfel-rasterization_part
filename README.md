# Differential Surfel Rasterization with an additional attribute (part label)
This is the rasterization engine for the paper "Self-supervised Learning of Hybrid Part-aware 3D Representations
of 2D Gaussians and Superquadrics".  It is modified from the original [Differential Surfel Rasterization](https://github.com/hbb1/diff-surfel-rasterization/tree/e0ed0207b3e0669960cfad70852200a4a5847f61).  Differential Part Surfel Rasterization can support each Gaussian with an additional part attribute, and the part-map can be rendered directly. (Given the time elapsed, I am not sure it works for part attribute optimization via given part-label maps. In our work, we only render part map.)

If you can make use of it in your own research, please be so kind to cite us.

## BibTeX
```
@misc{gao2025selfsupervisedlearninghybridpartaware,
      title={Self-supervised Learning of Hybrid Part-aware 3D Representation of 2D Gaussians and Superquadrics}, 
      author={Zhirui Gao and Renjiao Yi and Yuhang Huang and Wei Chen and Chenyang Zhu and Kai Xu},
      year={2025},
      eprint={2408.10789},
      archivePrefix={arXiv},
      primaryClass={cs.CV},
      url={https://arxiv.org/abs/2408.10789}, 
}
```
