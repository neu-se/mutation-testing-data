# Report (Precomputed mutators --concurrency 1)
| Project | #Prompts | #Mutants | #Killed | #Survived | #Timeout | MutationScore | LLMorpheus Time | Stryker Time | #Prompt Tokens | #Completion Tokens | #Total Tokens  |
|:--------|:---------|:---------|:--------|:----------|----------|---------------|-----------------|--------------|----------------|--------------------|----------------|
| Complex.js | 490 | 1125 | 678 | 446 | 1 | 60.36 | 3048.61 | 622.31 | 948398 | 75411 | 1023809 |
| countries-and-timezones | 106 | 211 | 183 | 28 | 0 | 86.73 | 1070.74 | 302.32 | 101694 | 23740 | 125434 |
| crawler-url-parser | 176 | 239 | 140 | 99 | 0 | 58.58 | 1653.97 | 835.85 | 379359 | 30947 | 410306 |
| delta | 462 | 733 | 597 | 110 | 26 | 84.99 | 2880.16 | 3648.84 | 872234 | 65086 | 937320 |
| image-downloader | 42 | 77 | 62 | 15 | 0 | 80.52 | 430.49 | 326.72 | 23017 | 9110 | 32127 |
| node-dirty | 154 | 258 | 146 | 99 | 13 | 61.63 | 1526.71 | 230.04 | 240242 | 24142 | 264384 |
| node-geo-point | 140 | 295 | 213 | 82 | 0 | 72.2 | 1410.98 | 963.4 | 310873 | 26313 | 337186 |
| node-jsonfile | 68 | 152 | 54 | 45 | 53 | 70.39 | 690.67 | 530.41 | 54864 | 15130 | 69994 |
| plural | 153 | 273 | 198 | 74 | 1 | 72.89 | 1522.04 | 148.93 | 259635 | 26465 | 286100 |
| pull-stream | 351 | 774 | 438 | 280 | 56 | 63.82 | 2630.34 | 1397.17 | 194441 | 73763 | 268204 |
| q | 1051 | 1856 | 137 | 1635 | 84 | 11.91 | 4627.86 | 12869.01 | 2086666 | 127790 | 2214456 |
| spacl-core | 134 | 209 | 175 | 33 | 1 | 84.21 | 1350.91 | 714.31 | 157479 | 28174 | 185653 |
| zip-a-folder | 49 | 98 | 27 | 3 | 68 | 96.94 | 500.51 | 1073.84 | 80546 | 10244 | 90790 |
| Total | 3376 | 6300 | 3048 | 2949 | 303 | - | 23343.99 | 23663.15 | 5709448 | 536315 | 6245763 |
## Experimental Parameters
  - Model: codellama-34b-instruct
  - Temperature: 0
  - Max Tokens: 250
  - Max Nr of Prompts: 2000
  - Template: template-noexplanation.hb
  - System Prompt: SystemPrompt-MutationTestingExpert.txt
  - Rate Limit: benchmark mode
  - Number of Attempts: 3


