# Report (Precomputed mutators --concurrency 1)
| Project | #Prompts | #Mutants | #Killed | #Survived | #Timeout | MutationScore | LLMorpheus Time | Stryker Time | #Prompt Tokens | #Completion Tokens | #Total Tokens  |
|:--------|:---------|:---------|:--------|:----------|----------|---------------|-----------------|--------------|----------------|--------------------|----------------|
| Complex.js | 490 | 184 | 119 | 65 | 0 | 64.67 | 2730.84 | 97.59 | 893966 | 14461 | 908427 |
| countries-and-timezones | 106 | 48 | 43 | 5 | 0 | 89.58 | 1071.16 | 72.83 | 89939 | 3113 | 93052 |
| crawler-url-parser | 176 | 67 | 49 | 18 | 0 | 73.13 | 1636.68 | 220.83 | 359498 | 5576 | 365074 |
| delta | 462 | 201 | 167 | 28 | 6 | 86.07 | 2659.86 | 887.5 | 820541 | 13473 | 834014 |
| image-downloader | 42 | 10 | 7 | 3 | 0 | 70 | 430.65 | 65.72 | 18348 | 1449 | 19797 |
| node-dirty | 154 | 43 | 24 | 17 | 2 | 60.47 | 1526.53 | 37.3 | 223071 | 4496 | 227567 |
| node-geo-point | 140 | 62 | 54 | 8 | 0 | 87.1 | 1411.5 | 195.42 | 295321 | 4230 | 299551 |
| node-jsonfile | 68 | 22 | 11 | 3 | 8 | 86.36 | 690.89 | 77.9 | 47346 | 1831 | 49177 |
| plural | 153 | 92 | 78 | 14 | 0 | 84.78 | 1521.54 | 49.08 | 241953 | 5075 | 247028 |
| pull-stream | 351 | 149 | 88 | 54 | 7 | 63.76 | 2382.22 | 248.75 | 156016 | 9288 | 165304 |
| q | 1051 | 402 | 38 | 351 | 13 | 12.69 | 4158.01 | 2694.11 | 1970359 | 30070 | 2000429 |
| spacl-core | 134 | 25 | 23 | 2 | 0 | 92 | 1351.43 | 85.92 | 142466 | 4013 | 146479 |
| zip-a-folder | 49 | 20 | 5 | 1 | 14 | 95 | 500.71 | 229.75 | 75033 | 1594 | 76627 |
| Total | 3376 | 1325 | 706 | 569 | 50 | - | 22072.02 | 4962.70 | 5333857 | 98669 | 5432526 |
## Experimental Parameters
  - Model: codellama-34b-instruct
  - Temperature: 0
  - Max Tokens: 250
  - Max Nr of Prompts: 2000
  - Template: template-basic.hb
  - System Prompt: SystemPrompt-MutationTestingExpert.txt
  - Rate Limit: benchmark mode
  - Number of Attempts: 3


