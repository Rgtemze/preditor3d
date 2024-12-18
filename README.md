# PrEditor3D: Fast and Precise 3D Shape Editing

![preditor3d teaser](./assets/teaser.svg)


[PrEditor3D: Fast and Precise 3D Shape Editing](https://arxiv.org/abs/2412.06592) <br>
Ziya Erkoç, Can Gümeli, Chaoyang Wang, Matthias Niessner, Angela Dai, Peter Wonka, Hsin-Ying Lee, Peiye Zhuang

## Abstract

We propose a training-free approach to 3D editing that enables the editing of a single shape within a few minutes. The edited 3D mesh aligns well with the prompts, and remains identical for regions that are not intended to be altered. To this end, we first project the 3D object onto 4-view images and perform synchronized multi-view image editing along with user-guided text prompts and user-provided rough masks. However, the targeted regions to be edited are ambiguous due to projection from 3D to 2D. To ensure precise editing only in intended regions, we develop a 3D segmentation pipeline that detects edited areas in 3D space, followed by a merging algorithm to seamlessly integrate edited 3D regions with the original input. Extensive experiments demonstrate the superiority of our method over previous approaches, enabling fast, high-quality editing while preserving unintended regions.

![preditor3d overview](./assets/overview.svg)
