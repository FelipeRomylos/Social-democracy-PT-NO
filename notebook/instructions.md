## How to reproduce the ESS analysis

1. Download the dataset using the [European Social Survey Data Builder](https://ess.sikt.no/en/data-builder/).

2. Select the countries of interest and the corresponding ESS rounds.  
   In this project, **Norway** and **Portugal** were selected using **Round 4 (2008)** and **Round 8 (2016)**.  
   You may select other countries, but you will need to adapt the party recoding maps accordingly.

3. Make sure to include the following variables in your dataset:  
   `gincdif`, `dfincac`, `gvslvue`, `sbbsntx`, `sbeqsoc`, `sbstrec`.

4. Download the dataset as a `.csv` file.

5. To reproduce the analysis without modifying the code, ensure that the `.csv` file has the same filename used in the notebook/script (or update the file path accordingly).
