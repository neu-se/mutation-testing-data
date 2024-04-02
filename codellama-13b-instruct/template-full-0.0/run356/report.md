# Report (Precomputed mutators --concurrency 1)
| Project | #Prompts | #Mutants | #Killed | #Survived | #Timeout | MutationScore | LLMorpheus Time | Stryker Time | #Prompt Tokens | #Completion Tokens | #Total Tokens  |
|:--------|:---------|:---------|:--------|:----------|----------|---------------|-----------------|--------------|----------------|--------------------|----------------|
| Complex.js | 490 | 955 | 553 | 401 | 1 | 58.01 | 3041.58 | 506.22 | 967508 | 104246 | 1071754 |
| countries-and-timezones | 106 | 207 | 177 | 30 | 0 | 85.51 | 1070.84 | 308.67 | 105828 | 23971 | 129799 |
| crawler-url-parser | 176 | 247 | 129 | 118 | 0 | 52.23 | 1639.49 | 858.45 | 386223 | 39915 | 426138 |
| delta | 462 | 712 | 583 | 107 | 22 | 84.97 | 2978.12 | 3447.64 | 890252 | 103085 | 993337 |
| image-downloader | 42 | 77 | 48 | 29 | 0 | 62.34 | 430.52 | 459.07 | 24655 | 9339 | 33994 |
| node-dirty | 154 | 245 | 142 | 92 | 11 | 62.45 | 1527.4 | 208.98 | 246248 | 34892 | 281140 |
| node-geo-point | 140 | 304 | 237 | 67 | 0 | 77.96 | 1411.02 | 1011.58 | 316333 | 30715 | 347048 |
| node-jsonfile | 68 | 137 | 43 | 45 | 49 | 67.15 | 690.68 | 420.13 | 57516 | 15398 | 72914 |
| plural | 153 | 208 | 154 | 53 | 1 | 74.52 | 1521 | 112.81 | 265602 | 34926 | 300528 |
| pull-stream | 351 | 668 | 386 | 236 | 46 | 64.67 | 2481.3 | 1179.99 | 208130 | 77302 | 285432 |
| q | 1051 | 1713 | 122 | 1518 | 73 | 11.38 | 5249.72 | 11806.54 | 2127655 | 231355 | 2359010 |
| spacl-core | 134 | 185 | 160 | 25 | 0 | 86.49 | 1351.04 | 617.86 | 162705 | 30694 | 193399 |
| zip-a-folder | 49 | 87 | 27 | 55 | 5 | 36.78 | 500.58 | 495.97 | 82457 | 11494 | 93951 |
| Total | 3376 | 5745 | 2761 | 2776 | 208 | - | 23893.29 | 21433.91 | 5841112 | 747332 | 6588444 |
## Experimental Parameters
  - Model: codellama-13b-instruct
  - Temperature: 0
  - Max Tokens: 250
  - Max Nr of Prompts: 2000
  - Template: template-full.hb
  - System Prompt: SystemPrompt-MutationTestingExpert.txt
  - Rate Limit: benchmark mode
  - Number of Attempts: 3


