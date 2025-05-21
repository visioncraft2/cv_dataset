​3D场景理解（3D scene understanding）数据集总结

可用于3D场景理解的数据集

# ScanNet
## Paper: ScanNet: Richly-annotated 3D Reconstructions of Indoor Scenes

## 简介：
ScanNet 是一个大规模的 RGB-D 视频数据集，包含超过 1500 个室内扫描，总计 250 万个视角，提供三维相机参数、表面重建结果以及实例级语义分割标注。它被广泛用于 3D 场景理解任务，包括三维物体分类、语义体素标注与 CAD 模型匹配，是构建室内单房间任务基准的核心资源之一。
## 下载: https://github.com/ScanNet/ScanNet


# 3RScan
## Paper: 3RScan: A 3D RGB-D Dataset for Reconstructing and Relocalizing in Changing Indoor Environments

## 简介：
3RScan 是一个针对动态变化环境设计的 RGB-D 数据集，提供多次扫描的相同室内空间，支持三维重建、物体重定位和变化检测等任务。它支持跨时间点的语义一致性和实例匹配，适用于长时序场景理解研究。
## 下载: https://github.com/WaldJohannaU/3RScan
 

# ARKitScenes
Paper: ARKitScenes: A Diverse Real-World Dataset for 3D Indoor Scene Understanding Using Mobile RGB-D Data

## 简介：
ARKitScenes 是由 iOS ARKit 采集的多样化室内 RGB-D 场景数据集，强调移动设备上的数据采集与三维场景重建。数据包括场景重建、相机轨迹和物体注释，覆盖多种真实场景，适合评估在消费者设备上部署的 3D-VLM 能力。

## 下载: https://github.com/apple/ARKitScenes


# HM3D
## Paper: Habitat-Matterport 3D Dataset (HM3D): 1000 Large-Scale 3D Environments for Embodied AI

## 简介：
HM3D 是目前最大规模的高质量室内三维场景数据集之一，包含超过 1000 个真实建筑环境的高分辨率扫描，包括住宅、商业与公共空间，适用于跨房间场景理解、多房间导航和 embodied AI 研究。LSceneLLM 所引入的 XR-Scene 基准任务就基于此数据集构建，扩展了当前大场景理解的评测范围。

## 下载: https://github.com/facebookresearch/habitat-matterport3d-dataset?tab=readme-ov-file

以下是构建在上文提到的基础数据集上的任务型 3D数据集，它们围绕特定任务（如问答、目标定位、描述等）设计，广泛用于评估 3D Vision-Language Models（3D-VLMs）的性能。


ScanQA
Paper: ScanQA: 3D Question Answering for Spatial Scene Understanding
简介：
ScanQA 是一个建立在 ScanNet 上的 3D 场景问答 benchmark，包含超过 20,000 个基于场景的问答对，任务目标是让模型结合点云与自然语言问题生成合理的回答。ScanQA 的问题聚焦于室内空间关系、物体属性和位置描述，是最早推动 3D-VLM QA 任务的核心基准之一。
下载:https://github.com/ATR-DBI/ScanQA/blob/main/docs/dataset.md


ScanRefer
Paper: ScanRefer: 3D Object Localization in RGB-D Scans Using Natural Language
简介：
 ScanRefer 是一个基于 ScanNet 构建的 3D 目标定位任务 benchmark，提供超过 50,000 条自然语言描述，要求模型在 3D 点云中定位被描述的目标物体。它融合了自然语言理解、空间定位和三维几何感知，是评估 grounding 能力的关键数据集。
 下载: https://github.com/daveredrum/ScanRefer


Nr3D
Paper: ReferIt3D: Neural Listeners for Fine-Grained 3D Object Identification in Real-World Scenes
 简介：
 Nr3D 是从 ReferIt3D 项目中分离出的子集，专注于单目标、多候选对象间的语言理解与区分任务。它从真实室内环境（如 ScanNet）采样，强调精细语义区别的建模能力，是测试 referential language 理解性能的重要数据集。
 下载: https://github.com/referit3d/referit3d

​
#数据集 #3D
