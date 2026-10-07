# UCR HPCC work, 2017-2019

Work I wrote as lead HPC administrator in the High Performance Computing Center (HPCC) at the
University of California, Riverside, June 2017 to 2019. I built it for UCR HPCC; this
repository preserves my own contributions as a portfolio.

Every file here was created by me. Each commit is one of my original commits, with its
original date and message, and a pointer to the source commit in the `ucr-hpcc` GitHub
organization. Where others later edited a file, this repository keeps my last version before
those edits.

## What's here

| Folder | What it is |
|---|---|
| `aws-cluster-manual/` | The HPCC AWS Cluster (HPCC Cloud Service) user manual, 2018: lab-private HPC clusters in AWS launched on demand from the HPCC cluster with `hpcc_cloud`, my cfnCluster wrapper. Covers the intro, AWS account setup, the data egress waiver, cluster setup and operation, and billing and budget alerts. |
| `aws-cluster-modules/` | The start of the environment-module repository for software on those AWS clusters (2018). |
| `environment-modules/` | Environment modules I wrote for the HPCC cluster's software stack (2017-2019): about 57 packages, including CUDA and cuDNN, TensorFlow GPU, cfnCluster, BUSCO, GATK, SPAdes, Trinity, RAxML-NG, Gaussian, Rosetta and others. |
| `python-intro-workshop/` | Example scripts for the HPCC Introduction to Python workshop I taught (Oct 2018), from variables through Slurm job submission. |
| `slurm-examples/` | A Quantum ESPRESSO Slurm example (2019). |

## Related

- Workshops I taught at HPCC (19 sessions, 2017-2019) and their slide decks:
  https://charles-forsyth.github.io/handbook/2019/presentations.html
- CV: https://charles-forsyth.github.io/cv.html

## Notes

- The AWS screenshots are from a 2018 training account. Usernames, the account ID and an
  access key ID shown in the original screenshots are redacted.
- Host names such as `biocluster.ucr.edu` are historical and may no longer resolve.
- This repository is shared to document my work. The code and docs were created for UCR
  HPCC; no license is granted here beyond viewing.

Chuck Forsyth
