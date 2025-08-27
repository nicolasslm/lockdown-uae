# **COVID-19’s Impact on the UAE’s Economy: Evidence of its reliance on policies of foreign countries:**

This repository contains all the elements (jupyter notebook, data, ...) in order to reproduce the paper entitled "COVID-19’s Impact on the UAE’s Economy: Evidence of its reliance on policies of foreign countries".

The purpose of this repository is to allow full transparency and reproducibility for this study.

## Setting up locally:

1. Clone the repository with the following command in the terminal:

    `git clone https://github.com/nicolasslm/lockdown-uae.git`

2. Download the necessary packages (the ones at the start of the uae.ipynb notebook).

## Downloading the data:

Shapefiles have been included in the repository for your convenience. In order to download the relevant NTL data used in the study, you'll need to go into Payne Institute database (https://eogdata.mines.edu/nighttime_light/monthly/v10/) and download the data for the following months, each for the 75N60W tile:

- March 2019
- May 2019
- June 2019
- February 2020
- March 2020
- April 2020
- May 2020
- June 2020
- July 2020
- August 2020
- September 2020
- August 2021
- September 2022
- October 2023

This will be a lot of data so make sure you have enough storage and that your machine can handle it. 

For each folder you download, extract the data, take out the relevant .tif file (a file of this form: SVDNB_npp_20190301-20190331_75N060W_vcmcfg_v10_c201904071900.avg_rade9h.tif), put them into a folder (NTL_data in my case). This is to make the datacube will work. 