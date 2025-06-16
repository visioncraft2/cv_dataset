# 三维可变模型

三维可变模型（3D Morphable Model, 3DMM） 是一种统计建模方法，用于表示和操控三维形状，最常应用于人脸建模。该方法由 Blanz 和 Vetter 于 1999 年提出，其核心思想是在一组三维扫描数据上通过主成分分析（PCA）提取形状与纹理的变化模式。
通过这种方式，任意新的三维人脸都可以表示为若干基底的加权组合，从而实现对人脸的逼真建模、编辑与重建，即使输入仅为二维图像。之后类似的技术也被用于人体和其他方面的模型。因为其易用性和可控性而广泛使用。
3DMM 已成为计算机视觉、图形学与生物特征识别中的基础技术之一，广泛应用于：
人脸对齐与重建


-身份识别与验证


-虚拟人脸动画与表情驱动


-基于图像的人脸合成与增强


其结构紧凑、表达能力强，是连接三维几何世界与图像空间的关键桥梁。
该类模型的优势在于易于控制生成过程，方便理解，存在较少的生成错误。但缺点也显而易见，生成的对象当中缺乏多样性。比如人脸可变模型难以生成日常生活中常见的额外元素，例如头发，胡须，眼镜等类似物体，因此生成结果整体上看比较单一。

以下是一些常见模型的合集，通常包含有已经生成的三维可变模型。其中部分例子还包含生成过程的代码。


## 基于人脸的3D可变模型（3D face morphable model）:

Basel Face Model 2009: https://faces.dmi.unibas.ch/bfm/bfm2017.html

Basel Face Model 2019: https://faces.dmi.unibas.ch/bfm/bfm2019.html

Large Scale 3D Morphable Model: https://github.com/menpo/lsfm

Multilinear Wavelets: A Statistical Shape Space for Human Faces: http://facepage.gforge.inria.fr/

Surrey Face Model https://cvssp.org/faceweb/3dmm/facemodels/

FLAME: Articulated Expressive Head Model: http://flame.is.tue.mpg.de/

Liverpool-York Head Model: https://www-users.york.ac.uk/~np7/research/LYHM

CoMA: Convolutional Mesh Autoencoder: http://coma.is.tue.mpg.de/

ICT-FaceKIT - ICT Face Model: https://github.com/VGL-Group/ICT-FaceKit

Albedo Morphable Model: https://github.com/waps101/AlbedoMM

FaceVerse: a Fine-grained and Detail-controllable 3D Face Morphable Model from a Hybrid Dataset: https://www.liuyebin.com/faceverse/faceverse.html

INFACE: Large-Scale 3D Infant Face Model https://github.com/tillns/INFACE

## 基于人体的3D可变模型:

SMPL: A skinned Multi-Person Linear Model: http://smpl.is.tue.mpg.de/

SMPL-X: Expressive Body Model - SMPL with articulated hands and expressive face: https://smpl-x.is.tue.mpg.de/

MPII Human Shape Model: http://humanshape.mpi-inf.mpg.de/

GHUM & GHUML: Generative 3D Human Shape and Articulated Pose Models: https://github.com/google-research/google-research/tree/master/ghum

STAR: Sparse Articulated Human Body Model: http://star.is.tue.mpg.de/



## 其他相似模型：

The York Ear Model: https://www-users.york.ac.uk/~np7/research/YEM/

SMAL A Skinned Multi-Animal Linear Model of 3D Animal Shape http://smal.is.tue.mpg.de/

CAFM: A 3D Morphable Model for Animals https://github.com/sunyifan2017/CAFM-A-3D-Morphable-Model-for-Animals

CAPE: Clothed Auto Person Encoding https://cape.is.tue.mpg.de/
