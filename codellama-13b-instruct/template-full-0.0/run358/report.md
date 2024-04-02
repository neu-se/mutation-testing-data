# Report (Precomputed mutators --concurrency 1)
| Project | #Prompts | #Mutants | #Killed | #Survived | #Timeout | MutationScore | LLMorpheus Time | Stryker Time | #Prompt Tokens | #Completion Tokens | #Total Tokens  |
|:--------|:---------|:---------|:--------|:----------|----------|---------------|-----------------|--------------|----------------|--------------------|----------------|
| Complex.js | 490 | 955 | 553 | 401 | 1 | 58.01 | 3045.49 | 511.92 | 967508 | 104246 | 1071754 |
| countries-and-timezones | 106 | 207 | 177 | 30 | 0 | 85.51 | 1070.84 | 308.11 | 105828 | 23971 | 129799 |
| crawler-url-parser | 176 | 247 | 129 | 118 | 0 | 52.23 | 1639.5 | 877.27 | 386223 | 39906 | 426129 |
| delta | 462 | 712 | 583 | 107 | 22 | 84.97 | 2975.67 | 3533.28 | 890252 | 103025 | 993277 |
| image-downloader | 42 | 77 | 48 | 29 | 0 | 62.34 | 430.5 | 458.4 | 24655 | 9339 | 33994 |
| node-dirty | 154 | 245 | 142 | 92 | 11 | 62.45 | 1527.47 | 209.67 | 246248 | 34892 | 281140 |
| node-geo-point | 140 | 304 | 237 | 67 | 0 | 77.96 | 1411.06 | 994.07 | 316333 | 30715 | 347048 |
| node-jsonfile | 68 | 137 | 43 | 45 | 49 | 67.15 | 690.64 | 421.39 | 57516 | 15398 | 72914 |
| plural | 153 | 208 | 154 | 53 | 1 | 74.52 | 1521.06 | 112.22 | 265602 | 34926 | 300528 |
| pull-stream | 351 | 669 | 387 | 236 | 46 | 64.72 | 2493 | 1182.21 | 208130 | 77307 | 285437 |
| q | 1051 | 1715 | 122 | 1520 | 73 | 11.37 | 5177.8 | 11862.47 | 2127655 | 231214 | 2358869 |
| spacl-core | 134 | 185 | 160 | 25 | 0 | 86.49 | 1350.98 | 606.49 | 162705 | 30694 | 193399 |
| zip-a-folder | 49 | 87 | 27 | 55 | 5 | 36.78 | 500.52 | 486.21 | 82457 | 11494 | 93951 |
| Total | 3376 | 5748 | 2762 | 2778 | 208 | - | 23834.53 | 21563.71 | 5841112 | 747127 | 6588239 |
## Experimental Parameters
  - Model: codellama-13b-instruct
  - Temperature: 0
  - Max Tokens: 250
  - Max Nr of Prompts: 2000
  - Template: template-full.hb
  - System Prompt: SystemPrompt-MutationTestingExpert.txt
  - Rate Limit: benchmark mode
  - Number of Attempts: 3


