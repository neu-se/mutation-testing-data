# Report (Precomputed mutators --concurrency 1)
| Project | #Prompts | #Mutants | #Killed | #Survived | #Timeout | MutationScore | LLMorpheus Time | Stryker Time | #Prompt Tokens | #Completion Tokens | #Total Tokens  |
|:--------|:---------|:---------|:--------|:----------|----------|---------------|-----------------|--------------|----------------|--------------------|----------------|
| Complex.js | 490 | 1126 | 679 | 446 | 1 | 60.39 | 3053.84 | 617.9 | 948398 | 75377 | 1023775 |
| countries-and-timezones | 106 | 211 | 183 | 28 | 0 | 86.73 | 1070.72 | 306.03 | 101694 | 23805 | 125499 |
| crawler-url-parser | 176 | 239 | 140 | 99 | 0 | 58.58 | 1656.36 | 838.63 | 379359 | 31102 | 410461 |
| delta | 462 | 733 | 597 | 109 | 27 | 85.13 | 2886.73 | 3644.21 | 872234 | 64947 | 937181 |
| image-downloader | 42 | 77 | 62 | 15 | 0 | 80.52 | 430.48 | 330.08 | 23017 | 9107 | 32124 |
| node-dirty | 154 | 258 | 146 | 99 | 13 | 61.63 | 1526.82 | 243.25 | 240242 | 24153 | 264395 |
| node-geo-point | 140 | 298 | 216 | 82 | 0 | 72.48 | 1410.93 | 999.44 | 310873 | 26143 | 337016 |
| node-jsonfile | 68 | 152 | 54 | 45 | 53 | 70.39 | 690.54 | 480.47 | 54864 | 15130 | 69994 |
| plural | 153 | 273 | 198 | 74 | 1 | 72.89 | 1522.37 | 144.72 | 259635 | 26473 | 286108 |
| pull-stream | 351 | 773 | 440 | 277 | 56 | 64.17 | 2649.32 | 1395.27 | 194441 | 73826 | 268267 |
| q | 1051 | 1854 | 136 | 1634 | 84 | 11.87 | 4627.96 | 12851.25 | 2086666 | 127807 | 2214473 |
| spacl-core | 134 | 209 | 177 | 31 | 1 | 85.17 | 1350.9 | 680.52 | 157479 | 28203 | 185682 |
| zip-a-folder | 49 | 98 | 27 | 3 | 68 | 96.94 | 500.52 | 1098.96 | 80546 | 10244 | 90790 |
| Total | 3376 | 6301 | 3055 | 2942 | 304 | - | 23377.49 | 23630.73 | 5709448 | 536317 | 6245765 |
## Experimental Parameters
  - Model: codellama-34b-instruct
  - Temperature: 0
  - Max Tokens: 250
  - Max Nr of Prompts: 2000
  - Template: template-noexplanation.hb
  - System Prompt: SystemPrompt-MutationTestingExpert.txt
  - Rate Limit: benchmark mode
  - Number of Attempts: 3


