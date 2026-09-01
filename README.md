# TranslatorPharcogenomicsKG

## Code structure
  * Pharmacogenomics_KG_parsers:
   ** individual parsers for each source for the KG, including implementation of filtering criteria & data modeling choice
  * RIGs:
   ** contains Reference Information Guide for each source
  * FDA_approvde_drurgs_code:
   ** helper function to extract the latest FDA approvded drug list
  * HGNC_human_gene_code:
   ** helper function to extract the latest HGNC gene list
  * TCT_sanity_check_code:
   ** test pharmacogenomics KG's access via TCT
  * domanin_expert_tables:
   ** additional domain expert hand curated tables as source
