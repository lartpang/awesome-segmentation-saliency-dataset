# Another Awesome Dataset List ![Badge](https://img.shields.io/badge/-As%20awesome%20as%20you%20think!-red?style=flat-square)

| [![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT) | ![GitHub last commit](https://img.shields.io/github/last-commit/lartpang/awesome-segmentation-saliency-dataset?style=flat-square) | ![GitHub issues](https://img.shields.io/github/issues/lartpang/awesome-segmentation-saliency-dataset?style=flat-square) | ![GitHub stars](https://img.shields.io/github/stars/lartpang/awesome-segmentation-saliency-dataset?style=flat-square) |
| ---------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------- |

> [!note]
> - 💖 Some great tools can be found at [resource websites](#resource-websites).
> - 😄 Please **cite the related paper** if you **use their dataset**
> - 🌜 I list some other datasets in the issue [https://github.com/lartpang/awesome-segmentation-saliency-dataset/issues/15](https://github.com/lartpang/awesome-segmentation-saliency-dataset/issues/15). I hope it works for you.

- [Another Awesome Dataset List ](#another-awesome-dataset-list-)
  - [Saliency](#saliency)
    - [RGB Saliency](#rgb-saliency)
      - [MSRA(MSRA10K/MSRA-B)](#msramsra10kmsra-b)
      - [SED1/2](#sed12)
      - [ASD(MSRA1000/MSRA1K)](#asdmsra1000msra1k)
      - [DUT-OMRON](#dut-omron)
      - [DUTS](#duts)
      - [DUTS-MM/DUTS-MQ](#duts-mmduts-mq)
      - [SOC (Salient Objects in Clutter)](#soc-salient-objects-in-clutter)
      - [HKU-IS](#hku-is)
      - [SOD (Salient Object Dataset)](#sod-salient-object-dataset)
      - [Infrared](#infrared)
      - [ImgSal](#imgsal)
      - [ECSSD/CSSD](#ecssdcssd)
      - [THUR15K](#thur15k)
      - [Bruce-A](#bruce-a)
      - [Judd-A](#judd-a)
      - [PASCAL-S](#pascal-s)
      - [UCSB](#ucsb)
      - [OSIE](#osie)
      - [ACSD](#acsd)
      - [WXSOD](#wxsod)
    - [RGB-D Saliency](#rgb-d-saliency)
      - [SIP](#sip)
      - [NLPR/RGBD1000](#nlprrgbd1000)
      - [NJU400/2000](#nju4002000)
      - [STEREO/SSB](#stereossb)
      - [LFSD](#lfsd)
      - [RGBD135/DES](#rgbd135des)
      - [DUT-RGBD/DUTLF-Depth](#dut-rgbddutlf-depth)
      - [SSD/SSD100](#ssdssd100)
      - [ReDWeb-S](#redweb-s)
      - [COME15K](#come15k)
    - [RGB-T Saliency](#rgb-t-saliency)
      - [UVT2000](#uvt2000)
      - [un-VT821/1000/5000](#un-vt82110005000)
      - [VT723](#vt723)
      - [VT5000](#vt5000)
      - [VT1000](#vt1000)
      - [VT821](#vt821)
    - [Dichotomous Image Segmentation](#dichotomous-image-segmentation)
      - [DIS5K](#dis5k)
    - [High-Resolution Saliency](#high-resolution-saliency)
      - [HRSOD/DAVIS-S](#hrsoddavis-s)
    - [Co-Saliency](#co-saliency)
      - [ImagePair](#imagepair)
      - [MSRC](#msrc)
      - [WICOS](#wicos)
      - [iCoSeg](#icoseg)
      - [CoCA: Common Category Aggregation (CoCA) dataset](#coca-common-category-aggregation-coca-dataset)
      - [CoSal2015](#cosal2015)
      - [CoSOD3k](#cosod3k)
      - [RGBDCosal150](#rgbdcosal150)
      - [RGBDCoseg183](#rgbdcoseg183)
      - [INCT2016](#inct2016)
    - [Video Saliency](#video-saliency)
      - [RSD(PKU-RSD)](#rsdpku-rsd)
      - [STC](#stc)
    - [Reasoning SOD](#reasoning-sod)
      - [OC-SODBench](#oc-sodbench)
    - [Other](#other)
      - [XPIE](#xpie)
      - [SOS](#sos)
      - [MSO](#mso)
      - [ILSO-1K/2K](#ilso-1k2k)
      - [HS-SOD](#hs-sod)
      - [KAIST Salient Pedestrian Dataset](#kaist-salient-pedestrian-dataset)
      - [Grayscale-Thermal Foreground Detection Dataset](#grayscale-thermal-foreground-detection-dataset)
  - [COD (Camouflaged/Concealed Object Detection)](#cod-camouflagedconcealed-object-detection)
    - [RGB Image COD](#rgb-image-cod)
      - [NC4K](#nc4k)
      - [COD10K](#cod10k)
      - [CAMO](#camo)
      - [CHAMELEON](#chameleon)
      - [CPD1K: Camouflaged People Dataset](#cpd1k-camouflaged-people-dataset)
      - [CPD-UAV](#cpd-uav)
    - [RGB Video COD](#rgb-video-cod)
      - [MoCA-Mask](#moca-mask)
      - [CAD (Camouflaged Animation Dataset)](#cad-camouflaged-animation-dataset)
      - [YUV20K](#yuv20k)
      - [CAMotion](#camotion)
    - [RGB-T Image COD](#rgb-t-image-cod)
      - [Camo-M3FD](#camo-m3fd)
    - [RGB-D Image COD](#rgb-d-image-cod)
      - [ACOD-12K](#acod-12k)
      - [CODD](#codd)
    - [Terahertz Image COS/COD](#terahertz-image-coscod)
      - [Active Terahertz Imaging Datasets](#active-terahertz-imaging-datasets)
    - [Open-Vocabulary Camouflaged Object Segmentation](#open-vocabulary-camouflaged-object-segmentation)
      - [OVCamo](#ovcamo)
  - [DBD (Defocus Blur Detection)](#dbd-defocus-blur-detection)
    - [CUHK](#cuhk)
    - [DUT](#dut)
      - [Real-V1](#real-v1)
      - [Real-V2](#real-v2)
      - [Simulated Dataset](#simulated-dataset)
    - [CTCUG](#ctcug)
    - [EBD](#ebd)
  - [Industrial Scene](#industrial-scene)
    - [Crack Detection](#crack-detection)
      - [T-CRACK \& C-CRACK](#t-crack--c-crack)
    - [Surface Defect Detection](#surface-defect-detection)
      - [SD-saliency-900](#sd-saliency-900)
    - [AD (Anomaly Detection)](#ad-anomaly-detection)
      - [MVTec AD](#mvtec-ad)
      - [MPDD](#mpdd)
  - [Medical Scene](#medical-scene)
    - [Trichomonas Vaginalis Segmentation](#trichomonas-vaginalis-segmentation)
      - [TVMI3K](#tvmi3k)
    - [Vessel Segmentation](#vessel-segmentation)
      - [XCAD](#xcad)
  - [Segmentation](#segmentation)
    - [VOS (Video Object Segmentation)](#vos-video-object-segmentation)
      - [DAVIS](#davis)
      - [TAO-VOS](#tao-vos)
      - [OVOS](#ovos)
    - [Image Segmentation](#image-segmentation)
      - [aNYU](#anyu)
      - [Supervisely Portrait Dataset](#supervisely-portrait-dataset)
      - [Clothing Parsing](#clothing-parsing)
      - [HumanParsing-Dataset](#humanparsing-dataset)
      - [Look into Person (LIP)](#look-into-person-lip)
      - [Taobao Commodity Dataset (TCD)](#taobao-commodity-dataset-tcd)
      - [Object Extraction Dataset](#object-extraction-dataset)
      - [Clothing Co-Parsing (CCP) Dataset](#clothing-co-parsing-ccp-dataset)
      - [People segmentation dataset](#people-segmentation-dataset)
  - [Matting](#matting)
    - [alphamatting.com](#alphamattingcom)
    - [Composition-1k: Deep Image Matting](#composition-1k-deep-image-matting)
    - [Semantic Human Matting](#semantic-human-matting)
    - [Matting-Human-Datasets](#matting-human-datasets)
    - [PFCN](#pfcn)
    - [Deep Automatic Portrait Matting](#deep-automatic-portrait-matting)
  - [Other](#other-1)
    - [Large-scale Fashion (DeepFashion) Database](#large-scale-fashion-deepfashion-database)
    - [Tencent ML-Images](#tencent-ml-images)
  - [need your help...](#need-your-help)
  - [Reference](#reference)
    - [Survey](#survey)
    - [Project](#project)
  - [More](#more)
    - [Similiar Projects](#similiar-projects)
    - [Research Institutes](#research-institutes)
    - [Resource Websites](#resource-websites)

## Saliency

### RGB Saliency

#### MSRA(MSRA10K/MSRA-B)

* Paper: [Learningto detect a salient object](http://mmlab.ie.cuhk.edu.hk/2007/CVPR07_detect.pdf)
* Home: Nankai University Media Computing Laboratory: [https://mmcheng.net/zh/msra10k/](https://mmcheng.net/zh/msra10k/)
* Download:
  + MSRA10K(formally named as THUS10000; [195MB](http://mftp.mmcheng.net/Data/MSRA10K_Imgs_GT.zip): images + binary masks):
    - Pixel accurate salient object labeling for **10000 images** from MSRA dataset.
    - Please cite our paper [https://mmcheng.net/SalObj/] if you use it.
    - Saliency maps and salient object region segmentation for other 20+ alternative methods are also available ([Baidu Yun](http://pan.baidu.com/s/1dEaQqlF#path=%252FShare%252FSalObjRes)).
  + MSRA-B ([111MB](http://mftp.mmcheng.net/Data/MSRA-B.zip): images + binary masks):
    - Pixel accurate salient object labeling for **5000 images** from MSRA-B dataset.
    - Please cite the corresponding paper [https://mmcheng.net/drfi/] if you use it.

We study visual attention by detecting salient objects in input images. We formulate salient object detection as an image segmentation problem, where we separate salient objects from image background. We propose a series of novel features, including multi-scale contrast, center-surround histograms and color space distributions, to describe salient objects locally, regionally and globally. Conditional random fields are learned to efficiently combine these features for salient object detection. We also built an image database containing tens of thousands of fully labeled images tagged by multiple users. To the best of our knowledge, it is the first large-scale image database for quantitative evaluation of visual attention algorithms. We validated our method on this image database, which is publicly available in this paper.

People may have different opinions about salient objects in images. To solve the problem of "what salient objects may look like in a given image", we conduct a voting strategy by labeling "ground truth" salient objects in multiple users' images. In this paper, we focus on the case of a single salient object in an image. Salient object representation. Typically, we represent a given object as a binary mask $A={a_x}$ in a given image I. For each pixel x, $a_x∈{1, 0}$ is a binary label to indicate whether a pixel belongs to a salient object. **For labeling and evaluation, we ask the user to draw a rectangle to specify a salient object. Our detection algorithm also outputs a rectangle.**

Image sources. We collected a very large image database of 130,099 high-quality images from various sources, mainly from image forums and image search engines. We then manually selected more than 60,000 images, each of which contained a salient object or a unique foreground object. We further selected 20,840 images for labeling. During the selection process, we excluded any images containing very large salient objects, allowing for a more accurate assessment of the performance of the detection.

Labeling consistency. For each image to be labeled, we ask the user to draw a rectangle that encloses the largest object in the image according to his/her own understanding. Rectangles labeled by different users are usually not the same. To reduce labeling inconsistency, we select a "real" label from rectangles drawn by multiple users.

<details>
<summary>中文介绍</summary>

我们通过检测输入图像中的显著对象来研究视觉注意力. 我们将显著对象检测表示为图像分割问题, 我们将显著对象与图像背景分开. 我们提出了一系列新颖的特征, 包括多尺度对比度, 中心环绕直方图和颜色空间分布, 以在本地, 区域和全局描述显著对象. 学习条件随机场以有效地组合这些特征以用于显著对象检测. 我们还构建了一个**包含由多个用户标记的数以万计的完全标记图像的图像数据库**. 据我们所知, 它是第一个用于视觉注意算法定量评估的大型图像数据库. 我们在此图像数据库上验证了我们的方法, 该数据库在本文中是公开的.

人们可能对图像中的显著对象有不同的看法. 为了解决"给定图像中可能是什么样的显著对象"的问题, 我们通过在多个用户的图像中标记"真值"显著对象来进行投票策略. 在本文中, 我们关注图像中单个显著对象的情况. 显著性对象表示. 通常, 我们**将给定对象表示为给定image I中的二元mask** $A={a_x}$. 对于每个像素x, $a_x∈{1, 0}$是二进制标签, 以指示像素是否属于显著对象.**为了标记和评估, 我们要求用户绘制一个矩形来指定一个显著对象. 我们的检测算法也输出一个矩形.**

图像来源. 我们收集了一个非常大的图像数据库, 其中130, 099个来自各种来源的高质量图像, 主要来自图像论坛和图像搜索引擎. 然后我们手动选择60, 000多个图像, 每个图像包含一个显著对象或一个独特的前景对象. 我们进一步选择了20, 840张图片进行标记. 在选择过程中, 我们**排除了包含非常大的显著对象的任何图像**, 从而可以更准确地评估检测的性能.

标记一致性. 对于每个要标记的图像, 我们请用户绘制一个矩形, 该矩形包围图像中最大的对象根据他/她自己的理解. 由不同用户标记的矩形通常不相同. 为了减少标签的不一致性, 我们从多个用户绘制的矩形中选择一个"真实"标签.

</details>

#### SED1/2

| Single target | Dual target | The ground truth gives the result of segmenting each image by three different human subjects |
| ------------- | ----------- | -------------------------------------------------------------------------------------------- |

* [Salient objectdetection: A benchmark](https://arxiv.org/abs/1501.02741)
* [Image Segmentation by Probabilistic Bottom-Up Aggregation and Cue Integration](http://www.wisdom.weizmann.ac.il/~meirav/Segmentation_Alpert_Galun_Brandt_Basri.pdf)
* Project: [http://www.wisdom.weizmann.ac.il/~vision/Seg_Evaluation_DB/index.html](http://www.wisdom.weizmann.ac.il/~vision/Seg_Evaluation_DB/index.html)
* Download: [http://www.wisdom.weizmann.ac.il/~vision/Seg_Evaluation_DB/dl.html](http://www.wisdom.weizmann.ac.il/~vision/Seg_Evaluation_DB/dl.html)

The purpose of this work is to provide an empirical and scientific basis for image segmentation research. Evaluating the results produced by segmentation algorithms is challenging because it is difficult to come up with canonical test sets that provide underlying real segmentations. This is partly because manually delineating segments in everyday complex images can be laborious. Furthermore, people often tend to incorporate semantic considerations into their segmentation, which is beyond the scope of data-driven segmentation algorithms. Therefore, many existing algorithms show only few segmentation results. To evaluate segmentations produced by different algorithms, we compiled a database, Currently **contains 200 grayscale images along with ground-truth annotated segmentations**. The database is specifically designed to avoid potential blurring by merging images that clearly depict one or two objects in the foreground that differ from their surroundings solely through intensity, texture, or other low-level cues. Ground-truth segmentations are obtained by asking human subjects to manually separate grayscale images (color sources are also provided) into two or three categories, where each image is segmented by three different human subjects. Segments are evaluated by evaluating their consistency with ground-truth segmentations and their amount of fragmentation. Together with this database evaluation, We provide code for evaluating a given segmentation algorithm. This way, different segmentation algorithms may have comparable results, see the "Evaluation Tests" section for more details.

<details>
<summary>中文介绍</summary>

这项工作的目的是为图像分割研究提供经验和科学依据. 评估分割算法产生的结果具有挑战性, 因为很难提出提供基础真实分割的规范测试集. 这部分是因为在日常复杂图像中手动描绘片段可能是费力的. 此外, 人们往往倾向于将语义考虑纳入其分段中, 这超出了数据驱动的分割算法的范围. 因此, 许多现有算法仅显示很少的分割结果. 为了评估由不同算法产生的分割, 我们编制了一个数据库, 目前**包含200个灰度图像以及真实标注分割**. 该数据库专门设计用于避免潜在的模糊, 仅通过仅通过强度, 纹理或其他低水平线索合并清晰描绘前景中与其周围环境不同的一个或两个物体的图像. 通过要求人类对象手动地将灰度图像(还提供颜色源)分成两个或三个类别来获得地面真实分割, 其中**每个图像由三个不同的人类对象分割**. 通过评估其与真实分割的一致性及其碎片量来评估分割. 与此数据库评估一起, 我们提供了用于评估给定分割算法的代码. 这样, 不同的分割算法可能具有可比较的结果以获得更多细节, 请参阅"评估测试"部分.

</details>

#### ASD(MSRA1000/MSRA1K)

* Paper: [A two-stage approach to saliency detection inimages](https://www.researchgate.net/publication/224312323_A_two-stage_approach_to_saliency_detection_in_images)
* *Related:
  + T. Liu, J. Sun, N.-N. Zheng, X. Tang, and H.-Y. Shum, "[Learning to detect a salient object](http://research.microsoft.com/en-us/um/people/jiansun/salientobject/salient_object.htm), " in *Proc. IEEE Conf. Comput. Vis. Pattern Recognit.*, 2007, pp.1–8.
  + R. Achanta, S. Hemami, F. Estrada, and S. Süsstrunk, "[Frequency-tuned salient region detection](http://ivrlwww.epfl.ch/supplementary_material/RK_CVPR09/), " in *Proc. IEEE Conf. Comput. Vis. Pattern Recognit.*, 2009, pp.1597–1604.
* Download: [http://download.csdn.net/detail/wanyq07/9839322](http://download.csdn.net/detail/wanyq07/9839322)
  + Note on Download: Because it is based on the MSRA image data set, after Sun Jian left, his page disappeared on MARA, and related resources could not be found. A CSDN blog shared it. The original image download address: [MSRA image data set (1000 images with real annotations)](http://download.csdn.net/detail/tuconghuan/8357509). The size of the annotation images downloaded above has been uniformly changed to 512*512. So here is an address: [ASD size is the same](http://download.csdn.net/detail/zzb4702/9559378)

ASD contains 1, 000 images with pixel-wise ground-truths. The images are selected from the MSRA-A dataset, where only the bounding boxes around salient regions are provided. The accurate salient masks in ASD are created based on object contours.

This data set contains 1000 images (MSRA1000). The database comes from the description of the database and the results of some algorithms (IT, MZ, GB, SR, AC, IG) can be found in [Frequency-tuned Salient Region Detection](http://ivrlwww.epfl.ch/supplementary_material/RK_CVPR09/index.html) (FT algorithm => The improved data set here is called ACSD, related information can be found in [ACSD](#acsd), In addition, it also contains the ground truth maps of these 1000 test images.

<details>
<summary>中文介绍</summary>

ASD 包含 1, 000 张具有像素级真实情况的图像。这些图像选自 MSRA-A 数据集，其中仅提供显著区域周围的边界框。 ASD 中准确的显著掩模是根据对象轮廓创建的。

这个数据集包含有1000张图(MSRA1000)这个数据库来自于 该数据库的说明以及一些算法(IT, MZ, GB, SR, AC, IG ) 的结果可以在Frequency-tuned Salient Region Detection (FT算法 => 这里改进的数据集叫做ACSD, 相关可见ACSD, 此外其中还包含了这1000张测试图的真值图.

</details>

#### DUT-OMRON

* Paper: C. Yang, L. Zhang, H. Lu, X. Ruan, and M.-H. Yang, "[Saliency detection via graph-based manifold ranking](http://saliencydetection.net/dut-omron/), " in *Proc. IEEE Conf. Comput. Vis. Pattern Recognit.*, 2013, pp.3166–3173.
* Project: [http://saliencydetection.net/dut-omron/#outline-container-org0e04792](http://saliencydetection.net/dut-omron/#outline-container-org0e04792)
* Download: [http://saliencydetection.net/dut-omron/download/DUT-OMRON-image.zip](http://saliencydetection.net/dut-omron/download/DUT-OMRON-image.zip)

The database consists of 5,168 high-quality images manually selected from over 140,000 images. We resized the images to be 400 pixels wide or 400 pixels high, where the other side is smaller than 400. The images in our database have one or more salient objects and relatively complex backgrounds. We had a total of 25 participants, used to aggregate ground truth, with five participant labels per image. They all had normal or corrected-to-normal vision and were aware of the goals of our experiment. We construct pixel-wise ground-truth annotations, bounding boxes, and eye-fixation ground-truth annotations for the proposed database.

Our dataset is the only one with large-scale ground-truth annotations in terms of eye fixation, bounding boxes and pixels. Compared with the ASD and MSRA datasets and some other eye fixation datasets (i.e. MIT and NUSEF datasets), the images in the dataset are more difficult and therefore more challenging and provide more room for improvement in related saliency studies.

<details>
<summary>中文介绍</summary>

数据库包括从超过140, 000张图像中手动选择的5, 168个高质量图像. 我们将图像的大小调整为宽为400或高为400像素, 其中另一条边小于400. 我们数据库的图像具有一个或多个显著对象和相对复杂的背景. 我们共有25名参与者, 用于汇总真值, 每个图像有五个参与者标签. 他们都有正常或矫正到正常的视力并且意识到我们实验的目标. 我们为提出的数据库构建像素方面的真实标注, 边界框, 和眼睛固定标注真值.

我们的数据集是唯一一个具有眼睛固定, 边界框和像素方面的大规模真实标注的数据集. 与ASD和MSRA数据集以及其他一些眼睛固定数据集(即MIT和NUSEF数据集)相比, 数据集中的图像更加困难, 因此更具挑战性, 并为相关的显著性研究提供了更多的改进空间.

</details>

#### DUTS

* Project: [http://saliencydetection.net/duts/](http://saliencydetection.net/duts/)

We contribute a large scale data set named DUTS, **containing 10, 553 training images and 5, 019 test images**. All training images are collected from the ImageNet DET training/val sets, while test images are collected from the ImageNet DET test set and the SUN data set.
Both the training and test set contain very challenging scenarios for saliency detection. Accurate pixel-level ground truths are manually annotated by 50 subjects.
To our knowledge, DUTS is currently **the largest saliency detection benchmark** with the explicit training/test evaluation protocol.
For fair comparison in the future research, the training set of DUTS serves as a good candidate for learning DNNs, while the test set and other public data sets can be used for evaluation.

<details>
<summary>中文介绍</summary>

我们贡献了一个名为 DUTS 的大规模数据集，**包含 10, 553 个训练图像和 5, 019 个测试图像**。所有训练图像均从 ImageNet DET 训练/验证集收集，而测试图像则从 ImageNet DET 测试集和 SUN 数据集收集。
训练集和测试集都包含显著性检测非常具有挑战性的场景。准确的像素级地面事实由 50 名受试者手动注释。
据我们所知，DUTS 是目前**最大的显著性检测基准**，具有明确的训练/测试评估协议。
为了在未来的研究中进行公平比较，DUTS的训练集可以作为学习DNN的良好候选，而测试集和其他公共数据集可以用于评估。

</details>

#### DUTS-MM/DUTS-MQ

* Paper:
  * [Pluralistic Salient Object Detection](https://ieeexplore.ieee.org/document/10960495)
  * [arXiv](https://arxiv.org/abs/2409.02368)
* Download: Not specified in the paper page.

Pluralistic Salient Object Detection (PSOD) is proposed for generating multiple plausible salient segmentation results for a given image, instead of forcing conventional SOD into a single-mask setting.

DUTS-MM builds upon DUTS and enriches the ground-truth mask annotations by improving mask quality, reducing annotation inconsistency, and providing multiple ground-truth masks for images with saliency ambiguity. DUTS-MQ contains about 100K image-mask pairs with human-annotated preference scores, supporting human-aligned learning and evaluation of mask quality.

<details>
<summary>中文介绍</summary>

提出了多元显著目标检测 (PSOD)，用于为给定图像生成多个合理的显著分割结果，而不是强制传统 SOD 进入单掩模设置。

DUTS-MM 基于 DUTS 构建，通过提高掩模质量、减少注释不一致以及为具有显著性模糊的图像提供多个真值掩模来丰富真值掩模注释。 DUTS-MQ 包含约 100K 个图像-掩模对，具有人工注释的偏好分数，支持人类对齐的掩模质量学习和评估。

</details>

#### SOC (Salient Objects in Clutter)


* Paper: [Salient Objects in Clutter](https://arxiv.org/abs/2105.03053)
  * Chinese Version: [https://dengpingfan.github.io/papers/[2022][TPAMI]SOC_Chinese.pdf](https://dengpingfan.github.io/papers/%5B2022%5D%5BTPAMI%5DSOC_Chinese.pdf)
* Project:
  * [https://github.com/DengPingFan/SOC-DataAug](https://github.com/DengPingFan/SOC-DataAug)
  * [https://mmcheng.net/socbenchmark/](https://mmcheng.net/socbenchmark/)
* Download: See [https://mmcheng.net/socbenchmark/](https://mmcheng.net/socbenchmark/)

We propose a new high-quality dataset and update the previous saliency benchmark. Specifically, our dataset called SOC, Salient Objects in Clutter, includes images with salient and non-salient objects from daily object categories. Beyond object category annotations, each salient image is accompanied by attributes (e.g., appearance change, clutter) that reflect common challenges in real-world scenes, and can help 1) gain a deeper insight into the SOD problem, 2) investigate the pros and cons of the SOD models, and 3) objectively assess models from different perspectives. Finally, we report attribute-based performance assessment on our SOC dataset. We believe that our dataset and results will open new directions for future research on salient object detection.

SOC has 6,000 images with 80 common categories. Half of the images contain salient objects and the others contain none.**Each salient-object-contained image is annotated with instance-level SOD ground-truth, object category (e.g., dog, book), and challenging factors** (e.g., big/small object).**The non-salient object subset has 783 texture images and 2, 217 real-scene images** (e.g., aurora, sky).

<details>
<summary>中文介绍</summary>

我们提出了一个新的高质量数据集并更新了之前的显著性基准。具体来说，我们的数据集名为 SOC（杂乱中的显著对象），包括来自日常对象类别的显著和非显著对象的图像。除了对象类别注释之外，每个显著图像都附有反映现实世界场景中常见挑战的属性（例如外观变化、杂乱），并且可以帮助 1) 更深入地了解 SOD 问题，2) 研究 SOD 模型的优缺点，以及 3) 从不同角度客观评估模型。最后，我们报告了对 SOC 数据集进行基于属性的性能评估。我们相信我们的数据集和结果将为显著目标检测的未来研究开辟新的方向。

SOC 拥有 6,000 张图像，包含 80 个常见类别。一半图像包含显著对象，其他图像不包含。**每个包含显著对象的图像都用实例级 SOD 真值、对象类别（例如狗、书）和挑战性因素**（例如大/小对象）进行注释。**非显著对象子集有 783 个纹理图像和 2, 217 个真实场景图像**（例如极光、天空）。

</details>

#### HKU-IS

* Project: [https://i.cs.hku.hk/~gbli/deep_saliency.html](https://i.cs.hku.hk/~gbli/deep_saliency.html)
* Paper: [Visual Saliency Based on Multiscale Deep Features](http://i.cs.hku.hk/~yzyu/publication/mdfsaliency-cvpr15.pdf)
* Download:
  + [Google Drive](https://drive.google.com/open?id=0BxNhBO0S5JCRQ1N6V25VeVh6cHc&authuser=0)
  + [Baidu Yun](http://pan.baidu.com/s/1c0EpNfM)

The dataset contains 4447 images with pixel annotations of salient objects.
Visual saliency is a fundamental problem in cognitive and computational sciences, including computer vision. In this paper, we find that high-quality visual saliency models can be learned from multi-scale features extracted using deep convolutional neural networks (CNN). Successful in visual recognition tasks. To learn such a saliency model, we introduce a neural network structure with fully connected layers on top of the CNN responsible for feature extraction at three different scales. We then propose an improved method to enhance the spatial consistency of our saliency results. Finally, aggregating multiple saliency maps computed for different levels of image segmentation can further improve performance, resulting in better saliency maps than those produced by a single segmentation. To facilitate further research and evaluation of visual saliency models, **we also constructed a new large database including 4447 challenging images and their pixel saliency annotations**.

<details>
<summary>中文介绍</summary>

数据集包含4447个具有显著对象的像素注释的图像
视觉显著性是包括计算机视觉在内的认知和计算科学中的一个基本问题. 在本文中, 我们发现可以从使用深度卷积神经网络(CNN)提取的多尺度特征中学习高质量的视觉显著性模型. 视觉识别任务的成功. 为了学习这样的显著性模型, 我们引入了一种神经网络结构, 它在CNN顶部具有完全连接的层, 负责三个不同尺度的特征提取. 然后, 我们提出一种改进方法来增强我们的显著性结果的空间一致性. 最后, 针对不同级别的图像分割计算的聚合多个显著性图可以进一步提高性能, 从而产生比由单个分割产生的显著性图更好的显著性图. 为了促进对视觉显著性模型的进一步研究和评估, **我们还构建了一个新的大型数据库, 包括4447个具有挑战性的图像及其像素显著性注释**.

</details>

#### SOD (Salient Object Dataset)

* Project: [http://elderlab.yorku.ca/SOD/](http://elderlab.yorku.ca/SOD/)
* Download
  + Official: [http://elderlab.yorku.ca/SOD/SOD.zip](http://elderlab.yorku.ca/SOD/SOD.zip)
  + Baidu Cloud: [https://pan.baidu.com/s/1IMElTPwD4yTo2TMSRU-keQ](https://pan.baidu.com/s/1IMElTPwD4yTo2TMSRU-keQ)

This dataset is a collection of salient object boundaries based on the Berkeley Segmentation Dataset (BSD). Seven subjects were asked to select salient objects in each image used in BSD. Each subject was randomly shown a subset of the Berkeley Segmentation Dataset as boundaries that overlapped on the corresponding image. You can then select which regions or segments correspond to salient objects by clicking on them.
For each of the 300 images used in BSD, there is a .mat file that can be opened by Matlab. Loading each mat file reads into memory a structure called "SES", which is an array of data collected from each subject's session in SOD.

💝 The original images are available from the Berkely Segmentation Dataset at: [http://www.eecs.berkeley.edu/Research/Projects/CS/vision/grouping/segbench/](http://www.eecs.berkeley.edu/Research/Projects/CS/vision/grouping/segbench/)

<details>
<summary>中文介绍</summary>

此数据集是基于Berkeley Segmentation Dataset(BSD)的显著对象边界的集合. 要求七个对象选择BSD中使用的每个图像中的显著对象. 每个主题随机显示伯克利分割数据集的子集, 作为在相应图像上重叠的边界. 然后, 可以通过单击选择哪些区域或区段对应于显著对象.
对于BSD中使用的300个图像的每个图像, 都有一个.mat文件可以由Matlab打开. 加载每个mat文件会将一个名为"SES"的结构读入内存, 该结构是从SOD中每个主题的会话中收集的数据数组.

</details>

#### Infrared

* Project: [https://ivrl.epfl.ch/research-2/research-downloads/supplementary_material-cvpr11-index-html/](https://ivrl.epfl.ch/research-2/research-downloads/supplementary_material-cvpr11-index-html/)
* Paper: [http://infoscience.epfl.ch/record/167478](http://infoscience.epfl.ch/record/167478)
* Download: [http://ivrgwww.epfl.ch/supplementary_material/cvpr11/nirscene1.zip](http://ivrgwww.epfl.ch/supplementary_material/cvpr11/nirscene1.zip)

We capture hundreds of images of color (RGB) and near-infrared (NIR) scenes using a simple modification of a conventional SLR camera. We show that the addition of near-infrared information leads to a significant improvement in performance in scene recognition tasks, and that the improvement is still greater when using an appropriate 4-dimensional color representation. In particular, we propose MSIFT - a multispectral SIFT descriptor that, when combined with a kernel-based classifier, exceeds the performance of state-of-the-art scene recognition techniques (such as GIST) and their multispectral extensions. We extensively test our algorithm using a new dataset of hundreds of RGB-NIR scene images and benchmark it on Torralba's scene classification dataset.

<details>
<summary>中文介绍</summary>

我们使用对传统SLR相机的简单修改来捕获数百个彩色(RGB)和近红外(NIR)场景的图像. 我们表明, 近红外信息的添加导致场景识别任务中的性能显著提高, 并且当使用适当的4维颜色表示时, 改进仍然更大. 特别地, 我们提出了MSIFT-一种多光谱SIFT描述符, 当与基于内核的分类器结合时, 超过了现有技术的场景识别技术(例如GIST)及其多光谱扩展的性能. 我们使用数百个RGB-NIR场景图像的新数据集对我们的算法进行了广泛的测试, 并对Torralba的场景分类数据集进行了基准测试.

</details>

#### ImgSal

* Project: [https://sites.google.com/site/jianlinudt/saliency-database](https://sites.google.com/site/jianlinudt/saliency-database)
* Author's homepage: [http://www.escience.cn/people/jianli/DataBase.html](http://www.escience.cn/people/jianli/DataBase.html)

Database features

1. A collection of 235 color images, divided into six different categories;
2. Provide human fixed records (saccade data) and human marking results;
3. Easy to use.

We will consider the detection of salient regions of different sizes simultaneously. In fact, an acceptable saliency detector should detect large and small salient regions. In addition, saliency detection should also locate salient regions in cluttered backgrounds and regions with repeated distractors. We also note that for any saliency detector, different images present different difficulties. However, existing saliency benchmarks (such as Bruce's dataset, Hou'dataset, Harel's dataset, etc.) are image collections, No attempt was made to classify the difficulty of the required analysis. Therefore, we created a new saliency benchmark for saliency model validation. This database provides REGION ground truth (human labeling) and FIXATION ground truth (via eye trackers).
Image set A database containing 235 images was collected using Google and referring to recent literature. The images in this database are 480 x 640 pixels and are divided into 6 categories: 1) 50 images with large salient areas; 2) 80 images with intermediate salient areas; 3) 60 images with small salient areas; 4) 15 images with cluttered backgrounds; 5) 15 images with repeated distractors; 6) 15 images with large and small salient areas.

<details>
<summary>中文介绍</summary>

数据库的特点

1. 235个彩色图像的集合, 分为六个不同的类别;
2. 提供人类固定记录(扫视数据)和人类标记结果;
3. 易于使用.

我们将同时考虑不同大小的显著区域的检测. 实际上, 可接受的显著性检测器应该检测大的和小的显著区域. 此外, 显著性检测还应该定位杂乱背景中的显著区域和具有重复干扰物的区域. 我们还注意到, 对于任何显著性检测器, 不同的图像呈现不同的难度. 但是, 现有的显著性基准(例如Bruce的数据集, Hou'dataset, Harel的数据集等)是图像集合, 没有尝试对所需分析的难度进行分类. 因此, 我们为显著性模型验证创建了一个新的显著性基准. 该数据库提供REGION真值(人类标记)和FIXATION真值(通过眼动仪).
图像集使用Google以及参考最近的文献收集了包含235张图像的数据库. 此数据库中的图像为480 x 640像素, 分为6类: 1)50个具有大显著区域的图像; 2)具有中间显著区域的80幅图像; 3)具有小显著区域的60幅图像; 4)背景杂乱的15幅图像; 5)带有重复干扰物的15张图像; 6)具有大和小显著区域的15个图像.

</details>

#### ECSSD/CSSD

* Download: [http://www.cse.cuhk.edu.hk/leojia/projects/hsaliency/dataset.html](http://www.cse.cuhk.edu.hk/leojia/projects/hsaliency/dataset.html)
  + ECSSD (1000 images)
    - [ECSSD images (64.6MB)](http://www.cse.cuhk.edu.hk/leojia/projects/hsaliency/data/ECSSD/images.zip)
    - [ECSSD ground truth masks (1.78MB)](http://www.cse.cuhk.edu.hk/leojia/projects/hsaliency/data/ECSSD/ground_truth_mask.zip) (Updated on 9 April, 2015)
  + CSSD (200 images)
    - [CSSD images (18.7MB)](http://www.cse.cuhk.edu.hk/leojia/projects/hsaliency/data/CSSD/images.zip)
    - [CSSD groud truth masks (0.75MB)](http://www.cse.cuhk.edu.hk/leojia/projects/hsaliency/data/CSSD/ground_truth_mask.zip)

CSSD contains 200 images, while ECSSD is an extension of the former and contains 1,000 images.

Although MSRA-1000 has a wide variety of image content, the background structure is mainly simple and smooth. To represent the situations into which natural images typically fall, we extended the Complex Scene Saliency Dataset (CSSD) to a larger dataset (ECSSD) containing 1000 images, which contains many semantically meaningful but structurally complex images for evaluation. The images were obtained from the Internet and 5 assistants were asked to make ground truth masks. Several examples with corresponding masks are shown above.

<details>
<summary>中文介绍</summary>

其中CSSD包含了200张图, 而ECSSD是前者的扩展集包含有1000张图

虽然MSRA-1000的图像内容种类繁多, 但背景结构主要是简单而流畅. 为了表示自然图像通常落入的情况, 我们将复杂场景显著性数据集(CSSD)扩展到包含1000个图像的更大数据集(ECSSD), 其中包含许多语义上有意义但结构复杂的图像用于评估. 这些图像是从互联网上获取的, 并要求5名助手制作地面真相面具. 上面显示了几个带有相应掩模的例子.

</details>

#### THUR15K

* Paper: [https://mmcheng.net/zh/gsal/](https://mmcheng.net/zh/gsal/)
* Download: [https://mmcheng.net/mftp/Data/THUR15000.zip](https://mmcheng.net/mftp/Data/THUR15000.zip)
  + Baidu Cloud: [https://pan.baidu.com/s/1u-E-8ujnxBz0mdmXsJglvg](https://pan.baidu.com/s/1u-E-8ujnxBz0mdmXsJglvg)

Efficient identification of salient objects in large image sets is essential for many applications, including image retrieval, surveillance, image annotation, and object recognition. We propose a simple, fast, and efficient algorithm to locate and segment salient objects by analyzing collections of images. As a key novelty, we introduce population saliency to achieve superior unsupervised salient object segmentation by extracting salient objects that maximize inter-image similarity and intra-image sharpness (in a collection of pre-filtered images). To evaluate our method, We constructed a large benchmark dataset containing 15K images across multiple categories with over 6000 pixel-accurate ground-truth annotations for salient object regions. In all our tests, group saliency consistently outperformed state-of-the-art single-image saliency algorithms, resulting in higher accuracy and better recall. Our algorithm successfully processed image collections of a larger order than any existing benchmark dataset, including a variety of heterogeneous images from various inter-network sources.
We introduce a labeled dataset of categorical images for evaluating sketch-based image retrieval. We downloaded approximately 3000 images for each of 5 keywords: "butterfly", "coffee cup", "dog jumping", "giraffe" and "plane", together including approximately 15000 images. ** For each image, if there is a non-blurred object with the correct content matching the query keyword and a large part of the object is visible, we label such an object region. Similar to MSRA10K, Salient regions are labeled at the pixel level. We only label salient object regions for objects that are almost fully visible, since partially occluded objects are less useful for shape matching. Unlike MSRA10K, the THUR15K dataset does not contain salient regions labeled for every image in the dataset, i.e., some images may not have any salient regions. This dataset is used to evaluate shape-based image retrieval performance.**

<details>
<summary>中文介绍</summary>

有效识别大型图像集中的显著对象对于许多应用是必不可少的, 包括图像检索, 监视, 图像注释和对象识别. 我们提出了一种简单, 快速, 有效的算法, 通过分析图像集合来定位和分割显著对象. 作为一个关键的新颖性, 我们通过提取最大化图像间相似性和图像内清晰度的显著对象(在预过滤图像的集合中)来引入群体显著性以实现优越的无监督显著对象分割. 为了评估我们的方法, 我们构建了一个大型基准数据集, **该数据集包含多个类别的15K图像, 适用于显著对象区域的6000多个像素精确的真值注释**. 在我们的所有测试中, group saliency 始终优于最先进的单图像显著性算法, 从而实现更高的精度和更好的回忆. 我们的算法成功处理了比任何现有基准数据集更大的订单的图像集合, 包括来自各种网络间源的各种异构图像.
我们引入了分类图像的标记数据集, 用于评估基于草图的图像检索. 我们为5个关键字中的每一个Download了大约3000张图像:"蝴蝶", "咖啡杯", "狗跳", "长颈鹿"和"平面", 一起包括大约15000张图像.**对于每个图像, 如果存在具有与查询关键字匹配的正确内容的非模糊对象并且对象的大部分可见, 则我们标记这样的对象区域. 与MSRA10K类似, 显著区域以像素级别标记. 我们只标记几乎完全可见的对象的显著对象区域, 因为部分遮挡的对象对形状匹配不太有用. 与MSRA10K不同, THUR15K数据集不包含为数据集中的每个图像标记的显著区域, 即, 一些图像可能没有任何显著区域. 该数据集用于评估基于形状的图像检索性能.**

</details>

#### Bruce-A

* Paper: [https://papers.nips.cc/paper/2830-saliency-based-on-information-maximization.pdf](https://papers.nips.cc/paper/2830-saliency-based-on-information-maximization.pdf)

#### Judd-A

* Paper: [http://people.csail.mit.edu/torralba/publications/wherepeoplelook.pdf](http://people.csail.mit.edu/torralba/publications/wherepeoplelook.pdf)

#### PASCAL-S

* Project:
  + [https://ccvl.jhu.edu/datasets/](https://ccvl.jhu.edu/datasets/)
  + [http://www.cbi.gatech.edu/salobj/](http://www.cbi.gatech.edu/salobj/)
* Download:
  + Baidu Yun: [https://pan.baidu.com/s/1DZcfwCYdeMW4EGawhXQyig](https://pan.baidu.com/s/1DZcfwCYdeMW4EGawhXQyig)
  + Page: [http://academictorrents.com/details/6c49defd6f0e417c039637475cde638d1363037e](http://academictorrents.com/details/6c49defd6f0e417c039637475cde638d1363037e)

Free inpainting on a subset of 850 images from PASCAL VOC. Collected with 8 subjects, 3s viewing time, Eyelink II eye tracker. Performance of most algorithms shows that PASCAL-S is less biased than most saliency datasets.

💔 Since its annotated true value has multiple values, a common practice is to use the `255/2` value as the threshold for processing before using this data set

<details>
<summary>中文介绍</summary>

对来自PASCAL VOC的850张图像子集的自由修复. 收集8个主题, 3s观看时间, Eyelink II眼动仪. 大多数算法的性能表明PASCAL-S比大多数显著性数据集偏差更小.

💔 由于其标注的真值有多个值, 常见的做法是使用 `255/2` 值作为阈值进行处理后, 再使用该数据集

</details>

#### UCSB

* Paper: [https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3954044/](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3954044/)
* Download: [https://labs.psych.ucsb.edu/eckstein/miguel/research_pages/saliencydata.html](https://labs.psych.ucsb.edu/eckstein/miguel/research_pages/saliencydata.html)

#### OSIE

* Paper: [https://jov.arvojournals.org/article.aspx?articleid=2193943](https://jov.arvojournals.org/article.aspx?articleid=2193943)

A large number of previous models are used to predict people's appearance in natural scenes, focusing on pixel-level image attributes. To bridge the semantic gap between the predictive power of computational saliency models and human behavior, we propose a new saliency architecture that divides information into three levels: pixel-level image attributes, object-level attributes, and semantic-level attributes. Object and semantic-level information are usually ignored, or only a few sample object categories are discussed, where scaling to a large number of object categories is not feasible nor neurally justified. To solve this problem, This work builds a principled vocabulary of basic properties to describe object and semantic-level information, thereby not restricting a limited number of object categories. We build a new dataset of 500 images containing eye-tracking data from 15 observers and annotation data for 5,551 segmented objects with fine outlines and 12 semantic attributes (publicly available in the paper). The experimental results demonstrate the importance of object- and semantic-level information in predicting visual attention.

<details>
<summary>中文介绍</summary>

大量先前的模型用于预测人们在自然场景中的外观, 侧重于像素级图像属性. 为了弥合计算显著性模型的预测能力与人类行为之间的语义差距, 我们提出了一种新的显著性体系结构, 它将信息分为三个层次: 像素级图像属性, 对象级属性和语义级属性. 通常忽略对象和语义级别信息, 或者仅讨论少数样本对象类别, 其中缩放到大量对象类别是不可行的, 也不是神经合理的. 为了解决这个问题, 这项工作构建了一个基本属性的原则词汇表来描述对象和语义级信息, 从而不限制有限数量的对象类别. 我们**建立了一个包含500个图像的新数据集, 其中包含15个观察者的眼动追踪数据和5, 551个具有精细轮廓和12个语义属性的分段对象的注释数据**(可在论文中公开获得). 实验结果证明了对象和语义级信息在预测视觉注意力方面的重要性.

</details>

#### ACSD

* Paper: [Frequency-tuned salient region detection](https://infoscience.epfl.ch/record/135217/files/1708.pdf)
* Project: [https://ivrl.epfl.ch/research-2/research-current/research-saliency/supplementary_material-rk_cvpr09-index-html/](https://ivrl.epfl.ch/research-2/research-current/research-saliency/supplementary_material-rk_cvpr09-index-html/)
* Download: [Only GT](https://ivrl.epfl.ch/wp-content/uploads/2018/08/binarymasks.zip)

Made based on the ASD data set (MSRA1K).
We obtained a real database from 1000 images proposed in [Z. Wang and B. Li. A two-stage approach to saliency detection in images. ICASSP 2008.]. The ground truth in [Z. Wang and B. Li. We manually segment salient objects within user-drawn rectangles to obtain binary masks as shown below. Such masks are both accurate and allow us to handle multiple salient objects clearly.

<details>
<summary>中文介绍</summary>

基于ASD数据集(MSRA1K)制作.
我们从[Z. Wang and B. Li. A two-stage approach to saliency detection in images. ICASSP 2008.]中提出的1000个图像中获得了一个真实数据库. [Z. Wang and B. Li. A two-stage approach to saliency detection in images. ICASSP 2008.]中的基本事实是在显著区域周围的用户绘制的矩形. 这是不准确的, 并将多个对象合二为一. 我们手动分割用户绘制的矩形内的显著对象以获得二进制掩码, 如下所示. 这样的掩膜既准确又允许我们清楚地处理多个显著对象.

</details>

#### WXSOD

* Paper: [WXSOD: A Benchmark for Robust Salient Object Detection in Adverse Weather Conditions](https://arxiv.org/abs/2508.12250)
* Project: [https://github.com/C-water/WXSOD](https://github.com/C-water/WXSOD)
* Download: [https://github.com/C-water/WXSOD?tab=readme-ov-file#--dataset-access](https://github.com/C-water/WXSOD?tab=readme-ov-file#--dataset-access)

WXSOD dataset provides a large-scale dataset (14,945 RGB images) for salient object detection under extreme weather conditions. Distinguishing itself from existing RGB-SOD benchmarks, it provides images with ​​diverse degradation​​ patterns and ​​pixel-wise annotations​​. Our dataset contains:
- A synthetic training set consisting of 12,891 images, including 8 types of weather noise and a small amount of clean images.
- A composite test set consisting of 1,500 images, including 8 types of weather noise and a small amount of clean images.
- A real test set consisting of 554 images, including 5 types of weather noise.

<details>
<summary>中文介绍</summary>

WXSOD数据集提供了大规模数据集（14,945张RGB图像），用于极端天气条件下的显著目标检测。与现有的 RGB-SOD 基准不同，它为图像提供了多种退化模式和像素级注释。我们的数据集包含：
- 由 12,891 张图像组成的合成训练集，其中包括 8 种天气噪声和少量干净图像。
- 由 1,500 张图像组成的复合测试集，其中包括 8 种天气噪声和少量干净图像。
- 由 554 张图像组成的真实测试集，其中包括 5 种天气噪声。

</details>

### RGB-D Saliency

Thanks:

* @JXingZhao: [https://github.com/JXingZhao/ContrastPrior](https://github.com/JXingZhao/ContrastPrior)
* @jiwei0921: [https://github.com/jiwei0921/RGBD-SOD-datasets](https://github.com/jiwei0921/RGBD-SOD-datasets)
* More Details can be found at: [http://dpfan.net/d3netbenchmark/](http://dpfan.net/d3netbenchmark/)

#### SIP

* Paper: Rethinking RGB-D Salient Object Detection: Models, Datasets, and Large-Scale Benchmarks:https://arxiv.org/pdf/1907.06781.pdf
* Project: [http://dpfan.net/d3netbenchmark/](http://dpfan.net/d3netbenchmark/)
* Download: See [http://dpfan.net/d3netbenchmark/](http://dpfan.net/d3netbenchmark/)

We carefully collect a new salient person (SIP) dataset, which consists of 1K high-resolution images that cover diverse real-world scenes from various viewpoints, poses, occlusion, illumination, and background.

<details>
<summary>中文介绍</summary>

我们仔细收集了一个新的显著人物（SIP）数据集，该数据集由 1K 高分辨率图像组成，涵盖了来自不同视点、姿势、遮挡、照明和背景的不同现实世界场景。

</details>

#### NLPR/RGBD1000

* Paper: [Rgbd salient object detection: a benchmark and algorithms](https://docs.google.com/uc?authuser=0&id=0B1wzzt1_uP1rb250d0t6dVFXWG8&export=download)
* Project: [https://sites.google.com/site/rgbdsaliency/home](https://sites.google.com/site/rgbdsaliency/home)
* Download: [https://sites.google.com/site/rgbdsaliency/dataset](https://sites.google.com/site/rgbdsaliency/dataset)

NLPR is also called RGBD1000 dataset which including 1,000 images. There may exist multiple salient objects in each image. The structured light depth images are obtained by the Microsoft Kinect under different illumination conditions.

<details>
<summary>中文介绍</summary>

NLPR 也称为 RGBD1000 数据集，包含 1,000 张图像。每幅图像中可能存在多个显著物体。结构光深度图像是通过Microsoft Kinect在不同光照条件下获得的。

</details>

#### NJU400/2000

* Paper:

  + NJU400: [Depth saliency based on anisotropic center-surround difference](http://mcg.nju.edu.cn/publication/2014/icip14-jur.pdf)
  + NJU2000: [Depth-aware salient object detection using anisotropic center-surround difference](http://mcg.nju.edu.cn/publication/2015/spic15-jur.pdf)
* Project:

  * [MGG](http://mcg.nju.edu.cn/index.html)
  * [http://mcg.nju.edu.cn/publication/2014/icip14-jur/index.html](http://mcg.nju.edu.cn/publication/2014/icip14-jur/index.html)
* Download:

  * Official:
    + [http://mcg.nju.edu.cn/resource.html](http://mcg.nju.edu.cn/resource.html)
    + [http://mcg.nju.edu.cn/dataset/nju400.zip](http://mcg.nju.edu.cn/dataset/nju400.zip)
    + [http://mcg.nju.edu.cn/dataset/nju2000.zip](http://mcg.nju.edu.cn/dataset/nju2000.zip)

  + See [http://dpfan.net/d3netbenchmark/](http://dpfan.net/d3netbenchmark/)

NJU2000 contains 2003 stereo image pairs with diverse objects and complex, challenging scenarios, along with ground-truth map. The stereo images are gathered from 3D movies, the Internet, and photographs taken by a Fuji W3 stereo camera.

<details>
<summary>中文介绍</summary>

NJU2000 包含 2003 个立体图像对，其中包含不同的对象和复杂且具有挑战性的场景，以及真值地图。立体图像是从 3D 电影、互联网以及 Fuji W3 立体相机拍摄的照片中收集的。

</details>

#### STEREO/SSB

* Paper: [Leveraging stereopsis for saliency analysis](http://web.cecs.pdx.edu/~fliu/papers/cvpr2012.pdf)
* Project: [http://web.cecs.pdx.edu/~fliu/](http://web.cecs.pdx.edu/~fliu/)
* Download: See [http://dpfan.net/d3netbenchmark/](http://dpfan.net/d3netbenchmark/)

SSB is also called STEREO dataset, which consists of 1000 pairs of binocular images.

<details>
<summary>中文介绍</summary>

SSB也称为STEREO数据集，由1000对双目图像组成。

</details>

#### LFSD

* Paper: [Saliency Detection on Light Field](https://ieeexplore.ieee.org/document/7570181)
* Project: [https://sites.duke.edu/nianyi/publication/saliency-detection-on-light-field/](https://sites.duke.edu/nianyi/publication/saliency-detection-on-light-field/)
* Download:
  * Official: See [https://sites.duke.edu/nianyi/publication/saliency-detection-on-light-field/](https://sites.duke.edu/nianyi/publication/saliency-detection-on-light-field/)
  * See [http://dpfan.net/d3netbenchmark/](http://dpfan.net/d3netbenchmark/)

We acquire 100 light fields using the Lytro light field camera. For each light field, we provide: (a) Raw light field data, (b) A rough focal stack  (c) An all-focus image deriving from focal stack  (d) The ground truth corresponding to all-focus image.

To get a valid ground-truth, we ask three individuals to manually segment the saliency regions from the all-focus image. The result are deemed ground truth only when all three results are consistent (i.e., they have an overlap of over 90%)

<details>
<summary>中文介绍</summary>

我们使用 Lytro 光场相机获取 100 个光场。对于每个光场，我们提供：（a）原始光​​场数据，（b）粗略的焦点堆栈（c）从焦点堆栈导出的全焦点图像（d）与全焦点图像相对应的真值。

为了获得有效的基本事实，我们要求三个人从全焦点图像中手动分割显著区域。仅当所有三个结果一致（即它们重叠超过 90%）时，结果才被视为真实结果

</details>

#### RGBD135/DES

* Paper: [Depth Enhanced Saliency Detection Method](https://dl.acm.org/doi/pdf/10.1145/2632856.2632866)
* Project: [https://github.com/HzFu/DES_code](https://github.com/HzFu/DES_code)
* Download:
  * Official:
    + Baidu Pan: [https://pan.baidu.com/s/1pLv2B8n](https://pan.baidu.com/s/1pLv2B8n)
    + Google Drive: [https://onedrive.live.com/redir?resid=F3A8A31ABFAC51B0!256&amp;authkey=!AC4-yOEjn0bgrCQ&amp;ithint=file%2crar](https://onedrive.live.com/redir?resid=F3A8A31ABFAC51B0!256&authkey=!AC4-yOEjn0bgrCQ&ithint=file%2Crar)
  + See [http://dpfan.net/d3netbenchmark/](http://dpfan.net/d3netbenchmark/)

In our experiments, we provide a new RGB-D saliency detection dataset. We take 135 RGB-D indoor images by Kinect with the resolution 640×480. Then, three users are asked to mark the salient object of each image. We employ the overlapping areas of the manually labelled object as the ground truth.

<details>
<summary>中文介绍</summary>

在我们的实验中，我们提供了一个新的 RGB-D 显著性检测数据集。我们通过Kinect拍摄了135张RGB-D室内图像，分辨率为640×480。然后，要求三名用户标记每张图像的显著对象。我们使用手动标记对象的重叠区域作为基本事实。

</details>

#### DUT-RGBD/DUTLF-Depth

* Paper: [Depth-induced Multi-scale Recurrent Attention Network for Saliency Detection](https://openaccess.thecvf.com/content_ICCV_2019/papers/Piao_Depth-Induced_Multi-Scale_Recurrent_Attention_Network_for_Saliency_Detection_ICCV_2019_paper.pdf)
* Project: [https://github.com/jiwei0921/DMRA_RGBD-SOD](https://github.com/jiwei0921/DMRA_RGBD-SOD)
* Download:
  * Official: [https://pan.baidu.com/s/1FwUFmNBox_gMZ0CVjby2dg](https://pan.baidu.com/s/1FwUFmNBox_gMZ0CVjby2dg)
  * See [http://dpfan.net/d3netbenchmark/](http://dpfan.net/d3netbenchmark/)

The dataset is part of DUTLF dataset captured by Lytro camera, and we selected a more accurate 1200 depth map pairs for more accurate RGB-D saliency detection.
We create a large scale RGB-D dataset(DUTLF-Depth) with 1200 paired images containing more complex scenarios, such as multiple or transparent objects, similar foreground and background, complex background, low-intensity environment. This challenging dataset can contribute to comprehensively evaluating saliency models.
And we split the dataset including 800 training set and 400 test set.

<details>
<summary>中文介绍</summary>

该数据集是Lytro相机捕获的DUTLF数据集的一部分，我们选择了更准确的1200个深度图对来进行更准确的RGB-D显著性检测。
我们创建了一个大规模 RGB-D 数据集（DUTLF-Depth），其中包含 1200 张配对图像，其中包含更复杂的场景，例如多个或透明物体、相似的前景和背景、复杂的背景、低强度环境。这个具有挑战性的数据集有助于全面评估显著性模型。
我们将数据集分为 800 个训练集和 400 个测试集。

</details>

#### SSD/SSD100

* Paper: [A Three-Pathway Psychobiological Framework of Salient Object Detection Using Stereoscopic Technology](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8265566)
* Download: See [http://dpfan.net/d3netbenchmark/](http://dpfan.net/d3netbenchmark/)

Our SSD100 dataset is built on three stereo movies. The movies contain both the indoors and outdoors scenes. We pick up one stereo image pair at each hundred frames. It totally has tens of thousands of stereo image pairs. We make the image acquisition and image annotation independent to each other, we can avoid dataset design bias, namely a specific type of bias that is caused by experimenters unnatural selection of dataset images. The chosen stereo image pairs are based on one principle: choose the one which the computer detect the salient objects within the complex scenes where even the human cannot tell the salient objects at once. After picking up the stereo image pairs, we divide the image pairs into left images and right images both in 960x1080 size. When we build the ground truth of salient objects, we adhere to the following rules: 1) we mark the salient objects, taking the advice of most people; 2) disconnected regions of the same object are labeled separately; 3) we use solid regions to approximate hollow objects, such as bike wheels. Besides, we will expand this dataset continually in future.

<details>
<summary>中文介绍</summary>

我们的 SSD100 数据集基于三部立体电影构建。电影包含室内和室外场景。我们每一百帧拾取一对立体图像。它总共有数万个立体图像对。我们使图像采集和图像注释彼此独立，我们可以避免数据集设计偏差，即由于实验者对数据集图像的不自然选择而引起的特定类型的偏差。所选择的立体图像对基于一个原则：选择计算机在复杂场景中检测到显著对象的一对，即使人类也无法立即分辨出显著对象。拾取立体图像对后，我们将图像对分为左图像和右图像，尺寸均为 960x1080。当我们构建显著对象的基本事实时，我们遵循以下规则：1）我们标记显著对象，听取大多数人的建议； 2）同一物体的不相连区域分别标记； 3）我们使用实心区域来近似空心物体，例如自行车车轮。此外，我们将在未来不断扩展这个数据集。

</details>

#### ReDWeb-S

* Paper: [SMAC: Learning Selective Mutual Attention and Contrast for RGB-D Saliency Detection](https://arxiv.org/abs/2010.05537)
* Download: See [https://github.com/nnizhang/SMAC#redweb-s](https://github.com/nnizhang/SMAC#redweb-s)
* Project: [https://github.com/nnizhang/SMAC](https://github.com/nnizhang/SMAC)

We construct a new large-scale challenging dataset ReDWeb-S and it has totally 3179 images with various real-world scenes and high-quality depth maps. We split the dataset into a training set with 2179 RGB-D image pairs and a testing set with the remaining 1000 image pairs.

<details>
<summary>中文介绍</summary>

我们构建了一个新的大规模具有挑战性的数据集ReDWeb-S，它总共有3179张图像，具有各种真实世界场景和高质量的深度图。我们将数据集分为包含 2179 个 RGB-D 图像对的训练集和包含剩余 1000 个图像对的测试集。

</details>

#### COME15K

* Paper: [Cascaded RGB-D SOD with COME15K dataset](https://arxiv.org/abs/2109.07246)
* Download: See [https://github.com/JingZhang617/cascaded_rgbd_sod#come15k-rgb-d-sod-dataset](https://github.com/JingZhang617/cascaded_rgbd_sod#come15k-rgb-d-sod-dataset)
* Project: [https://github.com/JingZhang617/cascaded_rgbd_sod](https://github.com/JingZhang617/cascaded_rgbd_sod)

Our new COME15K dataset is based on Holo50K, which is a stereo dataset, including scenarios from both indoor and outdoor. We first filter the Holo50K dataset and then obtain 16,000 stereo image pairs for labelling (the candidate labeled set) and another 5,000 image pairs as the unlabeled set. Note that the stereo pairs in Holo50K dataset are directly captured by a stereo camera without rectification, we use a modified version of a SOTA off-the-shelf stereo matching algorithm to compute the depth for both the candidate labeled set and unlabeled set with the left-right view images as input.

<details>
<summary>中文介绍</summary>

我们新的 COME15K 数据集基于 Holo50K，这是一个立体数据集，包括室内和室外的场景。我们首先对 Holo50K 数据集进行过滤，然后获得 16,000 个立体图像对进行标记（候选标记集），另外 5,000 个图像对作为未标记集。请注意，Holo50K 数据集中的立体对是由立体相机直接捕获的，无需进行校正，我们使用 SOTA 现成立体匹配算法的修改版本来计算候选标记集和未标记集的深度，并以左右视图图像作为输入。

</details>

### RGB-T Saliency

#### UVT2000

* Paper: [TMM 2024 | Alignment-Free RGBT Salient Object Detection: Semantics-guided Asymmetric Correlation Network and A Unified Benchmark](https://arxiv.org/pdf/2406.00917)
* Download: See <https://github.com/Angknpng/SACNet?tab=readme-ov-file#uvt2000>.
* Project: <https://github.com/Angknpng/SACNet>

UVT2000 contains 2000 unaligned visible-thermal image pairs with ground truth annotations, directly captured by a pair of thermal infrared and CCD cameras without any alignment. Therefore, the misalignment of the image pairs is a natural result of camera shooting and reflects the issues in practical applications. Additionally, the image pairs are collected from a variety of real-world scenarios, which are  annotated with 11 challenge attributes to facilitate the study of specific issues.

<details>
<summary>中文介绍</summary>

UVT2000 包含 2000 个未对齐的可见热图像对，带有真值注释，由一对热红外和 CCD 相机直接捕获，无需任何对齐。因此，图像对的错位是相机拍摄的自然结果，反映了实际应用中的问题。此外，图像对是从各种现实场景中收集的，并注释有 11 个挑战属性，以方便对特定问题的研究。

</details>

#### un-VT821/1000/5000

* Paper: [TIP 2022 | Weakly Alignment-Free RGBT Salient Object Detection With Deep Correlation Network](https://ieeexplore.ieee.org/document/9779787)
* Download: <https://github.com/lz118/Deep-Correlation-Network?tab=readme-ov-file#unaligned-dataset>
* Project: <https://github.com/lz118/Deep-Correlation-Network>

We use the training set of VT5000 to train our network and compare the performances on VT821, VT1000 and VT5000’s testing set. For proving our performance on unaligned image pairs, we randomly make the spatial affine transformation on all the testing data.

<details>
<summary>中文介绍</summary>

我们使用 VT5000 的训练集来训练我们的网络，并比较 VT821、VT1000 和 VT5000 测试集上的性能。为了证明我们在未对齐图像对上的性能，我们对所有测试数据随机进行空间仿射变换。

</details>

#### VT723

* Paper: [Mirror Complementary Transformer Network for RGB-thermal Salient Object Detection](https://arxiv.org/abs/2207.03558)
* Download: See [https://github.com/jxr326/SwinMCNet#the-proposed-dataset](https://github.com/jxr326/SwinMCNet#the-proposed-dataset)
* Project: [https://github.com/jxr326/SwinMCNet](https://github.com/jxr326/SwinMCNet)

To further validate the robustness of the proposed model under common challenging scenes in real world, we build a more challenging RGB-T SOD dataset VT723 based on a large public semantic segmentation RGB-T dataset used in the autonomous driving domain. We pick image pairs in which the salient objects are significant in at least one of their color and thermal modalities. After careful screening, we collectd 723 sets of RGB-thermal image pairs in which 473 are taken during daytime and 250 are taken at night. The SOD ground truths are obtained by professional annotators looking at both modalities, selecting common salient regions, and manually marking pixel by pixel on the original segmentation ground truths.

<details>
<summary>中文介绍</summary>

为了进一步验证所提出的模型在现实世界中常见的挑战性场景下的鲁棒性，我们基于自动驾驶领域使用的大型公共语义分割RGB-T数据集构建了更具挑战性的RGB-T SOD数据集VT723。我们选择图像对，其中显著物体至少在其颜色和热模态之一上具有重要意义。经过仔细筛选，我们收集了723组RGB热图像对，其中473组是白天拍摄的，250组是夜间拍摄的。 SOD 基本事实是由专业注释者通过查看两种模式、选择共同显著区域并在原始分割基本事实上手动逐像素标记来获得的。

</details>

#### VT5000

* Paper: [RGBT Salient Object Detection: A Large-scale Dataset and Benchmark](https://arxiv.org/pdf/2007.03262.pdf)
* Project:
  * [http://chenglongli.cn/code-dataset/](http://chenglongli.cn/code-dataset/)
  * [https://github.com/lz118/RGBT-Salient-Object-Detection](https://github.com/lz118/RGBT-Salient-Object-Detection)
* Download: [https://pan.baidu.com/s/13_9tJXHDmWLNjqkbMNl1hw](https://pan.baidu.com/s/13_9tJXHDmWLNjqkbMNl1hw) (likp)

This work contributes such a RGBT image dataset named VT5000, including 5000 spatially aligned RGBT image pairs with ground truth annotations. VT5000 has 11 challenges collected in different scenes and environments for exploring the robustness of algorithms. With this dataset, we propose a powerful baseline approach, which extracts multi-level features within each modality and aggregates these features of all modalities with the attention mechanism, for accurate RGBT salient object detection.

<details>
<summary>中文介绍</summary>

这项工作贡献了一个名为 VT5000 的 RGBT 图像数据集，其中包括 5000 个空间对齐的 RGBT 图像对，并带有真实注释。 VT5000收集了11个不同场景和环境下的挑战，用于探索算法的鲁棒性。借助该数据集，我们提出了一种强大的基线方法，该方法提取每种模态中的多级特征，并通过注意力机制聚合所有模态的这些特征，以实现准确的 RGBT 显著对象检测。

</details>

#### VT1000

* Paper: [RGB-T Image Saliency Detection via Collaborative Graph Learning](https://ieeexplore.ieee.org/document/8744296)
* Project: [http://chenglongli.cn/code-dataset/](http://chenglongli.cn/code-dataset/)
* Download:
  + Baidu Pan: [https://pan.baidu.com/s/1eGQJhvnKnqV1KJ1GY_63NA](https://pan.baidu.com/s/1eGQJhvnKnqV1KJ1GY_63NA)
  + Google Drive: [https://drive.google.com/file/d/1NCPFNeiy1n6uY74L0FDInN27p6N_VCSd/view?usp=sharing](https://drive.google.com/file/d/1NCPFNeiy1n6uY74L0FDInN27p6N_VCSd/view?usp=sharing)

Existing RGB-T image benchmark dataset for saliency detection has several limitations: i) The alignment errors might be large. The used RGB and thermal cameras have totally different imaging parameters and are mounted on tripods, and they use a homography matrix to approximate the transformations of two images. ii) The aligned method introduces blank boundaries in some modality, which might destroy the boundary prior to some extent. iii) Most of scenes are very simple, which makes the dataset less challenge and diverse. In this paper, we contribute a larger dataset for the purpose of RGB-T image saliency detection. The imaging hardware includes highly aligned RGB and thermal cameras, and the  transformation between two modal images are thus only translation and scale. This setup makes the images of different modalities highly aligned, and have no blank boundaries. Furthermore, we take more challenges and diversities into account when building up the dataset and collect 1000 RGB-T image pairs

<details>
<summary>中文介绍</summary>

现有的用于显著性检测的 RGB-T 图像基准数据集有几个限制： i) 对齐误差可能很大。所使用的RGB和热成像相机具有完全不同的成像参数，并且安装在三脚架上，并且它们使用单​​应矩阵来近似两个图像的变换。 ii）对齐方法在某些模态中引入了空白边界，这可能会在一定程度上破坏先前的边界。 iii）大多数场景都非常简单，这使得数据集的挑战性和多样性较低。在本文中，我们贡献了一个更大的数据集用于 RGB-T 图像显著性检测。成像硬件包括高度对齐的 RGB 和热成像相机，因此两个模态图像之间的转换只是平移和缩放。这种设置使不同模态的图像高度对齐，并且没有空白边界。此外，我们在构建数据集时考虑了更多的挑战和多样性，并收集了 1000 个 RGB-T 图像对

</details>

#### VT821

* Paper: [A Unified RGB-T Saliency Detection Benchmark: Dataset, Baselines, Analysis and A Novel Approach](https://arxiv.org/pdf/1701.02829.pdf)
* Project: [http://chenglongli.cn/code-dataset/](http://chenglongli.cn/code-dataset/)
* Download:
  + Baidu Pan: [http://pan.baidu.com/s/1bpEaeQV](http://pan.baidu.com/s/1bpEaeQV)
  + Google Drive: [https://drive.google.com/file/d/0B4fH4G1f-jjNR3NtQUkwWjFFREk/view?usp=sharing](https://drive.google.com/file/d/0B4fH4G1f-jjNR3NtQUkwWjFFREk/view?usp=sharing)

This work contributes such a RGB-T image dataset, which includes 821 spatially aligned RGB-T image pairs and their ground truth annotations for saliency detection purpose. The image pairs are with high diversity recorded under different scenes and environmental conditions, and we annotate 11 challenges on these image pairs for performing the challengesensitive analysis for different saliency detection algorithms.

<details>
<summary>中文介绍</summary>

这项工作贡献了这样一个 RGB-T 图像数据集，其中包括 821 个空间对齐的 RGB-T 图像对及其用于显著性检测目的的真值注释。在不同场景和环境条件下记录的图像对具有高度多样性，我们在这些图像对上注释了 11 个挑战，以便对不同的显著性检测算法进行挑战敏感分析。

</details>

### Dichotomous Image Segmentation

#### DIS5K

* Paper: [Highly Accurate Dichotomous Image Segmentation](https://arxiv.org/abs/2203.03041)
* Project: [https://xuebinqin.github.io/dis/index.html](https://xuebinqin.github.io/dis/index.html)
* Download: See [https://github.com/xuebinqin/DIS#11-dis-dataset-v10-dis5k](https://github.com/xuebinqin/DIS#11-dis-dataset-v10-dis5k)

We first manually collected over 12,000 images from Flickr based on our pre-designed keywords. Then, according to the structural complexities of the objects, we obtained 5,470 images covering 225 categories in 22 groups. Note that the adopted selection strategy is similar to Zhou et al. Most selected images only contain single objects  to obtain rich and highly accurate structures and details. Meanwhile, the segmentation and labeling confusions caused by the co-occurrence of multiple objects from different categories are avoided to the greatest extent. Therefore, the labeled targets in our DIS5K are mainly the "foreground objects of the images defined by the predesigned keywords" regardless of their characteristics e.g., salient, common, camouflaged, meticulous, etc.
Each image of DIS5K is manually labeled with pixel-wise accuracy using GIMP The average per-image labeling time is ∼30 minutes and some images cost up to 10 hours. It is worth mentioning that some of our labeled ground truth (GT) masks are visually close to the image matting GT. The labeled targets, including transparent and translucent, are binary masks with one pixel's highest accuracy.

<details>
<summary>中文介绍</summary>

我们首先根据预先设计的关键字从 Flickr 手动收集了 12,000 多张图像。然后，根据对象的结构复杂性，我们获得了涵盖22组225个类别的5,470张图像。请注意，采用的选择策略与 Zhou 等人类似。大多数选定的图像仅包含单个对象，以获得丰富且高度准确的结构和细节。同时，最大程度地避免了不同类别的多个对象共现造成的分割和标注混乱。因此，DIS5K中的标记目标主要是“由预先设计的关键字定义的图像的前景对象”，无论其特征如何，例如显著的、常见的、伪装的、细致的等。
DIS5K 的每张图像均使用 GIMP 以像素级精度手动标记。每张图像的平均标记时间为 ∼30 分钟，某些图像长达 10 小时。值得一提的是，我们的一些标记的真值 (GT) 掩模在视觉上与图像抠图 GT 很接近。标记的目标（包括透明和半透明）是具有单像素最高精度的二值掩模。

</details>

### High-Resolution Saliency

#### HRSOD/DAVIS-S

* Paper: [Towards High-Resolution Salient Object Detection](https://arxiv.org/pdf/1908.07274.pdf)
* Project: [https://github.com/yi94code/HRSOD](https://github.com/yi94code/HRSOD)
* Download:
  + HRSOD: [https://drive.google.com/open?id=1bmDGlkzqHoduNigi_GO4Qy9sA9sIaZcY](https://drive.google.com/open?id=1bmDGlkzqHoduNigi_GO4Qy9sA9sIaZcY)
  + DAVIS-S: [https://drive.google.com/open?id=1q1H7yoITLS6i2n-PhgYMIxLdjyhge5AR](https://drive.google.com/open?id=1q1H7yoITLS6i2n-PhgYMIxLdjyhge5AR)

We contribute a High-Resolution Salient Object Detection (HRSOD) dataset, containing 1610 training images and 400 test images. The total 2010 images are collected from the website of Flickr with the license of all creative commons. Pixel-level ground truths are manually annotated by 40 subjects. The shortest edge of each image in our HRSOD is more than 1200 pixels.

<details>
<summary>中文介绍</summary>

我们贡献了一个高分辨率显著目标检测（HRSOD）数据集，包含 1610 个训练图像和 400 个测试图像。 2010 年的全部图片均来自 Flickr 网站，并获得所有知识共享许可。像素级真实情况由 40 名受试者手动注释。我们的 HRSOD 中每张图像的最短边缘超过 1200 像素。

</details>

### Co-Saliency

Some tools for the evaluation:

* Python:
  + [https://github.com/zzhanghub/eval-co-sod](https://github.com/zzhanghub/eval-co-sod)
    - A GPU-accelerated evaluation tool (based on Python & PyTorch) for co-saliency detection task. It can automatically evaluate 8 metrics and draw 4 types of curves. [http://zhaozhang.net/coca.html](http://zhaozhang.net/coca.html)
  + [https://github.com/lartpang/PySODEvalToolkit](https://github.com/lartpang/PySODEvalToolkit)
    - A Python-based salient object detection evaluation toolbox.
    - Based on [PySODMetrics](https://github.com/lartpang/PySODMetrics): A simple and efficient implementation of SOD metrics.
* MATLAB:
  + [http://dpfan.net/wp-content/uploads/CoSalBenchmark-EvaluationTools.zip](http://dpfan.net/wp-content/uploads/CoSalBenchmark-EvaluationTools.zip)
    - From [http://dpfan.net/CoSOD3K/](http://dpfan.net/CoSOD3K/)

#### ImagePair

* Paper: [A Co-Saliency Model of Image Pairs](https://ieeexplore.ieee.org/document/5771591?arnumber=5771591)
* Download: See [http://dpfan.net/CoSOD3K/](http://dpfan.net/CoSOD3K/)

We collected from various databases such as Microsoft Research Cambridge image database, the Caltech-256 Object Categories database, and PASCAL VOC dataset.

<details>
<summary>中文介绍</summary>

我们从各种数据库中收集数据，例如微软剑桥图像数据库、Caltech-256 对象类别数据库和 PASCAL VOC 数据集。

</details>

#### MSRC

* Paper: [Object Categorization by Learned Universal Visual Dictionary](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/criminisi_iccv2005.pdf)
* Project: [https://www.microsoft.com/en-us/research/project/image-understanding/?from=http%3A%2F%2Fresearch.microsoft.com%2Fvision%2Fcambridge%2Frecognition%2F#overview](https://www.microsoft.com/en-us/research/project/image-understanding/?from=http%3A%2F%2Fresearch.microsoft.com%2Fvision%2Fcambridge%2Frecognition%2F#overview)
* Download: See [http://dpfan.net/CoSOD3K/](http://dpfan.net/CoSOD3K/)

#### WICOS

* Paper: [Co-Saliency Detection within a Single Image](https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/viewFile/16886/16351)
* Download: See [http://dpfan.net/CoSOD3K/](http://dpfan.net/CoSOD3K/)

Since most existing image datasets used for saliency detection do not consider the within-image co-saliency, we collect a new dataset of 364 images for performance evaluation. In the experiment, we test the proposed method and other comparison methods on the new dataset and quantitatively evaluate their performance based on the annotated ground truth.

<details>
<summary>中文介绍</summary>

由于大多数用于显著性检测的现有图像数据集不考虑图像内的协同显著性，因此我们收集了 364 个图像的新数据集用于性能评估。在实验中，我们在新数据集上测试了所提出的方法和其他比较方法，并根据注释的真值定量评估了它们的性能。

</details>

#### iCoSeg

* Paper: [iCoseg: Interactive Co-segmentation with Intelligent Scribble Guidance](http://users.ece.cmu.edu/~dbatra/publications/assets/bkpcl_cvpr10.pdf)
* Project: [http://chenlab.ece.cornell.edu/projects/touch-coseg/](http://chenlab.ece.cornell.edu/projects/touch-coseg/)
* Download: See [http://dpfan.net/CoSOD3K/](http://dpfan.net/CoSOD3K/)
  + Dataset Samples: [http://chenlab.ece.cornell.edu/projects/touch-coseg/iCoseg_dataset.pdf](http://chenlab.ece.cornell.edu/projects/touch-coseg/iCoseg_dataset.pdf)
  + Official Link: [http://chenlab.ece.cornell.edu/projects/touch-coseg/CMU_Cornell_iCoseg_dataset.zip](http://chenlab.ece.cornell.edu/projects/touch-coseg/CMU_Cornell_iCoseg_dataset.zip)

We introduce and make publicly available the largest co-segmentation dataset yet, the CMU-Cornell iCoseg Dataset, with 38 groups, 643 images, and pixelwise hand-annotated groundtruth. Through machine experiments and real user studies with our developed interface, we show that iCoseg can intelligently recommend regions to scribble on, and users following these recommendations can achieve good quality cutouts with significantly lower time and effort than exhaustively examining all cutouts.

<details>
<summary>中文介绍</summary>

我们引入并公开了迄今为止最大的联合分割数据集，即 CMU-Cornell iCoseg 数据集，其中包含 38 个组、643 张图像和逐像素手工注释的基本事实。通过机器实验和使用我们开发的界面进行的真实用户研究，我们表明 iCoseg 可以智能地推荐要涂鸦的区域，并且遵循这些建议的用户可以获得高质量的剪贴画，而与彻底检查所有剪贴画相比，花费的时间和精力要少得多。

</details>

#### CoCA: Common Category Aggregation (CoCA) dataset

* Paper: [Gradient-Induced Co-Saliency Detection](https://arxiv.org/pdf/2004.13364.pdf)
* Project: [http://zhaozhang.net/coca.html](http://zhaozhang.net/coca.html)
* Download: Our dataset is freely available for research, but not for commercial use.
  + Baidu Pan: [https://pan.baidu.com/s/1tEgkrdaO6HUEzditrcmsJA](https://pan.baidu.com/s/1tEgkrdaO6HUEzditrcmsJA) (iqf3)
  + Google Drive: [https://drive.google.com/file/d/1ImAJmqeOdBSvWUh5InLdrw7dEUHdnb1w/view?usp=sharing](https://drive.google.com/file/d/1ImAJmqeOdBSvWUh5InLdrw7dEUHdnb1w/view?usp=sharing)

CoCA dataset consists of 80 categories with 1295 images, covering everyday indoor and outdoor scenes. It is worth noting that these categories are outright staggered with Microsoft COCO. In our CoCA dataset, except for the co-salient object(s), each image contains at least one extraneous salient object, which enables the dataset to better evaluate the models' ability of discovering co-salient object(s) among multiple foregrounds. We provide four levels of annotations: class level, bounding box level, object level, and instance level. Different levels of annotations of our dataset corresponds to different tasks, such as co-localization, few-shot object segmentation, co-saliency detection, and instance co-segmentation.

<details>
<summary>中文介绍</summary>

CoCA数据集由80个类别、1295张图像组成，涵盖日常的室内和室外场景。值得注意的是，这些类别与 Microsoft COCO 完全交错。在我们的 CoCA 数据集中，除了共同显著对象之外，每张图像都包含至少一个无关的显著对象，这使得数据集能够更好地评估模型在多个前景中发现共同显著对象的能力。我们提供四个级别的注释：类级别、边界框级别、对象级别和实例级别。我们的数据集的不同级别的注释对应于不同的任务，例如协同定位、少镜头对象分割、协同显著性检测和实例协同分割。

</details>

#### CoSal2015

* Paper: [Detection of Co-salient Objects by Looking Deep and Wide](http://dpfan.net/wp-content/uploads/2016IJCVCODW169%E3%80%90CoSal2015-Dataset%E3%80%91Detection-of-co-salient-objects-by-looking-deep-and-wide.pdf)
* Project: [http://www.escience.cn/people/JunweiHan/Co-saliency.html](http://www.escience.cn/people/JunweiHan/Co-saliency.html)
* Download: See [http://dpfan.net/CoSOD3K/](http://dpfan.net/CoSOD3K/)

Additionally, we also evaluated the proposed algorithm on a newly established benchmark dataset, i.e., the Cosal2015 dataset (see Fig. 7). In this dataset, we collected 50 image groups containing totally 2015 images from challenging scenarios in the ILSVRC2014 detection set (Russakovsky et al. 2015) and YouTube video set (Prest et al. 2012). 20 subjects were asked to view these image groups and provide the pixel-level annotation manually. Thus, the established dataset is a bigger and more challenging benchmark that can be used for evaluating the co-saliency detection algorithms.

<details>
<summary>中文介绍</summary>

此外，我们还在新建立的基准数据集 Cosal2015 数据集上评估了所提出的算法（见图 7）。在此数据集中，我们收集了 50 个图像组，其中包含来自 ILSVRC2014 检测集（Russakovsky 等人，2015）和 YouTube 视频集（Prest 等人，2012）中具有挑战性场景的 2015 个图像。 20 名受试者被要求查看这些图像组并手动提供像素级注释。因此，建立的数据集是一个更大、更具挑战性的基准，可用于评估协同显著性检测算法。

</details>

#### CoSOD3k

* Paper:
  + [Taking a Deeper Look at Co-Salient Object Detection](https://openaccess.thecvf.com/content_CVPR_2020/papers/Fan_Taking_a_Deeper_Look_at_Co-Salient_Object_Detection_CVPR_2020_paper.pdf)
  + [Re-thinking Co-Salient Object Detection](https://arxiv.org/pdf/2007.03380.pdf)
* Project: [http://dpfan.net/CoSOD3K/](http://dpfan.net/CoSOD3K/)
* Download: See [http://dpfan.net/CoSOD3K/](http://dpfan.net/CoSOD3K/)

Co-salient object detection (CoSOD) is a newly emerging and rapidly growing branch of salient object detection (SOD), which aims to detect the co-occurring salient objects in multiple images. However, existing CoSOD datasets often have a serious data bias, which assumes that each group of images contains salient objects of similar visual appearances. This bias results in the ideal settings and the effectiveness of the models, trained on existing datasets, may be impaired in real-life situations, where the similarity is usually semantic or conceptual. To tackle this issue, we first collect a new high-quality dataset, named CoSOD3k, which contains 3, 316 images divided in 160 groups with multiple level annotations, i.e., category, bounding box, object, and instance levels. CoSOD3k makes a significant leap in terms of diversity, difficulty and scalability, benefiting related vision tasks. Besides, we comprehensively summarize 34 cutting-edge algorithms, benchmarking 19 of them over four existing CoSOD datasets (MSRC, iCoSeg, Image Pair and CoSal2015) and our CoSOD3k with a total of ∼61K images (largest scale), and reporting group-level performance analysis. Finally, we discuss the challenge and future work of CoSOD. Our study would give a strong boost to growth in the CoSOD community. Benchmark toolbox and results are available on our project page.

<details>
<summary>中文介绍</summary>

共显著目标检测（CoSOD）是显著目标检测（SOD）的一个新兴且快速发展的分支，旨在检测多幅图像中同时出现的显著目标。然而，现有的 CoSOD 数据集通常存在严重的数据偏差，即假设每组图像都包含具有相似视觉外观的显著对象。这种偏差会导致理想的设置和在现有数据集上训练的模型的有效性在现实生活中可能会受到损害，其中相似性通常是语义或概念上的。为了解决这个问题，我们首先收集一个新的高质量数据集，名为 CoSOD3k，其中包含 3, 316 张图像，分为 160 组，具有多个级别注释，即类别、边界框、对象和实例级别。 CoSOD3k 在多样性、难度和可扩展性方面取得了重大飞跃，有利于相关的视觉任务。此外，我们全面总结了 34 种前沿算法，在四个现有 CoSOD 数据集（MSRC、iCoSeg、Image Pair 和 CoSal2015）和我们的 CoSOD3k（总共 61K 图像（最大规模））上对其中 19 种进行了基准测试，并报告了组级性能分析。最后，我们讨论了 CoSOD 的挑战和未来的工作。我们的研究将有力推动 CoSOD 社区的发展。基准工具箱和结果可在我们的项目页面上找到。

</details>

#### RGBDCosal150

* Paper: [Co-saliency Detection for RGBD Images Based on Multi-constraint Feature Matching and Cross Label Propagation](https://arxiv.org/abs/1710.05172)
* Project: [https://rmcong.github.io/proj_RGBD_cosal.html](https://rmcong.github.io/proj_RGBD_cosal.html)
* Download:
  * Official: [https://github.com/rmcong/RGBD-Cosal150-Dataset](https://github.com/rmcong/RGBD-Cosal150-Dataset)

In this dataset, we collected 21 image groups containing totally 150 images from RGBD NJU-1985 (NJU2000) dataset with pixellevel ground truth, and the original depth maps are provided by the dataset itself.

<details>
<summary>中文介绍</summary>

在此数据集中，我们从具有像素级真实值的 RGBD NJU-1985 (NJU2000) 数据集中收集了 21 个图像组，共包含 150 张图像，原始深度图由数据集本身提供。

</details>

#### RGBDCoseg183

* Paper: [Object-based RGBD image co-segmentation with mutex constraint](http://www.cv-foundation.org/openaccess/content_cvpr_2015/html/Fu_Object-Based_RGBD_Image_2015_CVPR_paper.html)
* Download:
  * OneDrive: https://onedrive.live.com/redir?resid=F3A8A31ABFAC51B0!269&authkey=!AHUBN0lk5kQLWzQ&ithint=file%2czip
  * BaiduYun: https://pan.baidu.com/s/1cAMin0

We have constructed one ourselves with some images from the [RGBD Scenes Dataset](http://rgbd-dataset.cs.washington.edu/) and some that were captured by ourselves. The dataset contains 16 image sets, each of 6 to 17 images taken from indoor scenes with one common foreground object (193 images in total). Pixel-level ground-truth is labeled for the common foreground object in each image.

<details>
<summary>中文介绍</summary>

我们自己使用 RGBD 场景数据集 中的一些图像和我们自己捕获的一些图像构建了一个。该数据集包含 16 个图像集，每个图像集有 6 到 17 张图像，取自具有一个共同前景物体的室内场景（总共 193 张图像）。像素级真值标记为每个图像中的常见前景对象。

</details>

#### INCT2016

* Paper: [Unsupervised co-segmentation for indefinite number of common foreground objects](https://pubmed.ncbi.nlm.nih.gov/26886987/)

INCT2016 is a more challenging dataset with larger appearance variation, indefinite number of targets, and complicated backgrounds, which contains 291 images distributed in 12 categories with pixel-level ground truth. INCT2016 is built by expanding the [Coseg-Rep](http://www.jifengdai.org/publications/ICCV_Cosegmentation_2013.pdf) dataset.

<details>
<summary>中文介绍</summary>

INCT2016是一个更具挑战性的数据集，具有较大的外观变化、不确定的目标数量和复杂的背景，其中包含分布在12个类别的291张图像，具有像素级的真实值。 INCT2016是通过扩展Coseg-Rep数据集构建的。

</details>

### Video Saliency

#### RSD(PKU-RSD)

* Paper: [A dataset and evaluation methodology for visual saliency in video](https://ieeexplore.ieee.org/document/5202529)
* Project: [https://pkuml.org/resources/dataset.html](https://pkuml.org/resources/dataset.html)
* Download: [https://pkuml.org/resources/pku-rsd.html](https://pkuml.org/resources/pku-rsd.html)

We constructed this PKU-RSD (Region Saliency Dataset) dataset that captures spatiotemporal visual saliency for evaluating different video saliency models. This dataset contains 431 short videos covering various scenarios (surveillance, advertising, news, cartoons, movies, etc.) and the corresponding annotation results of salient objects in sampled keyframes manually labeled by 23 subjects.

<details>
<summary>中文介绍</summary>

我们构建了这个PKU-RSD(区域显著性数据集)数据集, 可以捕获时空视觉显著性, 用于评估不同的视频显著性模型. 该数据集包含431个短视频, 其涵盖各种场景(监视, 广告, 新闻, 卡通, 电影等)以及由23个主题手动标记的采样关键帧中的显著对象的相应注释结果.

</details>

#### STC

* Paper: [Detection of salient objects with focused attention based on spatial and temporal coherence](https://link.springer.com/article/10.1007%2Fs11434-010-4387-1)
* Download: This dataset is freely available from the author.

To demonstrate quantitatively the advantages of using spatial and temporal coherence, we carried out our experiments on 32 video segments with a total of 4820 frames collected from the internet. Each video segment contains a single salient object, which ranges from humans performing various activities and animals in the wild, to vehicles both on the ground and in the air. All the frames are annotated with object bounding boxes, and the detection performance is evaluated in terms of mean precision (P), recall (R), F-measure (F0.5), and boundary displacement errors (BDE).

<details>
<summary>中文介绍</summary>

为了定量地展示使用空间和时间相干性的优势，我们对从互联网收集的 32 个视频片段（总共 4820 帧）进行了实验。每个视频片段都包含一个显著对象，范围从进行各种活动的人类和野外动物，到地面和空中的车辆。所有帧都用对象边界框进行注释，并根据平均精度（P）、召回率（R）、F-measure（F0.5）和边界位移误差（BDE）来评估检测性能。

</details>

### Reasoning SOD

#### OC-SODBench

* Paper: [Revisiting Salient Object Detection from an Observer-Centric Perspective](https://arxiv.org/abs/2602.06369)
* Project: [https://github.com/Dustzx/OC_SOD](https://github.com/Dustzx/OC_SOD)
* Download: See [https://github.com/Dustzx/OC_SOD](https://github.com/Dustzx/OC_SOD)

OC-SODBench is a reasoning-oriented salient object detection benchmark introduced by the Observer-Centric Salient Object Detection (OC-SOD) formulation. Instead of assuming a single objective salient region for each image, OC-SOD predicts salient regions conditioned on observer-specific factors such as preferences or intents. The paper reports that OC-SODBench contains 33k training, validation, and test images with 152k textual prompts and object pairs.

The OC-SODAgent is an iterative framework that first performs initial segmentation with SAM2, then uses a Vision Language Model (VLM) to evaluate quality and semantic alignment, and finally refines the segmentation mask according to VLM feedback. The repository also includes a dataset generation pipeline organized around intent, saliency, and preference.

<details>
<summary>中文介绍</summary>

OC-SODBench 是由以观察者为中心的显著对象检测 (OC-SOD) 公式引入的面向推理的显著对象检测基准。 OC-SOD 不是为每个图像假设单个客观显著区域，而是根据观察者特定因素（例如偏好或意图）预测显著区域。该论文报告称，OC-SODBench 包含 33k 个训练、验证和测试图像，以及 152k 个文本提示和对象对。

OC-SODAgent 是一个迭代框架，首先使用 SAM2 执行初始分割，然后使用视觉语言模型 (VLM) 评估质量和语义对齐，最后根据 VLM 反馈细化分割掩码。该存储库还包括围绕意图、显著性和偏好组织的数据集生成管道。

</details>

### Other

#### XPIE

* Paper: [What is and what is not a salient object? Learning salient object detector by ensembling linear exemplar regressors](https://www.researchgate.net/publication/320971838_What_is_and_What_is_Not_a_Salient_Object_Learning_Salient_Object_Detector_by_Ensembling_Linear_Exemplar_Regressors)
* Project:
  * cvteam: [http://cvteam.net/](http://cvteam.net/)
  * [http://cvteam.net/projects/CVPR17-ELE/ELE.html](http://cvteam.net/projects/CVPR17-ELE/ELE.html)
* Download: [http://cvteam.net/projects/CVPR17-ELE/XPIE.tar.gz](http://cvteam.net/projects/CVPR17-ELE/XPIE.tar.gz)

Finding out what is and what is not a salient object can help develop better features and models in Salient Object Detection (SOD). In this paper, we studied the images that were selected and discarded when building a new SOD dataset and found that many similar candidates, complex shapes and low objectness are the three main attributes of many non-salient objects. Furthermore, objects may have different properties that make them salient.
In order to comprehensively explain what are and are not salient objects, a feasible solution is to study the entire process of building a new SOD dataset by observing the main characteristics of the objects contained in the dataset or in the images discarded from the dataset. From these observations, we can infer the key properties of salient and non-salient objects as well as the subjective biases that may exist in image-based SOD datasets. To this end, we build a large SOD dataset (called XPIE) and record all the details of the construction process. 1) We first collect three types of images from three sources, including Panoramio, ImageNet, and two fixation datasets. These operations are fully automated to avoid introducing too much subjective bias. 2) After that, we resize each image so that its maximum side length is 300 pixels, and discard all grayscale or color images with a minimum side length less than 128 pixels. 3) Finally, we obtain 29,600 color images in three image subsets. Denoted as Set-P, Set-I, respectively. Set-E.
**Set-P contains 8,800 images of places of interest with geographical information (e.g., GPS and tags), Set-I with object tags contains 19,600 images, and Set-E contains 1,200 images with human fixations**.
For these images, we asked two engineers to annotate them in two stages. In the first stage, the images were assigned a binary label: 'yes' for containing non-explicit objects, 'no' otherwise. After the first stage, we labeled 21,002 images as 'yes', and 8,598 images as 'no'. In the second stage, the two engineers were further asked to manually label the accurate boundaries of salient objects in the 10,000 images labeled 'yes'. Note that we had 10 volunteers involved in the entire process to check the quality of the annotations. **Finally, we obtained binary masks for 10,000 images**.

<details>
<summary>中文介绍</summary>

找出什么是什么和什么不是显著对象可以有助于在显著对象检测(SOD)中开发更好的特征和模型. 在本文中, 我们研究了在构建新的SOD数据集时选择和丢弃的图像, 发现许多相似的候选者, 复杂形状和低对象性是很多非显著对象的三个主要属性. 此外, 对象可能具有使其显著的不同属性.
为了全面解释什么是和什么不是显著对象, 一个可行的解决方案是通过观察包含在数据集中或从数据集中丢弃的图像中的对象的主要特征来研究构建新SOD数据集的整个过程. 从这些观察中, 我们可以推断显著和非显著对象的关键属性以及基于图像的SOD数据集中可能存在的主观偏差. 为此, 我们构建了一个大的SOD数据集(称为XPIE)并记录构建过程中的所有细节. 1) 我们首先从三个来源收集三种图像, 包括Panoramio, ImageNet和两个fixation数据集. 这些操作是全自动的, 以避免引入太多的主观偏见. 2) 之后, 我们调整每个图像的大小, 使其最大边长为300像素, 并丢弃所有最小边长小于128像素的灰度或彩色图像. 3) 最后, 我们在三个图像子集中获得29, 600个彩色图像. 分别表示为Set-P, Set-I, Set-E.
**Set-P 包含8, 800具有地理信息的感兴趣地点的图像(例如, GPS和标签), 具有对象标签的Set-I包含19, 600图像, 以及Set-E包含1, 200个human fixations图像**.
对于这些图像, 我们要求两位工程师通过两个阶段对其进行注释. 在第一阶段, 图像被分配一个二进制标记:'是'用于包含非明确对象, 否则为'否'. 在第一阶段之后, 我们将21, 002张图片标记为"是", 并且8, 598图像标记为"否". 在第二阶段, 这两位工程师进一步要求手动标记标记为"是"的10, 000张图像中的显著对象的准确边界. 注意我们有10名志愿者参与整个过程, 以检查注释的质量.**最后, 我们获得了10, 000张图像的二进制掩码**.

</details>

#### SOS

* Paper: Salient object subitizing
  * [CVPR Version](https://cs-people.bu.edu/jmzhang/SOS/SOS_preprint.pdf)
  * [Arxiv Version](http://arxiv.org/abs/1607.07525)
* Project: [http://cs-people.bu.edu/jmzhang/sos.html](http://cs-people.bu.edu/jmzhang/sos.html)
* Download:
  * Extended version: [http://www.cs.bu.edu/groups/ivc/data/SOS/ESOS.zip](http://www.cs.bu.edu/groups/ivc/data/SOS/ESOS.zip) (see the arXiv paper for detials)
  * Initial version. Bounding Box Annotations (training split only): [http://www.cs.bu.edu/groups/ivc/data/SOS/SOS.zip](http://www.cs.bu.edu/groups/ivc/data/SOS/SOS.zip)

We have collected an image dataset for salient object subitizing. The source images are from four public image datasets: COCO, VOC07, ImageNet and SUN. Each  image is labeled as containing 0, 1, 2, 3 or 4+ salient objects by Amazon Mechanic Turk workers.

<details>
<summary>中文介绍</summary>

我们收集了用于显著对象子化的图像数据集。源图像来自四个公共图像数据集：COCO、VOC07、ImageNet 和 SUN。 Amazon Mechanic Turk 工作人员将每个图像标记为包含 0、1、2、3 或 4 个以上显著对象。

</details>

#### MSO

* Paper: Salient object subitizing
  * [CVPR Version](https://cs-people.bu.edu/jmzhang/SOS/SOS_preprint.pdf)
  * [Arxiv Version](http://arxiv.org/abs/1607.07525)
* Project: [http://cs-people.bu.edu/jmzhang/sos.html](http://cs-people.bu.edu/jmzhang/sos.html)
* Download: [http://www.cs.bu.edu/groups/ivc/data/SOS/MSO.zip](http://www.cs.bu.edu/groups/ivc/data/SOS/MSO.zip)

We assembled a Multi-Salient-Object (MSO) dataset. Images of the MSO dataset are taken from the test set of the SOS dataset. We removed images with severely overlapping salient objects. We also removed the images for which we find it ambiguous to label the indicated number of salient objects. This leaves us with 1224 images out of 1380 images from our SOS test set. As shown in the table below, more than half of the images in our MSO dataset contain either zero salient objects or multiple salient objects. We believe that this dataset provides a more realistic setting to evaluate salient object detection methods. Currently only bounding box annotations are available, but we will share the object segmentation annotations in the near future.

<details>
<summary>中文介绍</summary>

我们组装了一个多显著对象（MSO）数据集。 MSO 数据集的图像取自 SOS 数据集的测试集。我们删除了具有严重重叠的显著物体的图像。我们还删除了我们发现标记指定数量的显著对象不明确的图像。这使得我们的 SOS 测试集中有 1380 张图像中的 1224 张。如下表所示，我们的 MSO 数据集中超过一半的图像包含零个显著对象或多个显著对象。我们相信该数据集提供了更现实的设置来评估显著对象检测方法。目前仅提供边界框注释，但我们将在不久的将来分享对象分割注释。

</details>

#### ILSO-1K/2K

* Paper:
  * ILSO-1K (CVPR 2017): training (1400), testing (600): [Instance-level salient object segmentation](https://openaccess.thecvf.com/content_cvpr_2017/papers/Li_Instance-Level_Salient_Object_CVPR_2017_paper.pdf)
  * ILSO-2K (CVIU 2021): training (700), testing (300): [Instance-level salient object segmentation](https://www.sciencedirect.com/science/article/pii/S1077314221000515)
* Project:
  * [https://github.com/Kinpzz/MSRNet-CVIU](https://github.com/Kinpzz/MSRNet-CVIU)
* Download:
  * Baidu Pan: [https://pan.baidu.com/s/1O6ueVp2VZKRONxy0iboMzg](https://pan.baidu.com/s/1O6ueVp2VZKRONxy0iboMzg) (159u)
  * Google Drive: [https://drive.google.com/file/d/1tM_7IlDcQkqWB44kcZluJuiPd-Dnnw8k/view?usp=sharing](https://drive.google.com/file/d/1tM_7IlDcQkqWB44kcZluJuiPd-Dnnw8k/view?usp=sharing)

To promote the study of this problem, we built a new dataset with pixel-wise salient instance annotations in our preliminary version. This new dataset contains 1000 images that are mostly from existing datasets for salient region detection, including ECSSD (Yan et al., 2013), DUT-O (Yang et al., 2013), HKU-IS (Li and Yu, 2015), and MSO (Zhang et al., 2016) datasets. High-quality pixel-wise salient instance labeling and salient object contour are provided for each image. The dataset is divided into three parts, including 500 images for training, 200 images for validation, and 300 images for testing.
In this paper, we further extend the scale of the existing dataset with more challenging samples for salient instance segmentation. In order to distinguish between the dataset in the preliminary version of this paper and the extended dataset in this paper, we name the former **ILSO-1K** and the latter **ILSO-2K**.
For ILSO-2K, we collected another 1,246 noncopyrighted images from the Internet, most of which contain multiple salient object instances, complex background, or low color contrast. To reduce the label inconsistency, we asked three people to annotate the salient regions with different instance IDs in all selected images using a custom-designed interactive segmentation tool. Only the images with consistent salient instances labeling by all the three annotators are remained. Based on the high-quality salient instance segmentation labels, we can generate the salient instance contours for each image. In the end, another 1000 images with pixel-wise salient object instance labels as well as salient object contour labels are produced to extend the salient instance dataset. The new 1000 images are also randomly divided into three parts, including 500 images for training, 200 images for validation, and 300 images for testing.
In summary, the combination of these new 1000 images and ISLO-1K becomes our new dataset ILSO-2K, which in total has 1000 images for training, 400 images for validation, and 600 images for testing. Moreover, the number of images that have more
than 4 salient object instances in the extended 1000 images (173) is larger than that in ILSO-1K (98), which indicates the increment of difficulty in the extended dataset ILSO-2K.

<details>
<summary>中文介绍</summary>

为了促进这个问题的研究，我们在初步版本中构建了一个带有像素级显著实例注释的新数据集。这个新数据集包含 1000 张图像，大部分来自用于显著区域检测的现有数据集，包括 ECSSD (Yan et al., 2013)、DUT-O (Yang et al., 2013)、HKU-IS (Li and Yu, 2015) 和 MSO (Zhang et al., 2016) 数据集。为每个图像提供高质量的逐像素显著实例标记和显著对象轮廓。数据集分为三部分，其中500张图像用于训练，200张图像用于验证，300张图像用于测试。
在本文中，我们进一步扩展了现有数据集的规模，使用更具挑战性的样本来进行显著实例分割。为了区分本文初步版本中的数据集和本文中的扩展数据集，我们将前者命名为**ILSO-1K**，后者命名为**ILSO-2K**。
对于 ILSO-2K，我们从互联网上收集了另外 1,246 张无版权图像，其中大多数包含多个显著对象实例、复杂背景或低颜色对比度。为了减少标签不一致，我们要求三个人使用定制设计的交互式分割工具，在所有选定图像中用不同实例 ID 注释显著区域。仅保留由所有三个注释者标记的具有一致显著实例的图像。基于高质量的显著实例分割标签，我们可以为每个图像生成显著实例轮廓。最后，生成另外 1000 个具有逐像素显著对象实例标签以及显著对象轮廓标签的图像，以扩展显著实例数据集。新的1000张图像也被随机分为三部分，其中500张图像用于训练，200张图像用于验证，300张图像用于测试。
总之，这些新的 1000 张图像和 ISLO-1K 的组合成为我们的新数据集 ILSO-2K，其中总共有 1000 张图像用于训练，400 张图像用于验证，600 张图像用于测试。此外，图像数量越多
扩展的 1000 个图像中超过 4 个显著对象实例（173）比 ILSO-1K 中的显著对象实例（98）大，这表明扩展数据集 ILSO-2K 中的难度增加。

</details>

#### HS-SOD

* Paper: [Hyperspectral Image Dataset for Benchmarking on Salient Object Detection](https://arxiv.org/abs/1806.11314)
* Project: [https://github.com/gistairc/HS-SOD](https://github.com/gistairc/HS-SOD)
* Download: [http://data.airc.aist.go.jp/HS-SOD/HS-SOD.zip](http://data.airc.aist.go.jp/HS-SOD/HS-SOD.zip)

The data is collected at the public parks of Tokyo Waterfront City in Odaiba, Tokyo, Japan with the permission of Tokyo Port Terminal Corporation. We collected data in several days between August - September 2017 when the weather is sunny or partially cloudy. At each data collection day, a tripod was used to fix camera to minimize motion distortion on the images. We tried to keep the exposure time and gain for camera settings fixed as much as possible depending on the daylight conditions while keeping saturation of pixels values or image visibility in mind. As a reference to the dataset users, we are providing camera settings such as exposure time and gain values for each image in a text file with the corresponding data. We also did not apply normalization on captured bands. It may improve the quality of the hyperspectral images with higher colour contrast between foreground and background regions; however, it may also decrease the difficulty of dataset for benchmarking on salient object detection task.
After obtaining various hyperspectral images, we have selected 60 images from approximately fifty different scenes with the conditions: i) we removed distorted images due to motion in the scene (depending on the exposure time, one image may take a few seconds for camera), ii) we considered several aspects such as variations in salient object size, spatial positions of objects on images, number of salient objects,
foreground-background contrast, iii) a few images has the same scene but the object positions, object distance, or number of objects varied.
For the convenience of salient object detection task, we cropped spectral bands around the visible spectrum and we saved hyper-cubes for each scene in ".mat" file format after sensor dark-noise correction. As defined in [21], visible spectrum has a well accepted range of 380 - 780 nm though the range between 400 - 700nm as in [3], [4] may also be used. To keep the range wide and flexibility to the people who want to use the dataset, we selected the defined range of 380 - 780 nm in [21] for our dataset though visual stimulus might be weaker at the boundary of these ranges for human visual system [21]. Then, we rendered in sRGB colour images from hyperspectral images to create ground-truth salient object binary images by labelling the boundaries of salient objects.

<details>
<summary>中文介绍</summary>

经东京港码头公司许可，这些数据是在日本东京台场的东京海滨城的公园收集的。我们收集了 2017 年 8 月至 9 月期间天气晴朗或部分多云的几天内的数据。在每个数据收集日，都使用三脚架固定相机，以尽量减少图像的运动失真。我们尝试根据日光条件尽可能保持相机设置的曝光时间和增益固定，同时考虑像素值的饱和度或图像可见度。作为数据集用户的参考，我们在文本文件中提供相机设置，例如曝光时间和每个图像的增益值以及相应的数据。我们也没有对捕获的条带应用归一化。可以提高高光谱图像的质量，前景和背景区域之间的颜色对比度更高；然而，它也可能降低用于显著目标检测任务基准测试的数据集的难度。
在获得各种高光谱图像后，我们从大约五十个不同场景中选择了 60 张图像，条件如下：i）我们删除了由于场景中的运动而导致的扭曲图像（根据曝光时间，一张图像可能需要几秒钟的时间），ii）我们考虑了几个方面，例如显著物体大小的变化、图像上物体的空间位置、显著物体的数量、
前景-背景对比，iii) 一些图像具有相同的场景，但对象位置、对象距离或对象数量不同。
为了方便显著目标检测任务，我们裁剪了可见光谱周围的光谱带，并在传感器暗噪声校正后以“.mat”文件格式保存每个场景的超立方体。如 [21] 中所定义，可见光谱具有 380 - 780 nm 的广泛接受范围，尽管也可以使用 [3]、[4] 中的 400 - 700 nm 之间的范围。为了让想要使用数据集的人保持范围广泛和灵活性，我们在[21]中为我们的数据集选择了380 - 780 nm的定义范围，尽管人类视觉系统[21]在这些范围的边界处视觉刺激可能较弱。然后，我们从高光谱图像中渲染 sRGB 彩色图像，通过标记显著对象的边界来创建真实的显著对象二值图像。

</details>

#### KAIST Salient Pedestrian Dataset

* Paper: [Pedestrian Detection in Thermal Images Using Saliency Maps](https://ieeexplore.ieee.org/document/9025382)
* Project:
  * [https://information-fusion-lab-umass.github.io/Salient-Pedestrian-Detection/](https://information-fusion-lab-umass.github.io/Salient-Pedestrian-Detection/)
* Download: See [https://github.com/Information-Fusion-Lab-Umass/Salient-Pedestrian-Detection](https://github.com/Information-Fusion-Lab-Umass/Salient-Pedestrian-Detection)

We select 1702 images from the training set of the KAIST Multispectral Pedestrian dataset, by sampling every 15th image from all the images captured during the day and every 10thimage from all the images captured during the night, which contain pedestrians. These images were selected in order to have approximately the same number of images captured on both times of the day (913 day images and 789 night images), containing 4170 instances of pedestrians. We manually annotate these images using the VGG Image Annotator tool to generate the ground truth saliency masks based on the location of the bounding boxes on pedestrians in the original dataset. Additionally, we create a set of 362 images with similar annotations from the test set to validate our deep saliency detection networks, with 193 day images and 169 night images, containing 1029 instances of pedestrians.

<details>
<summary>中文介绍</summary>

我们从 KAIST 多光谱行人数据集的训练集中选择了 1702 个图像，从白天捕获的所有图像中每 15 个图像采样一次，从夜间捕获的所有图像中每 10 个图像采样一次，其中包含行人。选择这些图像的目的是为了在一天中的两个时间捕获大致相同数量的图像（913 张白天图像和 789 张夜间图像），其中包含 4170 个行人实例。我们使用 VGG 图像注释器工具手动注释这些图像，以根据原始数据集中行人边界框的位置生成真值显著性掩模。此外，我们从测试集中创建了一组具有相似注释的 362 个图像，以验证我们的深度显著性检测网络，其中包含 193 个白天图像和 169 个夜间图像，包含 1029 个行人实例。

</details>

#### Grayscale-Thermal Foreground Detection Dataset

* Paper: [WELD: Weighted Low-rank Decomposition for Robust Grayscale-Thermal Foreground Detection](https://ieeexplore.ieee.org/document/7457366)
* Project:
  * [http://www.sysu-hcp.net/resources/datasets/index.html](http://www.sysu-hcp.net/resources/datasets/index.html)
  * [http://vision.sysu.edu.cn/projects/grayscale_thermal_detection/](http://vision.sysu.edu.cn/projects/grayscale_thermal_detection/)

It is urgent need to study the multi-model moving object detection due to its own shortness of inadequate of single model videos. However, almost no complete good multi-model datasets to use, thus, we proposed a multi-model moving object detection dataset and the specific details as followings. Our multi-model moving object detection dataset mainly considered 7 challenges, i.e. interminttent motion, low illumination, bad weather, intense shadow, dynamic scene, background clutter, thermal crossover et al.

The following main aspects are taken into account in creating the grayscale-thermal video: 1. Scene category. Including laboratory rooms, campus roads, playgrounds and water pools et al. 2. Object category. Including rigid and non-rigid objects, such as vehicles, pedestrians and animals. 3. Intermittent motion. 4. Shadow effect. 5. Illumination condition. 6. Background factor.

<details>
<summary>中文介绍</summary>

由于单模型视频自身的不足，多模型运动目标检测亟待研究。然而，几乎没有完整的、好的多模型数据集可供使用，因此，我们提出了一个多模型运动物体检测数据集，具体细节如下。我们的多模型运动物体检测数据集主要考虑7个挑战，即间歇运动、低光照、恶劣天气、强烈阴影、动态场景、背景杂波、热交叉等。

创建灰度热视频主要考虑以下几个方面： 1.场景类别。包括实验室、校园道路、操场和水池等。 2.对象类别。包括刚性和非刚性物体，例如车辆、行人和动物。 3.间歇性运动。 4.阴影效果。 5、光照条件。 6.背景因素。

</details>

## COD (Camouflaged/Concealed Object Detection)

### RGB Image COD

#### NC4K

* Paper: [Simultaneously Localize, Segment and Rank the Camouflaged Objects](https://arxiv.org/abs/2103.04011)
* Project: [https://github.com/JingZhang617/COD-Rank-Localize-and-Segment](https://github.com/JingZhang617/COD-Rank-Localize-and-Segment)
* Download:
  + Baidu Pan: [https://pan.baidu.com/s/1bG4F2KJ_4UJG_7XG6ZNBHA](https://pan.baidu.com/s/1bG4F2KJ_4UJG_7XG6ZNBHA) (d581)
  + Google Drive: [https://drive.google.com/file/d/1kzpX_U3gbgO9MuwZIWTuRVpiB7V6yrAQ/view?usp=sharing](https://drive.google.com/file/d/1kzpX_U3gbgO9MuwZIWTuRVpiB7V6yrAQ/view?usp=sharing)

As far as we know, there only exists one large camouflaged object testing dataset, the COD10K, while the sizes of other testing datasets are less than 300. We then contribute another camouflaged object testing dataset, namely NC4K, which includes 4,121 images downloaded from the Internet. The new testing dataset can be used to evaluate the generalization ability of existing models.

<details>
<summary>中文介绍</summary>

据我们所知，只有一个大型伪装物体测试数据集COD10K，而其他测试数据集的大小都小于300。然后我们贡献了另一个伪装物体测试数据集NC4K，其中包括从互联网下载的4,121张图像。新的测试数据集可用于评估现有模型的泛化能力。

</details>

#### COD10K

* Paper: [Camouflaged Object Detection](https://openaccess.thecvf.com/content_CVPR_2020/papers/Fan_Camouflaged_Object_Detection_CVPR_2020_paper.pdf)
* Project: [https://dengpingfan.github.io/pages/COD.html](https://dengpingfan.github.io/pages/COD.html)
* Download:
  + Google Drive: [https://drive.google.com/file/d/1vRYAie0JcNStcSwagmCq55eirGyMYGm5/view?usp=sharing](https://drive.google.com/file/d/1vRYAie0JcNStcSwagmCq55eirGyMYGm5/view?usp=sharing)

We elaborately collect a novel dataset, called COD10K, which comprises 10,000 images covering camouflaged objects in various natural scenes, over 78 object categories. All the images are densely annotated with category, bounding-box, object-/instance-level, and mattinglevel labels. This dataset could serve as a catalyst for progressing many vision tasks, e.g., localization, segmentation, and alpha-matting, etc.

<details>
<summary>中文介绍</summary>

我们精心收集了一个名为 COD10K 的新颖数据集，其中包含 10,000 张图像，涵盖各种自然场景中的伪装物体，超过 78 个物体类别。所有图像都用类别、边界框、对象/实例级别和抠图级别标签进行了密集注释。该数据集可以作为推进许多视觉任务的催化剂，例如定位、分割和 alpha 抠图等。

</details>

#### CAMO

* Paper: [Anabranch network for camouflaged object segmentation](https://doi.org/10.1016/j.cviu.2019.04.006)
* Project:
  * [https://sites.google.com/view/ltnghia/research/camo](https://sites.google.com/view/ltnghia/research/camo)
  * [https://github.com/ltnghia/ANet](https://github.com/ltnghia/ANet)
* Download:
  * Official: [https://drive.google.com/open?id=1h-OqZdwkuPhBvGcVAwmh0f1NGqlH_4B6](https://drive.google.com/open?id=1h-OqZdwkuPhBvGcVAwmh0f1NGqlH_4B6)

Camouflaged Object (CAMO) dataset specifically designed for the task of camouflaged object segmentation. We focus on two categories, i.e., naturally camouflaged objects and artificially camouflaged objects, which usually correspond to animals and humans in the real world, respectively.

Camouflaged object images consists of 1250 images (1000 images for the training set and 250 images for the testing set). Non-camouflaged object images are collected from the MS-COCO dataset (1000 images for the training set and 250 images for the testing set).

CAMO has objectness mask ground-truth.

<details>
<summary>中文介绍</summary>

伪装对象（CAMO）数据集专门为伪装对象分割任务而设计。我们关注两类，即自然伪装的物体和人工伪装的物体，它们通常分别对应于现实世界中的动物和人类。

伪装物体图像由 1250 张图像组成（训练集 1000 张图像，测试集 250 张图像）。非伪装物体图像是从 MS-COCO 数据集中收集的（训练集有 1000 张图像，测试集有 250 张图像）。

CAMO 具有客观性掩盖事实真相。

</details>

#### CHAMELEON

* Project: [Animal Camouflage Analysis: CHAMELEON Database](https://www.polsl.pl/rau6/chameleon-database-animal-camouflage-analysis/)
* Download: Unavailable

The data set was crafted manually. In order to avoid personal bias, authors five fellow students were asked to collect a pool of camouflaged animals images and manually annotate its areas. The images were taken from the Internet, selected using Google image search using the 'camouflaged animal ' keyword. They were selected in order to present various camouflage efficiency – from animals clearly visible to almost invisible. Thanks to this a test pool was gathered, containing 76 photos (Fig. 2), which were taken by independent photographers who marked these as good examples of camouflaged animals. Next, image segments were annotated (Fig. 3) into four categories – C0 non-masking background (blue), C1 masking background (green), C2 masked foreground (black), C3 non-masked foreground (red).

The online survey was prepared using the Google forms. The users were requested to evaluate the visibility of a hidden animal with a numerical scale from 1 to 5, where ends of the scale were described as 'animal is in plain sight' and 'what animal'. The questionnaire form allowed to collect 191 answers from different countries. Then, in order to compensate personal bias, the raw responses were standardized using z-scores per person and then re-scaled backward to 1 to 5 scale. Z-scoring is computed as (where: i denotes user index, j denotes image index):

<details>
<summary>中文介绍</summary>

该数据集是手动制作的。为了避免个人偏见，作者要求五名同学收集一组伪装动物图像并手动注释其区域。这些图像取自互联网，通过谷歌图像搜索使用“伪装动物”关键字进行选择。选择它们是为了展示各种伪装效率——从动物清晰可见到几乎看不见。由此收集了一个测试库，其中包含 76 张照片（图 2），这些照片是由独立摄影师拍摄的，他们将这些照片标记为伪装动物的良好范例。接下来，图像片段被注释为四类（图 3）——C0 非遮蔽背景（蓝色）、C1 遮蔽背景（绿色）、C2 遮蔽前景（黑色）、C3 非遮蔽前景（红色）。

在线调查是使用谷歌表格准备的。用户被要求用从 1 到 5 的数字等级来评估隐藏动物的可见性，其中等级的末端被描述为“动物在明显的视野中”和“什么动物”。该调查问卷收集了来自不同国家的 191 个答案。然后，为了补偿个人偏见，使用每人的 z 分数对原始反应进行标准化，然后重新调整到 1 到 5 的等级。 Z 评分计算如下（其中：i 表示用户索引，j 表示图像索引）：

</details>

#### CPD1K: Camouflaged People Dataset

* Paper: [Detection of People With Camouflage Pattern Via Dense Deconvolution Network](https://ieeexplore.ieee.org/document/8336933)
* Project: [https://github.com/xfflyer/Camouflaged-people-detection](https://github.com/xfflyer/Camouflaged-people-detection)
* Download: [https://github.com/xfflyer/Camouflaged-Data](https://github.com/xfflyer/Camouflaged-Data)

To build the dataset, we initially collected the video clips of 20 groups, which included the people with different kinds of camouflage patterns. These videos are captured by a fixed camera to evaluate the camouflage performance of different camouflage patterns in each corresponding natural scenes. At the same time, they are naturally suitable for the evaluation of camouflaged people detection methods.

We take into account several factors that influence camouflage performance comprehensively. They include different styles of camouflage patterns, abundant natural scenes, different illumination and occlusion conditions, and different scales and postures of people. At last, 1000 images of size 480 × 854 are selected from the video clips. All the images are labeled as the pixel-level ground-truth annotation.

<details>
<summary>中文介绍</summary>

为了构建数据集，我们最初收集了 20 组的视频片段，其中包括具有不同种类迷彩图案的人。这些视频由固定摄像机拍摄，以评估不同迷彩图案在每个对应的自然场景中的迷彩性能。同时，它们天然适合评估伪装人员检测方法。

我们综合考虑了影响伪装性能的几个因素。它们包括不同风格的迷彩图案、丰富的自然场景、不同的光照和遮挡条件以及不同的人物尺度和姿势。最后，从视频片段中选择1000张尺寸为480×854的图像。所有图像都被标记为像素级真值注释。

</details>

#### CPD-UAV

* Paper: [CPD-UAV: A Benchmark Dataset for Detecting Personnel Visually Blended with the Environment Under UAV Perspective](https://doi.org/10.3390/drones10060447)
* Download: Not specified in the paper page.

CPD-UAV is a UAV-perspective camouflaged object detection benchmark for detecting visually blended individuals in aerial monitoring and search-and-rescue scenarios. It contains 1061 high-resolution images with pixel-level masks, covering diverse terrains and flight altitudes.

The dataset focuses on the domain gap between conventional natural-scene COD benchmarks and practical UAV scenarios, where artificial camouflage, top-down or oblique views, extreme scale variation, tiny targets, and vanishing boundaries make precise segmentation difficult. The paper reports that CPD-UAV is constructed from UAV videos and web-sourced images, followed by SAM-assisted annotation and expert cross-validation.

<details>
<summary>中文介绍</summary>

CPD-UAV 是一种无人机视角伪装物体检测基准，用于在空中监控和搜救场景中检测视觉混合个体。它包含 1061 张具有像素级掩模的高分辨率图像，涵盖不同的地形和飞行高度。

该数据集重点关注传统自然场景 COD 基准与实际无人机场景之间的领域差距，其中人工伪装、自上而下或倾斜视图、极端尺度变化、微小目标和消失边界使得精确分割变得困难。该论文报告称，CPD-UAV 由无人机视频和网络来源的图像构建而成，然后进行 SAM 辅助注释和专家交叉验证。

</details>

### RGB Video COD

#### MoCA-Mask

* Paper: [Implicit Motion Handling for Video Camouflaged Object Detection](http://arxiv.org/abs/2203.07363)
* Project:
  * [https://xueliancheng.github.io/SLT-Net-project/](https://xueliancheng.github.io/SLT-Net-project/)
  * [https://github.com/XuelianCheng/SLT-Net](https://github.com/XuelianCheng/SLT-Net)
* Download: [https://drive.google.com/file/d/1FB24BGVrPOeUpmYbKZJYL5ermqUvBo_6/view?usp=sharing](https://drive.google.com/file/d/1FB24BGVrPOeUpmYbKZJYL5ermqUvBo_6/view?usp=sharing)
  * More details can be found at [https://xueliancheng.github.io/SLT-Net-project/](https://xueliancheng.github.io/SLT-Net-project/)

The new dataset, or MoCA-Mask for short, contains 87 video sequences with 22,939 frames in total with pixel-wise ground truth masks. MoCA-Mask encapsulates a variety of challenges, such as complex backgrounds and tiny and well camouflaged objects. We provide annotations, bounding boxes, and dense segmentation masks for every five frames for all the videos in the dataset.

<details>
<summary>中文介绍</summary>

新数据集（简称 MoCA-Mask）包含 87 个视频序列，总共 22,939 帧，并带有逐像素地面真实掩模。 MoCA-Mask 封装了各种挑战，例如复杂的背景和微小且伪装良好的物体。我们为数据集中所有视频的每五帧提供注释、边界框和密集分割掩模。

</details>

#### CAD (Camouflaged Animation Dataset)

* Paper: [It's Moving! A Probabilistic Model for Causal Motion Segmentation in Moving Camera Videos](https://arxiv.org/abs/1604.00136)
* Project: [Causal Motion Segmentation in Moving Camera Videos](https://vis-www.cs.umass.edu/motionSegmentation/)
* Download:
  * [Camouflaged Animal Dataset](http://vis-www.cs.umass.edu/motionSegmentation/data/CamouflagedAnimalDataset.zip)
  * [Binary Mask from SLT-Net](https://drive.google.com/file/d/1LwswF3axQ0BSC6DllTpyL77Ktruy-6M6/view?usp=sharing)

#### YUV20K

* Paper: [YUV20K: A Complexity-Driven Benchmark and Trajectory-Aware Alignment Model for Video Camouflaged Object Detection](https://arxiv.org/abs/2604.09985)
* Project: [https://github.com/K1NSA/YUV20K](https://github.com/K1NSA/YUV20K)
* Download: See [https://github.com/K1NSA/YUV20K](https://github.com/K1NSA/YUV20K)

YUV20K is a pixel-level annotated, complexity-driven benchmark for video camouflaged object detection (VCOD). It contains 24,295 annotated frames from 91 scenes and 47 species, focusing on challenging spatiotemporal scenarios such as large-displacement motion, camera motion, occlusion, multiple objects, hunting, and tiny objects. The project also introduces Motion Feature Stabilization (MFS) and Trajectory-Aware Alignment (TAA) modules for handling motion-induced appearance instability and temporal feature misalignment.

The dataset is planned to be released through Baidu Netdisk and Google Drive. According to the project page, users need to complete a CC BY-NC 4.0 data access agreement and email it to obtain the unzip password.

<details>
<summary>中文介绍</summary>

YUV20K 是用于视频伪装对象检测 (VCOD) 的像素级注释、复杂性驱动的基准。它包含来自 91 个场景和 47 个物种的 24,295 个带注释的帧，重点关注具有挑战性的时空场景，例如大位移运动、相机运动、遮挡、多个物体、狩猎和微小物体。该项目还引入了运动特征稳定（MFS）和轨迹感知对齐（TAA）模块，用于处理运动引起的外观不稳定和时间特征错位。

该数据集计划通过百度网盘和Google Drive发布。根据项目页面，用户需要填写一份CC BY-NC 4.0数据访问协议并通过电子邮件发送以获得解压密码。

</details>

#### CAMotion

* Paper: [CAMotion: A High-Quality Benchmark for Camouflaged Moving Object Detection in the Wild](https://arxiv.org/abs/2604.08287)
* Project:
  * [https://www.camotion.focuslab.net.cn/](https://www.camotion.focuslab.net.cn/)
  * [https://github.com/Garyson1204/CAMotion](https://github.com/Garyson1204/CAMotion)
* Download:
  * Google Drive: [https://drive.google.com/file/d/1YzNdlDhsfgXTZ-Ya1w9wn3SjTXwU2xFs/view?usp=drive_link](https://drive.google.com/file/d/1YzNdlDhsfgXTZ-Ya1w9wn3SjTXwU2xFs/view?usp=drive_link)
  * Baidu Netdisk: See [https://www.camotion.focuslab.net.cn/](https://www.camotion.focuslab.net.cn/)
  * Depth and Optical Flow: [Google Drive](https://drive.google.com/file/d/1xEx1BMHFJaOGl_SJ8r5vRsNTfbRURRjs/view?usp=sharing) / Baidu NetDisk: See [https://www.camotion.focuslab.net.cn/](https://www.camotion.focuslab.net.cn/)

CAMotion is a high-quality benchmark for camouflaged moving object detection in the wild. It contains 149,319 image frames, 30,028 annotated frames, and 151 species, making it substantially larger than MoCA-Mask in both frame count and species coverage. CAMotion provides pixel-level annotations and sequence-level/frame-level statistics for analyzing motion characteristics in challenging VCOD scenarios.

The benchmark labels eight attributes for detailed evaluation: uncertain edge (UE), big object (BO), multiple objects (MO), small object (SO), occlusion (OC), shape complexity (SC), out-of-view (OV), and motion blur (MB). The project also reports evaluations of 18 COD/VCOD models with metrics including S-measure, weighted F-measure, mean E-measure, MAE, mean Dice, and mean IoU.

<details>
<summary>中文介绍</summary>

CAMotion 是野外伪装移动物体检测的高质量基准。它包含 149,319 个图像帧、30,028 个带注释的帧和 151 个物种，使其在帧数和物种覆盖范围上都远远大于 MoCA-Mask。 CAMotion 提供像素级注释和序列级/帧级统计数据，用于分析具有挑战性的 VCOD 场景中的运动特征。

该基准标记了八个属性进行详细评估：不确定边缘（UE）、大物体（BO）、多物体（MO）、小物体（SO）、遮挡（OC）、形状复杂性（SC）、视野外（OV）和运动模糊（MB）。该项目还报告了对 18 个 COD/VCOD 模型的评估，其指标包括 S-measure、加权 F-measure、平均 E-measure、MAE、平均 Dice 和平均 IoU。

</details>

### RGB-T Image COD

#### Camo-M3FD

* Paper: [Camo-M3FD: A New Benchmark Dataset for Cross-Spectral Camouflaged Pedestrian Detection](https://arxiv.org/abs/2604.16582)
* Project: [https://cod-espol.github.io/Camo-M3FD/](https://cod-espol.github.io/Camo-M3FD/)
* Download: [https://www.kaggle.com/datasets/hvelesaca/camo-m3fd](https://www.kaggle.com/datasets/hvelesaca/camo-m3fd)

Camo-M3FD is a benchmark for cross-spectral camouflaged pedestrian detection derived from the M3FD dataset. It consists of 614 registered visible-thermal image pairs with high-quality pixel-level masks, focusing on safety-critical pedestrian cases where foreground and background have high visual similarity.

The dataset is curated from pedestrian-centric M3FD samples using quantitative camouflage metrics for foreground-background similarity in color, texture, and boundary consistency. The final split follows an 80/10/10 protocol: 492 pairs for training, 61 for validation, and 61 for testing. The project benchmarks state-of-the-art COD methods on visible, thermal, and visible+thermal inputs, showing that thermal cues improve localization while multispectral fusion helps refine structural details.

<details>
<summary>中文介绍</summary>

Camo-M3FD 是源自 M3FD 数据集的跨光谱伪装行人检测的基准。它由 614 个注册的可见热图像对组成，具有高质量的像素级掩模，重点关注前景和背景具有高度视觉相似性的安全关键行人案例。

该数据集是根据以行人为中心的 M3FD 样本进行整理的，使用定量伪装指标来确定颜色、纹理和边界一致性方面的前景-背景相似性。最终的分割遵循 80/10/10 协议：492 对用于训练，61 对用于验证，61 对用于测试。该项目对可见光、热能和可见光+热能输入的最先进 COD 方法进行了基准测试，表明热线索可改善定位，而多光谱融合有助于细化结构细节。

</details>

### RGB-D Image COD

#### ACOD-12K

* Paper: [Depth-Aware Concealed Crop Detection in Dense Agricultural Scenes](https://openaccess.thecvf.com/content/CVPR2024/papers/Wang_Depth-Aware_Concealed_Crop_Detection_in_Dense_Agricultural_Scenes_CVPR_2024_paper.pdf)
* Project: [RISNet](https://github.com/Kki2Eve/RISNet)
* Download: <https://github.com/Kki2Eve/RISNet?tab=readme-ov-file#datasets>

In this paper, we introduce a new benchmark named Concealed Crop Detection (CCD), designed for identifying concealed objects in dense agricultural scenes.
We observe that unimodal information lacks the capacity to discern subtle distinctions between objects and backgrounds.
To overcome this limitation, we integrate depth maps to supplement spatial information absent in RGB data.
The geometric priors from depth maps effectively mitigate interference caused by noise, thereby enhancing CCD performance.
To facilitate research on CCD, we have curated an extensive RGB-D dataset, ACOD-12K.
Leveraging the ZED2i depth camera during fieldwork, we capture 6092 images of concealed objects within dense agricultural scenes, simultaneously recording corresponding depth images.
In comparison to the existing COD datasets, ACOD-12K exhibits several advantages:
* ACOD-12K is the sole existing multi-modal COD dataset.
* ACOD-12K is the largest-scale COD dataset with the
highest image resolution among the existing datasets.
* ACOD-12K boasts a higher object density, with these objects situated in diverse scenes and distributed randomly
across different positions within the images.
* In contrast to the current COD datasets, ACOD-12K focuses on the distinctive challenges presented by concealed objects in dense agricultural scenes.

<details>
<summary>中文介绍</summary>

在本文中，我们介绍了一种名为隐藏作物检测（CCD）的新基准，旨在识别密集农业场景中的隐藏物体。
我们观察到单峰信息缺乏辨别物体和背景之间细微区别的能力。
为了克服这个限制，我们集成深度图来补充 RGB 数据中缺少的空间信息。
深度图的几何先验有效地减轻了噪声造成的干扰，从而提高了CCD的性能。
为了促进 CCD 的研究，我们整理了一个广泛的 RGB-D 数据集 ACOD-12K。
在野外工作中，我们利用 ZED2i 深度相机捕获了密集农业场景中隐藏物体的 6092 张图像，同时记录了相应的深度图像。
与现有的 COD 数据集相比，ACOD-12K 具有以下几个优点：
* ACOD-12K 是唯一现有的多模式 COD 数据集。
* ACOD-12K 是规模最大的 COD 数据集
现有数据集中最高的图像分辨率。
* ACOD-12K拥有更高的物体密度，这些物体位于不同的场景中并且随机分布
跨越图像内的不同位置。
* 与当前的 COD 数据集相比，ACOD-12K 重点关注密集农业场景中隐藏物体带来的独特挑战。

</details>

#### CODD

* Paper: [A new benchmark for camouflaged object detection: RGB-D camouflaged object detection dataset](https://www.degruyter.com/document/doi/10.1515/phys-2024-0060/html)
* Download: [CODD-Dateset](https://github.com/zcc0616/CODD-Dateset)

This dataset is obtained by converting the existing salient object detection RGB-D datasets by image-to-image translation techniques, which is comparable to the current widely used camouflaged object detection dataset in terms of diversity and complexity.

<details>
<summary>中文介绍</summary>

该数据集是通过图像到图像转换技术转换现有的显著目标检测RGB-D数据集而获得的，在多样性和复杂性方面与当前广泛使用的伪装目标检测数据集相当。

</details>

### Terahertz Image COS/COD

#### Active Terahertz Imaging Datasets

* Paper:
  * [Concealed Object Segmentation in Terahertz Imaging via Adversarial Learning](https://www.sciencedirect.com/science/article/abs/pii/S0030402619304991)
  * [Active Terahertz Imaging Dataset for Concealed Object Detection](https://arxiv.org/abs/2105.03677)
* Project: [https://linglix.github.io/THz_Dataset/](https://linglix.github.io/THz_Dataset/)
* Download:
  * [Google Drive](https://drive.google.com/drive/folders/1A6LiyWAvRmKIJN5yXQZ3HxZVwNEFz8uV?usp=sharing)
  * [Baidu Netdisk](https://pan.baidu.com/s/1MRPyeMtzCQRO5ydgX0rSHA) (x3od)

The active Terahertz imaging datasets are designed for concealed object segmentation and concealed object detection in security inspection scenarios. The segmentation dataset is organized into training, validation, and testing splits with pixel-level masks. The detection dataset contains 3,157 JPEG images acquired by a 140 GHz active Terahertz imaging system with a spatial resolution of 5 mm × 5 mm. It covers 11 concealed-object classes, 0–3 objects per image, front and back views of 10 human subjects, and diverse object positions, clothing, materials, and poses.

The detection annotations provide bounding boxes and class labels in Pascal VOC format. The official split contains 2,555 training images and 602 testing images, with 1,349 labeled concealed objects in total. The released directories are `THZ_dataset_seg_IMG/{train,val,test}` for segmentation and `THZ_dataset_det_VOC/{Annotations,JPEGImages}` for detection.

<details>
<summary>中文介绍</summary>

主动太赫兹成像数据集专为安检场景中的隐藏物体分割和隐藏物体检测而设计。分割数据集被组织成带有像素级掩模的训练、验证和测试分割。检测数据集包含由 140 GHz 主动太赫兹成像系统采集的 3,157 张 JPEG 图像，空间分辨率为 5 mm × 5 mm。它涵盖 11 个隐藏物体类别、每张图像 0-3 个物体、10 个人类主体的前视图和后视图，以及不同的物体位置、服装、材料和姿势。

检测注释提供 Pascal VOC 格式的边界框和类标签。官方划分包含 2,555 张训练图像和 602 张测试图像，共标注 1,349 个隐藏物体。发布的目录是用于分割的`THZ_dataset_seg_IMG/{train,val,test}`和用于检测的`THZ_dataset_det_VOC/{Annotations,JPEGImages}`。

</details>

### Open-Vocabulary Camouflaged Object Segmentation

#### OVCamo

* Paper: [Open-Vocabulary Camouflaged Object Segmentation](https://arxiv.org/abs/2311.11241)
* Project: [OVCOS: Open-Vocabulary Camouflaged Object Segmentation](https://lartpang.github.io/docs/ovcamo.html)
* Download: [Github Releases](https://github.com/lartpang/OVCamo/releases/tag/dataset-v1.0)

Our data is collected from existing CSU datasets that have finely annotated segmentation maps. Specifically, the OVCamo integrates 11,483 hand-selected images covering 75 object classes reconstructed from several public datasets.

<details>
<summary>中文介绍</summary>

我们的数据是从现有的 CSU 数据集中收集的，这些数据集具有精细注释的分割图。具体来说，OVCamo 集成了 11,483 个手工选择的图像，涵盖从多个公共数据集重建的 75 个对象类别。

</details>

## DBD (Defocus Blur Detection)

### CUHK

- Paper: [Discriminative Blur Detection Features](https://ieeexplore.ieee.org/document/6909775)
- Project: <https://www.cse.cuhk.edu.hk/leojia/projects/dblurdetect/>
- Download: <https://www.cse.cuhk.edu.hk/leojia/projects/dblurdetect/dataset.html>

We build a new blur detection dataset that contains 1000 images with human labeled ground-truth blur regions. These data provide useful resource to understand blur with respect to structure diversity in natural images. It enables training and testing, which is traditionally hard to implement without suitable data. Ground truth masks are produced by 10 helpers. These images are collected from internet. They consist of images with out-of-focus blur and partial motion blur. Some sample images are shown in the above figure.

<details>
<summary>中文介绍</summary>

我们构建了一个新的模糊检测数据集，其中包含 1000 张带有人类标记的真实模糊区域的图像。这些数据为理解自然图像中结构多样性的模糊提供了有用的资源。它可以实现培训和测试，而这在传统上如果没有合适的数据就很难实现。 Ground Truth 面具由 10 名助手制作。这些图像是从互联网收集的。它们由具有失焦模糊和部分运动模糊的图像组成。上图显示了一些示例图像。

</details>

### DUT

#### Real-V1

- Paper: [Defocus Blur Detection via Multi-stream Bottom-Top-Bottom Fully Convolutional Network](https://www.computer.org/csdl/proceedings-article/cvpr/2018/642000d080/17D45WUj90B)

To facilitate the study and evaluation of defo cus blur detection (DBD) methods, we construct a new DBD dataset consisting of 500 images with pixel-wise annotations. We note that the proposed dataset is very challenging since numerous images contain homogeneous regions, low contrast focal regions and background clutter.

<details>
<summary>中文介绍</summary>

为了促进散焦模糊检测（DBD）方法的研究和评估，我们构建了一个新的 DBD 数据集，该数据集由 500 张带有像素级注释的图像组成。我们注意到，所提出的数据集非常具有挑战性，因为大量图像包含均匀区域、低对比度焦点区域和背景杂乱。

</details>

#### Real-V2

- Paper: [Defocus Blur Detection via Multi-Stream Bottom-Top-Bottom Network](https://ieeexplore.ieee.org/document/8673588)

We extend the previous dataset [Defocus Blur Detection via Multi-stream Bottom-Top-Bottom Fully Convolutional Network] by adding a training part with 600 challenging images with pixel-level annotations and thereby achieving the first attempt to construct a defocus blur dataset consisting of training and testing parts. There exist several characteristics for the images in our dataset: (1) There are various scenes; (2) Images contain the homogeneous regions with different scales; (3) The background (unfocused area) is complex; and (4) The focused area has low contrast. To improve label accuracy, we demand three volunteers to annotate focused areas in all 1100 images individually using a custom designed interactive segmentation tool. In addition, our dataset is divided into two parts: 600 training images and 500 testing images.

<details>
<summary>中文介绍</summary>

我们扩展了之前的数据集[通过多流下-上-下全卷积网络进行散焦模糊检测]，添加了包含600张具有像素级注释的挑战性图像的训练部分，从而实现了构建由训练和测试部分组成的散焦模糊数据集的首次尝试。我们数据集中的图像存在以下几个特点：（1）场景多样； (2) 图像包含不同尺度的同质区域； （3）背景（非聚焦区域）复杂； (4)聚焦区域对比度低。为了提高标签准确性，我们要求三名志愿者使用定制设计的交互式分割工具分别对所有 1100 张图像中的重点区域进行注释。此外，我们的数据集分为两部分：600 张训练图像和 500 张测试图像。

</details>

#### Simulated Dataset

We collect 2000 clear images from the Berkeley segmentation dataset [45] and uncompressed colour image dataset [46]. To simulate the blur images for the DBD task, we first adopt a Gaussian filter for each image to smooth half of the image as the out-of-focus blur region, and the remaining half as the in-focus region. Then, four blurred versions can be obtained by smoothing regions of different positions (up, down, left and right) for each image. For each blurred version, we use a Gaussian filter with a standard deviation of 2 and a window of 7x7 to repeatedly blur the image five times. Therefore, for each image, we can obtain 20 simulated images (four blurred versions and five different blurring levels for each version).

<details>
<summary>中文介绍</summary>

我们从 Berkeley 分割数据集 [45] 和未压缩的彩色图像数据集 [46] 中收集了 2000 张清晰图像。为了模拟 DBD 任务的模糊图像，我们首先对每个图像采用高斯滤波器，以平滑图像的一半作为失焦模糊区域，剩余一半作为对焦区域。然后，通过对每个图像的不同位置（上、下、左、右）的区域进行平滑，可以获得四个模糊版本。对于每个模糊版本，我们使用标准差为 2 和窗口为 7x7 的高斯滤波器来重复模糊图像五次。因此，对于每个图像，我们可以获得 20 个模拟图像（四个模糊版本，每个版本有五个不同的模糊级别）。

</details>

### CTCUG

- Paper: [DeFusionNET: Defocus Blur Detection via Recurrently Fusing and Refining Discriminative Multi-Scale Deep Features](https://ieeexplore.ieee.org/document/9161280)

Based on our observations, in most of the images of above mentioned two datasets, the foreground objects are usually in-focus while the background is usually blurry, which leads to the fact that the blur detection methods may be biased to object regions and reduce to foreground/background segmentation. In reality, foreground objects with strong semantic meaning may also be defocused. In addition, the content contained in the images of previous datasets are easy, nearly no complex background or foreground. With these points in mind, we collect a new dataset (referred to as CTCUG) which contains 150 images with manual pixel-wise annotations. We invite five students to manually annotate the defocus areas from each image and the final annotated ground truths are obtained by averaging the results from the five independently labelled masks.

<details>
<summary>中文介绍</summary>

根据我们的观察，在上述两个数据集的大多数图像中，前景物体通常是清晰的，而背景通常是模糊的，这导致模糊检测方法可能会偏向于物体区域并减少到前景/背景分割。实际上，具有较强语义意义的前景物体也可能会散焦。此外，之前数据集的图像包含的内容很简单，几乎没有复杂的背景或前景。考虑到这些点，我们收集了一个新的数据集（称为 CTCUG），其中包含 150 张带有手动逐像素注释的图像。我们邀请五名学生手动注释每张图像的散焦区域，并通过对五个独立标记的掩模的结果进行平均来获得最终注释的基本事实。

</details>

### EBD

- Paper: [Depth and DOF Cues Make A Better Defocus Blur Detector](https://arxiv.org/abs/2306.11334)
- Project: <https://github.com/yuxinjin-whu/d-dffnet>

The test datasets mentioned above have several limitations, including a lack of high-resolution images and a limited number of images with wide or shallow depth of field. In response, we collected a new DBD test dataset (EBD) composed of 1605 high-resolution images, selected from the EBB! (Rendering natural camera bokeh effect with deep learning) dataset and manually annotated with pixel-wise labels to produce defocus maps. As for the images in the EBD dataset, 1305 have a shallow depth of field (achieved using an aperture size of f/1.8), resulting in a strong bokeh effect. The remaining 300 images have a wide depth of field (achieved using an aperture size of f/16), resulting in sharp photos. All images have a resolution around 1600x1024.

<details>
<summary>中文介绍</summary>

上述测试数据集存在一些局限性，包括缺乏高分辨率图像以及景深较宽或较浅的图像数量有限。作为回应，我们收集了一个新的 DBD 测试数据集 (EBD)，由 1605 张高分辨率图像组成，选自 EBB！ （通过深度学习渲染自然相机散景效果）数据集并使用像素级标签手动注释以生成散焦图。对于EBD数据集中的图像，1305具有浅景深（使用f/1.8的光圈大小实现），从而产生强烈的散景效果。其余 300 张图像具有较宽的景深（使用 f/16 的光圈大小实现），从而产生清晰的照片。所有图像的分辨率约为 1600x1024。

</details>

## Industrial Scene

### Crack Detection

* Target Characteristic: Tubular/Curvilinear Structure

#### T-CRACK & C-CRACK

* Paper: [EAFNet: Extraction-amplification-fusion network for tiny cracks detection](https://doi.org/10.1016/j.engappai.2024.108691)
* Project: <https://github.com/EAFNet/EAFNet>

T-CRACK dataset consists of six backgrounds: bituminous road surface, cement road surface, wall surface, bridge surface, glass surface and stone surface. There are 1898 images in the dataset, of which 1334 images are used for training, 197 images are used for validation and 367 images are used for testing. The images from the different datasets are taken at different angles, with different light resolutions and other conditions. Moreover, the distribution and shape of tiny cracks vary from one background to another. These make T-CRACK dataset challenging.

To verify the generalization ability of models, we add images with large cracks and images without cracks to T-CRACK dataset to form C-CRACK dataset. 2698 images in total are included in C-CRACK dataset, of which 1934 images are used for training, 487 images for validation and 277 images for testing.

<details>
<summary>中文介绍</summary>

T-CRACK数据集由六种背景组成：沥青路面、水泥路面、墙面、桥梁表面、玻璃表面和石材表面。数据集中有 1898 张图像，其中 1334 张图像用于训练，197 张图像用于验证，367 张图像用于测试。不同数据集的图像是在不同角度、不同光线分辨率和其他条件下拍摄的。此外，微小裂纹的分布和形状因背景而异。这些使得 T-CRACK 数据集具有挑战性。

为了验证模型的泛化能力，我们将有大裂纹的图像和无裂纹的图像添加到T-CRACK数据集中，形成C-CRACK数据集。 C-CRACK数据集中总共包含2698张图像，其中1934张图像用于训练，487张图像用于验证，277张图像用于测试。

</details>

### Surface Defect Detection

#### SD-saliency-900

* Paper: [Saliency detection for strip steel surface defects using multiple constraints and improved texture features](https://www.sciencedirect.com/science/article/pii/S0143816619317361)
* Project: <https://github.com/SongGuorong/MCITF>

We collected three kinds of typical defects as the benchmark database (i.e., SD-saliency-900) in our experiments, including Inclusion, Patches, and Scratches. In this database, each type of defect contains 300 images (the original resolution is 200×200 pixel). Then we contributed the corresponding pixel-wise binary maps, which are generated by the open annotation tool: LabelMe.

<details>
<summary>中文介绍</summary>

我们在实验中收集了三种典型缺陷作为基准数据库（即SD-saliency-900），包括Inclusion、Patches和Scratches。该数据库中，每种缺陷包含300张图像（原始分辨率为200×200像素）。然后我们贡献了相应的像素级二值图，这些图是由开放注释工具LabelMe生成的。

</details>

### AD (Anomaly Detection)

* Target Characteristic: Small, Multiple Types

#### MVTec AD

* Paper:
  * [MVTec AD – A Comprehensive Real-World Dataset for Unsupervised Anomaly Detection](https://www.mvtec.com/fileadmin/Redaktion/mvtec.com/company/research/datasets/mvtec_ad.pdf)
  * [The MVTec Anomaly Detection Dataset: A Comprehensive Real-World Dataset for Unsupervised Anomaly Detection](https://link.springer.com/content/pdf/10.1007/s11263-020-01400-4.pdf)
* Project: [https://www.mvtec.com/company/research/datasets/mvtec-ad](https://www.mvtec.com/company/research/datasets/mvtec-ad)

MVTec AD is a dataset for benchmarking anomaly detection methods with a focus on industrial inspection. It contains over 5000 high-resolution images divided into fifteen different object and texture categories. Each category comprises a set of defect-free training images and a test set of images with various kinds of defects as well as images without defects. Pixel-precise annotations of all anomalies are also provided.

<details>
<summary>中文介绍</summary>

MVTec AD 是一个用于对异常检测方法进行基准测试的数据集，重点关注工业检测。它包含超过 5000 张高分辨率图像，分为 15 个不同的对象和纹理类别。每个类别包括一组无缺陷的训练图像和一组具有各种缺陷的图像以及无缺陷的图像。还提供所有异常的像素精确注释。

</details>

#### MPDD

* Paper: [Deep learning-based defect detection of metal parts: evaluating current methods in complex conditions](https://ieeexplore.ieee.org/document/9631567)
* Project: [https://github.com/stepanje/mpdd](https://github.com/stepanje/mpdd)

It is focused on a domain of metal fabrication and it reflects real-world situations encountered on a human-operated production lines. The proposed dataset contains 6 classes of metal parts. For training, only samples without defects should be used, because it is assumed that semi-supervised or unsupervised AD methods will be used, as we cannot know all types of defects in advance. Testing samples contain parts with and without defects. Anomalous samples are provided with pixel-precise ground truth masks to enable evaluation of defect segmentation. All images were resized to 1024 x 1024 pixels. There are various types of defects available in the dataset, and overall they are intended to cover a wide range of scenarios that can be encountered in metal fabrication and painting industry.
All images in the dataset were taken using standard consumer-grade camera, we used two LED light sources to illuminate the scene from two separate positions to reduce shadows. In most cases, we also placed a neutral green screen in the background to make the samples more suitable for machine vision tasks, assuming that placing a background, e.g. on the real production line, is usually not an issue. To mimic complex conditions that must be faced when acquiring visual data in some industrial applications, we rotated and moved the components during image acquisition.

<details>
<summary>中文介绍</summary>

它专注于金属制造领域，反映了人工操作生产线上遇到的现实情况。建议的数据集包含 6 类金属零件。对于训练，只应使用没有缺陷的样本，因为假设将使用半监督或无监督 AD 方法，因为我们无法提前知道所有类型的缺陷。测试样品包含有缺陷和没有缺陷的零件。为异常样本提供像素精确的真值掩模，以实现缺陷分割的评估。所有图像的大小均调整为 1024 x 1024 像素。数据集中提供了各种类型的缺陷，总体而言，它们旨在涵盖金属制造和涂装行业中可能遇到的各种场景。
数据集中的所有图像均使用标准消费级相机拍摄，我们使用两个 LED 光源从两个不同的位置照亮场景以减少阴影。在大多数情况下，我们还在背景中放置了中性绿屏，以使样本更适合机器视觉任务，假设放置背景，例如在实际生产线上，通常不是问题。为了模拟在某些工业应用中采集视觉数据时必须面对的复杂条件，我们在图像采集过程中旋转和移动组件。

</details>

## Medical Scene

### Trichomonas Vaginalis Segmentation

* Target Characteristic: Small, Multiple, Sparse, Subcircular

#### TVMI3K

- Paper: [Trichomonas Vaginalis Segmentation in Microscope Images](https://arxiv.org/abs/2207.00973)
- Project: <https://github.com/CellRecog/cellRecog>

In this work, we collect the first large-scale Microscopic Image dataset of Trichomonas Vaginalis, called TVMI3K, which consists of 3,158 images covering Trichomonas of various appearances in diverse backgrounds, with high-quality annotations including object-level mask labels, object boundaries, and challenging attributes.

<details>
<summary>中文介绍</summary>

在这项工作中，我们收集了第一个大规模阴道毛滴虫显微图像数据集，称为 TVMI3K，它由 3,158 张图像组成，涵盖不同背景下各种外观的毛滴虫，并具有高质量注释，包括对象级掩模标签、对象边界和具有挑战性的属性。

</details>

### Vessel Segmentation

* Target Characteristic: Tubular/Curvilinear Structure

#### XCAD

- Paper: [Self-Supervised Vessel Segmentation via Adversarial Learning](https://doi.org/10.1109/ICCV48922.2021.00744)
- Project: <https://github.com/AISIGSJTU/SSVS>

We build an X-ray angiography coronary artery disease (XCAD) dataset with coronary angiography images obtained during stent placement using a General Electric Innova IGS 520 system. Each image has a resolution of 512x512 pixels with one channel. The train ing set contains 1621 mask frames and 1621 coronary an giograms. The testing set contains 126 independent coronary angiograms with vessel segmentation maps annotated by experienced radiologists. Note that the training set and the testing set have no shared samples.

<details>
<summary>中文介绍</summary>

我们使用通用电气 Innova IGS 520 系统在支架置入过程中获得的冠状动脉造影图像构建了 X 射线血管造影冠状动脉疾病 (XCAD) 数据集。每张图像的分辨率为 512x512 像素，具有一个通道。训练集包含 1621 个掩模帧和 1621 个冠状动脉造影图。该测试集包含 126 个独立的冠状动脉血管造影照片，以及由经验丰富的放射科医生注释的血管分割图。请注意，训练集和测试集没有共享样本。

</details>

## Segmentation

### VOS (Video Object Segmentation)

#### DAVIS

* Project: [https://davischallenge.org/index.html](https://davischallenge.org/index.html)
* Paper: [A Benchmark Dataset and Evaluation Methodology for Video Object Segmentation](https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Perazzi_A_Benchmark_Dataset_CVPR_2016_paper.pdf)
* Download:
  + [DAVIS 2016](https://davischallenge.org/davis2016/code.html) In each video sequence a single instance is annotated.
  + [DAVIS 2017](https://davischallenge.org/davis2017/code.html) In each video sequence multiple instances are annotated.

#### TAO-VOS

* Project: [https://www.vision.rwth-aachen.de/page/taovos](https://www.vision.rwth-aachen.de/page/taovos)
* Paper: [Reducing the Annotation Effort for Video Object Segmentation Datasets](https://arxiv.org/abs/2011.01142)
* Download, Mask Annotations (train + val): [https://www.vision.rwth-aachen.de/media/resource_files/taovos_v1_annotations_only.zip](https://www.vision.rwth-aachen.de/media/resource_files/taovos_v1_annotations_only.zip)

We annotated 126 validation sequences of the Tracking Any Object (TAO) dataset with segmentation masks for video object segmentation. Additionally, we annotated all 500 training sequences semi-automatically while ensuring a high quality (for details see paper below).

Compared to existing VOS datasets, sequences in TAO-VOS are significantly longer, cover more objects per sequence, and cover more different classes.

<details>
<summary>中文介绍</summary>

我们使用视频对象分割的分割掩码注释了跟踪任何对象 (TAO) 数据集的 126 个验证序列。此外，我们半自动注释了所有 500 个训练序列，同时确保高质量（详细信息请参阅下面的论文）。

与现有的 VOS 数据集相比，TAO-VOS 中的序列明显更长，每个序列覆盖更多对象，并覆盖更多不同的类。

</details>

#### OVOS

* Project: [https://ieee-dataport.org/documents/ovos-occluded-video-object-segmentation-dataset](https://ieee-dataport.org/documents/ovos-occluded-video-object-segmentation-dataset)
* Paper: [Region Aware Video Object Segmentation with Deep Motion Modeling](https://arxiv.org/abs/2207.10258)

OVOS is an extension of the training set of OVIS dataset in video instance segmentation since the segmentation of the first frame is not available for the validation set. To meet the format of DAVIS for convenient evaluation, we only select the objects that appear in the first frame as targets and resize videos to make their shortest size 480 pixels. OVOS comes with accurate annotations and includes severe object occlusions. The presented OVOS dataset contains 607 video sequences with a total of 42149 frames and 2034 objects, which is larger than the current largest YouTube-VOS 2019 validation set (507 videos with a total of 13710 frames).

<details>
<summary>中文介绍</summary>

OVOS是视频实例分割中OVIS数据集训练集的扩展，因为第一帧的分割不可用于验证集。为了满足DAVIS格式方便评估，我们只选择第一帧中出现的物体作为目标，并调整视频大小使其最短尺寸为480像素。 OVOS 具有准确的注释，并包含严重的对象遮挡。所提出的 OVOS 数据集包含 607 个视频序列，总共 42149 帧和 2034 个对象，这比当前最大的 YouTube-VOS 2019 验证集（507 个视频，总共 13710 帧）还要大。

</details>

### Image Segmentation

#### aNYU

aNYU dataset for semantic image segmentation with objects and visual attributes

* Paper: [Dense Semantic Image Segmentation with Objects and Attributes](http://kylezheng.org/densesegattobjdataset/denseseg4objatt_CVPR2014_Kyle.pdf)
* Project: [https://kylezheng.org/research-projects/densesegattobj/](https://kylezheng.org/research-projects/densesegattobj/)
* Download: [http://www.robots.ox.ac.uk/~szheng/aNYU/aNYU.tar.gz](http://www.robots.ox.ac.uk/~szheng/aNYU/aNYU.tar.gz)

aNYU is a dataset that augments the NYU v2 dataset with 11 additional visual attributes: 1: Wood(Material) 2: Painted(Material) 3: Paper(Material) 4: Glass(Material) 5: Brick(Material) 6: Metal(Material) 7: Flat(Shape) 8: Plastic(Material) 9: Textured(Material) 10: Glossy(Surface) 11: Shiny(Surface).
We have released this dataset (1449 Images in total, with train/validation split as follows. You can also randomly shuffle the 1449 images, and then take the top 725 images for training, then 100 images for validation, and the rest 624 images for the test).

<details>
<summary>中文介绍</summary>

用于使用对象和视觉属性进行语义图像分割的纽约大学数据集

aNYU 是一个数据集，它在 NYU v2 数据集上增加了 11 个附加视觉属性： 1: 木材（材料） 2: 涂漆（材料） 3: 纸张（材料） 4: 玻璃（材料） 5: 砖（材料） 6: 金属（材料） 7: 平面（形状） 8: 塑料（材料） 9: 纹理（材料） 10:有光泽（表面） 11：有光泽（表面）。
我们已经发布了这个数据集（总共1449张图像，训练/验证分割如下。您也可以随机洗牌这1449张图像，然后取前725张图像进行训练，然后取100张图像进行验证，其余624张图像进行测试）。

</details>

#### Supervisely Portrait Dataset

* Project: [https://supervise.ly/](https://supervise.ly/)

The dataset **consists of 5711 images, with 6884 high-quality annotated human body instances**. All steps were completed in-house at Supervisely, without any coding. More importantly, these steps were performed by in-house annotators without any machine learning expertise. The data scientists simply controlled and managed the process. The annotation team consisted of two members and the entire process took only 4 days.

<details>
<summary>中文介绍</summary>

数据集 **由5711张图片组成, 有6884个高质量的标注的人体实例**. 所有步骤在Supervisely内部完成的, 没有任何编码. 更重要的是, 这些步骤是被内部的注释器执行的, 没有任何机器学习专业知识. 数据科学家仅仅只是控制和管理这过程. 注释组由两名成员组成并且这整个过程只花了4天.

</details>

#### Clothing Parsing

* Paper: [Parsing Clothing in Fashion Photographs](http://vision.is.tohoku.ac.jp/~kyamagu/papers/yamaguchi_cvpr2012.pdf)
* Project: [http://vision.is.tohoku.ac.jp/~kyamagu/research/clothing_parsing/](http://vision.is.tohoku.ac.jp/~kyamagu/research/clothing_parsing/)
* Download: See [http://vision.is.tohoku.ac.jp/~kyamagu/research/clothing_parsing/](http://vision.is.tohoku.ac.jp/~kyamagu/research/clothing_parsing/)

We introduce a novel dataset, useful for training and testing clothing estimation techniques. This dataset consists of 158,235 photographs collected from Chictopia.com, a social networking website for fashion bloggers. On this website, fashionistas upload "outfit of the day" type pictures, designed to draw attention to their fashion choices or as a form of social interaction with peers. Because these are people who particularly care about their clothes they tend to display a wide range of styles, accessories, and garments. However, pictures are also often depicted in relatively simple poses (mostly standing), against relatively clean backgrounds, and without many other people in the picture. This makes for an ideal scenario for studying clothing! In addition, users also provide additional outfit information in the form of tags, comments, and links, etc (e.g. Fig 3). We make use of the tag portion of this meta-data to extract useful information about what clothing items might be present in each photo (but can also ignore this information if we want to study clothing parsing with no prior knowledge of items). Sometimes the tags are noisy or  incomplete, but often they cover the items in an outfit well. As a training and evaluation set, we select 685 photos with good visibility of the full body and covering a variety of clothing items. For this carefully selected subset, we design and make use of 2 Amazon Mechanical Turk jobs to gather annotations. The first Turk job gathers ground truth pose annotations for the usual 14 body parts. The second Turk job gathers ground truth clothing labels on superpixel regions. All annotations are verified and corrected if necessary to obtain high quality annotations.

<details>
<summary>中文介绍</summary>

我们引入了一个新颖的数据集，可用于训练和测试服装估计技术。该数据集包含从时尚博主社交网站 Chictopia.com 收集的 158,235 张照片。在这个网站上，时尚达人上传“每日服装”类型的图片，旨在引起人们对他们的时尚选择的关注，或者作为与同龄人进行社交互动的一种形式。因为这些人特别关心自己的衣服，所以他们倾向于展示各种款式、配饰和服装。然而，图片也经常以相对简单的姿势（主要是站立）描绘，背景相对干净，并且图片中没有很多其他人。这为学习服装提供了理想的场景！此外，用户还以标签、评论、链接等形式提供额外的着装信息（如图3）。我们利用此元数据的标签部分来提取有关每张照片中可能存在哪些服装的有用信息（但如果我们想在没有先验知识的情况下研究服装解析，也可以忽略此信息）。有时标签很杂乱或不完整，但通常它们可以很好地覆盖服装中的物品。作为训练和评估集，我们选择了 685 张全身可见度良好且涵盖各种服装项目的照片。对于这个精心挑选的子集，我们设计并使用 2 个 Amazon Mechanical Turk 作业来收集注释。第一项 Turk 工作收集常见 14 个身体部位的地面真实姿势注释。 Turk 的第二项工作是在超像素区域收集真实的服装标签。如有必要，所有注释都会经过验证和更正，以获得高质量的注释。

</details>

#### HumanParsing-Dataset

* Paper:
  * TPAMI 2015: [Deep Human Parsing with Active Template Regression](https://ieeexplore.ieee.org/document/7053923)
  * ICCV 2015: [Human Parsing with Contextualized Convolutional Neural Network](https://ieeexplore.ieee.org/document/7423822)
* Project:
  + [https://github.com/lemondan/HumanParsing-Dataset](https://github.com/lemondan/HumanParsing-Dataset)
  + [http://sysu-hcp.net/](http://sysu-hcp.net/)
* Download:
  * [http://sysu-hcp.net/resources/datasets/index.html](http://sysu-hcp.net/resources/datasets/index.html)
  * [http://pan.baidu.com/s/1qY8bToS](http://pan.baidu.com/s/1qY8bToS) (kjgk)

This human parsing dataset includes the detailed pixel-wise annotations for fashion images, which is proposed in our TPAMI paper "Deep Human Parsing with Active Template Regression", and ICCV 2015 paper "Human Parsing with Contextualized Convolutional Neural Network". This dataset contains 7700 images. We use 6000 images for training, 1000 for testing and 700 as the validation set.

<details>
<summary>中文介绍</summary>

该人体解析数据集包括时尚图像的详细像素级注释，这是在我们的 TPAMI 论文“Deep Human Parsing with Active Template Regression”和 ICCV 2015 论文“Human Parsing with Contextualized Convolutional Neural Network”中提出的。该数据集包含 7700 张图像。我们使用 6000 张图像进行训练，1000 张图像用于测试，700 张图像作为验证集。

</details>

#### Look into Person (LIP)

* Paper:
  * CVPR 2017: [Look into Person: Self-supervised Structure-sensitive Learning and A New Benchmark for Human Parsing](https://ieeexplore.ieee.org/document/8100198)
  * TPAMI 2018 [Look into Person: Joint Body Parsing &amp; Pose Estimation Network and a New Benchmark](https://ieeexplore.ieee.org/document/8327922)
* Project: [https://github.com/Engineering-Course/LIP_SSL](https://github.com/Engineering-Course/LIP_SSL)
* Download:
  * Baidu Pan: [http://pan.baidu.com/s/1nvqmZBN](http://pan.baidu.com/s/1nvqmZBN)
  * Google Drive: [https://drive.google.com/drive/folders/0BzvH3bSnp3E9QjVYZlhWSjltSWM?resourcekey=0-nkS8bDVjPs3bEw3UZW-omA&amp;usp=sharing](https://drive.google.com/drive/folders/0BzvH3bSnp3E9QjVYZlhWSjltSWM?resourcekey=0-nkS8bDVjPs3bEw3UZW-omA&usp=sharing)

Look into Person (LIP) is a new large-scale dataset, focus on semantic understanding of person. Following are the detailed descriptions.
The dataset contains 50, 000 images with elaborated pixel-wise annotations with 19 semantic human part labels and 2D human poses with 16 key points.
The annotated 50,000 images are cropped person instances from COCO dataset with size larger than 50*50. The images collected from the real-world scenarios contain human appearing with challenging poses and views, heavily occlusions, various appearances and low-resolutions. We are working on collecting and annotating more images to increase diversity.

<details>
<summary>中文介绍</summary>

Look into Person (LIP) 是一个新的大规模数据集，专注于人的语义理解。以下是详细描述。
该数据集包含 50, 000 张图像，带有详细的像素级注释，具有 19 个语义人体部位标签和具有 16 个关键点的 2D 人体姿势。
带注释的 50,000 张图像是从 COCO 数据集中裁剪出的人物实例，尺寸大于 50*50。从现实世界场景中收集的图像包含具有挑战性的姿势和视图、严重遮挡、各种外观和低分辨率的人类出现。我们正在努力收集和注释更多图像以增加多样性。

</details>

#### Taobao Commodity Dataset (TCD)

* Paper: [PISA: Pixelwise Image Saliency by Aggregating Complementary Appearance Contrast Measures with Edge-Preserving Coherence](https://ieeexplore.ieee.org/document/7106497)
* Project: [http://www.sysu-hcp.net/resources/datasets/index.html](http://www.sysu-hcp.net/resources/datasets/index.html)

TCD contains 800 commodity images (dresses, jeans, T-shirts, shoes and hats) from the shops on the Taobao website. The ground truth masks of the TCD dataset are obtained by inviting common sellers of Taobao website to annotate their commodities, i.e., masking salient objects that they want to show from their exhibition. These images include all kinds of commodity with and without human models, thus having complex backgrounds and scenes with highly complex foregrounds. Pixel-accurate ground truth masks are given.

<details>
<summary>中文介绍</summary>

TCD 包含淘宝网站上商店的 800 个商品图片（连衣裙、牛仔裤、T 恤、鞋子和帽子）。 TCD数据集的groundtruth mask是通过邀请淘宝网站的普通卖家注释他们的商品而获得的，即掩盖他们想要在展览中展示的显著物体。这些图像包括各种有或没有人体模型的商品，因此具有复杂的背景和前景高度复杂的场景。给出了像素精确的地面真实掩模。

</details>

#### Object Extraction Dataset

* Paper: [Deep Joint Task Learning for Generic Object Extraction](https://proceedings.neurips.cc/paper/2014/file/d81f9c1be2e08964bf9f24b15f0e4900-Paper.pdf)
* Project:
  * [https://objectextraction.github.io/](https://objectextraction.github.io/)
  * [http://www.sysu-hcp.net/resources/datasets/index.html](http://www.sysu-hcp.net/resources/datasets/index.html)
* Download: See [http://objectextraction.github.io/](http://objectextraction.github.io/)

This Object Extraction newly collected by us contains 10183 images with groundtruth segmentation masks. We selected the images from the PASCAL, iCoseg, Internet dataset as well as other data (most of them are about people and clothes) from the web. We randomly split the dataset with 8230 images for training and 1953 images for testing.

<details>
<summary>中文介绍</summary>

我们新收集的对象提取包含 10183 个带有真实分割掩模的图像。我们从 PASCAL、iCoseg、Internet 数据集以及网络上的其他数据（大部分是关于人和衣服的）中选择图像。我们将数据集随机分割为 8230 张图像用于训练，1953 张图像用于测试。

</details>

#### Clothing Co-Parsing (CCP) Dataset

* Paper: [Clothing Co-Parsing by Joint Image Segmentation and Labeling](https://ieeexplore.ieee.org/document/6909803)
* Project: [https://github.com/bearpaw/clothing-co-parsing](https://github.com/bearpaw/clothing-co-parsing)
* Download: [https://github.com/bearpaw/clothing-co-parsing](https://github.com/bearpaw/clothing-co-parsing)

Clothing Co-Parsing (CCP) dataset is a new clothing database including elaborately annotated clothing items. 2,098 high-resolution street fashion photos with totally 59 tags. Wide range of styles, accessaries, garments, and pose. All images are with image-level annotations. 1000+ images are with pixel-level annotations.

<details>
<summary>中文介绍</summary>

服装协同解析（CCP）数据集是一个新的服装数据库，包括精心注释的服装项目。 2,098 张高分辨率街头时尚照片，共 59 个标签。各种风格、配饰、服装和姿势。所有图像都带有图像级注释。 1000 多张图像带有像素级注释。

</details>

#### People segmentation dataset

* Paper: [Early Hierarchical Contexts Learned by Convolutional Networks for Image Segmentation](http://www.cbsr.ia.ac.cn/users/ynyu/icpr2014.pdf)
* Project: [http://www.cbsr.ia.ac.cn/users/ynyu/dataset/](http://www.cbsr.ia.ac.cn/users/ynyu/dataset/)
* Download: See [http://www.cbsr.ia.ac.cn/users/ynyu/dataset/](http://www.cbsr.ia.ac.cn/users/ynyu/dataset/)

The dataset used in this paper is finely labeled manually for the purpose of foreground segmentation. There are 5,389 images in the training set. The task is to segment the most salient person in an image, including his/her clothing, e.g., long dresses and hats, and any objects in his/her hands such as handbags. The images have various sources such as street-shots, advertisements and news. The persons in these images vary greatly in terms of scales and poses. To train our model, we randomly pick out 500 images from the training set for validation. The test set is not public so that no model can be trained using these data.

<details>
<summary>中文介绍</summary>

本文使用的数据集是为了前景分割而手动精细标记的。训练集中有 5,389 张图像。任务是分割图像中最显著的人物，包括他/她的衣服，例如长裙和帽子，以及他/她手中的任何物体，例如手提包。这些图像有多种来源，例如街拍、广告和新闻。这些图像中的人物在比例和姿势方面差异很大。为了训练我们的模型，我们从训练集中随机挑选 500 张图像进行验证。测试集不是公开的，因此无法使用这些数据来训练模型。

</details>

## Matting

*From [Semantic Human Matting](https://arxiv.org/abs/1809.01354)*

### alphamatting.com

* Project: [http://alphamatting.com/datasets.php](http://alphamatting.com/datasets.php)
* Download: See [http://alphamatting.com/datasets.php](http://alphamatting.com/datasets.php)

This is an existing benchmark for image matting methods. It includes 8 test images, each with 3 different 3D figures, namely "small", "large" and "user"

<details>
<summary>中文介绍</summary>

这是图像matting方法的现有基准. 它**包括8个测试图像, 每个图像有3个不同的三维图形**, 即"small", "large"和"user"

</details>

### Composition-1k: Deep Image Matting

* Paper: [Deep Image Matting](https://arxiv.org/abs/1703.03872)
* Project: [https://sites.google.com/view/deepimagematting](https://sites.google.com/view/deepimagematting)
* Download: Please contact Brian Price (bprice@adobe.com) for the dataset.

We create a large-scale matting dataset using composition. Images with objects on simple backgrounds were carefully extracted and were composited onto new background images to create a dataset with 45500 training images and 1000 test images.

<details>
<summary>中文介绍</summary>

我们使用合成创建一个大规模抠图数据集。仔细提取具有简单背景的对象的图像并将其合成到新的背景图像上，以创建包含 45500 个训练图像和 1000 个测试图像的数据集。

</details>

### Semantic Human Matting

* Paper: [Semantic Human Matting](https://arxiv.org/abs/1809.01354)

We propose a novel fusion strategy which naturally gives a probabilistic estimation of the alpha matting. We also construct a very large dataset with high quality annotations consisting of 35,513 unique foregrounds to facilitate the learning and evaluation of human matting.

<details>
<summary>中文介绍</summary>

我们提出了一种新颖的融合策略，它自然地给出了 alpha 抠图的概率估计。我们还构建了一个包含 35,513 个独特前景的高质量注释的非常大的数据集，以促进人类抠图的学习和评估。

</details>

### Matting-Human-Datasets

* Project: [https://github.com/aisegmentcn/matting_human_datasets](https://github.com/aisegmentcn/matting_human_datasets)
* Download:
  + Baidu Pan:[https://pan.baidu.com/s/1R9PJJRT-KjSxh-2-3wCGxQ](https://pan.baidu.com/s/1R9PJJRT-KjSxh-2-3wCGxQ)  (dzsn)
  + Mega:[https://mega.nz/#F!Gh8CFAyb!e2ppUh-copP76GbE8IWAEQ](https://mega.nz/#F!Gh8CFAyb!e2ppUh-copP76GbE8IWAEQ)
  + Kaggle:[https://www.kaggle.com/laurentmih/aisegmentcom-matting-human-datasets/](https://www.kaggle.com/laurentmih/aisegmentcom-matting-human-datasets/)

This data set is currently the largest known portrait matting data set, containing 34,427 images and corresponding matting result images. The data set is high-quality annotated by Beijing Wanxing Technology Co., Ltd., and the portrait soft segmentation model trained using this data set has been commercially used.
The original pictures in the data set come from Flickr, Baidu, and Taobao. After face detection and area cropping, a 600*800 half-length portrait is generated.

<details>
<summary>中文介绍</summary>

本数据集为目前已知最大的人像matting数据集, 包含34427张图像和对应的matting结果图. 数据集由北京玩星汇聚科技有限公司高质量标注, 使用该数据集所训练的人像软分割模型已商用.
数据集中的原始图片来源于Flickr, 百度, 淘宝. 经过人脸检测和区域裁剪后生成了600*800的半身人像.

</details>

### PFCN

* Paper: [Automatic Portrait Segmentation for Image Stylization](https://onlinelibrary.wiley.com/doi/10.1111/cgf.12814)
* Download:
  * Baidu Pan: [http://pan.baidu.com/s/1bQ4yHC](http://pan.baidu.com/s/1bQ4yHC)
  * OneDrive: [https://1drv.ms/u/s!ApwdOxIIFBH19TzDv7nRfH5ZsMNL](https://1drv.ms/u/s!ApwdOxIIFBH19TzDv7nRfH5ZsMNL)

We collected 1800 portrait images from Flickr and manually labeled it hem with Photoshop quick selection. We captured a range of portrait types but biased the Flickr searches toward natural self portraits that were captured with mobile front-facing cameras. These are challenging images that represent thetypical cases that we would like to handle. We then ran a face de-tector on each image, and automatically scaled and cropped the im-age to 600× 800 according the bounding box of the face detection result as shown in Figure 3(a) and (b). This process excludes im-ages for which the face detector failed. Some of the portrait imagesin our dataset are shown in Figure 5 and display large variation-s in age, color, background, clothing, accessories, head position, hair style, etc. We include such large variations in our dataset tomake our model more robust to challenging inputs. We split the 1800 labeled images into a 1500 image training dataset and a 300 image testing/validation dataset. Because more data tends to pro-duce better results, w e augmented our training dataset by perturb-ing the rotations and scales of our original training images.

<details>
<summary>中文介绍</summary>

我们从 Flickr 收集了 1800 张肖像图像，并使用 Photoshop 快速选择手动标记其下摆。我们拍摄了一系列肖像类型，但 Flickr 搜索偏向于使用移动前置摄像头拍摄的自然自画像。这些具有挑战性的图像代表了我们想要处理的典型案例。然后，我们在每张图像上运行人脸检测器，并根据人脸检测结果的边界框自动将图像缩放和裁剪为 600×800，如图 3(a) 和 (b) 所示。此过程排除面部检测器失败的图像。我们数据集中的一些肖像图像如图 5 所示，在年龄、颜色、背景、服装、配饰、头部位置、发型等方面显示出较大的变化。我们在数据集中包含如此大的变化，以使我们的模型对具有挑战性的输入更加稳健。我们将 1800 张标记图像分为 1500 张图像训练数据集和 300 张图像测试/验证数据集。因为更多的数据往往会产生更好的结果，所以我们通过扰动原始训练图像的旋转和比例来增强我们的训练数据集。

</details>

### Deep Automatic Portrait Matting

* Paper: [Deep Automatic Portrait Matting](http://www.cse.cuhk.edu.hk/~leojia/projects/automatting/papers/deepmatting.pdf)
* Project: [http://www.cse.cuhk.edu.hk/~leojia/projects/automatting/](http://www.cse.cuhk.edu.hk/~leojia/projects/automatting/)
* Download: [https://1drv.ms/u/s!ApwdOxIIFBH19Ts5EuFd9gVJrKTo](https://1drv.ms/u/s!ApwdOxIIFBH19Ts5EuFd9gVJrKTo)

After this labeling process, we collect 2,000 images with high-quality mattes. These images are randomly split into the training and testing sets with 1,700 and 300 images respectively.

<details>
<summary>中文介绍</summary>

经过此标记过程后，我们收集了 2,000 张具有高质量遮罩的图像。这些图像被随机分为训练集和测试集，分别包含 1,700 张和 300 张图像。

</details>

## Other

### Large-scale Fashion (DeepFashion) Database

* Paper: [DeepFashion: Powering Robust Clothes Recognition and Retrieval with Rich Annotations](https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Liu_DeepFashion_Powering_Robust_CVPR_2016_paper.pdf)
* Project:
  * [https://liuziwei7.github.io/projects/DeepFashion.html](https://liuziwei7.github.io/projects/DeepFashion.html)
  * [http://mmlab.ie.cuhk.edu.hk/projects/DeepFashion.html](http://mmlab.ie.cuhk.edu.hk/projects/DeepFashion.html)
  + [Multimedia Laboratory](http://mmlab.ie.cuhk.edu.hk/)
  + mmfashion: [https://github.com/open-mmlab/mmfashion](https://github.com/open-mmlab/mmfashion)
* Download: See [http://mmlab.ie.cuhk.edu.hk/projects/DeepFashion.html](http://mmlab.ie.cuhk.edu.hk/projects/DeepFashion.html)

We contribute DeepFashion database, a large-scale clothes database, which has several appealing properties: First, DeepFashion contains over 800,000 diverse fashion images ranging from well-posed shop images to unconstrained consumer photos. Second, DeepFashion is annotated with rich information of clothing items. Each image in this dataset is labeled with 50 categories, 1,000 descriptive attributes, bounding box and clothing landmarks. Third, DeepFashion contains over 300,000 cross-pose/cross-domain image pairs.

Four benchmarks are developed using the DeepFashion database, including Attribute Prediction, Consumer-to-shop Clothes Retrieval, In-shop Clothes Retrieval, and Landmark Detection. The data and annotations of these benchmarks can be also employed as the training and test sets for the following computer vision tasks, such as Clothes Detection, Clothes Recognition, and Image Retrieval.

<details>
<summary>中文介绍</summary>

我们贡献了 DeepFashion 数据库，这是一个大规模的服装数据库，它有几个吸引人的特性：首先，DeepFashion 包含超过 800,000 个不同的时尚图像，从摆好姿势的商店图像到不受约束的消费者照片。其次，DeepFashion标注了丰富的服装单品信息。该数据集中的每张图像都标有 50 个类别、1,000 个描述性属性、边界框和服装地标。第三，DeepFashion 包含超过 300,000 个跨姿势/跨域图像对。

使用 DeepFashion 数据库开发了四个基准，包括属性预测、消费者到商店的衣服检索、店内衣服检索和地标检测。这些基准的数据和注释也可以用作以下计算机视觉任务的训练和测试集，例如衣服检测、衣服识别和图像检索。

</details>

### Tencent ML-Images

* Paper: [Tencent ML-Images: A Large-Scale Multi-Label Image Database for Visual Representation Learning](https://arxiv.org/abs/1901.01703)
* Project: [https://github.com/Tencent/tencent-ml-images](https://github.com/Tencent/tencent-ml-images)
* Download: See [https://github.com/Tencent/tencent-ml-images#download-images](https://github.com/Tencent/tencent-ml-images#download-images)

ML-Images: the largest open-source multi-label image database, including 17, 609, 752 training and 88, 739 validation image URLs, which are annotated with up to 11, 166 categories

<details>
<summary>中文介绍</summary>

ML-Images：最大的开源多标签图像数据库，包括 17、609、752 个训练图像 URL 和 88、739 个验证图像 URL，标注了多达 11、166 个类别

</details>

## need your help...

> I have forgotten the source of some data sets. If you have seen them, I hope you can add them.

* SegTrackV1/V2
* ViSal
* MCL
* UVSD
* VOS

## Reference

### Survey

* [Salient Object Detection: A Survey](https://link.springer.com/article/10.1007/s41095-019-0149-9)
* [Review of Visual Saliency Detection With Comprehensive Information](https://ieeexplore.ieee.org/document/8466906/)
* [Salient Object Detection in the Deep Learning Era: An In-Depth Survey](https://pubmed.ncbi.nlm.nih.gov/33434124/)
* [RGB-D salient object detection: A survey](https://link.springer.com/article/10.1007/s41095-020-0199-z)
* [Salient Objects in Clutter](https://arxiv.org/abs/2105.03053)

### Project

- [https://github.com/wenguanwang/SODsurvey](https://github.com/wenguanwang/SODsurvey)
  - Part of the content of this document is referenced from the review paper. Thanks to the author for his work, the summary is very detailed!

## More

### Similiar Projects

* [awesome-semantic-segmentation](https://github.com/mrgloom/awesome-semantic-segmentation)

### Research Institutes

* Baidu Research Institute: [https://ai.baidu.com/broad/introduction](https://ai.baidu.com/broad/introduction)
* Sun Yat-sen University Human-Machine-Object Intelligent Integration Laboratory: [http://www.sysu-hcp.net/resources/](http://www.sysu-hcp.net/resources/)
* Dalian University of Technology IIAU-LAB: [http://ice.dlut.edu.cn/lu/publications.html](http://ice.dlut.edu.cn/lu/publications.html)
* CUHK Multimedia Laboratory: [http://mmlab.ie.cuhk.edu.hk/datasets.html](http://mmlab.ie.cuhk.edu.hk/datasets.html)

### Resource Websites

* TC-11 Online Resources: [http://tc11.cvc.uab.es/datasets/type/](http://tc11.cvc.uab.es/datasets/type/)
* CVonline: Image Databases: [http://homepages.inf.ed.ac.uk/rbf/CVonline/Imagedbase.htm](http://homepages.inf.ed.ac.uk/rbf/CVonline/Imagedbase.htm)
  + Chinese: [https://blog.csdn.net/zhaoliang027/article/details/83376167](https://blog.csdn.net/zhaoliang027/article/details/83376167)
* MediaEval Benchmark: [http://www.multimediaeval.org/datasets/](http://www.multimediaeval.org/datasets/)
* Mit Saliency Benchmark: [http://saliency.mit.edu/datasets.html](http://saliency.mit.edu/datasets.html)
* Datasets for machine learning: [https://www.datasetlist.com/](https://www.datasetlist.com/)
* UCI machine learning repository: [https://archive.ics.uci.edu/ml/datasets.html](https://archive.ics.uci.edu/ml/datasets.html)
* Kaggle datasets: [https://www.kaggle.com/datasets](https://www.kaggle.com/datasets)
* Google Dataset Seaerch:
  + [https://toolbox.google.com/datasetsearch](https://toolbox.google.com/datasetsearch)
  + [https://ai.google/tools/datasets/](https://ai.google/tools/datasets/)
  + [https://datasetsearch.research.google.com/](https://datasetsearch.research.google.com/)
  + AI developer artifact! Google launches data set search Dataset Search: [https://mp.weixin.qq.com/s/ErbwXAz-_AJrmUGMHZIcwg](https://mp.weixin.qq.com/s/ErbwXAz-_AJrmUGMHZIcwg)
  + Making it easier to discover datasets: [https://www.blog.google/products/search/making-it-easier-discover-datasets/](https://www.blog.google/products/search/making-it-easier-discover-datasets/)
* ⭐️⭐️⭐️ Yet Another Computer Vision Index To Datasets (YACVID): This website provides a list of frequently used computer vision datasets. Wait, there is more! There is also a description containing common problems, pitfalls and characteristics and now a searchable TAG cloud.: [http://yacvid.hayko.at/](http://yacvid.hayko.at/)
* ⭐️⭐️⭐️ IEEE DataPort provides a sustainable platform to all data owners in support of research and IEEE's overall mission of Advancing Technology for Humanity: [https://ieee-dataport.org/](https://ieee-dataport.org/)
