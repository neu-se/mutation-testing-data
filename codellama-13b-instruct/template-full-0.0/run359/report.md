# Report (Precomputed mutators --concurrency 1)
| Project | #Prompts | #Mutants | #Killed | #Survived | #Timeout | MutationScore | LLMorpheus Time | Stryker Time | #Prompt Tokens | #Completion Tokens | #Total Tokens  |
|:--------|:---------|:---------|:--------|:----------|----------|---------------|-----------------|--------------|----------------|--------------------|----------------|
| Complex.js | 490 | 955 | 553 | 401 | 1 | 58.01 | 3065.97 | 514.43 | 967508 | 104246 | 1071754 |
| countries-and-timezones | 106 | 207 | 177 | 30 | 0 | 85.51 | 1070.82 | 328.45 | 105828 | 23951 | 129779 |
| crawler-url-parser | 176 | 247 | 124 | 118 | 5 | 52.23 | 1638.27 | 905.63 | 386223 | 39906 | 426129 |
| delta | 462 | 712 | 583 | 107 | 22 | 84.97 | 2954.39 | 3471.08 | 890252 | 103085 | 993337 |
| image-downloader | 42 | 77 | 48 | 29 | 0 | 62.34 | 430.5 | 458.13 | 24655 | 9339 | 33994 |
| node-dirty | 154 | 245 | 142 | 92 | 11 | 62.45 | 1526.96 | 207.8 | 246248 | 34892 | 281140 |
| node-geo-point | 140 | 304 | 237 | 67 | 0 | 77.96 | 1411.06 | 1003.76 | 316333 | 30715 | 347048 |
| node-jsonfile | 68 | 137 | 43 | 45 | 49 | 67.15 | 690.67 | 421.74 | 57516 | 15398 | 72914 |
| plural | 153 | 208 | 154 | 53 | 1 | 74.52 | 1521.03 | 111.45 | 265602 | 34926 | 300528 |
| pull-stream | 351 | 669 | 387 | 236 | 46 | 64.72 | 2483.02 | 1186.04 | 208130 | 77307 | 285437 |
| q | 1051 | 1713 | 123 | 1518 | 72 | 11.38 | 5276.52 | 11824.34 | 2127655 | 231254 | 2358909 |
| spacl-core | 134 | 185 | 159 | 26 | 0 | 85.95 | 1350.99 | 617.51 | 162705 | 30694 | 193399 |
| zip-a-folder | 49 | 87 | 27 | 55 | 5 | 36.78 | 500.53 | 490.95 | 82457 | 11494 | 93951 |
| Total | 3376 | 5746 | 2757 | 2777 | 212 | - | 23920.73 | 21541.31 | 5841112 | 747207 | 6588319 |
## Experimental Parameters
  - Model: codellama-13b-instruct
  - Temperature: 0
  - Max Tokens: 250
  - Max Nr of Prompts: 2000
  - Template: template-full.hb
  - System Prompt: SystemPrompt-MutationTestingExpert.txt
  - Rate Limit: benchmark mode
  - Number of Attempts: 3


