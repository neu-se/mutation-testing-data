# Report (Precomputed mutators --concurrency 1)
| Project | #Prompts | #Mutants | #Killed | #Survived | #Timeout | MutationScore | LLMorpheus Time | Stryker Time | #Prompt Tokens | #Completion Tokens | #Total Tokens  |
|:--------|:---------|:---------|:--------|:----------|----------|---------------|-----------------|--------------|----------------|--------------------|----------------|
| Complex.js | 490 | 1198 | 726 | 471 | 1 | 60.68 | 3087.58 | 637.1 | 967508 | 102428 | 1069936 |
| countries-and-timezones | 106 | 217 | 188 | 29 | 0 | 86.64 | 1070.89 | 313.12 | 105828 | 23427 | 129255 |
| crawler-url-parser | 176 | 282 | 156 | 126 | 0 | 55.32 | 1645.11 | 679.89 | 386223 | 39210 | 425433 |
| delta | 462 | 768 | 636 | 100 | 32 | 86.98 | 2941.55 | 3838.23 | 890252 | 98951 | 989203 |
| image-downloader | 42 | 90 | 73 | 17 | 0 | 81.11 | 430.54 | 377.12 | 24655 | 9175 | 33830 |
| node-dirty | 154 | 274 | 161 | 101 | 12 | 63.14 | 1526.11 | 248.57 | 246248 | 33038 | 279286 |
| node-geo-point | 140 | 302 | 223 | 79 | 0 | 73.84 | 1411.06 | 999.59 | 316333 | 29959 | 346292 |
| node-jsonfile | 68 | 153 | 49 | 47 | 57 | 69.28 | 690.69 | 478.32 | 57516 | 14829 | 72345 |
| plural | 153 | 280 | 204 | 75 | 1 | 73.21 | 1521.04 | 147.85 | 265602 | 34164 | 299766 |
| pull-stream | 351 | 771 | 441 | 273 | 57 | 64.59 | 2477.99 | 1400.76 | 208130 | 76398 | 284528 |
| q | 1051 | 2031 | 159 | 1788 | 84 | 11.96 | 5231.88 | 14004.86 | 2127655 | 220252 | 2347907 |
| spacl-core | 134 | 239 | 197 | 41 | 1 | 82.85 | 1351.05 | 805.3 | 162705 | 29283 | 191988 |
| zip-a-folder | 49 | 100 | 23 | 3 | 74 | 97 | 500.57 | 1152.62 | 82457 | 10705 | 93162 |
| Total | 3376 | 6705 | 3236 | 3150 | 319 | - | 23886.06 | 25083.33 | 5841112 | 721819 | 6562931 |
## Experimental Parameters
  - Model: codellama-34b-instruct
  - Temperature: 0
  - Max Tokens: 250
  - Max Nr of Prompts: 2000
  - Template: template-full.hb
  - System Prompt: SystemPrompt-MutationTestingExpert.txt
  - Rate Limit: benchmark mode
  - Number of Attempts: 3


