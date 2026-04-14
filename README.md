# 4DN Multiplexed FISH Metadata

Metadata and download manifests for mouse multiplexed FISH datasets from the [4DN Data Portal](https://data.4dnucleome.org/).

## Papers Covered

| # | Label | PMID/DOI | Sets | Trace Files |
|---|-------|----------|------|-------------|
| 2 | Hafner_2023_PMID37146570 | PMID:37146570 | 32 | 48 |
| 3 | Tastemel_2025_PMID40060486 | PMID:40060486 | 11 | 11 |
| 4 | Huang_2021_PMID34002095 | PMID:34002095 | 5 | 5 |
| 5 | Murphy_2024_PMID38361032 | PMID:38361032 | 5 | 10 |
| 6 | Fujimori_2023_doi_2023.10.03.560616 | doi:10.1101/2023.10.03.560616 | 4 | 8 |
| 7 | Jensen_2025_PMID39626660 | PMID:39626660 | 3 | 3 |

**Total: 60 experiment sets, 85 trace core CSV files**

## Files

- `metadata/all_papers_combined.csv` - Combined metadata for all 6 papers (85 rows)
- `metadata/Hafner_2023_PMID37146570.csv` - Hafner et al. 2023 (48 rows)
- `metadata/Tastemel_2025_PMID40060486.csv` - Tastemel et al. 2025 (11 rows)
- `metadata/Huang_2021_PMID34002095.csv` - Huang et al. 2021 (5 rows)
- `metadata/Murphy_2024_PMID38361032.csv` - Murphy & Boettiger 2024 (10 rows)
- `metadata/Fujimori_2023_doi_2023.10.03.560616.csv` - Fujimori et al. 2023 (8 rows)
- `metadata/Jensen_2025_PMID39626660.csv` - Jensen et al. 2025 (3 rows)

## Columns

| Column | Description |
|--------|-------------|
| paper | Publication label |
| expset_accession | 4DN experiment set accession |
| condition | Condition/dataset label |
| dataset | Dataset label |
| biosource | Biosource summary |
| sample_type | Biosource type |
| tissue_source | Tissue of origin |
| treatment | Treatments applied |
| modification | Genetic modifications |
| assay_target | Experiment type/assay |
| imaging_rounds | Number of imaging rounds |
| num_bio_reps | Number of biological replicates |
| bio_rep_index | Biological replicate index |
| trace_core_file_accession | 4DN file accession for trace core CSV |
| trace_core_url | Direct download URL for trace core CSV |
| all_fofct_types | All FOF-CT file types present in this set |

## Data Source

All data retrieved from the [4DN Data Portal](https://data.4dnucleome.org/) using the public API.
Search URL: https://data.4dnucleome.org/browse/?type=ExperimentSetReplicate&experimentset_type=replicate&experiments_in_set.experiment_type.display_title=multiplexed+FISH&experiments_in_set.biosample.biosource.organism.name=mouse

Generated: 2026-04-14
