# Creating Backburns Dataset with Spatial Analysis

This project deduplicates and organises a dataset of 396 backburn records supplied by DEECA's Applied Fire Sciences (AFS) team, building a reproducible pipeline that can also be run on future data entries. It reassigns backburns matched to the wrong fire incident using spatial and temporal checks, and groups duplicate records of the same operation using buffered Intersection over Union (IoU) and directional coverage.

## Data

The dataset contains backburns on Victorian public land from 2012 to the 2025 fire season, extracted from DEECA's eMap platform. Each backburn record is matched to a bushfire incident in the Victorian Wildfire Research Database (VWFRD).

## Repositories

- [DEECA Backburn Dataset Repository (Private)](https://github.com/vic-ffm/ds-back-burning-dataset.git): DEECA data-processing workflow
- [ETC5543 Monash Project Repository](https://github.com/HJY353/ETC5543.git): report and project materials i.e presentation 

## Authors

Hendrickson Joewono You and Ibtesam Ifaz, as part of the ETC5543 internship with DEECA.

## Note

All materials and workflows in this project are reproducible and were produced using version control, including the report. The presentation is the exception and has two versions: `backburns-text` and `presentation.pptx`. The `presentation.pptx` version includes DEECA branding and cannot be reproduced through Quarto.
