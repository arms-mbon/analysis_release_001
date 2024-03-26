Here are the output files containing the taxonomic assignments from the PEMA processing of the ARMS-MBON sequences taken between 2018 and 2020, for the COI, 18S, and ITS marker genes. 

The first chunk of files are "Extended final tables" that contain the following information:
* an ASV/OTU identifier (these numbers being unique with a single PEMA run)
* the number of reads for each sample that was processed: each sample is in a separate column, with the title being the material sample ID that can be found in ENA (note: these material sample IDs are not always exactly the same as used in the sampling logsheets in the [sample data folder](https://github.com/arms-mbon/data_workspace/tree/main/qualitycontrolled_data/combined), but they are close)  
* the full taxonomic classification as returned by the reference database used*
* the associated NBCI taxon ID (where there is one)

*PEMA v.2.1.4 was used during this processing phase. In this version, for COI gene sequences, the taxonomic classification in these tables stops at the genus level. The species-level classification is not included in the Extended Final Tables. To obtain species-level classification for COI gene sequences, we used the "tax_assignments" files (see below). These files include detailed classifications beyond the genus level for each ASV provided in the Extended Final Tables.
   
The filenames of the extended final tables contain:
* the date the samples were sequenced (e.g. April2021)
* the gene type (e.g. COI)
* whether or not the blank (sequences) were included

The second chunk of files are the more detailed taxonomic assignements which are produced only for the COI dataset. These contain:
* an ASV identifier  (these numbers being unique with a single PEMA run; the first part of this ID, before the "_", is included in the ID in the first column of its linked Extended_final_table)
* For each node of the taxonomic classification: its name and its confidence level
  
Their filenames contain:
* the date the samples were sequenced (e.g. April2021)
* the gene type (e.g. COI)

There is also a file indicating which samples produced [no results](https://github.com/arms-mbon/analysis_release_001/tree/main/taxonomic_assignments/Samples_with_no_results.xlsx) 
and those which [were removed because they occurred in the blanks](https://github.com/arms-mbon/analysis_release_001/tree/main/taxonomic_assignments/OTUs_ASVs%20that%20were%20removed_modified%20because%20they%20occurred%20in%20the%20blanks.xlsx)
