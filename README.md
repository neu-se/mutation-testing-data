# mutation-testing-data

This directory contains all experimental data associated with a paper entitled "LLMorpheus: Mutation Testing using Large Language Models" that is currently under submission.

The directory contains subdirectories for each of the LLMs used in the evaluation:
  - codellama-13b-instruct
  - codellama-34b-instruct
  - mixtral-8x7b-instruct

Each of these directories is further organized into subdirectories corresponding to the prompt template and temperature setting used for experiments. Within each of these, all data associated with 5 full experiments is contained for each subject application (prompts, completions, Stryker report, etc)

The top-level StrykerJS directory contains the results of applying the standard mutators on StrykerJS on the subject applications.

The file `issta2024-submitted-with-appendix.pdf` is a version of the ISSTA submission with an appendix that provides more detailed data for the experiments reported on in the paper.

The file `llmorpheus.tgz` contains an anonymized snapshot of the code for LLMorpheus. LLMorpheus will be open-sourced later this month. We plan submit LLMorpheus to the ISSTA Artifact Evaluation track.

The remaining files are concerned with the experiments in which we manually inspected and classified a subset of the surviving mutants.
