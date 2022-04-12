# CD4-T-cells-ileum

**Count data of bulk RNA-seq data derived from four patients with Crohn’s disease (paired inflamed and non-inflamed ileum) and control subjects (non-inflamed ileum)**
Live T cell receptor (TCR)γδ, TCRγδ-CD8-CD4-, CD8, CD4CD8 (CD4CD8α, CD4CD8αα form the vast majority of this population), CD4 effector (CD127+CD25-), and CD4 Treg 
(CD127lowCD25high) cells were sorted. The sorted cells were thawed for TRIzol (Thermo Fisher Scientific) RNA extraction and stored at −80°C until library preparation.
Sequencing libraries were prepared using the Cel-Seq2 Sample Preparation Protocol and sequenced as 75bp paired-end on a NextSeq 500 (Utrecht Sequencing Facility). 
The reads were demultiplexed and aligned to the human cDNA reference genome (hg38) using BWA (version 0.7.13). Multiple reads mapping to the same gene with the same 
unique molecular identifier (UMI, 6bp long) were counted as a single read.

Files

CD4 ileum_raw counts.txt - raw count data of all sequenced samples

Legend CD4 ileum - sample description




**Count data of single cell RNA-seq data derived from four patients with Crohn’s disease (paired inflamed and non-inflamed ileum)**
Live CD3+CD8-CD4+ cells were sorted into 384-well hard shell plates (Biorad) with 5 μl of vapor-lock (QIAGEN) containing 100-200 nl of RT primers, dNTPs and synthetic 
mRNA Spike-Ins and immediately spun down and frozen to −80°C. Cells were prepared for SORT-seq as previously described.7 Illumina sequencing libraries were then 
prepared with the TruSeq small RNA primers (Illumina) and sequenced single-end at 75 bp read length with 75.000 reads per cell on a NextSeq500 platform (Illumina). 
Sequencing reads were mapped against the reference human genome (GRCh38) with BWA.

Files

Barcode counts = raw mapped counts
Sample description is in the title of every tsv file. 
*For patient 4_inflamed and non-inflamed epithelium.Barcodecounts cells 278-288, 296-360
and 369-384 contain non-inflamed intraepithelial CD4 T cells from patient 4. 
