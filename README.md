# analysis_release_001

[PEMA](https://github.com/hariszaf/pema) is the metabarcoding analysis pipeline we use to process the COI, 18S, and ITS raw sequences obtained from the ARMS-MBON samples. In this repository you will find the bioinformatics results associated with the EurOBIS DOI XXX (still to be created): species identifications from ARMS-MBON data from 2018-2020 for the COI marker gene.

The raw sequences are deposted in [ENA](https://www.ebi.ac.uk/ena/browser/home) and information regarding these can be found in [the data workspace repo](https://github.com/arms-mbon/data_workspace/tree/main/qualitycontrolled_data) and with the [SOPs](https://github.com/arms-mbon/documentation/tree/main/standard_operating_procedures). 

The sequences were processed through PEMA after being grouped by gene and by MiSeq sequencing run. Included in this repository are:
* The parameter files used as input for each PEMA processing run
* The taxonomic assignment files output by PEMA
* The fasta files output by PEMA 

The full set of PEMA files (i.e. for all the ARMS-MBON processing we have done) can be found in [ARMS GitHub working space](https://github.com/arms-mbon/data_workspace/tree/main/analysis_data/from_pema): this repository is specifically those results published in EurOBIS DOI XXX, from [processing_batch1](https://github.com/arms-mbon/data_workspace/tree/main/analysis_data/from_pema/processing_batch1).

Some of the PEMA processing metadata for these COI runs. Links to all included algorithms and databases can be found in the PEMA URL, as well as HowTos and references
| parameter | value |
| --- | --- | 
| PEMA URL | https://github.com/hariszaf/pema | 
| PEMA version | v2.1.4 | 
| ref database for taxonomy assignment | Midori v2 | 
| clustering algorithm | Swarm | 




