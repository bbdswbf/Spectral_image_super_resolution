# Spectral_image_super_resolution

# 光谱单图超分数据集

| 数据集 | 描述 | 下载地址 |
|------------|------------|----------|
| CAVE   | 是由可调滤波片（VariSpec Liquid Crystal Tunable Filter）和CCD相机（Apogee Alta U260）采集的。由 32 张日常物体（例如雕像、食物）的光谱图像组成，在400-700nm范围内以10nm的波长间隔采集，分辨率为512×512×31。      | [下载链接](http://www.cs.columbia.edu/CAVE/databases/multispectral) |
| Harvard    | 是使用可调滤波片光谱相机Nuance FX采集的，包含 50个真实世界的室内和室外图像，具有420-720nm范围内间隔10nm的31个通道。空间分辨率为1392×1040。      | [下载链接](http://vision.seas.harvard.edu/hyperspec/explore.html) |
| ICVL    | 使用Specim PS Kappa DX4光谱相机采集的，包含203个城市(住宅/商业)、郊区、农村、室内和植物场景。原始图像拥有400-1000nm的519个通道和1392×1300的空间分辨率。常用的数据为400-700nm大约间隔10nm的31个通道。      | [下载链接](https://icvl.cs.bgu.ac.il/hyperspectral/) |
| NUS    | 使用Specim PFD-CL-65-V10E光谱相机采集的，包含64个场景。原始图像同样是400-1000nm的，而常用的是400-700nm的31个通道。      | [下载链接](http://www.comp.nus.edu.sg/~whitebal/spectral_reconstruction/index.html) |
| Botswana    | 由美国宇航局地球观测1号(EO-1)卫星上的Hyperion传感器拍摄的，由400-2500nm的242个光谱通道组成，光谱分辨率为10nm。空间大小为1496×256。      | [下载链接](https://www.ehu.eus/ccwintco/index.php?title=Hyperspectral_Remote_Sensing_Scenes) |
| Chikusei    | 由Headwall Hyperspec-VNIR-C成像传感器在日本Chikusei的农业和城市地区拍摄的，由363-1018nm的128个光谱波段组成。空间大小为2517×2335像素，其中单个像素相当于2.5×2.5m2的几何分辨率。      | [下载链接](http://naotoyokoya.com/Download.html) |
| Pavia University    | 由意大利帕维亚大学上空的ROSIS机载传感器于2003年获取的，包括610×340个像素和115个光谱通道。      | [下载链接](https://www.ehu.eus/ccwintco/index.php?title=Hyperspectral_Remote_Sensing_Scenes) |
| Pavia Center    | 描述      | [下载链接](https://www.ehu.eus/ccwintco/index.php?title=Hyperspectral_Remote_Sensing_Scenes) |
| Urban    | 描述      | [下载链接](https://rslab.ut.ac.ir/data) |
| Washington DC    | 描述      | [下载链接](https://engineering.purdue.edu/~biehl/MultiSpec/hyperspectral.html) |
| Indians Pines    | 描述      | [下载链接](https://www.ehu.eus/ccwintco/index.php?title=Hyperspectral_Remote_Sensing_Scenes) |
| Foster    | 描述      | [下载链接](https://personalpages.manchester.ac.uk/staff/d.h.foster/Local/_Illumination/_HSIs/Local/_Illumination/_HSIs/_2015.html) |
| Hoston    | 描述      | [下载链接](http://dase.grss-ieee.org/) |
| UCMERCED    | 描述      | [下载链接](http://vision.ucmerced.edu/datasets) |

# 光谱融合超分数据集

| 数据集 | 描述 | 下载地址 |
|------------|------------|----------|
| QuickBird    | 由QuickBird卫星采集的，包括低分辨多光谱图像和全色图像。 低分辨多光谱图像和全色图像的空间分辨率分别为2.44m和0.61m。 低分辨多光谱图像有四个通道，分别是R、G、B、NIR。      | [下载链接](https://www.satimagingcorp.com/satellite-sensors/quickbird/) |
| HypSen   | 由Earth Observing-1卫星上的Hyperion传感器采集的30m分辨率高光谱图像和Sentinel-2A卫星采集的10m分辨率多光谱图像组成。去除噪声和水吸收带后，低分辨率高光谱图像由84个光谱通道组成，而高分辨率多光谱图像包含13个光谱通道。      | [下载链接](https://example.com/dataset2) |
| AVIRIS Cuprite    | 由 NASA的机载可见光和红外成像光谱仪（AVIRIS）在内华达州赤铜矿区上空遥感采集，包含四张尺寸为512×512×224的图像，光谱范围为从370nm到2500nm。     | [下载链接](https://example.com/dataset3) |



# Dataset Project

| Method                   | Scene | Base Framework | Supervision Paradigm | Publication Venue | Code Link |
|--------------------------|-------|-----------------|-----------------------|----------------------|-----------------------|
| 3D-FCNN (Mei et al., 2017) | SpaSR | CNN | Supervised | RS | [Link](https://example.com/3d-fcnn) |
| SDCNN (Li et al., 2017) | SpaSR | CNN | Supervised | NC | [Link](https://example.com/sdcnn) |
| 1D2DCNN (Li et al., 2019) | SpaSR | CNN | Supervised | RS | [Link](https://example.com/1d2dcnn) |
| IDN (Hu et al., 2019) | SpaSR | CNN | Supervised | RS | [Link](https://example.com/idn) |
| MW-3D-CNN (Yang et al., 2019) | SpaSR | CNN | Supervised | RS | [Link](https://example.com/mw-3d-cnn) |
| DFMF (Xie et al., 2019) | SpaSR | CNN | Supervised | TGRS | [Link](https://example.com/dfmf) |
| RIFN (Hu et al., 2020) | SpaSR | CNN | Supervised | TGRS | [Link](https://example.com/rifn) |
| 3DASRGAN (Dou et al., 2020) | SpaSR | GAN | Supervised | RS | [Link](https://example.com/3dasrgan) |
| MCNet (Li et al., 2020c) | SpaSR | CNN | Supervised | RS | [Link](https://github.com/qianngli/MCNet) |
| SSPSR (Jiang et al., 2020) | SpaSR | CNN | Supervised | TGRS | [Link](https://github.com/junjun-jiang/SSPSR) |
| SFCSR (Wang et al., 2020a) | SpaSR | CNN | Supervised | TIE | [Link](https://github.com/qianngli/SFCSR) |
| UCNN (Lu et al., 2021) | SpaSR | CNN | Supervised | RS | [Link](https://example.com/ucnn) |
| MMCA (Magid et al., 2021) | SpaSR | CNN | Supervised | ICCV | [Link](https://example.com/mmca) |
| SGARDN (Liu et al., 2021) | SpaSR | CNN | Supervised | TGRS | [Link](https://example.com/sgardn) |
| Bi3DQRNN (Fu et al., 2021) | SpaSR | CNN | Supervised | JSTARS | [Link](https://github.com/zhiyuan0112/Bi-3DQRNN) |
| INR (Zhang et al., 2022a) | SpaSR | CNN | Supervised | TGRS | [Link](https://example.com/inr) |
| RFSR (Wang et al., 2022) | SpaSR | CNN | Supervised | TGRS | [Link](https://example.com/rfsr) |
| DualSR (Li et al., 2022c) | SpaSR | CNN | Supervised | TIP | [Link](https://github.com/qianngli/DualSR) |
| SRAGAN (Li et al., 2021b) | SpaSR | GAN | Supervised | TGRS | [Link](https://example.com/sragan) |
| LE-GAN (Shi et al., 2022) | SpaSR | CNN | Supervised | TGRS | [Link](https://example.com/le-gan) |
| DSSTSR (Long et al., 2023) | SpaSR | Transformer | Supervised | TGRS | [Link](https://example.com/dsstsr) |
| HSCNN (Xiong et al., 2017) | SpeSR | CNN | Supervised | ICCVW | [Link](https://example.com/hscnn) |
| GANSSR (Lore et al., 2019) | SpeSR | GAN | Supervised | CVPRW | [Link](https://example.com/ganssr) |
| AWAN (Li et al., 2020a) | SpeSR | CNN | Supervised | CVPRW | [Link](https://github.com/Deep-imagelab/AWAN) |
| PDFN (Zhang et al., 2020a) | SpeSR | CNN | Supervised | AAAI | [Link](https://example.com/pdfn) |
| SSRAN (Zheng et al., 2021c) | SpeSR | CNN | Supervised | TGRS | [Link](https://example.com/ssran) |
| DAGDN (Zhu et al., 2021a) | SpeSR | DUN | Supervised | TCI | [Link](https://github.com/zbzhzhy/GD-Net) |
| SEN (Zhu et al., 2021b) | SpeSR | CNN | Unsupervised | ICCV | [Link](https://github.com/zbzhzhy/Unsupervised-Spectral-Reconstruction) |
| HSACS (Li et al., 2021a) | SpeSR | CNN | Supervised | TNNLS | [Link](https://example.com/hsacs) |
| SSRN-IPH (Hang et al., 2021) | SpeSR | CNN | Supervised | TIP | [Link](https://example.com/ssrn-iph) |
| SSN (Fu et al., 2022) | SpeSR | CNN | Supervised | TPAMI | [Link](https://example.com/ssn) |
| DRCRNet (Li et al., 2022a) | SpeSR | CNN | Supervised | CVPRW | [Link](https://github.com/jojolee6513/DRCR-net) |
| PoNet (He et al., 2022) | SpeSR | DUN | Supervised | IF | [Link](https://example.com/ponet) |
| MST++ (Cai et al., 2022) | SpeSR | Transformer | Supervised | CVPRW | [Link](https://github.com/caiyuanhao1998/MST-plus-plus) |
| MFormer (Li et al., 2023b) | SpeSR | Transformer | Unsupervised | TGRS | [Link](https://example.com/mformer) |
| HPRN (Wu et al., 2023) | SpeSR | CNN | Supervised | TNNLS | [Link](https://github.com/deep-imagelab/hprn) |
| CTJN (Du et al., 2023) | SpeSR | CNN&Transformer | Supervised | TGRS | [Link](https://example.com/ctjn) |
| SSFAN (Liu et al., 2023) | SpeSR | GAN | Supervised | JSTARS | [Link](https://example.com/ssfan) |
| SSJSR (Mei et al., 2020) | SSSR | CNN | Supervised | TGRS | [Link](https://example.com/ssjsr) |
| US3RN (Ma et al., 2021) | SSSR | DUN | Supervised | TIP | [Link](https://github.com/junjun-jiang/US3RN) |
| SSFIN (Ma et al., 2022) | SSSR | CNN | Supervised | TCI | [Link](https://github.com/junjun-jiang/SSFIN) |
| PNN (Masi et al., 2016) | PS | CNN | Supervised | RS | [Link](https://example.com/pnn) |
| PanNet (Yang et al., 2017) | PS | CNN | Supervised | ICCV | [Link](https://example.com/pannet) |
| MSDCNN (Yuan et al., 2018) | PS | CNN | Supervised | TGRS | [Link](https://example.com/msdcnn) |
| PanGAN (Ma et al., 2020) | PS | GAN | Unsupervised | IF | [Link](https://github.com/jiayi-ma/PanGAN) |
| SSConv (Wang et al., 2021) | PS | CNN | Supervised | ACM MM | [Link](https://github.com/liangjiandeng/MUCNN) |
| GPPNN (Xu et al., 2021) | PS | DUN | Supervised | CVPR | [Link](https://github.com/xsxjtu/GPPNN) |
| HyperKite (Bandara et al., 2021) | PS | CNN | Supervised | TGRS | [Link](https://github.com/wgcban/DIP-HyperKite.git) |
| PanCSC-Net (Cao et al., 2021) | PS | DUN | Supervised | TGRS | [Link](https://example.com/pancsc-net) |
| HyperTransformer (Bandara et al., 2022) | PS | Transformer | Supervised | CVPR | [Link](https://github.com/wgcban/HyperTransformer) |
| Proximal PanNet (Cao et al., 2022) | PS | DUN | Supervised | AAAI | [Link](https://example.com/proximal-pannet) |
| panformer (Zhou et al., 2022a) | PS | Transformer | Supervised | AAAI | [Link](https://github.com/manman1995/pansharpening) |
| DIIB (Gao et al., 2022) | PS | CNN | Unsupervised | CVPRW | [Link](https://example.com/diib) |
| MDCUN (Yang et al., 2022) | PS | DUN | Supervised | CVPR | [Link](https://github.com/yggame/mdcun) |
| MutInf (Zhou et al., 2022b) | PS | CNN | Supervised | CVPR | [Link](https://github.com/manman1995/pansharpening) |
| LHFnet (Zhou et al., 2022c) | PS | CNN | Supervised | ACM MM | [Link](https://github.com/manman1995/pansharpening) |
| DR-NET (Xu et al., 2022) | PS | Transformer | Supervised | TGRS | [Link](https://example.com/dr-net) |
| PanViT (Meng et al., 2022) | PS | Transformer | Supervised | TGRS | [Link](https://example.com/panvit) |
| SFINet (Zhou et al., 2022d) | PS | CNN | Supervised | ECCV | [Link](https://github.com/manman1995/pansharpening) |
| UPanGAN (Xu et al., 2023) | PS | GAN | Unsupervised | IF | [Link](https://example.com/upangan) |
| iGDANet (Qu et al., 2023) | PS | DUN | Unsupervised | TCYB | [Link](https://example.com/igdanet) |
| uSDN (Qu et al., 2018) | MHF | CNN | Unsupervised | CVPR | [Link](https://github.com/aicip/usdn) |
| DBIN (Wang et al., 2019) | MHF | CNN | Supervised | ICCV | [Link](https://example.com/dbin) |
| HSRG (Fu et al., 2019) | MHF | CNN | Unsupervised | CVPR | [Link](https://example.com/hsrg) |
| CUCaNet (Yao et al., 2020) | MHF | CNN | Unsupervised | ECCV | [Link](https://github.com/danfenghong/ECCV2020_CUCaNet) |
| FusionNet (Wang et al., 2020b) | MHF | CNN | Unsupervised | TIP | [Link](https://example.com/fusionnet) |
| UAL (Zhang et al., 2020b) | MHF | CNN | Unsupervised | CVPR | [Link](https://github.com/JiangtaoNie/UAL) |
| DBSR (Zhang et al., 2020c) | MHF | CNN | Unsupervised | TNNLS | [Link](https://example.com/dbsr) |
| u2-MDN (Qu et al., 2021) | MHF | CNN | Unsupervised | TGRS | [Link](https://github.com/aicip/u2MDN) |
| PZRes-Net (Zhu et al., 2020) | MHF | CNN | Supervised | TIP | [Link](https://github.com/ZHU-Zhiyu/PZRes-Net) |
| MHF-Net (Xie et al., 2020) | MHF | DUN | Supervised | TPAMI | [Link](https://github.com/XieQi2015/MHF-net/tree/master) |
| HyCoNet (Zheng et al., 20201b) | MHF | CNN | Unsupervised | TGRS | [Link](https://github.com/saber-zero/hyperfusion) |
| NonRegSRNet (Zheng et al., 2021c) | MHF | CNN | Unsupervised | TGRS | [Link](https://github.com/saber-zero/NonRegSRNet) |
| MoG-DCN (Dong et al., 2021) | MHF   | DUN             | Supervised            | TIP                 | [Link](https://see.xidian.edu.cn/faculty/wsdong/Projects/MoG-DCN.htm) |
| DEIL (Fu et al., 2022b)      | MHF   | CNN             | Unsupervised          | TPAMI               | [Link](https://example.com/deil)              |
| S2DMDN (Dong et al., 2022a)  | MHF   | DUN             | Supervised            | TGRS                | [Link](https://example.com/s2dmdn)            |
| UDALN (Li et al., 2022b)     | MHF   | CNN             | Unsupervised          | GRSL                | [GitHub](https://github.com/JiaxinLiCAS/UDALN_GRS) |
| Fusformer (Hu et al., 2022a) | MHF   | Transformer      | Supervised            | TGRS                | [GitHub](https://github.com/J-FHu/Fusformer)   |
| GuidedNet (Ran et al., 2023) | MHF   | CNN             | Supervised            | TCYB                | [GitHub](https://github.com/Evangelion09/GuidedNet) |
| PSRT (Deng et al., 2023)     | MHF   | Transformer      | Supervised            | TGRS                | [GitHub](https://github.com/Deng-shangqi/PSRT) |
| DPLN (Zhang et al., 2023)    | MHF   | CNN             | Unsupervised          | CAAI TRIT           | [Link](https://example.com/dpln)              |
| BUSIFusion (Dong et al., 2023)| MHF   | DUN             | Unsupervised          | TCI                 | [Link](https://example.com/busifusion)        |

## How to Use

Provide additional information and instructions on how to download and use the dataset here.

