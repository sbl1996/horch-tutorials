# Object Detection using SSD in SVHN dataset

In this tutorial, you will learn to:
- Use object detection on the SVHN dataset.
- Understand the basic of SSD.
- Get started in `horch`.

## Setup

### Download Data
Get the data as a tar file [here](https://drive.google.com/open?id=1eexDhJC6UpCghrxqwSyqKnqDRmHInP9B).

Unzip `train.tar` and put the files as follows:

```bash
.
├── Object Detection using SSD in SVHN dataset v1.ipynb
├── README.md
├── SVHN
│   ├── annotations
│   │   └── train.json
│   └── train
│       ├── 1.png
│       ├── 2.png
│       ├── 3.png
│       ├── 4.png
│       ├── ......
│       └── 33402.png
├── cosinelr.png
├── get_loc_cls_preds.png
├── model.png
└── train.png
```

### Install requirements

First, update your pytorch to the lastest stable version. Then run the following instructions to install requirements.

```bash
pip install matplotlib
pip install jupyter
pip install pybind11
pip install -U git+https://github.com/sbl1996/hpycocotools.git
pip install -U git+https://github.com/sbl1996/pytorch-hrvvi-ext.git#egg=pytorch-hrvvi-ext[coco]
```

### Start IPython:
After you have the SVHN data, you should start the IPython notebook server from the
this directory, with the `jupyter notebook` command.
