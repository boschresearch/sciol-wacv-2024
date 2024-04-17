# SciOL and MuLMS-Img

This repository contains companion material for the following [publication](https://openaccess.thecvf.com/content/WACV2024/papers/Tarsi_SciOL_and_MuLMS-Img_Introducing_a_Large-Scale_Multimodal_Scientific_Dataset_and_WACV_2024_paper.pdf):

> Tim Tarsi, Heike Adel, Jan Hendrik Metzen, Dan Zhang, Matteo Finco, Annemarie Friedrich. **SciOL and MuLMS-Img: Introducing A Large-Scale Multimodal Scientific Dataset and Models for Image-Text Tasks in the Scientific Domain.** WACV 2024.

Please direct any questions regarding the dataset or publication
to [Tim Tarsi](mailto:tim.tarsi@gmail.com)

## Overview
In scientific publications, a substantial part of the information is expressed via figures containing images and diagrams. However, existing training and evaluation data for retrieval systems is either limited to one modality or focus on non-scientific domains, making their application to scientific publications challenging.  We address this gap by introducing two novel datasets: (1) SciOL, the largest openly-licensed pre-training corpus for multimodal models in the scientific domain, covering multiple sciences including materials science, physics, and computer science, and (2) MuLMS-Img, a high-quality dataset in the materials science domain, manually annotated for various image-text tasks. 

## MuLMS-Img
The Multi-Layer Materials Science (MuLMS) corpus [1] is a dataset of 50 scientific publications in the materials science domain annotated for various natural language processing tasks. MuLMS-Img extends this dataset by providing over 14500 high quality, manual annotations for various image-text tasks, e.g., Figure type Classification, Optical Character Recognition (OCR) and Text Role Labeling and Figure Retrieval.

You can find the data here: [MuLMS-Img](https://huggingface.co/datasets/Timbrt/MuLMS-Img)


## SciOL
Scientific Openly-Licensed Publications (SciOL) is the largest openly-licensed pre-training corpus for multimodal models in the scientific domain, covering multiple sciences including materials science, physics, and computer science. It consists of over 2.7M scientific scientific publications converted into semi-structured data. SciOL contains over 14 Billion tokens of extracted and structured text.

We host the textual data here: [SciOL-text](https://huggingface.co/datasets/Timbrt/SciOL-text)

For the image-caption pairs see: [SciOL-CI](https://huggingface.co/datasets/Timbrt/SciOL-CI)

## Citation
If you use our work, please cite our paper:
```
@InProceedings{Tarsi_2024_WACV,
    author    = {Tarsi, Tim and Adel, Heike and Metzen, Jan Hendrik and Zhang, Dan and Finco, Matteo and Friedrich, Annemarie},
    title     = {SciOL and MuLMS-Img: Introducing a Large-Scale Multimodal Scientific Dataset and Models for Image-Text Tasks in the Scientific Domain},
    booktitle = {Proceedings of the IEEE/CVF Winter Conference on Applications of Computer Vision (WACV)},
    month     = {January},
    year      = {2024},
    pages     = {4560-4571}
}

```

## References

[1] Timo Pierre Schrader, Matteo Finco, Stefan Grünewald, Felix Hildebrand and Annemarie Friedrich. MuLMS: A Multi-Layer Annotated Text Corpus for Information Extraction in the Materials Science Domain. WIESP 2023.
