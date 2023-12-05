# RS-DatasetsHub
Welcome to **RS-DatasetsHub**! 
This curated collection hosts essential datasets used within the remote sensing community. Each dataset featured here is accompanied by pertinent details, including the paper in which it was published, the year of publication, the number of classes, the total number of images, image sizes, and the specific tasks for which the datasets are well-suited.

## Datasets
All the datasets reported in the following section are available [here](https://mega.nz/folder/SNlR3ayC#7EFZiVPhmmkKsrL4LtXmNQ). Each dataset directory is structured as follows: 
```
- dataset_folder:
  - dataset_images:
      - image_1
      - image_2
      - .
      - .
      - .
  - dataset.json
```
Depending on the dataset task, the `dataset.json` may contain both the paths and captions of the images. Furthermore, some dataset may have sub-directories for better organizing images based on the class. 

## Papers 

| Paper Name                                                                                                      | Dataset Name | Publication Year | Number of Categories | Number of Images | Images Size | Task |
|:---------------------------------------------------------------------------------------------------------------:|:--------------:|:---------------------:|:----------------------:|:------------------:|:----------------:|:------:|
| [Exploring Models and Data for Remote Sensing Image Caption Generation, Lu et al.](https://arxiv.org/pdf/1712.07835v1.pdf) | **RSICD**   | 2017 | 30    | 10,921  | 224x224 | Captioning & Classification |
| [UC-Merced Data Set, Yang, Newsam](https://www.researchgate.net/publication/221589425_Bag-of-visual-words_and_spatial_extensions_for_land-use_classification) | **UCMD**   | 2010 | 21    | 2,100  | 256x256 | Captioning & Classification |
| [Exploring a Fine-Grained Multiscale Method for Cross-Modal Remote Sensing Image Retrieval, Yuan et al.](https://arxiv.org/ftp/arxiv/papers/2204/2204.09868.pdf) | **RSITMD**   | 2022 | 32    | 4,743   | 224x224 | Captioning & Classification |
| [PatternNet: A Benchmark Dataset for Performance Evaluation of Remote Sensing Image Retrieval, Zhou et al.](https://arxiv.org/ftp/arxiv/papers/1706/1706.03424.pdf) | **PatternNet**   | 2017 | 38    | 30,400  | 256x256 | Classification |
| [EuroSAT: A Novel Dataset and Deep Learning Benchmark for Land Use and Land Cover Classification, Helber et al.](https://www.researchgate.net/publication/319463676_EuroSAT_A_Novel_Dataset_and_Deep_Learning_Benchmark_for_Land_Use_and_Land_Cover_Classification/link/5c41669c299bf12be3d04de1/download) | **EuroSAT**   | 2017 | 10    | 2700  | 64x64 | Classification |
| [Scene Classification With Recurrent Attention of VHR Remote Sensing Images, Wang et al.](https://ieeexplore.ieee.org/document/8454883) | **OPTIMAL-31**   | 2018  | 31    | 1860| 256x256 | Classification |
| [Feature significance-based multibag-of-visual-words model for remote sensing image scene classification, Zhao et al.](https://www.researchgate.net/publication/305259567_Feature_significance-based_multibag-of-visual-words_model_for_remote_sensing_image_scene_classification) | **RSC11**   | 2016  | 100    | 1231 | 512x512 | Classification |
| [Aid: A benchmark data set for performance evaluation of aerial scene classification, Xia et al.](https://ieeexplore.ieee.org/document/7907303) | **AID**   | 2017  | 30    | 10,000| 600x600 | Classification |
| [MLRSNet: A Multi-label High Spatial Resolution Remote Sensing Dataset for Semantic Scene Understanding, Qi et al.](https://www.sciencedirect.com/science/article/abs/pii/S0924271620302677) | **MLRSNet**   | 2020  | 31    | 109,161| 256x256 | Classification |
| [RSI-CB: A Large-Scale Remote Sensing Image Classification Benchmark via Crowdsource Da, Li et al.](https://arxiv.org/ftp/arxiv/papers/1705/1705.10450.pdf) | **RSI-CB256**   | 2017 | 35    | 24,000 | 256x256 | Classification |
| [RSI-CB: A Large-Scale Remote Sensing Image Classification Benchmark via Crowdsource Da, Li et al.](https://arxiv.org/ftp/arxiv/papers/1705/1705.10450.pdf) | **RSI-CB128**   | 2017  | 45    | 36,000 | 128x128 | Classification |
| [NWPU-Captions Dataset and MLCA-Net for Remote Sensing Image Captioning, Cheng et al.](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9866055) | **NWPU-Captions**   | 2016  | 45    | 31,500 | 256,256 | Captioning & Classification |
| [Dirichlet-Derived Multiple Topic Scene Classification Model for High Spatial Resolution Remote Sensing Imagery, Zhao et al.](https://ieeexplore.ieee.org/document/8454883) |  **SIRI-WHU\WHU-earth**   | 2016  | 12    | 2,400 | 200x200 | Classification |
| [Structural High-resolution Satellite Image Indexing, Xia et al.](https://www.researchgate.net/publication/41501734_Structural_High-resolution_Satellite_Image_Indexing) | **WHU-RS19**   | 2012  | 12    | 1,013 | 600x600 | Classification |
| [Deep learning based feature selection for remote sensing scene classification, Zou et al.](https://ieeexplore.ieee.org/document/7272047) | **RSSCN7**  | 2018  | 7    | 2,800 | 400x400 | Classification |

## Contribution 

Any contribution to this work is welcome and very deeply appreciated.

## Citation 

If you have have found and used a dataset in your work thanks to this repository, please consider citing
```
@online{rsDatasetsHub,
    author={Angelo Nazzaro}, 
    title = {RS-DatasetsHub},
    publisher={Github},
    url={https://github.com/NeuRoNeLab/RS-DatasetsHub},
    year={2023}
}
```
