This repository contains the data used in the article ["Conspiracy of Corporate Networks in Corruption Scandals", Frontiers in Physics, 6, 2021.](https://www.frontiersin.org/articles/10.3389/fphy.2021.667471/full)

Permanent repository in figshare: https://doi.org/10.6084/m9.figshare.13847612.v2

* For privacy protection, we have held in anonymity all the information regarding identification of the companies and associated people. 
* There is one csv file for each of the four cases analyzed in the article. 
* The number in the file names correspond to the case number as it appears in the article text.

The "casex_edgelist.csv" files contain the following information:
* source: Company identifier.
* target: Personnel identifier.
* edge_type: SH, ADM, COM, LR.
* shell: True or False whether the company is identified as shell or not.
* creation_date: Date of company creation in YYYY-MM-DD format when available, otherwise NaT.
