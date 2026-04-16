# 4DN Human Multiplexed FISH Metadata

Metadata and download manifests for **human** multiplexed FISH datasets from the [4DN Data Portal](https://data.4dnucleome.org/browse/?type=ExperimentSetReplicate&experimentset_type=replicate&experiments_in_set.experiment_type.display_title=multiplexed+FISH&experiments_in_set.biosample.biosource.organism.name=human).

> **Note:** All 89 experiment sets in this repository use human (*Homo sapiens*) samples, as retrieved via the 4DN portal's organism filter.

**Last updated:** 2026-04-14 | **Total experiment sets:** 89 | **Total trace CSV files:** 120

---

## Papers Covered

| # | Label | Publication | Sets | Trace Files |
|---|-------|-------------|------|-------------|
| 1 | Bintu_2018_PMID30361340 | Bintu B et al. (2018) PMID:30361340 | 10 | 10 |
| 2 | Nir_2018_PMID30586358 | Nir G et al. (2018) PMID:30586358 | 1 | 0 |
| 3 | Su_2020_PMID32822575 | Su JH et al. (2020) PMID:32822575 | 3 | 3 |
| 4 | Wang_2016_PMID27445307 | Wang S et al. (2016) PMID:27445307 | 5 | 0 |
| 5 | Cheng_2021_PMID34749781 | Cheng Y et al. (2021) PMID:34749781 | 9 | 0 |
| 6 | Llimos_2022_PMID35440565 | Llimos G et al. (2022) PMID:35440565 | 2 | 4 |
| 7 | Fujimori_2023_doi_10.1101_2023.10.03.560616 | Fujimori T et al. (2023) doi:10.1101/2023.10.03.560616 | 18 | 59 |
| 8 | Cheng_2023_PMID36778402 | Cheng Y et al. (2023) PMID:36778402 | 15 | 15 |
| 9 | Chen_2023_PMID36996812 | Chen LF et al. (2023) PMID:36996812 | 5 | 8 |
| 10 | Patterson_2023_PMID37540754 | Patterson B et al. (2023) PMID:37540754 | 21 | 21 |

---

## Per-Paper Descriptions

### 1. Bintu_2018_PMID30361340
**Bintu B et al. (2018) — PMID:30361340**
- **Cell type:** HCT116, IMR-90, A549, K562 (human immortalized/primary cells)
- **Chromatin target:** 2-Mb regions on chr21 (chr21:28–30 Mb and chr21:34–37 Mb); consecutive 30-kb locus panels (65 or 83 loci)
- **Experiment type:** Chromatin tracing with cohesin depletion (RAD21-AID); cell cycle tracking (Geminin)
- **Conditions (10 sets):** IMR90 chr21:28–30 Mb, IMR90 chr21:18–20 Mb (no TADs), IMR90 chr21:34–37 Mb across cell cycle, A549 chr21:28–30 Mb, K562 chr21:28–30 Mb, HCT116 chr21:28–30 Mb ± cohesin depletion, HCT116 chr21:34–37 Mb ± cohesin depletion + post-division

### 2. Nir_2018_PMID30586358
**Nir G et al. (2018) — PMID:30586358**
- **Cell type:** GM23248 (human lymphoblastoid cell line)
- **Chromatin target:** 8-Mb walks on chr19 (22 genomic regions)
- **Experiment type:** Super-resolution imaging of chromosome walks
- **Conditions (1 set):** Wild-type GM23248 cells — no FOF-CT trace files available

### 3. Su_2020_PMID32822575
**Su JH et al. (2020) — PMID:32822575**
- **Cell type:** IMR-90 (human lung fibroblasts)
- **Chromatin target:** Genome-scale — 1,041 genomic loci (DNA-MERFISH); combined DNA+RNA-MERFISH of 1,137 genes
- **Experiment type:** DNA-MERFISH (genome-scale imaging); alpha-amanitin transcription inhibition
- **Conditions (3 sets):** DNA-MERFISH of 1,041 loci (untreated), DNA-MERFISH (alpha-amanitin treated), DNA+RNA-MERFISH of 1,137 genes

### 4. Wang_2016_PMID27445307
**Wang S et al. (2016) — PMID:27445307**
- **Cell type:** IMR-90 (human lung fibroblasts)
- **Chromatin target:** Consecutive TAD-scale loci on chrX, chr21, chr22, chr20 (14–40 TADs per chromosome)
- **Experiment type:** Chromatin tracing of single chromosomes (sequential FISH)
- **Conditions (5 sets):** chrX (Xi), chrX (Xa), chr22, chr21, chr20 — no FOF-CT trace files available (older pre-FOF-CT format)

### 5. Cheng_2021_PMID34749781
**Cheng Y et al. (2021) — PMID:34749781**
- **Cell type:** IMR-90, RPE-hTERT (human cells)
- **Chromatin target:** 28 consecutive 30-kb loci on chrX with XIST RNA FISH; mH2A.1 protein staining
- **Experiment type:** Chromatin tracing of chrX with epigenetic/RNA markers and pharmacological treatments
- **Conditions (9 sets):** IMR90 untreated (open/closed chromatin), DNA methylation inhibitor, EZH2 inhibitor, hyper H3K27me3, transcription inhibitor, HDAC inhibitor; RPE-1 untreated — no FOF-CT trace files available

### 6. Llimos_2022_PMID35440565
**Llimos G et al. (2022) — PMID:35440565**
- **Cell type:** B-lymphocyte primary cells (LCLs with homozygous reference or mutant indel on chr17)
- **Chromatin target:** 200-kb region on chr17 (AXIN2 variable chromatin module); 8-kb resolution
- **Experiment type:** Multiplexed FISH studying non-coding variant effects on chromatin module formation
- **Conditions (2 sets):** Homozygous reference, homozygous mutant (indel in chr17); 2 bio replicates each

### 7. Fujimori_2023_doi_10.1101_2023.10.03.560616
**Fujimori T et al. (2023) — doi:10.1101/2023.10.03.560616 (preprint)**
- **Cell type:** K562 (human erythroleukemia); 293T (HEK293T with TetR-KRAB/DNMT3B/HDAC4 doxycycline-inducible silencing systems)
- **Chromatin target:** MYC locus on chr8 (48 × 10-kb segments, ~480 kb); AAVS1 locus on chr19 (custom genome assembly with pJT039-chr19 insert, 19 readout steps at 5-kb resolution)
- **Experiment type:** Multiplexed FISH of MYC locus in K562 (widefield vs custom microscope); Multiplexed FISH of AAVS1 chromatin with inducible TetR-KRAB/DNMT3B/HDAC4 silencing (wildtype, EEW25AAA mutant, Y46A mutant) and doxycycline treatments
- **Conditions (18 sets):** K562 MYC widefield/customscope; 293T rTetR-KRAB (wt/Y46A/EEW25AAA) ± dox 1d/5d, washout; rTetR-DNMT3B ± dox 5d+22d washout; rTetR-HDAC4 ± dox 1d/5d
### 8. Cheng_2023_PMID36778402
**Cheng Y et al. (2023) — PMID:36778402**
- **Cell type:** H1-hESC differentiated to neural progenitor cells, RPE-hTERT, A549 (human cancer/immortalized cell lines)
- **Chromatin target:** 27 TADs on Chr22; 34 TADs on Chr21; Geminin (cell cycle marker)
- **Experiment type:** Perturb-tracing: high-content screening of 3D genome regulators via multiplexed FISH with CRISPR perturbations (CHD7 knockdown/overexpression, ZNF114, PCBP1, 137-gene screen)
- **Conditions (15 sets):** H1-hESC NPC shCHD7/control on Chr22; RPE-hTERT siCHD7/control on Chr21 and Chr22; A549 siCHD7/shCHD7/sgZNF114/sgPCBP1/controls on Chr22; CHD7 overexpression; 137-gene knockdown screen
### 9. Chen_2023_PMID36996812
**Chen LF et al. (2023) — PMID:36996812**
- **Cell type:** H9 differentiated to cranial neural crest cells (CNCCs); H9 ESCs
- **Chromatin target:** 80 spaced regions at SOX9 locus
- **Experiment type:** Chromatin tracing of SOX9 locus with and without CTCF binding site deletions
- **Conditions (5 sets):** CNCCs wt, CNCCs with CTCF deletions at E1.35 and SOX9 promoter; ESC undifferentiated; multiple bio replicates

### 10. Patterson_2023_PMID37540754
**Patterson B et al. (2023) — PMID:37540754**
- **Cell type:** IMR-90 (human fibroblasts); HES-3, H9, H7-hESC (human embryonic stem cells)
- **Chromatin target:** chrX TADs (20+20 TADs, ~100 kb per TAD); XIST RNA FISH; ATRX protein staining
- **Experiment type:** Chromatin tracing of chrX folding conformations in naive and primed human pluripotent stem cells during X-chromosome inactivation
- **Conditions (21 sets):** IMR-90 mTeSR1/5iLAF/5iLA; HES-3 mTeSR1/5iLAF/5iLA/4iLAF+tMEKi; H9 mTeSR1/5iLAF/5iLA combined (XIST+/−), ATRX+/−; H7 day2/4/6 (XIST+/−)
---

## Files

- `metadata/all_papers_combined.csv` — All 120 trace file entries across 10 papers (161 lines with header including expsets without trace files)
- Individual per-paper files in the `metadata/` folder.

### CSV Column Glossary

| Column | Description |
|--------|-------------|
| `paper` | Unique label (Author_Year_PMID or _doi) |
| `expset_accession` | 4DN experiment set accession |
| `condition` | Experimental condition label |
| `dataset_label` | Dataset description |
| `biosource` | Cell line or tissue name |
| `biosample_type` | e.g. immortalized cells, primary cells |
| `biosample_category` | e.g. immortalized cell line, primary cell |
| `tissue` | Tissue or cell line of origin |
| `treatments_summary` | e.g. doxycycline treatment |
| `modifications_summary` | Genetic modifications |
| `assay_target` | Assay type (multiplexed FISH) |
| `imaging_rounds` | Number of imaging rounds |
| `num_bio_reps` | Number of biological replicates |
| `bio_rep_index` | Biological replicate index for this file |
| `trace_core_file_accession` | 4DN file accession for trace core CSV |
| `trace_core_url` | Direct S3 download URL for FOF-CT trace core CSV |
| `all_fofct_types` | All FOF-CT file types available (pipe-separated) |

| readout_resolution | Step/readout resolution (e.g. 30 kb, TAD-level) |
| region_size | Genomic region size/range (e.g. chr21:28-30 Mb) |
| cell_type_detail | Detailed cell type/biosource from 4DN portal |
| treatment_detail | Specific treatment details from 4DN portal |

## Download Trace Files

```bash
# Download all trace CSVs using wget
tail -n +2 metadata/all_papers_combined.csv | cut -d',' -f16 | grep -v '^$' | sort -u | wget -i -
```

---

**Source:** [4DN Data Portal — Human Multiplexed FISH](https://data.4dnucleome.org/browse/?type=ExperimentSetReplicate&experimentset_type=replicate&experiments_in_set.experiment_type.display_title=multiplexed+FISH&experiments_in_set.biosample.biosource.organism.name=human)
