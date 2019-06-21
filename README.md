![method outline](https://github.com/yufu2015/PathImaging/blob/master/readme.svg)

# Pan-cancer quantitative histopathology analysis using deep learning

This directory contains the code to quantify histopathology features from H&E stained images using Inception-V4 in a Pan-cancer tissue classification setting.

The code is in shell and python.


## External Prerequisites:

OpenSlide
https://openslide.org/

tensorflow
https://www.tensorflow.org/install

## Dataset

The histopathology images used are from TCGA (https://portal.gdc.cancer.gov/), open access to all. Only images from frozen tissue are included.

The dataset is composed with 42 normal and tumor tissue types from 28 cancer types. Labels used in the classification can be found here /data/codebook.txt.

## How to use
Run inception/pipeline.sh (with user defined directories)


  



