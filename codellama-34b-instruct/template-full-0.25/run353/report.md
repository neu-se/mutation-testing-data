# Report (Precomputed mutators --concurrency 1)
| Project | #Prompts | #Mutants | #Killed | #Survived | #Timeout | MutationScore | LLMorpheus Time | Stryker Time | #Prompt Tokens | #Completion Tokens | #Total Tokens  |
|:--------|:---------|:---------|:--------|:----------|----------|---------------|-----------------|--------------|----------------|--------------------|----------------|
| Complex.js | 490 | 1168 | 717 | 451 | 0 | 61.39 | 3082.97 | 613.65 | 967508 | 101316 | 1068824 |
| countries-and-timezones | 106 | 225 | 199 | 26 | 0 | 88.44 | 1070.86 | 326.66 | 105828 | 22979 | 128807 |
| crawler-url-parser | 176 | 268 | 161 | 107 | 0 | 60.07 | 1641.17 | 853.01 | 386223 | 38790 | 425013 |
| delta | 462 | 760 | 620 | 106 | 34 | 86.05 | 2952.5 | 3773.99 | 890252 | 99524 | 989776 |
| image-downloader | 42 | 85 | 71 | 14 | 0 | 83.53 | 470.58 | 359.76 | 24655 | 8898 | 33553 |
| node-dirty | 154 | 265 | 167 | 86 | 12 | 67.55 | 1526.98 | 239.71 | 246248 | 32476 | 278724 |
| node-geo-point | 140 | 296 | 220 | 76 | 0 | 74.32 | 1411.01 | 1001.71 | 316333 | 29427 | 345760 |
| node-jsonfile | 68 | 158 | 55 | 49 | 54 | 68.99 | 690.74 | 500.76 | 57516 | 14495 | 72011 |
| plural | 153 | 291 | 215 | 75 | 1 | 74.23 | 1521.11 | 158 | 265602 | 33838 | 299440 |
| pull-stream | 351 | 775 | 448 | 276 | 51 | 64.39 | 2510.21 | 1355.46 | 208130 | 75432 | 283562 |
| q | 1051 | 2041 | 151 | 1803 | 87 | 11.66 | 5390.06 | 14133.05 | 2127655 | 217855 | 2345510 |
| spacl-core | 134 | 226 | 189 | 36 | 1 | 84.07 | 1350.98 | 752.72 | 162705 | 29399 | 192104 |
| zip-a-folder | 49 | 104 | 48 | 50 | 6 | 51.92 | 520.57 | 564.11 | 82457 | 10749 | 93206 |
| Total | 3376 | 6662 | 3261 | 3155 | 246 | - | 24139.74 | 24632.59 | 5841112 | 715178 | 6556290 |
## Experimental Parameters
  - Model: codellama-34b-instruct
  - Temperature: 0.25
  - Max Tokens: 250
  - Max Nr of Prompts: 2000
  - Template: template-full.hb
  - System Prompt: SystemPrompt-MutationTestingExpert.txt
  - Rate Limit: benchmark mode
  - Number of Attempts: 3


