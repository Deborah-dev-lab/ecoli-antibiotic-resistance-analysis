GROUP 2 — E. COLI COMPARATIVE GENOMICS RESEARCH
Strathmore University

RESEARCH TOPIC
Investigating the Evolution and Distribution of Antibiotic Resistance Among Selected Escherichia coli Strains Using Comparative Genomics

GROUP MEMBERS
160588 — Kirui Sharlet Jerono
166531 — Deborah Kaburu
166488 — Bwibo Ethan Nimrod
166386 — Githinji Nathan Rugo
162831 — Wangeci Brown Kamau
165852 — Njenga Martin Njuguna

PROJECT OVERVIEW
This research investigates genomic differences among selected Escherichia coli strains to support a later investigation of antibiotic resistance genes, their distribution, and evolutionary relationships. The current notebook covers Stage 2 (Dataset Description) and Stage 3 (Data Preparation and Exploratory Data Analysis). Antibiotic resistance genes and phylogenetic relationships have not yet been analysed.

DATA SOURCE AND TYPE
Source: NCBI RefSeq Genome Database
https://www.ncbi.nlm.nih.gov/datasets/genome/
Data: Genomic DNA sequences (FASTA) and assembly metadata (JSONL).
Nine verified E. coli genome assemblies comprising 15 DNA sequence records were analysed. Ten accessions were initially requested; one did not resolve through the NCBI Datasets service.

WORK COMPLETED IN GOOGLE COLAB
1. Downloaded and organised NCBI genomic sequences and metadata.
2. Used Python and Biopython to calculate sequence lengths, nucleotide counts, GC content, and ambiguity counts.
3. Aggregated 15 sequence records into nine assembly-level summaries.
4. Checked duplicates, missing values, assembly classifications, and ambiguous nucleotide symbols.
5. Compared calculated genome lengths and GC content against NCBI metadata; all nine genome lengths matched exactly.
6. Calculated descriptive statistics and nucleotide composition.
7. Created charts comparing genome length, GC content, and nucleotide composition.
8. Completed final validation checks and exported processed CSV results.

KEY FINDINGS
- Mean assembled genome length: approximately 5.11 million base pairs.
- Genome length range: 4,641,652–5,620,522 base pairs.
- Mean GC content: approximately 50.58%.
- Standard A, T, G, and C bases counted: 45,987,571.
- Ambiguous N bases: 4,316; other non-ATGCN symbols: 2,734.
- No duplicate assembly accessions or missing values in the genome-level summary.
- All nine calculated assembly lengths matched NCBI metadata.

FILES
Group_2_Ecoli_Comparative_Genomics.ipynb — Main notebook containing code, outputs, charts, and explanations (download separately from Colab).
ecoli_analysis_results.zip — Supporting processed CSV datasets (downloaded separately from Colab).
README.txt — This project overview.

HOW TO REVIEW
Open the .ipynb file in Google Colab or Jupyter Notebook to inspect the executed code, tables, charts, and interpretations. The CSV files in ecoli_analysis_results.zip contain processed results. The original FASTA files are not included in this folder unless added separately.

LIMITATIONS AND NEXT STEPS
The sample contains nine selected assemblies, including eight classified as Complete Genome and one as Chromosome. Some sequences contain ambiguous symbols. The current analysis describes genomic characteristics only; it does not demonstrate antibiotic resistance or evolutionary relationships. Future stages will investigate resistance genes, genomic variations, and phylogenetic relatedness.
