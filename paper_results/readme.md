## The scripts for the results generation in the paper


### Method validation 
| Files  | Description |
| :------------- | :------------- |
| ../simulation.py| simulate benchmark data to evaluate LocalHGT|
|../generate_run_scripts.py| generate batch runing scripts for LocalHGT in evaluation|
|../evaluation.py| evaluate LocalHGT's accuracy in benchmark data|
|../count_table_empty_with_k.py| evaluate hash collision after kmer counting in the complex sample|
| bkp_match_v2.py | Identify HGT event in real-data (initial version) |
|validate_bkp_match.py|Validate the identified HGT events using matched long-read data|
| batch_validate_match.py | Perform the event validation with a batch manner |



### Real-data analyses
| Files  | Description |
| :------------- | :------------- |
|build_UHGG_reference.py| download and prepare the UHGG reference database| 
| basic_statistics.py | Characterize HKP distribution among samples |
| analyze_transfer_gene.py | Analyze the function of HGT-related genes and analyze the HGT transfer patterns  |
| microhomology.py | Test the enrichment of microhomology in HGT breakpoint junctions |
|  mechanism.py| Assign the mutational mechanism for HGT events |
|  mechanism_taxonomy.py| Analyze the assigned mechanisms |
|ana_time_lines.py| examine whether HGT can serve as fingerprints in time-series cohort| 
| kegg_enrichment.py | Given KO list, perform KEGG enrichment analysis |
| association_study.py | Analyze the functional association between HGT and diseases |
| HGT_classifier.py | identify differential HGTs, construct the classifier for each disease |
| CRC_LODO_Analysis.py | Evaluate the integration of HGT and abundance biomarkers in eight CRC cohorts |
| additional_validation.py  | Get information of the indepedent CRC cohort|
| HGT_network.py | Perform HGT network analyses |






