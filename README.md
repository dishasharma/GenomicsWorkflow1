This repository contains codes for optimizing and benchmarking Broad's Whole genome sequencing analysis pipeline with CROMWELL workflow manager and WDL scripts. 

The comparisions include:
1. Baseline : Config File for Baseline.20K.
2. Baseline.20k : BWA-Mem, Samtools, Picard (No Multiprocessing, GATK)
3. Mem2.20K : 20K reads with BWA-Mem2 rather than BWA-Mem in the pipeline with BWA-Mem2, MarkDuplicatesSparks (Multiprocessing), GATK
4. Mem2.json : Config file for Mem2.20K.
