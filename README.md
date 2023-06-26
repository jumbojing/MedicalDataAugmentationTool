# MedicalDataAugmentationTool
This tool allows on-the-fly augmentation and training for networks in the medical imaging domain. It uses [SimpleITK](http://www.simpleitk.org/) to load and augment input data, and [Tensorflow](https://www.tensorflow.org/) to define and train networks.
As this framework is mainly used for research, some files are not well documented. However, I'm working on improving this.
If you have problems or find any bugs, don't hesitate to send me a message.

Update: The `bin` folder with example experiments got removed.
The individual experiments of our papers are now in dedicated repositories due to increased memory requirements.

List of experiment repositories:

> 【译】**MedicalDataAugmentationTool**
> 该工具允许对医学成像领域的网络进行实时增强和培训。它使用[SimpleITK](http://www.simpleitk.org/)加载和扩充输入数据，以及[Tensorflow](https://www.tensorflow.org/)以定义和训练网络。
> 由于该框架主要用于研究，一些文件没有得到很好的记录。然而，我正在努力改进这一点。
> 如果你有问题或发现任何错误，请随时给我发消息。
> 更新：带有示例实验的“bin”文件夹已被删除。
> 由于内存需求的增加，我们论文的单个实验现在都在专用的存储库中。
> 实验存储库列表：

  * [HeatmapRegression](https://github.com/christianpayer/MedicalDataAugmentationTool-HeatmapRegression)
  * [MMWHS](https://github.com/christianpayer/MedicalDataAugmentationTool-MMWHS)
  * [CellTracking](https://github.com/christianpayer/MedicalDataAugmentationTool-CellTracking)
  * [VerSe](https://github.com/christianpayer/MedicalDataAugmentationTool-VerSe)
  * [HeatmapUncertainty](https://github.com/christianpayer/MedicalDataAugmentationTool-HeatmapUncertainty)

## Citation
If you use this code for your research, please cite any of our papers.

[Modeling Annotation Uncertainty with Gaussian Heatmaps in Landmark Localization](https://github.com/christianpayer/MedicalDataAugmentationTool-HeatmapUncertainty)
```
@article{Thaler2021,
title   = {Modeling Annotation Uncertainty with Gaussian Heatmaps in Landmark Localization},
author  = {Thaler, Franz and Payer, Christian and Urschler, Martin and {\v{S}}tern, Darko},
journal = {Journal of Machine Learning for Biomedical Imaging},
year    = {2021}
}
```

[Coarse to Fine Vertebrae Localization and Segmentation with SpatialConfiguration-Net and U-Net](https://doi.org/10.5220/0008975201240133)

```
@inproceedings{Payer2020,
  title     = {Coarse to Fine Vertebrae Localization and Segmentation with SpatialConfiguration-Net and U-Net},
  author    = {Payer, Christian and {\v{S}}tern, Darko and Bischof, Horst and Urschler, Martin},
  booktitle = {Proceedings of the 15th International Joint Conference on Computer Vision, Imaging and Computer Graphics Theory and Applications - Volume 5: VISAPP},
  doi       = {10.5220/0008975201240133},
  pages     = {124--133},
  volume    = {5},
  year      = {2020}
}
```

[Segmenting and Tracking Cell Instances with Cosine Embeddings and Recurrent Hourglass Networks](https://doi.org/10.1016/j.media.2019.06.015):

```
@article{Payer2019b,
  title   = {Segmenting and Tracking Cell Instances with Cosine Embeddings and Recurrent Hourglass Networks},
  author  = {Payer, Christian and {\v{S}}tern, Darko and Feiner, Marlies and Bischof, Horst and Urschler, Martin},
  journal = {Medical Image Analysis},
  volume  = {57},
  year    = {2019},
  month   = {oct},
  pages   = {106--119},
  doi     = {10.1016/j.media.2019.06.015},
}
```

[Integrating Spatial Configuration into Heatmap Regression Based CNNs for Landmark Localization](https://doi.org/10.1016/j.media.2019.03.007):

```
@article{Payer2019a,
  title   = {Integrating Spatial Configuration into Heatmap Regression Based {CNNs} for Landmark Localization},
  author  = {Payer, Christian and {\v{S}}tern, Darko and Bischof, Horst and Urschler, Martin},
  journal = {Medical Image Analysis},
  volume  = {54},
  year    = {2019},
  month   = {may},
  pages   = {207--219},
  doi     = {10.1016/j.media.2019.03.007},
}
```

[Instance Segmentation and Tracking with Cosine Embeddings and Recurrent Hourglass Networks](https://doi.org/10.1007/978-3-030-00934-2_1):

```
@inproceedings{Payer2018b,
  title     = {Instance Segmentation and Tracking with Cosine Embeddings and Recurrent Hourglass Networks},
  author    = {Payer, Christian and {\v{S}}tern, Darko and Neff, Thomas and Bischof, Horst and Urschler, Martin},
  booktitle = {Medical Image Computing and Computer-Assisted Intervention - {MICCAI} 2018},
  doi       = {10.1007/978-3-030-00934-2_1},
  pages     = {3--11},
  year      = {2018},
}
```

[Multi-label Whole Heart Segmentation Using CNNs and Anatomical Label Configurations](https://doi.org/10.1007/978-3-319-75541-0_20):

```
@inproceedings{Payer2018a,
  title     = {Multi-label Whole Heart Segmentation Using {CNNs} and Anatomical Label Configurations},
  author    = {Payer, Christian and {\v{S}}tern, Darko and Bischof, Horst and Urschler, Martin},
  booktitle = {Statistical Atlases and Computational Models of the Heart. ACDC and MMWHS Challenges. STACOM 2017},
  doi       = {10.1007/978-3-319-75541-0_20},
  pages     = {190--198},
  year      = {2018},
}
```

[Regressing Heatmaps for Multiple Landmark Localization Using CNNs](https://doi.org/10.1007/978-3-319-75541-0_20):

```
@inproceedings{Payer2016,
  title     = {Regressing Heatmaps for Multiple Landmark Localization Using {CNNs}},
  author    = {Payer, Christian and {\v{S}}tern, Darko and Bischof, Horst and Urschler, Martin},
  booktitle = {Medical Image Computing and Computer-Assisted Intervention - {MICCAI} 2016},
  doi       = {10.1007/978-3-319-46723-8_27},
  pages     = {230--238},
  year      = {2016},
}
```
