# Artifact for studying and improving the soundness of feature-Based debloating

## About

This is the artifact associated with the paper "Studying and Improving the Soundness of Feature-Based
Debloating". The artifact consists of the following four repositories:

1. [fuzzing-deb-with-sanitzers](https://github.com/the-Soundness-of-Debloating/fuzzing-deb-with-sanitzers):
This repository facilitates the execution of symcc, afl++, and radasma. It contains scripts for running these tools, the raw results of the Soundness Issues (without deduplication), and scripts for analyzing, validating, and deduplicating the results.
2. [deb-soundnessIssue](https://github.com/the-Soundness-of-Debloating/deb-soundnessIssue):This repository records the deduplicated results of the fuzzing tools and also includes scripts for analyzing these results.

3. [deb-soundnessIssue-distribution-chart](https://github.com/the-Soundness-of-Debloating/deb-soundnessIssue-distribution-chart): This repository contains the scripts for generating the distribution chart of the soundness issues.
4. [debloating_analysis_tools](https://github.com/the-Soundness-of-Debloating/debloating_analysis_tools): This repository contains the tool for augmenting debloated programs.

Overall, the first three repositories are part of our study section, while the last one is dedicated to our tool, CovExitAug.