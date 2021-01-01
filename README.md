## RNA-seq Variant Calling with VarDict

This workflow uses [VarDict](https://github.com/AstraZeneca-NGS/VarDict) to call variants in RNA-seq data. The workflow accepts aligned bam files as input and outputs annotated vcf files.

Downstream analysis of vcfs for the manucsript "Comprehensive molecular characterization of papillary thyroid cancer in relation to ionizing radiation dose following the Chernobyl nuclear power plant accident" included intersections with cancer data sets (TCGA and PCAWG) and recent thyroid cancer literature. Potential driver mutations were corroborated with WGS data. 

#### Dependencies:
  - [Snakemake](https://snakemake.readthedocs.io/en/stable/)
  - [pandas](https://pandas.pydata.org/docs/)
  - [Samtools](http://www.htslib.org/)
  - [bedtools](https://bedtools.readthedocs.io/en/latest/)
  - [VarDict](https://github.com/AstraZeneca-NGS/VarDict)
  - [SnpEff](https://pcingola.github.io/SnpEff/se_introduction/)
