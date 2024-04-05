# Report (Precomputed mutators --concurrency 1)
| Project | #Prompts | #Mutants | #Killed | #Survived | #Timeout | MutationScore | LLMorpheus Time | Stryker Time | #Prompt Tokens | #Completion Tokens | #Total Tokens  |
|:--------|:---------|:---------|:--------|:----------|----------|---------------|-----------------|--------------|----------------|--------------------|----------------|
| Complex.js | 490 | 1121 | 674 | 446 | 1 | 60.21 | 3054.59 | 596.41 | 948398 | 75593 | 1023991 |
| countries-and-timezones | 106 | 211 | 183 | 28 | 0 | 86.73 | 1070.75 | 306.48 | 101694 | 23740 | 125434 |
| crawler-url-parser | 176 | 239 | 140 | 99 | 0 | 58.58 | 1653.25 | 791.38 | 379359 | 31096 | 410455 |
| delta | 462 | 733 | 597 | 110 | 26 | 84.99 | 2869.41 | 3656.14 | 872234 | 64872 | 937106 |
| image-downloader | 42 | 77 | 62 | 15 | 0 | 80.52 | 430.47 | 328.44 | 23017 | 9109 | 32126 |
| node-dirty | 154 | 258 | 146 | 99 | 13 | 61.63 | 1526.59 | 236.98 | 240242 | 24096 | 264338 |
| node-geo-point | 140 | 298 | 216 | 82 | 0 | 72.48 | 1410.99 | 992.09 | 310873 | 26143 | 337016 |
| node-jsonfile | 68 | 152 | 54 | 45 | 53 | 70.39 | 690.55 | 485.04 | 54864 | 15130 | 69994 |
| plural | 153 | 273 | 198 | 74 | 1 | 72.89 | 1521.62 | 145.62 | 259635 | 26482 | 286117 |
| pull-stream | 351 | 774 | 439 | 279 | 56 | 63.95 | 2631.99 | 1391.93 | 194441 | 73754 | 268195 |
| q | 1051 | 1855 | 138 | 1634 | 83 | 11.91 | 4695.78 | 12866.72 | 2086666 | 127918 | 2214584 |
| spacl-core | 134 | 209 | 175 | 33 | 1 | 84.21 | 1350.86 | 706.03 | 157479 | 28159 | 185638 |
| zip-a-folder | 49 | 98 | 26 | 3 | 69 | 96.94 | 500.51 | 1109.02 | 80546 | 10227 | 90773 |
| Total | 3376 | 6298 | 3048 | 2947 | 303 | - | 23407.36 | 23612.28 | 5709448 | 536319 | 6245767 |
## Experimental Parameters
  - Model: codellama-34b-instruct
  - Temperature: 0
  - Max Tokens: 250
  - Max Nr of Prompts: 2000
  - Template: template-noexplanation.hb
  - System Prompt: SystemPrompt-MutationTestingExpert.txt
  - Rate Limit: benchmark mode
  - Number of Attempts: 3


