### Numerical filtering and mathematical optimization
|Year|Title | Published  | Code       | Method |
|-------| ----- | ----- | ------- | ------- |
|2022|Sparse deconvolution improves the resolution of live-cell super-resolution fluorescence microscopy.|[Nat. Biotechnol.]()|  |-|
|2020|Fast and accurate sCMOS noise correction for fluorescence microscopy.|[Nat. Commun.]()|  |-|
|2018|Fast, long-term, super-resolution imaging with Hessian structured illumination microscopy.|[Nat. Biotechnol.]()|  |-|
|2014|Weighted nuclear norm minimization with application to image denoising.|[CVPR]()|  |WNNM|
|2007|Image denoising by sparse 3-d transform-domain collaborative filtering.|[TIP]()|  |BM3D|
|2004|A non-local algorithm for image denoising.|[CVPR]()|  |NLM|

### Deep neural networks
#### Learn the mapping between noisy images and their clean counterparts
|Year|Title | Published  | Code       | Method |
|-------| ----- | ----- | ------- | ------- |
|2022|Fast, efficient, and accurate neuro-imaging denoising via supervised deep learning.|[Nat. Commun.]()|  |-|
|2021|Global voxel transformer networks for augmented microscopy.|[Nat. Mach. Intell.]()|  |-|
|2021|Deep learning-based point-scanning super-resolution imaging.|[Nat. Methods]()|  |-|
|2021|Three-dimensional residual channel attention networks denoise and sharpen fluorescence microscopy image volumes.|[Nat. Methods]()|  |-|
|2018|Content-aware image restoration: pushing the limits of fluorescence microscopy.|[Nat. Methods]()|  |-|
|2017|Beyond a Gaussian denoiser: residual learning of deep CNN for image denoising.|[TIP]()|  |-|
|2017|MemNet: a persistent memory network for image restoration.|[CVPR]()|  |-|

### Self-supervised methods
#### Denoise images without clean ones
| State|Year|Title | Published  | Code       | Method |
|-------|-------| ----- | ----- | ------- | ------- |
|&#9744;|2024|Self-inspired learning for denoising live-cell super-resolution microscopy.|[Nat. Methods](https://doi.org/10.1038/s41592-024-02400-9)| [Pytorch](https://github.com/WeisongZhao/SN2N) |-|
||2023|Rationalized deep learning super-resolution microscopy for sustained live imaging of rapid subcellular processes.|[Nat. Biotechnol]()|  |-|
||2023|Spatial redundancy tranformer for self-supervised fluorescence image denoising.|[Nat. Comput. Sci.]()|  |-|
||2023|Real-time denoising enables high-sensitivity fluorescene time-lapse imaging beyond the shot-noise limit.|[Nat. Biotechnol]()|  |-|
||2023|Statistically unbiased prediction enables accurate denoising of voltage imaging data.|[Nat. Methods]()|  |-|
||2023|Bio-friendly long-term subcellular dynamic recording by self-supervised image enhancement microscopy.|[Nat. Methods]()|  |-|
||2023|Zero-Shot Noise2Noise: Efficient image denoising without any data.|[CVPR](https://openaccess.thecvf.com/content/CVPR2023/papers/Mansour_Zero-Shot_Noise2Noise_Efficient_Image_Denoising_Without_Any_Data_CVPR_2023_paper.pdf)|[Pytorch](https://colab.research.google.com/drive/1i82nyizTdszyHkaHBuKPbWnTzao8HF9b)  |Generate a pair of noisy images from a single noisy image and train a small network only on this pair.|
||2022|A fast blind zero-shot denoiser.|[Nat. Mach. Intell.]( https://doi.org/10.1038/s42256-022-00547-8)|  |-|
||2021|Removing independent noise in systems neuroscience data using DeepInterpolation.|[Nat. Methods]()|  |-|
||2021|Reinforcing neuron extraction and spike inference in calcium imaging using deep self-supervised denoising.|[Nat. Methods]()|  |-|
|&#9745;|2021|Recorrupted-to-Recorrupted: unsupervised deep learning for image denoise.|[CVPR]()|  |-|
||2021|Neighbor2Neighbor: self-supervised denoising from single noisy images.|[CVPR](https://openaccess.thecvf.com/content/CVPR2021/papers/Huang_Neighbor2Neighbor_Self-Supervised_Denoising_From_Single_Noisy_Images_CVPR_2021_paper.pdf)|  |Train only on a set of single noisy images, by sub-sampling a noisy image to create a pair of noisy images.|
||2019|Noise2Void-learning denoising from single noisy images.|[CVPR]()|  |Adopt the blind-spot strategy to avoid overfitting when training a DNN to map a noisy image to itself.|
||2019|Noise2Self: blind denoising by self-supervision.|[PMLR]()|  |Adopt the blind-spot strategy to avoid overfitting when training a DNN to map a noisy image to itself.|
|&#9745;|2018|Noise2Noise: learning image restoration without clean data.|[PMLR](https://proceedings.mlr.press/v80/lehtinen18a.html)|  |Train on different noisy observations of the same clean image.|



