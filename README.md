# Artifact for Studying and Improving the Soundness of Feature-Based Debloating

## About


This artifact, associated with the paper *"Studying and Improving the Soundness of Feature-Based Debloating"*.

The paper has three parts presenting:

* (1) A study that investigates the extent to which current feature-based debloating techniques
introduce soundness issues detected via fuzzing and provides analyses on the categories,
distribution, and causes of the issues.
* (2)  A new technique CovExitAug that performs coverage-based code pruning and conditional
branch augmentation for debloating with improved soundness.
* (3) An evaluation showing that CovExitAug's augmentation can significantly reduce soundness issues while incurring only a slight increase of program size and decrease of generality.   

Correspondingly, the artifact has three key components. 

### Component 1: Study of the Soundness of Feature-Based Debloating Techniques

1.  [fuzzing-deb-with-sanitizers](https://github.com/the-Soundness-of-Debloating/fuzzing-deb-with-sanitizers): This repository supports the execution of SymCC, AFL++, and Radamsa, providing scripts for running these tools, raw data on soundness issues (pre-deduplication), and scripts for analyzing, validating, and deduplicating results.

2.  [deb-soundnessIssue](https://github.com/the-Soundness-of-Debloating/deb-soundnessIssue): This repository logs the deduplicated results from the fuzzing tools and includes analysis scripts.

3.  [deb-soundnessIssue-distribution-chart](https://github.com/the-Soundness-of-Debloating/deb-soundnessIssue-distribution-chart): This repository includes scripts for generating distribution charts of soundness issues.

### Component 2: CovExitAug

4.  [debloating_analysis_tools](https://github.com/the-Soundness-of-Debloating/debloating_analysis_tools): This repository includes a tool, named CovExitAug , for augmenting debloated programs.

### Component 3: Evaluation of CovExitAug

5.  [covexitaug_evaluation](https://github.com/the-Soundness-of-Debloating/covexitaug_evaluation): This repository covers the generality evaluation of CovExitAug.

Note that the fuzzing results and analysis for CovExitAug are already included in **repo1** and **repo2**.
