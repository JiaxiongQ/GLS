# GLS

**GLS: Geometry-aware 3D Language Gaussian Splatting**

[![arXiv](https://img.shields.io/badge/arXiv-2411.17949-b31b1b.svg)](https://arxiv.org/pdf/2411.18066)

![alt text](assets/pipeline.png)

**GLS** extend indoor surface reconstruction and open-vocabulary segmentation by proposed novel strategy, to support **embodied intelligence** (e.g., navigation and manipulation). 
>Recently, 3D Gaussian Splatting (3DGS) has achieved significant performance on indoor surface reconstruction and open-vocabulary segmentation. This paper presents GLS, a unified framework of surface reconstruction and open-vocabulary segmentation based on 3DGS. GLS extends two fields by exploring the correlation between them. For indoor surface reconstruction, we introduce surface normal prior as a geometric cue to guide the rendered normal, and use the normal error to optimize the rendered depth. For open-vocabulary segmentation, we employ 2D CLIP features to guide instance features and utilize DEVA masks to enhance their view consistency. Extensive experiments demonstrate the effectiveness of jointly optimizing surface reconstruction and open-vocabulary segmentation, where GLS surpasses state-of-the-art approaches of each task on MuSHRoom, ScanNet++, and LERF-OVS datasets.

## Update

- [ ] Inference demo released.
- [ ] Training code released.

## Demo
We deveop a visulization tool based on [nerfview](https://github.com/hangg7/nerfview), for exploring the potential application on Embod
**[Application]** - Robot navigation.
![alt text](assets/demo_nav1.png)

## Citation

```bibtex
@article{qiu2024gls,
  title={GLS: Geometry-aware 3D Language Gaussian Splatting},
  author={Qiu, Jiaxiong and Liu, Liu and Su, Zhizhong and Lin, Tianwei},
  journal={arXiv preprint arXiv:2411.18066},
  year={2024}
}
```