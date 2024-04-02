# Report (Precomputed mutators --concurrency 1)
| Project | #Prompts | #Mutants | #Killed | #Survived | #Timeout | MutationScore | LLMorpheus Time | Stryker Time | #Prompt Tokens | #Completion Tokens | #Total Tokens  |
|:--------|:---------|:---------|:--------|:----------|----------|---------------|-----------------|--------------|----------------|--------------------|----------------|
| Complex.js | 490 | 955 | 553 | 401 | 1 | 58.01 | 3065.29 | 504.22 | 967508 | 104246 | 1071754 |
| countries-and-timezones | 106 | 207 | 177 | 30 | 0 | 85.51 | 1070.8 | 296.35 | 105828 | 23971 | 129799 |
| crawler-url-parser | 176 | 247 | 129 | 118 | 0 | 52.23 | 1646.62 | 799.72 | 386223 | 39938 | 426161 |
| delta | 462 | 712 | 583 | 107 | 22 | 84.97 | 2972.99 | 3511.68 | 890252 | 103085 | 993337 |
| image-downloader | 42 | 77 | 48 | 29 | 0 | 62.34 | 430.51 | 461.29 | 24655 | 9339 | 33994 |
| node-dirty | 154 | 245 | 142 | 92 | 11 | 62.45 | 1527.57 | 208.98 | 246248 | 34892 | 281140 |
| node-geo-point | 140 | 304 | 237 | 67 | 0 | 77.96 | 1411.07 | 1010.61 | 316333 | 30715 | 347048 |
| node-jsonfile | 68 | 137 | 43 | 45 | 49 | 67.15 | 690.63 | 424.92 | 57516 | 15398 | 72914 |
| plural | 153 | 200 | 148 | 51 | 1 | 74.5 | 1696.97 | 108.86 | 255187 | 33552 | 288739 |
| pull-stream | 351 | 669 | 386 | 237 | 46 | 64.57 | 2488.59 | 1182.03 | 208130 | 77307 | 285437 |
| q | 1051 | 1714 | 122 | 1519 | 73 | 11.38 | 5141.59 | 11793.14 | 2127655 | 231269 | 2358924 |
| spacl-core | 134 | 185 | 160 | 25 | 0 | 86.49 | 1350.98 | 624.29 | 162705 | 30694 | 193399 |
| zip-a-folder | 49 | 87 | 27 | 55 | 5 | 36.78 | 500.55 | 488.31 | 82457 | 11494 | 93951 |
| Total | 3376 | 5739 | 2755 | 2776 | 208 | - | 23994.16 | 21414.40 | 5830697 | 745900 | 6576597 |
## Experimental Parameters
  - Model: codellama-13b-instruct
  - Temperature: 0
  - Max Tokens: 250
  - Max Nr of Prompts: 2000
  - Template: template-full.hb
  - System Prompt: SystemPrompt-MutationTestingExpert.txt
  - Rate Limit: benchmark mode
  - Number of Attempts: 3


