#### Fluorescence microscopy
| State|Year|Title | Published  | Code       | Methods |PSF|
|-------|-------| ----- | ----- | ------- | ------- |------- |
||2025| Deep learning-based aberration compensation improves contrast and resolution in fluorescence microscopy| [Nat. Commun.](https://www.nature.com/articles/s41467-024-55267-x)  |[Tensorflow](https://github.com/CSBDeep/CSBDeep)  |1.Introduces synthetic aberrations to images acquired on the shallow side of image stacks, making them resemble those acquired deeper into the volume. 2. Train neural networks to reverse the effect of these aberrations.||
||2024| **Zero-shot learning** enables instant denoising and super-resolution in optical fluorescence microscopy| [Nat. Commun.](https://www-nature-com.accproxy.lib.szu.edu.cn/articles/s41467-024-48575-9#Sec30)  |[Tensorflow](https://github.com/TristaZeng/ZS-DeconvNet)  | |We used experimentally acquired or simulated PSFs (with PSF Generator Fiji plugin licensed by EPFL) that are corresponding to the imaging configurations.|
|&#9745;|2022|Incorporating the image formation process into deep learning improves network performance|[Nat. Methods](https://doi.org/10.1038/s41592-022-01652-7)|[Tensorflow](https://github.com/MeatyPlus/Richardson-Lucy-Net)|RLN combines the traditional Richardson-Lucy iteration with a fully convolutional network structure, establishing a connection to the image formation process and thereby improving network performance.||
#### Single-molecule localization microscopy
| State|Year|Title | Published  | Code       | Methods |PSF|
|-------|-------| ----- | ----- | ------- | ------- |------- |
||2023|Field-dependent deep learning enables high-throughput whole-cell 3D super-resolution imaging|[Nat. Methods]( https://doi.org/10.1038/s41592-023-01775-5)|[Pytorch](https://github.com/Li-Lab-SUSTech/FD-DeepLoc)|1.We present FD-DeepLoc, which combines both fast spatially variant PSF modeling and deep-learning-based single-molecule localization to achieve 3D super resolution over a large FOV and deep of field. 2.We introduce a small aberration variation to the trained PSF models, which **makes the network more robust when the theoretical and experimental PSF models are mismatched**.|Vectorial PSF|


