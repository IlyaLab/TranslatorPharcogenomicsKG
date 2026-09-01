# TranslatorPharcogenomicsKG

## Code structure
  1. Pharmacogenomics_KG_parsers:
   - individual parsers for each source for the KG, including implementation of filtering criteria & data modeling choice
  2. RIGs:
   - contains Reference Information Guide for each source
  3. FDA_approvde_drurgs_code:
   - helper function to extract the latest FDA approvded drug list
  4. HGNC_human_gene_code:
   - helper function to extract the latest HGNC gene list
  5. TCT_sanity_check_code:
   - test pharmacogenomics KG's access via TCT
  6. domanin_expert_tables:
   - additional domain expert hand curated tables as source
