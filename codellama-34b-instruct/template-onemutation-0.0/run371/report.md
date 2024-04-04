# Report (Precomputed mutators --concurrency 1)
| Project | #Prompts | #Mutants | #Killed | #Survived | #Timeout | MutationScore | LLMorpheus Time | Stryker Time | #Prompt Tokens | #Completion Tokens | #Total Tokens  |
|:--------|:---------|:---------|:--------|:----------|----------|---------------|-----------------|--------------|----------------|--------------------|----------------|
| Complex.js | 490 | 406 | 245 | 161 | 0 | 60.34 | 2763.09 | 214.8 | 927818 | 39505 | 967323 |
| countries-and-timezones | 106 | 79 | 66 | 13 | 0 | 83.54 | 1071.04 | 115.36 | 97242 | 8565 | 105807 |
| crawler-url-parser | 176 | 87 | 51 | 36 | 0 | 58.62 | 1636.32 | 285.19 | 371967 | 15616 | 387583 |
| delta | 462 | 266 | 221 | 37 | 8 | 86.09 | 2676.35 | 1249.33 | 852830 | 37349 | 890179 |
| image-downloader | 42 | 34 | 26 | 8 | 0 | 76.47 | 430.63 | 137.29 | 21253 | 3461 | 24714 |
| node-dirty | 154 | 98 | 55 | 40 | 3 | 59.18 | 1526.34 | 74.5 | 233774 | 12868 | 246642 |
| node-geo-point | 140 | 104 | 74 | 30 | 0 | 71.15 | 1411.31 | 337.02 | 304993 | 11183 | 316176 |
| node-jsonfile | 68 | 57 | 18 | 18 | 21 | 68.42 | 690.79 | 183.54 | 52008 | 5774 | 57782 |
| plural | 153 | 101 | 71 | 30 | 0 | 70.3 | 1521.35 | 52.33 | 253209 | 13401 | 266610 |
| pull-stream | 351 | 280 | 165 | 95 | 20 | 66.07 | 2403.01 | 497.08 | 179699 | 30238 | 209937 |
| q | 1051 | 703 | 46 | 630 | 27 | 10.38 | 4196.27 | 4832.34 | 2042524 | 82120 | 2124644 |
| spacl-core | 134 | 80 | 63 | 17 | 0 | 78.75 | 1351.29 | 269.13 | 151851 | 10793 | 162644 |
| zip-a-folder | 49 | 39 | 19 | 17 | 3 | 56.41 | 500.65 | 220.66 | 78488 | 4403 | 82891 |
| Total | 3376 | 2334 | 1120 | 1132 | 82 | - | 22178.44 | 8468.57 | 5567656 | 275276 | 5842932 |
## Experimental Parameters
  - Model: codellama-34b-instruct
  - Temperature: 0
  - Max Tokens: 250
  - Max Nr of Prompts: 2000
  - Template: template-onemutation.hb
  - System Prompt: SystemPrompt-MutationTestingExpert.txt
  - Rate Limit: benchmark mode
  - Number of Attempts: 3


