---
layout: page
title: "quantitative evaluation"
permalink: /qcmp/
---

## Quantitative comparison with more methods (on object-shaped holes)


| Methods | L1 loss | PSNR | SSIM|
| ------ | ------ | ------ | ------ |
| FFRN[1] | .0289 | 25.66 |.8787|
| ContextAttention[2] | .0300 |23.73 |.8649|
|FGAware[3] | .0244| 26.32 |.8811|
| PConv[4]  |.0212 |27.57 |.8876|
| PENNet[5] |.0236 |26.11 |.8845|
| Ours* |.0194| 28.20 |.8985|
| Ours |.0205 |27.67| .8949|


[1] Guo, Z., Chen, Z., Yu, T., Chen, J., Liu, S.: Progressive image inpainting with full-resolution residual network. In: Proceedings of the 27th ACM International Conference on Multimedia. ACM (2019)

[2] Yu, J., Lin, Z., Yang, J., Shen, X., Lu, X., Huang, T.S.: Generative image inpainting with contextual attention. In: IEEE Conference on Computer Vision and Pattern Recognition. pp. 5505–5514 (2018)

[3] Xiong, W., Yu, J., Lin, Z., Yang, J., Lu, X., Barnes, C., Luo, J.: Foreground-aware image inpainting. In: IEEE Conference on Computer Vision and Pattern Recognition (2019)

[4] Liu, G., Reda, F.A., Shih, K.J., Wang, T.C., Tao, A., Catanzaro, B.: Image inpainting for irregular holes using partial convolutions. In: European Conference on Computer Vision (2018)

[5] Zeng, Y., Fu, J., Chao, H., Guo, B.: Learning pyramid-context encoder network for high-quality image inpainting. In: IEEE Conference on Computer Vision and Pattern Recognition. pp. 1486–1494 (2019)
