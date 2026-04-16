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

### Genome-Wide and Multi-Scale Studies

These papers survey chromatin organization across hundreds to thousands of genomic loci, providing broad views of chromosome architecture, compartmentalization, and TAD organization. Several combine chromatin tracing with transcriptome (MERFISH) and epigenome (antibody-based) imaging.

#### Hafner_2023_PMID37146570
**Hafner A et al. (2023) — PMID:37146570**

This study performs multi-scale chromatin tracing in mouse embryonic stem cells (mESC, TC1 line) to systematically dissect the contributions of loop-extrusion machinery (CTCF, cohesin/RAD21) and Polycomb repressive complexes (PRC1/RING1B, PRC2/EED) to chromatin folding. Three genomic scales are imaged: a 2.28-Mb region on Chr6 at ~50-kb readout resolution (capturing TAD and sub-TAD structure), a 31-Mb region on Chr3 at ~1-Mb resolution (probing compartment-level organization), and a 150-Mb region on Chr3 at ~1-Mb resolution (chromosome-scale folding). Acute protein degradation (AID for CTCF and RAD21; dTAG for RING1B and EED) is used in combinatorial fashion, yielding 32 experiment sets across untreated, single-depletion, and double-depletion conditions. With 48 trace files, this is the largest dataset in the collection.

- **Cell type:** mESC (TC1 line)
- **Resolution / region:** ~50 kb over 2.28 Mb (Chr6); ~1 Mb over 31 Mb and 150 Mb (Chr3)
- **Conditions (32 sets, 48 trace files):** Untreated, CTCF-AID, RAD21-AID, RING1B-dTAG, EED-dTAG, and pairwise combinations, each at 3 genomic scales

---

#### LiuM_2024_doi_2023.07.23.550157
**Liu M et al. (2024) — doi:10.1101/2023.07.23.550157 (preprint)**

This preprint uses a genome-wide TAD survey design to investigate how Polycomb (PRC1/RNF2) regulates three-dimensional TAD organization in mouse lung and pancreatic cells, including cancer models. The primary imaging design tiles 473 TADs across Chr1–Chr19 at ~60-kb resolution per TAD (4 imaging rounds), enabling a genome-wide census of TAD compaction. A complementary fine-scale design images 10 specific gene loci at 5–20 kb resolution over ~200–400 kb each (5 additional experiment sets). Cell types include normal AT2 pneumocytes, LUAD tumors, adenoma, and pancreatic ductal/PDAC/PanIN cells. RNF2 is depleted via dTAG or shRNA to probe PRC1's causal role in TAD compaction.

- **Cell type:** Mouse AT2 pneumocytes, LUAD, adenoma, PDAC, PanIN, pancreatic ductal cells
- **Resolution / region:** ~60 kb per TAD across 473 TADs genome-wide; 5–20 kb at 10 specific gene loci
- **Conditions (22 sets, 29 trace files):** RNF2-dTAG depletion, shRNF2 knockdown, cancer vs. normal comparisons in lung and pancreas

---

#### LiuS_2025_PMID40009678
**Liu S et al. (2025) — PMID:40009678**

This paper combines genome-wide chromatin tracing, RNA-MERFISH, and MeCP2 protein immunostaining in mouse brain tissue to study how loss of MeCP2 (Rett syndrome model) disrupts 3D genome organization in specific neuronal cell types. A total of 2,000 genomic loci are imaged at ~1-Mb resolution across the genome in mouse visual cortex sections, alongside ~39 cell-type marker RNAs. By jointly profiling chromatin structure and transcriptional identity in the same cells, the study reveals cell-type-specific chromatin compartment changes in Mecp2-knockout neurons. This is one of only three studies in the collection using primary brain tissue.

- **Cell type:** Mouse visual cortex tissue (excitatory/inhibitory neurons, non-neuronal cells); WT and Mecp2 KO
- **Resolution / region:** ~1 Mb across 2,000 loci genome-wide
- **Conditions (3 sets, 10 trace files):** WT visual cortex, Mecp2 KO visual cortex, WT motor cortex (MOp)

---

#### LeDJ_2024_doi_2024.05.08.593251
**Le DJ et al. (2024) — doi:10.1101/2024.05.08.593251 (preprint)**

This preprint applies ORCA-based chromatin tracing to image 376 super-enhancers (SEs) genome-wide at 15-kb resolution in mouse embryonic stem cells (mESC, E14 line), probing whether SEs form spatial hubs and how SE clustering relates to gene activation. A second experiment set co-images 44 SEs together with RNA-FISH for nearby target genes, enabling direct correlation of SE 3D proximity with transcriptional output. This is the only study in the collection specifically focused on super-enhancer spatial organization at a genome-wide scale.

- **Cell type:** mESC (E14 line)
- **Resolution / region:** 15 kb across 376 super-enhancers genome-wide; 44 SEs + RNA-FISH
- **Conditions (2 sets, 2 trace files):** 376 SE ORCA imaging; 44 SE + RNA-FISH combined

---

#### TakeiY_2021_PMID34591592
**Takei Y et al. (2021) — PMID:34591592 (Nature)**

This landmark study performs one of the most comprehensive multi-modal single-cell profiling experiments published, simultaneously imaging chromatin organization, the transcriptome, and the epigenome in individual mouse brain cortex cells. At the genome-wide scale, 2,460 loci are imaged at ~1-Mb resolution; at the fine scale, 1,200 loci spanning 20 sub-megabase regions are imaged at 25-kb resolution. In parallel, 39 cell-type marker RNAs are detected via MERFISH, and 5–8 histone modifications are visualized using sequential antibody probes. Additional probes detect LINE1 repeats, minor satellites, and telomeres. This dataset enables joint analysis of compartment structure, local chromatin folding, gene expression, and epigenetic state within the same cells.

- **Cell type:** Mouse brain cortex neurons (in vivo primary tissue sections)
- **Resolution / region:** ~1 Mb across 2,460 loci genome-wide; 25 kb across 1,200 loci in 20 sub-Mb regions
- **Conditions (1 set, 6 trace files):** Wild-type brain cortex

---

#### TakeiY_2021_PMID33505024
**Takei Y et al. (2021) — PMID:33505024 (Science)**

A companion to the brain cortex study above, this paper applies the same multi-modal imaging framework to mouse embryonic stem cells (mESC). The design again uses 2,460 loci at ~1-Mb genome-wide resolution and 1,200 loci at 25-kb resolution in 20 sub-Mb regions, combined with 35 RNA species (MERFISH) and 10–17 chromatin marks (sequential antibody probes), plus LINE1, minor satellite, and telomere probes. Together with PMID:34591592, these two papers establish the genome-wide multi-omics chromatin imaging approach in both a stem cell and a differentiated tissue context.

- **Cell type:** mESC
- **Resolution / region:** ~1 Mb across 2,460 loci genome-wide; 25 kb across 1,200 loci in 20 sub-Mb regions
- **Conditions (1 set, 4 trace files):** Wild-type mESC

---

#### LiuM_2020_PMID32518300
**Liu M et al. (2020) — PMID:32518300**

One of the earliest demonstrations of integrated chromatin tracing and transcriptome imaging in primary tissue, this study performs multi-scale ORCA chromatin tracing on mouse Chr19 in fetal liver cells (~E14.5). The finest scale images 19 consecutive 5-kb loci (~95 kb total), while two broader scales tile 10 and 40 TADs across Chr19, revealing TAD boundaries and inter-TAD contacts. Concurrently, MERFISH detects 55 liver-specific marker RNAs and 82 Chr19 genes, enabling correlation of local chromatin folding with transcriptional activity. Nuclear landmarks (fibrillarin immunofluorescence for nucleoli, WGA for cell membrane) provide spatial context.

- **Cell type:** Mouse fetal liver cells (primary tissue, ~E14.5)
- **Resolution / region:** 5 kb (19 loci, ~95 kb); TAD-scale (10 and 40 TADs on Chr19); plus RNA-MERFISH
- **Conditions (1 set, 4 trace files):** Wild-type fetal liver

---

### Locus-Specific Studies

These papers use high-resolution chromatin tracing to dissect the 3D folding of individual gene loci, typically at 5–15 kb readout resolution over regions of 150 kb–900 kb. They focus on enhancer–promoter communication, Polycomb-mediated compaction, and the roles of CTCF/cohesin in loop formation at specific developmental or disease-relevant genomic regions.

#### Tastemel_2025_PMID40060486
**Tastemel M et al. (2025) — PMID:40060486**

This study uses chromatin tracing at the Sox2 locus in engineered mouse embryonic stem cells (F123-CASTx129 hybrid) to investigate how CTCF and cohesin organize enhancer–promoter topology and regulate Sox2 transcription. The imaging design covers a ~205-kb region on Chr3 spanning the Sox2 gene and its super-enhancer at ~15-kb readout resolution. A key feature is the insertion of a synthetic 7.5-kb CTCF-binding site cassette between Sox2 and its SE, enabling direct testing of how ectopic insulator elements alter loop architecture. Acute FKBP12(F36V)-dTAG degradation of CTCF or RAD21 is performed during ESC self-renewal and early differentiation (12 h and 24 h). A KAT6B knockout condition is also included.

- **Cell type:** mESC (F123 hybrid with Sox2 reporter and synthetic CBS insertions)
- **Resolution / region:** ~15 kb over ~205 kb (Sox2–SE locus, Chr3)
- **Conditions (11 sets, 11 trace files):** KAT6B KO; FKBP12-RAD21 and FKBP12-CTCF dTAG at multiple differentiation time points

---

#### Murphy_2024_PMID38361032
**Murphy SE and Boettiger AN (2024) — PMID:38361032**

This paper traces chromatin folding at the HoxA developmental gene cluster, a paradigmatic Polycomb-regulated locus, across three biological states: undifferentiated mESC (2i media), cervical neural progenitor cells differentiated from mESC, and E10.5 mouse embryonic brain tissue (in vivo). The imaging design covers 52 consecutive 5-kb readout positions spanning ~290 kb at the HoxA locus on Chr6, providing high-resolution maps of chromatin compaction. Acute dTAG-mediated degradation of EED and RING1B (PRC2 and PRC1 subunits) in mESC directly tests the causal role of Polycomb complexes in maintaining the compact chromatin state observed at HoxA.

- **Cell type:** mESC (2i), neural progenitors, E10.5 brain tissue
- **Resolution / region:** 5 kb over ~290 kb (HoxA locus, Chr6:52090001–52380006)
- **Conditions (5 sets, 10 trace files):** Untreated mESC, neural progenitors, brain tissue, dTAG EED/RING1B depletion

---

#### Huang_2021_PMID34002095
**Huang H et al. (2021) — PMID:34002095**

This study uses multiplexed chromatin and RNA FISH at the Sox2 locus in engineered mouse ESCs (F123-CASTx129 hybrid) to test how synthetic CTCF-binding site insertions reshape chromatin looping and alter Sox2 transcription. The ~210-kb region on Chr3 spanning Sox2 and its super-enhancer is imaged at 5-kb readout resolution, providing detailed maps of enhancer–promoter spatial distances. Four CTCF-binding sites are inserted either between Sox2 and the SE or downstream of both, alongside a mutant (non-binding) CTCF control. Each condition includes simultaneous Sox2 RNA FISH, enabling direct correlation of 3D chromatin architecture with transcriptional output in the same cells.

- **Cell type:** mESC (F123 hybrid with Sox2 RNA-FISH capability)
- **Resolution / region:** 5 kb over ~210 kb (Sox2–SE locus, Chr3:34601078–34811078)
- **Conditions (5 sets, 5 trace files):** WT, 4 CBS between Sox2 and SE, 4 CBS downstream, 4 mutant CBS; each with RNA FISH

---

#### Fujimori_2023_doi_2023.10.03.560616
**Fujimori T et al. (2023) — doi:10.1101/2023.10.03.560616 (preprint)**

This preprint tracks chromatin compaction dynamics at the Nanog locus during mouse ESC differentiation. The imaging design covers a ~150-kb region around the Nanog promoter on Chr6 at ~8-kb readout resolution (using 3 imaging rounds: DAPI + 2 DNA channels). By comparing undifferentiated mESCs (Day 0) with cells at Days 1, 2, and 3 of differentiation, the study captures the progressive chromatin remodeling that accompanies Nanog silencing as cells exit pluripotency.

- **Cell type:** mESC during early differentiation
- **Resolution / region:** ~8 kb over ~150 kb (Nanog locus, Chr6)
- **Conditions (4 sets, 8 trace files):** Day 0 (undifferentiated), Day 1, Day 2, Day 3

---

#### Jensen_2025_PMID39626660
**Jensen CL et al. (2025) — PMID:39626660**

This study investigates how local DNA sequence insertions reshape chromatin architecture at the Prdm8–Fgf5 locus in mouse ESCs (R1 line). The imaging design tiles 40 consecutive 5-kb readout positions with 10-kb step size (5-kb gaps between probes) across a ~400-kb region on Chr5 (Chr5:98150981–98550000), targeted with Cy5-labeled imaging oligos. Two types of sequence elements are inserted: a 7.5-kb USP element near Prdm8 and a 33-kb USF element near Fgf5, each compared to a non-targeting control. This study directly tests whether local sequence perturbations are sufficient to alter higher-order chromatin folding.

- **Cell type:** mESC (R1 line)
- **Resolution / region:** 5 kb readout (10-kb step) over ~400 kb (Prdm8–Fgf5 locus, Chr5:98150981–98550000)
- **Conditions (3 sets, 3 trace files):** Non-targeting control, USP Prdm8 insertion, USF Fgf5 insertion

---

#### Jay_2025_PMID40501665
**Jay A et al. (2025) — PMID:40501665**

This paper characterizes chromatin architecture at the Ets1–Fli1 locus, which encodes two critical transcription factors for T-cell development, in primary mouse double-positive (DP) alpha-beta thymocytes isolated from thymus. The ~900-kb region is imaged at ~15-kb readout resolution using Alexa Fluor 647-labeled probes. As the only study in the collection profiling primary thymic T-cell progenitors, it provides a unique view of chromatin organization at a key T-cell regulatory locus.

- **Cell type:** Mouse DP alpha-beta thymocytes (primary thymic T-cell progenitors)
- **Resolution / region:** ~15 kb over ~900 kb (Ets1–Fli1 locus)
- **Conditions (1 set, 1 trace file):** Wild-type DP T-cells

---

#### HungTC_2024_PMID38238628
**Hung TC et al. (2024) — PMID:38238628**

This study traces the Pitx1 developmental locus in mouse developing limb buds, a primary embryonic tissue. Consecutive 10-kb readout positions span an approximately 750-kb region on Chr13 (Chr13:55615000–56365000), imaged with Cy5-labeled probes. A distinctive feature of this dataset is its emphasis on biological reproducibility: 5 independent biological replicates are included, making it one of the most highly replicated chromatin tracing experiments in the collection. The Pitx1 locus is a well-studied model for tissue-specific enhancer–promoter regulation during limb development.

- **Cell type:** Mouse developing limb buds (primary embryonic tissue)
- **Resolution / region:** 10 kb over ~750 kb (Pitx1 locus, Chr13:55615000–56365000)
- **Conditions (1 set, 5 trace files):** Wild-type limb buds (5 biological replicates)

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
| readout_resolution | Step size per readout (e.g. 5 kb, ~50 kb, ~1 Mb) |
| region_size | Total genomic span of the traced region (e.g. ~2.28 Mb, genome-wide) |
| genomic_region | Genomic coordinates or target label (e.g. Chr6:50500001-52780076, 473 TADs Chr1-Chr19) 
| genome_assembly | Reference genome assembly (GRCm38 for all) |
| all_fofct_types | All FOF-CT file types available (pipe-separated) |

## Download Trace Files

```bash
# Download all trace CSVs using wget
tail -n +2 metadata/all_papers_combined.csv | cut -d',' -f16 | sort -u | wget -i -
```

## Source

[4DN Data Portal — Mouse Multiplexed FISH](https://data.4dnucleome.org/browse/?type=ExperimentSetReplicate&experimentset_type=replicate&experiments_in_set.experiment_type.display_title=multiplexed+FISH&experiments_in_set.biosample.biosource.organism.name=mouse)
