# Anchored Alignment: Preventing Positional Collapse in Multimodal Recommender Systems

## Code Introduction

We develop AnchorRec based on [MMRec]("https://github.com/enoche/MMRec"). Please refer to MMRec for data preparation and basic usage.

We add the following files for AnchorRec implementation:
```
src/anchorrec.py
src/configs/model/ANCHORREC.yaml
```

To run AnchorRec, you can either modify MMRec to include these files or simply run the provided `bash run.sh` script.

## Environment Setup
To create the conda environment, run:
```
conda env create -f env.yaml
```

- python 3.8
- Torch 2.4.1
  