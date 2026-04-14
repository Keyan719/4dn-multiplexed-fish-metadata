# 4DN Multiplexed FISH Metadata

Metadata and download manifests for **mouse** multiplexed FISH datasets from the [4DN Data Portal](https://data.4dnucleome.org/).

> **Note:** All 92 experiment sets in this repository use mouse (*Mus musculus*) samples, as retrieved via the 4DN portal's organism filter.

**Last updated:** 2026-04-14 | **Total experiment sets:** 92 | **Total trace CSV files:** 146

---

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

---

## Per-Paper Descriptions

### 1. Hafner_2023_PMID37146570
**Hafner A et al. (2023) — PMID:37146570**

- **Cell type:** Mouse embryonic stem cells (mESC, TC1 line)
- **Chromatin target:** 3-Mb region on Chr6; 30-Mb and 150-Mb regions on Chr3
- **Experiment type:** Chromatin tracing with acute protein degradation (AID / dTAG) to deplete CTCF, RAD21 (cohesin), RING1B, and EED (PRC1/PRC2)
- **Conditions (32 sets):** Untreated controls, +auxin (CTCF-AID, RAD21-AID), dTAG treatments, combined cohesin+PcG depletions at three genomic scales (3 Mb, 30 Mb, 150 Mb)

---

### 2. LiuM_2024_doi_2023.07.23.550157
**Liu M et al. (2024) — doi:10.1101/2023.07.23.550157 (preprint)**

- **Cell type:** Mouse lung (type II pneumocytes/AT2, LUAD tumors, adenoma) and pancreatic (PDAC, PanIN, ductal) primary cells from individual patient-derived xenografts
- **Chromatin target:** ~60-kb feature-containing regions of 473 TADs spanning Chr1–Chr19 (genome-wide TAD survey, 4 imaging rounds)
- **Experiment type:** Multiplexed FISH studying Polycomb (RNF2/PRC1) regulation of TAD organization in cancer vs. normal lung/pancreatic cells; RNF2 depletion via shRNA or dTAG
- **Conditions (22 sets):** RNF2 dTAG depletion in AT2 cells; shRNF2 knockdown in LUAD, adenoma, AT2 cells; PDAC vs. PanIN vs. pancreatic duct comparisons

---

### 3. Tastemel_2025_PMID40060486
**Tastemel M et al. (2025) — PMID:40060486**

- **Cell type:** Mouse embryonic stem cells (F123-CASTx129 hybrid with Sox2 reporter tags and synthetic CTCF-binding site insertions)
- **Chromatin target:** 205-kb region on Chr11 (Sox2 gene to super-enhancer); also a 7.5-kb synthetic CBS insertion between Sox2 and SE
- **Experiment type:** Multiplexed FISH with FKBP12(F36V)-dTAG degron for acute CTCF or RAD21 depletion, during ESC self-renewal and early differentiation; also KAT6B knockout
- **Conditions (11 sets):** KAT6B KO; FKBP12-RAD21 treated/control; FKBP12-CTCF treated at 12 h / 24 h across differentiation time points

---

### 4. Murphy_2024_PMID38361032
**Murphy SE and Boettiger AN (2024) — PMID:38361032**

- **Cell type:** mESC (2i media), cervical neural progenitor cells (differentiated from mESC), and E10.5 mouse brain tissue (in vivo)
- **Chromatin target:** 52 consecutive 5-kb loci at the HoxA locus (~260 kb total), imaged with Alexa Fluor 750
- **Experiment type:** Chromatin tracing of the HoxA locus across differentiation states and in vivo brain tissue; EED and RING1B (PRC1/PRC2) degraded via dTAG to probe Polycomb-mediated compaction
- **Conditions (5 sets):** Untreated mESC, neural progenitors, E10.5 brain tissue, mESC + dTAG depletion of EED/RING1B

---

### 5. Huang_2021_PMID34002095
**Huang H et al. (2021) — PMID:34002095**

- **Cell type:** Mouse embryonic stem cells (F123-CASTx129 hybrid with Sox2 RNA-FISH capability)
- **Chromatin target:** ~30-kb region between the Sox2 gene and its super-enhancer on Chr11, with synthetic CTCF site insertions at different positions
- **Experiment type:** Multiplexed chromatin + RNA FISH, testing how engineered CTCF-binding site insertions between / downstream of Sox2 and its SE alter looping and Sox2 transcription
- **Conditions (5 sets):** 4 CTCF sites between Sox2 and SE; 4 CTCF sites downstream of both; 4 mutant (non-binding) CTCF sites; WT controls; each with simultaneous Sox2 RNA FISH

---

### 6. Fujimori_2023_doi_2023.10.03.560616
**Fujimori T et al. (2023) — doi:10.1101/2023.10.03.560616 (preprint)**

- **Cell type:** Mouse embryonic stem cells (mESC) during early differentiation
- **Chromatin target:** ~150-kb region around the Nanog promoter on Chr6 (3 imaging rounds: DAPI + 2 DNA channels)
- **Experiment type:** Multiplexed FISH tracking chromatin compaction dynamics at the Nanog locus across ESC differentiation time points (0, 1, 2, 3 days)
- **Conditions (4 sets):** Day 0 (undifferentiated), Day 1, Day 2, Day 3 of differentiation

---

### 7. Jensen_2025_PMID39626660
**Jensen CL et al. (2025) — PMID:39626660**

- **Cell type:** Mouse embryonic stem cells (mESC, R1 line)
- **Chromatin target:** 40 consecutive 5-kb loci (with 5-kb spacing) at the Prdm8–Fgf5 locus (~400 kb), targeted with Cy5-labeled imaging oligos
- **Experiment type:** Multiplexed FISH testing the effect of local sequence insertions (USP/USF elements) on chromatin architecture at the Prdm8–Fgf5 locus
- **Conditions (3 sets):** Non-targeting control, 7.5-kb USP Prdm8 insertion, 33-kb USF Fgf5 insertion

---

### 8. LiuS_2025_PMID40009678
**Liu S et al. (2025) — PMID:40009678**

- **Cell type:** Mouse visual cortex tissue (in vivo; excitatory/inhibitory neurons and non-neuronal cells); wild-type and Mecp2 knockout (Rett syndrome model)
- **Chromatin target:** 2,000 genomic loci genome-wide (~1-Mb resolution), 3 fluorescence channels; plus RNA-MERFISH for ~39 MOp marker RNAs and MeCP2 protein immunostaining
- **Experiment type:** Joint chromatin + transcriptome + protein imaging in mouse visual cortex tissue sections; compares chromatin organization in WT vs. Mecp2 KO neurons
- **Conditions (3 sets):** WT visual cortex, Mecp2 KO, WT motor cortex (MOp)

---

### 9. LeDJ_2024_doi_2024.05.08.593251
**Le DJ et al. (2024) — doi:10.1101/2024.05.08.593251 (preprint)**

- **Cell type:** Mouse embryonic stem cells (mESC, E14 line)
- **Chromatin target:** 188 super-enhancers (SEs) genome-wide (ORCA imaging); a subset of 44 SEs also co-imaged with RNA-FISH
- **Experiment type:** ORCA-based chromatin tracing of SE hubs with simultaneous RNA expression detection, studying SE–gene spatial co-localization
- **Conditions (2 sets):** 188 SE imaging (ORCA only); 44 SE + RNA-FISH combined

---

### 10. Jay_2025_PMID40501665
**Jay A et al. (2025) — PMID:40501665**

- **Cell type:** Mouse double-positive (DP) alpha-beta thymocytes (primary T-cell progenitors from thymus)
- **Chromatin target:** 900-kb region around the Ets1–Fli1 locus (encodes key T-cell transcription factors), imaged with Alexa Fluor 647-labeled readout probes
- **Experiment type:** Multiplexed FISH in primary mouse thymic T cells to characterize chromatin architecture at the Ets1–Fli1 locus
- **Conditions (1 set):** Wild-type DP T-cells (1 biological replicate)

---

### 11. HungTC_2024_PMID38238628
**Hung TC et al. (2024) — PMID:38238628**

- **Cell type:** Mouse embryonic fibroblasts (MEF) or similar primary cells
- **Chromatin target:** Consecutive 10-kb loci at the Pitx1 developmental locus, imaged with Cy5-labeled readout probes
- **Experiment type:** Chromatin tracing of the Pitx1 enhancer–promoter locus with high biological replication (5 biological replicates)
- **Conditions (1 set, 5 bio reps):** Wild-type cells

---

### 12. TakeiY_2021_PMID34591592
**Takei Y et al. (2021) — PMID:34591592 (Nature)**

- **Cell type:** Mouse brain cortex neurons (in vivo, primary tissue sections)
- **Chromatin target:** 1,267 + 1,193 loci genome-wide (~1-Mb resolution); 1,200 loci from 20 regions at 25-kb resolution; plus 39 RNAs (MERFISH), 5–8 chromatin marks (antibody probes), LINE1 repeats, minor satellite, and telomere probes
- **Experiment type:** Highly multiplexed joint chromatin + transcriptome + epigenome imaging (ORCA + MERFISH + antibody probes) in mouse brain cortex tissue; one of the most comprehensive multi-modal chromatin tracing datasets published
- **Conditions (1 set, 6 trace file outputs):** Wild-type brain cortex

---

### 13. TakeiY_2021_PMID33505024
**Takei Y et al. (2021) — PMID:33505024 (Science)**

- **Cell type:** Mouse embryonic stem cells (mESC)
- **Chromatin target:** 1,267 + 1,193 loci genome-wide (~1-Mb resolution); 1,200 loci at 25-kb resolution from 20 sub-Mb regions; 35 RNAs (MERFISH); 10–17 chromatin marks (antibody probes); LINE1, minor satellite, telomeres
- **Experiment type:** Multiplexed joint chromatin + transcriptome + epigenome imaging in mESCs; companion paper to PMID:34591592; reveals genome-wide chromatin compartment organization and transcriptional correlations
- **Conditions (1 set, 4 trace file outputs):** Wild-type mESC

---

### 14. LiuM_2020_PMID32518300
**Liu M et al. (2020) — PMID:32518300**

- **Cell type:** Mouse fetal liver cells (primary tissue, ~E14.5)
- **Chromatin target:** 19 consecutive 5-kb loci on Chr19 (~95 kb); 10 TADs on Chr19; 40 TADs on Chr19; combined with MERFISH for 55 liver marker RNAs + 82 Chr19 genes; nucleolus (fibrillarin IF) and cell membrane (WGA)
- **Experiment type:** Multi-scale chromatin tracing at Chr19 in mouse fetal liver tissue combined with RNA MERFISH and nuclear landmark imaging; one of the earliest demonstrations of integrated chromatin + transcriptome imaging in primary tissue
- **Conditions (1 set, 4 bio reps/datasets):** Wild-type fetal liver

---

## Files

`metadata/all_papers_combined.csv` — All 146 trace file entries across all 14 papers (147 lines with header)

Individual per-paper files in the `metadata/` folder.

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
