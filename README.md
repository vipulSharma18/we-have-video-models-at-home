# we-have-video-models-at-home
How fast can we train a big video model?

## Roadmap:

### Data Plane:
NVIDIA DALI and fused pre-processing and training kernels to speed up training. cuVS and other tools for fast data pipelines.

### Model Plane:
Which models will train the fastest? Multimodal FLA kernels. Multimodal fused MoE kernels.

## Serving Plane:
Fast real-time inference for video models.

## References:
[1] M. Li et al., “SVDQuant: Absorbing Outliers by Low-Rank Components for 4-Bit Diffusion Models,” Mar. 03, 2025, arXiv: arXiv:2411.05007. doi: 10.48550/arXiv.2411.05007.    
[2] Y. Zhao and P. Krähenbühl, “Training a Large Video Model on a Single Machine in a Day,” Sept. 28, 2023, arXiv: arXiv:2309.16669. doi: 10.48550/arXiv.2309.16669.    
[3] M. Assran et al., “V-JEPA 2: Self-Supervised Video Models Enable Understanding, Prediction and Planning,” June 11, 2025, arXiv: arXiv:2506.09985. doi: 10.48550/arXiv.2506.09985.    
[4] “You can now train a 70b language model at home,” Answer.AI. Accessed: Sept. 14, 2025. [Online]. Available: https://www.answer.ai/posts/2024-03-06-fsdp-qlora.html    
