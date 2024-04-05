# Report (Precomputed mutators --concurrency 1)
| Project | #Prompts | #Mutants | #Killed | #Survived | #Timeout | MutationScore | LLMorpheus Time | Stryker Time | #Prompt Tokens | #Completion Tokens | #Total Tokens  |
|:--------|:---------|:---------|:--------|:----------|----------|---------------|-----------------|--------------|----------------|--------------------|----------------|
| Complex.js | 490 | 1125 | 678 | 446 | 1 | 60.36 | 3088.22 | 620.07 | 948398 | 75464 | 1023862 |
| countries-and-timezones | 106 | 211 | 183 | 28 | 0 | 86.73 | 1070.66 | 302.71 | 101694 | 23766 | 125460 |
| crawler-url-parser | 176 | 239 | 140 | 99 | 0 | 58.58 | 1653.8 | 799.42 | 379359 | 31089 | 410448 |
| delta | 462 | 733 | 598 | 108 | 27 | 85.27 | 2871.99 | 3718.3 | 872234 | 65148 | 937382 |
| image-downloader | 42 | 77 | 62 | 15 | 0 | 80.52 | 430.48 | 328.19 | 23017 | 9096 | 32113 |
| node-dirty | 154 | 258 | 146 | 99 | 13 | 61.63 | 1526.65 | 242.49 | 240242 | 24129 | 264371 |
| node-geo-point | 140 | 298 | 216 | 82 | 0 | 72.48 | 1410.97 | 985.29 | 310873 | 26143 | 337016 |
| node-jsonfile | 68 | 152 | 54 | 45 | 53 | 70.39 | 690.54 | 481.86 | 54864 | 15125 | 69989 |
| plural | 153 | 273 | 198 | 74 | 1 | 72.89 | 1522.07 | 145.74 | 259635 | 26527 | 286162 |
| pull-stream | 351 | 774 | 439 | 279 | 56 | 63.95 | 2643.33 | 1393.56 | 194441 | 73922 | 268363 |
| q | 1051 | 1854 | 138 | 1633 | 83 | 11.92 | 4623.16 | 12860.56 | 2086666 | 127954 | 2214620 |
| spacl-core | 134 | 209 | 175 | 33 | 1 | 84.21 | 1360.9 | 649.12 | 157479 | 28174 | 185653 |
| zip-a-folder | 49 | 98 | 26 | 3 | 69 | 96.94 | 500.51 | 1117.51 | 80546 | 10267 | 90813 |
| Total | 3376 | 6301 | 3053 | 2944 | 304 | - | 23393.28 | 23644.82 | 5709448 | 536804 | 6246252 |
## Experimental Parameters
  - Model: codellama-34b-instruct
  - Temperature: 0
  - Max Tokens: 250
  - Max Nr of Prompts: 2000
  - Template: template-noexplanation.hb
  - System Prompt: SystemPrompt-MutationTestingExpert.txt
  - Rate Limit: benchmark mode
  - Number of Attempts: 3


