# Dataset for Research

This repository contains the annotation files used in our research.

The JSON annotation files included in this repository were created as part of our work through manual annotation and curation. These annotation files represent our original contribution.

## Dataset Description

The image data used for training is based on the publicly available TAO dataset. The training JSON annotations correspond to the indexed images from the public dataset rather than directly referencing image filenames. The indexing defined in the JSON files should therefore be used to map each annotation to its corresponding image.
.
Similarly, the test JSON annotations are mapped using the indexing scheme adopted for our downloaded evaluation images.

The original TAO dataset is described in:

```bibtex
@article{tao2022internal,
  title={An internal waves data set from sentinel-1 synthetic aperture radar imagery and preliminary detection},
  author={Tao, Mingkai and Xu, Chengji and Guo, Lingxi and Wang, Xiaoqing and Xu, Yanlang},
  journal={Earth and Space Science},
  volume={9},
  number={12},
  pages={e2022EA002528},
  year={2022},
  publisher={Wiley Online Library}
}
```

## Evaluation Data

Our evaluation images and the corresponding binary masks used for evaluating the machine learning model outputs are available separately and can be accessed using the following Google Drive link:

$[**Google Drive:**] (https://drive.google.com/drive/folders/1GAVKWZqpX3NgFnGATJR440MpudkLl1c8?usp=sharing)

The evaluation images and binary masks are provided for research and reproducibility purposes only.

## Repository Contents

* `train-data-annotation.json` — Training annotations.
* `test-data-annotation.json` — Test annotations.

The source code used in this work is not included in the current release. It will be made publicly available following the publication of the associated research paper.

## Usage

Download the required training images from the official TAO dataset and use the provided annotation files to reproduce the training and testing annotations used in our research. The evaluation images and corresponding binary masks can be downloaded separately from the Google Drive link provided above.

## License and Usage

The JSON annotation files provided in this repository are our original work and are released for research and academic purposes only.

Users should obtain the original image data and follow the dataset usage guidelines provided in @tao2022internal ([paper link](https://agupubs.onlinelibrary.wiley.com/doi/pdf/10.1029/2022EA002528)).

If you use these annotation files, evaluation data, or any part of this repository in your research, please cite both the original TAO dataset (@tao2022internal) and our accompanying paper.

