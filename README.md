# 4DN Multiplexed FISH Metadata

Metadata and download manifests for mouse multiplexed FISH datasets from the [4DN Data Portal](https://data.4dnucleome.org/).

**Last updated:** 2026-04-14 | **Total experiment sets:** 92 | **Total trace CSV files:** 146

## Papers Covered

| # | Label | Publication | Sets | Trace Files |
|---|-------|-------------|------|-------------|
| 1 | Hafner_2023_PMID37146570 | Hafner A et al. (2023) PMID:37146570 | 32 | 48 |
| 2 | LiuM_2024_doi_2023.07.23.550157 | Liu M et al. (2024) doi:10.1101/2023.07.23.550157 | 22 | 29 |
| 3 | Tastemel_2025_PMID40060486 | Tastemel M et al. (2025) PMID:40060486 | 11 | 11 |
| 4 | Murphy_2024_PMID38361032 | Murphy SE and Boettiger AN (2024) PMID:38361032 | 5 | 10 |
| 5 | Huang_2021_PMID34002095 | Huang H et al. (2021) PMID:34002095 | 5 | 5 |
| 6 | Fujimori_2023_doi_2023.10.03.560616 | Fujimori T et al. (2023) doi:10.1101/2023.10.03.560616 | 4 | 8 |
| 7 | Jensen_2025_PMID39626660 | Jensen CL et al. (2025) PMID:39626660 | 3 | 3 |
| 8 | LiuS_2025_PMID40009678 | Liu S et al. (2025) PMID:40009678 | 3 | 10 |
| 9 | LeDJ_2024_doi_2024.05.08.593251 | Le DJ et al. (2024) doi:10.1101/2024.05.08.593251 | 2 | 2 |
| 10 | Jay_2025_PMID40501665 | Jay A et al. (2025) PMID:40501665 | 1 | 1 |
| 11 | HungTC_2024_PMID38238628 | Hung TC et al. (2024) PMID:38238628 | 1 | 5 |
| 12 | TakeiY_2021_PMID34591592 | Takei Y et al. (2021) PMID:34591592 | 1 | 6 |
| 13 | TakeiY_2021_PMID33505024 | Takei Y et al. (2021) PMID:33505024 | 1 | 4 |
| 14 | LiuM_2020_PMID32518300 | Liu M et al. (2020) PMID:32518300 | 1 | 4 |

## Files

`metadata/all_papers_combined.csv` — All 146 trace file entries (combined, 147 lines with header)

Individual files per paper in `metadata/` folder — see file listing above.

## CSV Column Glossary

| Column | Description |
|--------|-------------|
| paper | Unique label (Author_Year_PMID or _doi) |
| expset_accession | 4DN experiment set accession |
| condition | Experimental condition label |
| dataset_label | Dataset description |
| biosource | Cell line or tissue name |
| biosample_type | e.g. stem cells, primary cells, tissue |
| biosample_category | e.g. Mouse stem cell, Other |
| tissue | Tissue or cell line of origin |
| treatments_summary | e.g. DMSO treatment (4.0h), dTAG-13 treatment |
| modifications_summary | Genetic modifications |
| assay_target | Assay type (multiplexed FISH) |
| imaging_rounds | Number of imaging rounds |
| num_bio_reps | Number of biological replicates |
| bio_rep_index | Biological replicate index for this file |
| trace_core_file_accession | 4DN file accession for trace core CSV |
| trace_core_url | Direct S3 download URL for FOF-CT trace core CSV |
| all_fofct_types | All FOF-CT file types available (pipe-separated) |

## Download Trace Files

```bash
# Download all trace CSVs using wget
tail -n +2 metadata/all_papers_combined.csv | cut -d',' -f16 | sort -u | wget -i -
```

## Source

[4DN Data Portal — Mouse Multiplexed FISH](https://data.4dnucleome.org/browse/?type=ExperimentSetReplicate&experimentset_type=replicate&experiments_in_set.experiment_type.display_title=multiplexed+FISH&experiments_in_set.biosample.biosource.organism.name=mouse)
