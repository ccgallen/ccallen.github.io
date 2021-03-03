# Spribille Lab Workflows

## Quality control of short reads for genomes and metagenomes

### Pre-QC read quality

### MetaWRAP QC module

```markdown
# set up variables


# run QC module
conda activate metawrap-env
mkdir READ_QC
metawrap read_qc -1 RAW_READS/Sporothrix_1.fastq -2 RAW_READS/Sporothrix_2.fastq -t 24 -o READ_QC/Sporothrix
```

### Post-QC read quality
© 2021 GitHub, Inc.
Terms
Privacy
Security
Status
Docs
Contact GitHub
Pricing
API
Training
Blog
About

