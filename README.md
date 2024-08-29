# ReconX: Reconstruct Any Scene from Sparse Views with Video Diffusion Model

[**Paper**](https://arxiv.org/abs/2403.09625) | [**Project Page**](https://liuff19.github.io/ReconX/) | [**Video**](https://liuff19.github.io/ReconX/)

Official implementation of ReconX: Reconstruct Any Scene from Sparse Views with Video Diffusion Model

[Fangfu Liu](https://liuff19.github.io/), [Wenqiang Sun](https://github.com/wenqsun), Hanyang Wang, Yikai Wang, Haowen Sun, Junliang Ye, Jun Zhang, Yueqi Duan.


<p align="center"> All Code will be released soon... 🏗️ 🚧 🔨</p>

Abstract: *Advancements in 3D scene reconstruction have transformed 2D images from the real world into 3D models, producing realistic 3D results from hundreds of input photos. Despite great success in dense-view reconstruction scenarios, rendering a detailed scene from insufficient captured views is still an ill-posed optimization problem, often resulting in artifacts and distortions in unseen areas. In this paper, we propose ReconX, a novel 3D scene reconstruction paradigm that reframes the ambiguous reconstruction challenge as a temporal generation task. The key insight is to unleash the strong generative prior of large pre-trained video diffusion models for sparse-view reconstruction. However, 3D view consistency struggles to be accurately preserved in directly generated video frames from pre-trained models. To address this, given limited input views, the proposed ReconX first constructs a global point cloud and encodes it into a contextual space as the 3D structure condition. Guided by the condition, the video diffusion model then synthesizes video frames that are both detail-preserved and exhibit a high degree of 3D consistency, ensuring the coherence of the scene from various perspectives. Finally, we recover the 3D scene from the generated video through a confidence-aware 3D Gaussian Splatting optimization scheme. Extensive experiments on various real-world datasets show the superiority of our ReconX over state-of-the-art methods in terms of quality and generalizability.*

<p align="center">
    <img src="assets/teaser-3d.png">
</p>


## Subject-Driven 3D Content Generation

Visual results of Make-Your-3D on different subjects with customized text inputs. The multi-view results demonstrate that our method can generate 3D assets with high-fidelity, 3D consistency, subject preservation, and faithfulness to the text prompts.
<p align="center">
    <img src="assets/More-results.png">
</p>






## BibTeX

```bibtex
@misc{liu2024makeyour3d,
      title={Make-Your-3D: Fast and Consistent Subject-Driven 3D Content Generation}, 
      author={Fangfu Liu and Hanyang Wang and Weiliang Chen and Haowen Sun and Yueqi Duan},
      year={2024},
      eprint={2403.09625},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}
```
