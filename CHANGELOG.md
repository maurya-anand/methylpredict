# Changelog

All notable changes to this project will be documented in this file.

## [1.0.0] - 2025-11-13

### Release Notes

- Initial release of MethylPredict, a Nextflow pipeline for predicting DNA methylation from Oxford Nanopore sequencing data.
- Implements modular Nextflow DSL2 workflow with sample-wise output organization.
- Major features:
  - No methylation calls required - Works with standard ONT basecalled data containing base quality values (Guppy, Dorado).
  - Variant-aware methylation prediction - excludes CpG sites affected by variants.
- Supports execution with Docker, Singularity, Apptainer, and SLURM HPC environments.
