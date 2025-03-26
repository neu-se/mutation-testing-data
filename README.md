# mutation-testing-data

This repository contains all experimental data associated with a paper entitled "LLMorpheus: Mutation Testing using Large Language Models" that is currently under submission. You can find a draft of this paper in the `paper` subdirectory.

## LLMorpheus Quantitative Results

The top-level directory contains subdirectories for each of the LLMs used in the evaluation:
  - codellama-13b-instruct
  - codellama-34b-instruct
  - mixtral-8x7b-instruct
  - gpt-4o-mini
  - llama-3.3-70b-instruct

Each of these directories is further organized into subdirectories corresponding to the prompt template and temperature setting used for experiments. Within each of these, all data associated with 5 full experiments is contained for each subject application (prompts, completions, Stryker report, etc)

## Stryker.js Results

The top-level `StrykerJS` directory contains the results of applying the standard mutators on StrykerJS on the subject applications.

## LLMorpheus Case Study and Bug Dataset

The `case-study` directory contains experimental data for a case study in which LLMorpheus was applied to 40 real-world bugs. The directory contains an Excel sheet `case-study-results.xlsx` that provides details for each of the bugs. 

For each bug, there is a subdirectory (e.g., `fast-glob-223`) where the name reflects the name of the project in which the bug was found (`fast-glob`), and the issue number (`223`) where the bug was reported. Inside this directory is a sheet `results.xlsx` containing an analysis of the mutants produced by LLMorpheus for this bug.

For the 36 projects from GitHub, the sheet lists the project name, URL for GitHub repo, issue number for the bug report, commit SHA for the fix, old code fragment, new code fragment, etc.).  The remaining 4 bugs were taken from [Bugs.js](https://bugsjs.github.io/) and are identified by their project name and bug number. 

The remaining files are concerned with the experiments in which we manually inspected and classified a subset of the surviving mutants.

## Paper

The `paper` directory contains a paper about our work. An extended version can also be found that that includes an appendix with additional experimental results based on the data in this repository.

## Open source release

The open-source release of LLMorpheus can be found at https://github.com/neu-se/llmorpheus/. It depends on a modified version of StrykerJS that is available from https://github.com/neu-se/stryker-js.