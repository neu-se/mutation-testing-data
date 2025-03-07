# mutation-testing-data

This directory contains all experimental data associated with a paper entitled "LLMorpheus: Mutation Testing using Large Language Models" that is currently under submission. You can find a draft of this paper in the `paper` subdirectory.

The open-source release of LLMorpheus can be found at https://github.com/neu-se/llmorpheus/.

The directory contains subdirectories for each of the LLMs used in the evaluation:
  - codellama-13b-instruct
  - codellama-34b-instruct
  - mixtral-8x7b-instruct
  - gpt-4o-mini
  - llama-3.3-70b-instruct

Each of these directories is further organized into subdirectories corresponding to the prompt template and temperature setting used for experiments. Within each of these, all data associated with 5 full experiments is contained for each subject application (prompts, completions, Stryker report, etc)

The top-level StrykerJS directory contains the results of applying the standard mutators on StrykerJS on the subject applications.

The remaining files are concerned with the experiments in which we manually inspected and classified a subset of the surviving mutants.

