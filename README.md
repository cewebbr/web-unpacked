# The Web unpacked: a quantitative analysis of global Web usage

This repository contains the data and analysis for the paper [The Web unpacked: a quantitative analysis of global Web usage](https://arxiv.org/abs/2404.17095).


## Paper's abstract

This paper presents a comprehensive analysis of global web usage patterns based on data from SimilarWeb, a leading source for estimating web traffic. Leveraging a dataset comprising over 250,000 websites, we estimate the total web traffic and investigate its distribution among domains and industry sectors. We detail the characteristics of the top 116 domains, which comprise an estimated one-third of all web traffic. Our analysis scrutinizes various attributes of these domains, including their content sources and types, access requirements, offline presence, and ownership features. Our analysis reveals a significant concentration of web traffic, with a diminutive number of top websites capturing the majority of visits. Search engines, news and media, social networks, streaming, and adult content emerge as primary attractors of web traffic, which is also highly concentrated on platforms and USA-owned websites. Much of the traffic goes to for-profit but mostly free-of-charge websites, highlighting the dominance of business models not based on paywalls.


## Project's structure:

    .
	├── LICENSE                 <- Copy and use license for this project
    ├── README.md               <- This document
    ├── requirements.txt        <- Main required Python packages
    ├── data                    <- Data directory
    |   ├── raw                 <- Raw, original data
    |   ├── cleaned             <- Data cleaned by code in this project
    |   └── processed           <- Data further processed by code in this project
    └── analysis                <- Analysis notebooks
        └── plots               <- Plots created during analysis
    

## Annotated data

The results from the manual inspection and research about the 116 most visited domains in the world can be found here: 
[data/cleaned/domains-annotated_v03.csv](data/cleaned/domains-annotated_v03.csv)

The metadata about it is located here: [data/cleaned/domains-annotated_metadata_v03.md](data/cleaned/domains-annotated_metadata_v03.md).

## Acknowledgements

If you use any content in this repository (e.g. data, code or result), please cite the paper [The Web unpacked: a quantitative analysis of global Web usage](https://arxiv.org/abs/2404.17095).


## Contact

This project was created and developed by [Henrique S. Xavier](http://henriquexavier.net) (<https://github.com/hsxavier>).
