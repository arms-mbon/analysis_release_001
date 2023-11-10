# analysis_release_001

These are the data files associated with the first ARMS-MBON dataset submitted to EurOBIS ([DOI](https://doi.org/10.14284/620)): species identifications, fasta files, and PEMA parameter files, for the COI marker gene for the events between 2018 and 2020.  

[PEMA](https://github.com/hariszaf/pema) is the metabarcoding analysis pipeline we use to process the COI (and also 18S, and ITS) raw sequences obtained from the ARMS-MBON samples. 

The raw sequences are deposted in [ENA](https://www.ebi.ac.uk/ena/browser/home) and information regarding these can be found in [the data workspace repo](https://github.com/arms-mbon/data_workspace/tree/main/qualitycontrolled_data) and with the [SOPs](https://github.com/arms-mbon/documentation/tree/main/standard_operating_procedures). 

The sequences were processed through PEMA after being grouped by gene and by MiSeq sequencing run. Included in this repository are:
* The parameter files used as input for each PEMA processing run
* The taxonomic assignment files output by PEMA
* The fasta files output by PEMA

PEMA was run on sequences grouped by gene and by MiSeq sequencing run, and each group has its own parameter files, taxonomic assignment files, and fasta files. An overview of the processing -- including the material sample IDs, ENA accession numbers, dates and observatories etc - from which one can identify which samples were processed in which group, is provided as [pema_overview_COI_batch1.xlsx](https://github.com/arms-mbon/analysis_release_001/blob/main/pema_overview_COI_batch1.xlsx). 

The full set of PEMA files (i.e. for all the ARMS-MBON processing we have done) can be found in [ARMS GitHub working space](https://github.com/arms-mbon/data_workspace/tree/main/analysis_data/from_pema): this repository is specifically the subset of those results published in EurOBIS and have been take from [processing_batch1](https://github.com/arms-mbon/data_workspace/tree/main/analysis_data/from_pema/processing_batch1).

Some of the PEMA processing metadata for these COI runs. Links to all included algorithms and databases can be found in the PEMA URL, as well as HowTos and references.
| parameter | value |
| --- | --- | 
| PEMA URL | https://github.com/hariszaf/pema | 
| PEMA version | v2.1.4 | 
| ref database for taxonomy assignment | Midori v2 | 
| clustering algorithm | Swarm | 




