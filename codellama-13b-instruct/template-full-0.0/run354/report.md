# Report (Precomputed mutators --concurrency 1)
| Project | #Prompts | #Mutants | #Killed | #Survived | #Timeout | MutationScore | LLMorpheus Time | Stryker Time | #Prompt Tokens | #Completion Tokens | #Total Tokens  |
|:--------|:---------|:---------|:--------|:----------|----------|---------------|-----------------|--------------|----------------|--------------------|----------------|
| Complex.js | 490 | 955 | 553 | 401 | 1 | 58.01 | 3041.69 | 525.25 | 967508 | 104246 | 1071754 |
| countries-and-timezones | 106 | 207 | 177 | 30 | 0 | 85.51 | 1070.79 | 310.8 | 105828 | 23971 | 129799 |
| crawler-url-parser | 176 | 247 | 129 | 118 | 0 | 52.23 | 1637.98 | 803.17 | 386223 | 39906 | 426129 |
| delta | 462 | 712 | 583 | 107 | 22 | 84.97 | 2993.7 | 3529.05 | 890252 | 103085 | 993337 |
| image-downloader | 42 | 77 | 48 | 29 | 0 | 62.34 | 430.56 | 460.64 | 24655 | 9339 | 33994 |
| node-dirty | 154 | 245 | 142 | 92 | 11 | 62.45 | 1526.96 | 211.68 | 246248 | 34892 | 281140 |
| node-geo-point | 140 | 304 | 237 | 67 | 0 | 77.96 | 1411.04 | 1000.74 | 316333 | 30715 | 347048 |
| node-jsonfile | 68 | 138 | 43 | 45 | 50 | 67.39 | 690.65 | 425.39 | 57516 | 15398 | 72914 |
| plural | 153 | 208 | 154 | 53 | 1 | 74.52 | 1521 | 111.98 | 265602 | 34926 | 300528 |
| pull-stream | 351 | 669 | 386 | 237 | 46 | 64.57 | 2489.93 | 1188.59 | 208130 | 77308 | 285438 |
| q | 1051 | 1713 | 122 | 1518 | 73 | 11.38 | 5187.67 | 11850.22 | 2127655 | 231175 | 2358830 |
| spacl-core | 134 | 185 | 160 | 25 | 0 | 86.49 | 1350.97 | 616.43 | 162705 | 30694 | 193399 |
| zip-a-folder | 49 | 87 | 27 | 55 | 5 | 36.78 | 500.51 | 496.32 | 82457 | 11494 | 93951 |
| Total | 3376 | 5747 | 2761 | 2777 | 209 | - | 23853.45 | 21530.26 | 5841112 | 747149 | 6588261 |
## Experimental Parameters
  - Model: codellama-13b-instruct
  - Temperature: 0
  - Max Tokens: 250
  - Max Nr of Prompts: 2000
  - Template: template-full.hb
  - System Prompt: SystemPrompt-MutationTestingExpert.txt
  - Rate Limit: benchmark mode
  - Number of Attempts: 3


