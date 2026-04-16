# 4DN Human Multiplexed FISH Metadata

Metadata and download manifests for **human** multiplexed FISH datasets from the [4DN Data Portal](https://data.4dnucleome.org/browse/?type=ExperimentSetReplicate&experimentset_type=replicate&experiments_in_set.experiment_type.display_title=multiplexed+FISH&experiments_in_set.biosample.biosource.organism.name=human).

> **Note:** All 89 experiment sets in this repository use human (*Homo sapiens*) samples, as retrieved via the 4DN portal's organism filter.

**Last updated:** 2026-04-14 | **Total experiment sets:** 89 | **Total trace CSV files:** 120

---

## Papers Covered

| # | Label | Publication | Sets | Trace Files | Scope |
|---|-------|-------------|------|-------------|-------|
| 1 | Su_2020_PMID32822575 | Su JH et al. (2020) PMID:32822575 | 3 | 3 | Genome-wide |
| 2 | Wang_2016_PMID27445307 | Wang S et al. (2016) PMID:27445307 | 5 | 0 | Chromosome-scale |
| 3 | Nir_2018_PMID30586358 | Nir G et al. (2018) PMID:30586358 | 1 | 0 | Chromosome-scale |
| 4 | Patterson_2023_PMID37540754 | Patterson B et al. (2023) PMID:37540754 | 21 | 21 | Chromosome-scale |
| 5 | Cheng_2023_PMID36778402 | Cheng Y et al. (2023) PMID:36778402 | 15 | 15 | Chromosome-scale |
| 6 | Bintu_2018_PMID30361340 | Bintu B et al. (2018) PMID:30361340 | 10 | 10 | Locus-focused |
| 7 | Cheng_2021_PMID34749781 | Cheng Y et al. (2021) PMID:34749781 | 9 | 0 | Locus-focused |
| 8 | Llimos_2022_PMID35440565 | Llimos G et al. (2022) PMID:35440565 | 2 | 4 | Locus-focused |
| 9 | Fujimori_2023_doi_10.1101_2023.10.03.560616 | Fujimori T et al. (2023) doi:10.1101/2023.10.03.560616 | 18 | 59 | Locus-focused |
| 10 | Chen_2023_PMID36996812 | Chen LF et al. (2023) PMID:36996812 | 5 | 8 | Locus-focused |

---

## Per-Paper Descriptions

### Genome-Wide and Chromosome-Scale Studies

These studies scan large portions of individual chromosomes or the genome, tracing TAD-level or megabase-scale chromatin organization across many domains simultaneously.

#### 1. Su_2020_PMID32822575
**Su JH et al. (2020) — PMID:32822575**
*Genome-Scale Imaging of the 3D Organization and Transcriptional Activity of Chromatin* (Cell)

- **Cell type:** IMR-90 (human fetal lung fibroblasts)
- **Chromatin target:** Genome-scale — 1,041 genomic loci at ~3 Mb spacing (DNA-MERFISH); also combined DNA+RNA-MERFISH of 1,137 genes with landmark nuclear structures
- **Resolution:** ~30 kb per locus; genome-wide spacing ~3 Mb
- **Method:** DNA-MERFISH (multiplexed error-robust FISH) for simultaneous imaging of >1,000 genomic loci; combined with nascent RNA-MERFISH for transcriptional readout
- **Biological question:** How are chromatin domains, compartments, and trans-chromosomal interactions organized at genome scale, and how do they relate to transcription in single cells?
- **Key treatments:** Untreated control; alpha-amanitin transcription inhibition (100 µg/mL)
- **Conditions (3 sets):** DNA-MERFISH of 1,041 loci (untreated), DNA-MERFISH (alpha-amanitin treated), DNA+RNA-MERFISH of 1,137 genes

#### 2. Wang_2016_PMID27445307
**Wang S et al. (2016) — PMID:27445307**
*Spatial organization of chromatin domains and compartments in single chromosomes* (Science)

- **Cell type:** IMR-90 (human fetal lung fibroblasts)
- **Chromatin target:** Consecutive TADs across entire chromosomes — chrX (14 TADs on Xi, 16 TADs on Xa), chr21 (20 TADs), chr22 (26 TADs), chr20 (40 TADs)
- **Resolution:** TAD-level (~0.5–2 Mb per TAD)
- **Method:** Sequential FISH with TAD-specific probes; the earliest chromatin tracing study in this collection
- **Biological question:** How are TADs and A/B compartments spatially organized along individual chromosomes? How does folding differ between active X (Xa) and inactive X (Xi) chromosomes?
- **Conditions (5 sets):** chrX (Xi), chrX (Xa), chr22, chr21, chr20
- **Note:** No FOF-CT trace files available (older pre-FOF-CT format)

#### 3. Nir_2018_PMID30586358
**Nir G et al. (2018) — PMID:30586358**
*Walking along chromosomes with super-resolution imaging, contact maps, and integrative modeling* (PLoS Genetics)

- **Cell type:** GM23248 (human lymphoblastoid cell line, LCL)
- **Chromatin target:** 8 Mb walk on chr19 (22 genomic regions)
- **Resolution:** ~200 kb–1 Mb per walk step (super-resolution OligoSTORM / OligoDNA-PAINT imaging)
- **Method:** Super-resolution chromosome walks combined with integrative modeling using Hi-C restraints; visualizes A/B compartment structures at sub-megabase scale
- **Biological question:** What are the structural differences between A-type and B-type chromatin compartments in single cells? Can integrative modeling of imaging + Hi-C data reveal chromosome organization?
- **Conditions (1 set):** Wild-type GM23248 cells
- **Note:** No FOF-CT trace files available

#### 4. Patterson_2023_PMID37540754
**Patterson B et al. (2023) — PMID:37540754**
*Female naïve human pluripotent stem cells carry X chromosomes with Xa-like and Xi-like folding conformations* (Cell Reports)

- **Cell type:** IMR-90 (human fibroblasts); HES-3, H9, H7-hESC (human embryonic stem cells)
- **Chromatin target:** chrX TADs (20+20 TADs, ~100 kb per TAD); combined with XIST RNA FISH and ATRX protein staining
- **Resolution:** TAD-level (~100 kb per TAD)
- **Method:** Chromatin tracing of X chromosome folding at megabase resolution across multiple pluripotency states, combined with simultaneous XIST RNA and ATRX protein detection
- **Biological question:** What is the 3D folding state of X chromosomes in naïve versus primed human pluripotent stem cells? Do naïve X chromosomes resemble Xa or Xi conformations?
- **Key findings context:** Naïve X chromosomes exhibit both Xa-like and Xi-like folding conformations but lack the compaction of somatic Xi; XIST accumulation observed on damaged X chromosomes in H7 naïve cells
- **Conditions (21 sets):** IMR-90 mTeSR1/5iLAF/5iLA; HES-3 mTeSR1/5iLAF/5iLA/4iLAF+tMEKi; H9 mTeSR1/5iLAF/5iLA combined (XIST+/−), ATRX+/−; H7 day2/4/6 (XIST+/−)

#### 5. Cheng_2023_PMID36778402
**Cheng Y et al. (2023) — PMID:36778402**
*Perturb-tracing enables high-content screening of multiscale 3D genome regulators* (Nature Methods)

- **Cell type:** H1-hESC differentiated to neural progenitor cells (NPCs), RPE-hTERT, A549
- **Chromatin target:** 27 TADs on Chr22; 34 TADs on Chr21; cell cycle tracked with Geminin staining
- **Resolution:** TAD-level (~0.5–2 Mb per TAD)
- **Method:** Perturb-tracing — a high-content imaging screening platform combining pooled CRISPR perturbation, cellular barcode readout (BARC-FISH), and chromatin tracing; screened 137 genes for effects on chromatin folding
- **Biological question:** Can image-based screening identify novel regulators of multiscale chromatin organization (domains, compartments, chromosome territories)? How do specific perturbations (CHD7, ZNF114, PCBP1) affect 3D genome structure?
- **Key perturbations:** CHD7 knockdown/overexpression, siZNF114, sgPCBP1, 137-gene CRISPR screen
- **Conditions (15 sets):** H1-hESC NPC shCHD7/control on Chr22; RPE-hTERT siCHD7/control on Chr21 and Chr22; A549 siCHD7/shCHD7/sgZNF114/sgPCBP1/controls on Chr22; CHD7 overexpression; 137-gene knockdown screen

### Specific Genomic Region / Locus-Focused Studies

These studies focus on defined genomic loci (typically <2 Mb) at high resolution, probing chromatin domain formation, enhancer-promoter regulation, epigenetic mechanisms, or variant effects at specific genes.

#### 6. Bintu_2018_PMID30361340
**Bintu B et al. (2018) — PMID:30361340**
*Super-resolution chromatin tracing reveals domains and cooperative interactions in single cells* (Science)

- **Cell type:** IMR-90, HCT116, A549, K562
- **Chromatin target:** 2–3 Mb regions on chr21 — chr21:28–30 Mb (1.2 Mb core, extended to 2 Mb) and chr21:34–37 Mb (2.5 Mb); panels of 41–83 consecutive 30-kb loci
- **Resolution:** 30 kb (consecutive loci imaged by sequential hybridization with super-resolution STORM or diffraction-limited microscopy)
- **Method:** Pioneering super-resolution chromatin tracing method; kilobase-resolution, nanometer-scale positional accuracy; de novo identification of TADs and cooperative multiway chromatin interactions in single cells
- **Biological question:** Do TAD-like structures exist in single cells? How do cohesin depletion and cell type affect domain boundaries and chromatin hub formation?
- **Key treatments:** RAD21-AID cohesin depletion (auxin) in HCT116; cell cycle tracking (Geminin) in IMR-90
- **Conditions (10 sets):** IMR90 chr21:28–30 Mb, IMR90 chr21:18–20 Mb (no TADs), IMR90 chr21:34–37 Mb across cell cycle, A549 chr21:28–30 Mb, K562 chr21:28–30 Mb, HCT116 chr21:28–30 Mb ± cohesin depletion, HCT116 chr21:34–37 Mb ± cohesin depletion + post-division

#### 7. Cheng_2021_PMID34749781
**Cheng Y et al. (2021) — PMID:34749781**
*TAD-like single-cell domain structures exist on both active and inactive X chromosomes and persist under epigenetic perturbations* (Genome Biology)

- **Cell type:** IMR-90, RPE-hTERT
- **Chromatin target:** 28 consecutive 30-kb loci on chrX (~840 kb); simultaneous XIST RNA FISH and mH2A.1 protein staining
- **Resolution:** 30 kb
- **Method:** Chromatin tracing combined with epigenetic markers (XIST RNA, mH2A.1) and pharmacological perturbations targeting different epigenetic pathways
- **Biological question:** Do TAD-like single-cell domains exist on both active and inactive X chromosomes? Do epigenetic perturbations (DNA methylation, H3K27me3, HDAC, transcription) disrupt single-cell domain structures?
- **Key treatments:** DNA methylation inhibitor (5-aza-2’-deoxycytidine), EZH2 inhibitor (GSK126), transcription inhibitor (alpha-amanitin), HDAC inhibitor (TSA)
- **Conditions (9 sets):** IMR90 untreated (open/closed chromatin), DNA methylation inhibitor, EZH2 inhibitor, hyper H3K27me3, transcription inhibitor, HDAC inhibitor; RPE-1 untreated
- **Note:** No FOF-CT trace files available

#### 8. Llimos_2022_PMID35440565
**Llimos G et al. (2022) — PMID:35440565**
*A leukemia-protective germline variant mediates chromatin module formation via transcription factor nucleation* (Nature Communications)

- **Cell type:** B-lymphocyte primary cells (LCLs with homozygous reference or mutant indel on chr17)
- **Chromatin target:** 200-kb region on chr17 encompassing the AXIN2-linked variable chromatin module (VCM); chr17:63486119–63686118
- **Resolution:** 8 kb
- **Method:** Multiplexed FISH to measure 3D chromatin compaction at a specific non-coding variant site associated with CLL predisposition; examines how a 5-bp indel (MEF2 binding site creation) controls super-enhancer activity and chromatin module formation
- **Biological question:** How does a non-coding germline variant alter 3D chromatin organization at a variable chromatin module (VCM)? Does MEF2-dependent super-enhancer activation cause long-range chromatin compaction?
- **Conditions (2 sets):** Homozygous reference, homozygous mutant (indel in chr17); 2 biological replicates each

#### 9. Fujimori_2023_doi_10.1101_2023.10.03.560616
**Fujimori T et al. (2023) — doi:10.1101/2023.10.03.560616** (preprint; published PMID:37873344)
*Single-cell chromatin state transitions during epigenetic memory formation* (Nature)

- **Cell type:** K562 (human erythroleukemia); 293T (HEK293T with TetR-KRAB/DNMT3B/HDAC4 doxycycline-inducible silencing systems)
- **Chromatin target:** MYC locus on chr8 (48 × 10 kb segments, ~480 kb); AAVS1 locus on chr19 (19 readout steps at 5 kb resolution, ~95 kb)
- **Resolution:** 10 kb (MYC locus); 5 kb (AAVS1 locus)
- **Method:** Multiplexed FISH to measure chromatin compaction during inducible epigenetic silencing; tracks how different repressors (TetR-KRAB, DNMT3B, HDAC4) and their mutants cause chromatin structural changes; widefield vs. custom microscope comparison
- **Biological question:** How does chromatin structure change during gene silencing and epigenetic memory formation? Does compaction predict long-term epigenetic memory? Which repressive modifications (H3K9me3, DNA methylation, HDAC-mediated) cause lasting chromatin compaction?
- **Key treatments:** Doxycycline induction (1 µg/mL) for 1 day, 5 days, and 22-day washout; wildtype vs mutant repressors (EEW25AAA, Y46A)
- **Conditions (18 sets):** K562 MYC widefield/customscope; 293T rTetR-KRAB (wt/Y46A/EEW25AAA) ± dox 1d/5d, washout; rTetR-DNMT3B ± dox 5d+22d washout; rTetR-HDAC4 ± dox 1d/5d

#### 10. Chen_2023_PMID36996812
**Chen LF et al. (2023) — PMID:36996812**
*Structural elements promote architectural stripe formation and facilitate ultra-long-range gene regulation at a human disease locus* (Molecular Cell)

- **Cell type:** H9 differentiated to cranial neural crest cells (CNCCs); H9 ESCs (undifferentiated)
- **Chromatin target:** SOX9 locus — 80 spaced regions spanning the SOX9 TAD (~1.5 Mb); includes Pierre Robin sequence (PRS) enhancer clusters at >1.25 Mb distance from SOX9 promoter
- **Resolution:** ~15–20 kb (spaced probes across the TAD)
- **Method:** Optical reconstruction of chromatin architecture (ORCA) imaging to trace 3D locus topology; combines chromatin tracing with CTCF binding site deletions to study stripe formation and ultra-long-range enhancer-promoter contacts
- **Biological question:** How do CTCF-bound structural elements within the SOX9 TAD mediate architectural stripe formation and ultra-long-range enhancer-promoter contacts relevant to Pierre Robin sequence?
- **Key perturbations:** CTCF binding site deletions at E1.35 and SOX9 promoter
- **Conditions (5 sets):** CNCCs wt, CNCCs with CTCF deletions at E1.35 and SOX9 promoter; ESC undifferentiated; multiple biological replicates

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
| `readout_resolution` | Step/readout resolution (e.g. 30 kb, TAD-level) |
| `region_size` | Genomic region size/range (e.g. chr21:28-30 Mb) |
| `cell_type_detail` | Detailed cell type/biosource from 4DN portal |
| `treatment_detail` | Specific treatment details from 4DN portal |

## Download Trace Files

```bash
# Download all trace CSVs using wget
tail -n +2 metadata/all_papers_combined.csv | cut -d',' -f16 | grep -v '^$' | sort -u | wget -i -
```

---

**Source:** [4DN Data Portal — Human Multiplexed FISH](https://data.4dnucleome.org/browse/?type=ExperimentSetReplicate&experimentset_type=replicate&experiments_in_set.experiment_type.display_title=multiplexed+FISH&experiments_in_set.biosample.biosource.organism.name=human)
