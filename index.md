# RNA-seq Tutorial Outline 
### Packages Needed
- SRA Toolkit
- Fastqc
- multiqc 
- trimmomatic 
- Kallisto
- R
  - Tximport
  - DESeq2
 
 
### Pipeline Steps
-	Examining data on SRA Database
  -	https://datacarpentry.org/organization-genomics/03-ncbi-sra/index.html


{{ site.baseurl }}{% link _posts/firstpost.md %}


-	Examining Read quality 
    - FASTQC for quality control metrics
    - summarise FASTQC with multiqc
      -	https://datacarpentry.org/wrangling-genomics/02-quality-control/index.html
-	Trimming and Filtering Reads using trimmomatic 
  -	https://datacarpentry.org/wrangling-genomics/03-trimming/index.html
-	Pseudalignment using kallisto
  -	Pseudoalignment vs alignment
    -	<<kallisto.pdf>>
    -	<<kallisto and pseudoalignment.pdf>>
 
-	Import DESeq2 into RNA-seq 
  -	https://ycl6.gitbook.io/guide-to-rna-seq-analysis/differential-expression-analysis/differential-gene-expression/dge-analysis-with-salmon-input
  -	https://lashlock.github.io/compbio/R_presentation.html

 
-	Introduction to shell 
  -	https://datacarpentry.org/shell-genomics/
  -	https://linuxjourney.com/lesson/the-shell
-	Introduction to R
  -	https://datacarpentry.org/genomics-r-intro/
 
 
 

