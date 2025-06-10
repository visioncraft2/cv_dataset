人脸视频数据集合集

# 人脸视频生成 / 表情迁移 / 唇形同步

## MEAD

Paper: MEAD: A Large-Scale Audio-Visual Dataset for Emotional Talking-Face Generation
简介：MEAD（Multi-view Emotional Audio-visual Dataset）是一个大规模的多情绪音视频数据集，涵盖 60 名说话人、8 种基本情绪（包括中性、高兴、愤怒、厌恶、恐惧、悲伤、惊讶、蔑视），每种情绪又包含多个强度等级。所有视频均为正面拍摄并具备统一的背景和灯光条件，适用于情感驱动的说话人生成、唇形合成、表情迁移、跨情绪语音驱动等研究。
下载：https://github.com/uniBruce/Mead

##HDTF (High-Definition Talking Face)
Paper: Flow-guided One-shot Talking Face Generation with a High-resolution Audio-visual Dataset
简介：HDTF 提供高分辨率、清晰人脸的视频数据，专为说话人驱动的面部动画任务设计，如视频合成、唇形同步、表情迁移等，具有更真实的口型、头部运动和面部动态。
下载：https://github.com/MRzzm/HDTF

##CelebV-HQ

Paper: CelebV-HQ: A Large-Scale Video-Based High-Quality Talking Head Dataset
简介：高质量人脸视频数据集，采集于名人采访视频，具有高清分辨率和良好的表情变化，适用于视频生成、表情迁移、唇形合成等任务。
下载：https://github.com/CelebV-HQ/CelebV-HQ

##FaceVid-1K

Paper: FaceVid-1K: A Large-Scale High-Quality Multiracial Human Face Video Dataset
简介：该数据集用于人脸视频生成，支持文本生成视频（text-to-video）和图像生成视频（image-to-video）等任务。作者建立了性能基准，并与在相关公开数据集上训练的模型进行了对比，以验证其优越性。。
下载：https://huggingface.co/datasets/jjuik2014/FaceVid-1K-Part

# 人脸识别 / 验证 / 表征学习

## VoxCeleb

Paper: VoxCeleb: Large-scale speaker verification in the wild
简介：VoxCeleb 是一个大规模的说话人识别数据集，收集自 YouTube 上的采访视频，包含同步的人脸和语音信息，适用于说话人识别、人脸识别、音视频对齐等多模态任务。
下载：http://www.robots.ox.ac.uk/~vgg/data/voxceleb/

## YouTube Faces Dataset (YTF)

Paper: YouTube Faces Database: A Database for Studying Face Recognition in Unconstrained Videos
简介：YTF 包含 1595 个名人的视频片段，提供对同一人的不同视频样本，常用于视频级别的人脸识别研究，是衡量在“非配合”环境中识别性能的标准数据集之一。
下载：https://www.cs.tau.ac.il/~wolf/ytfaces/

# 人脸伪造检测 / Deepfake 识别

## DFDC (Deepfake Detection Challenge Dataset)
Paper: The Deepfake Detection Challenge (DFDC) Dataset
简介：由 Facebook AI 组织的深度伪造检测挑战数据集，包含超过 10 万个深伪视频，涵盖多种伪造方法和拍摄环境，广泛用于训练和评估深度伪造检测模型。
下载：https://ai.facebook.com/datasets/dfdc/

## FaceForensics++
Paper: FaceForensics++: Learning to Detect Manipulated Facial Images
简介：一个用于检测人脸伪造（如DeepFake、Face2Face等）的数据集，包含多种伪造方法下的视频数据，同时保留了原始视频帧和操控后的帧，适用于伪造检测、表情编辑等任务。
下载：https://github.com/ondyari/FaceForensics

## VFHQ

Paper: VFHQ: A Large-Scale High-Quality Video Dataset for Video Face Forgery Detection
简介：高清自然人脸行为视频数据集，覆盖自然眨眼、说话、头部动作等，用于伪造检测、人脸生成与多任务建模。
下载：https://liangbinxie.github.io/projects/vfhq/

# 唇读 / 音视频同步 / 声纹建模

## AVSpeech

Paper: Looking to Listen at the Cocktail Party: A Speaker-Independent Audio-Visual Model for Speech Separation
简介：AVSpeech 是一个大型音视频语料库，包含 4700 小时以上的演讲视频片段，画面中单一清晰人脸在说话，广泛用于音视频分离、说话人同步、唇形驱动生成等研究。
下载：https://looking-to-listen.github.io/avspeech/

## LRW

Paper: Lip Reading in the Wild
简介：超过 50 万个唇读视频片段，词汇覆盖广泛，拍摄自 BBC 节目，适用于唇形识别与音视频联合建模。
下载：https://www.robots.ox.ac.uk/~vgg/data/lip_reading/lrw1.html

# 人脸关键点跟踪 / 表情估计

## 300-VW (300 Videos in the Wild)
Paper: 300-VW: A 300 Videos in the Wild Facial Landmark Tracking Dataset
简介：该数据集包含300个现实世界中拍摄的视频，提供详细的人脸关键点标注，涵盖各种照明、姿态和遮挡条件，常用于人脸跟踪和关键点检测研究。
下载：http://ibug.doc.ic.ac.uk/resources/300-VW/

# 人脸表情检测

##UvA-NEMO Smile Database
Paper: Are You Really Smiling at Me? Spontaneous versus Posed Enjoyment Smiles
简介：UvA-NEMO Smile Database 是一个大规模微笑数据集，包含来自 400 名受试者的 1240 段微笑视频（其中 597 段为自然微笑，643 段为虚假微笑）。受试者的年龄范围从 8 岁到 76 岁不等。视频为彩色 RGB，分辨率为 1920×1080 像素，帧率为每秒 50 帧，并在受控光照条件下拍摄。为了进一步进行光照和颜色归一化，视频背景中还包含了一个色彩校准板。
下载：http://www.uva-nemo.org/obtain.html
