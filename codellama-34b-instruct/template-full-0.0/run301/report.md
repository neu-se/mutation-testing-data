# Report (Precomputed mutators)
| Project | #Prompts | #Mutants | #Killed | #Survived | #Timeout | MutationScore | LLMorpheus Time | Stryker Time | #Prompt Tokens | #Completion Tokens | #Total Tokens  |
|:--------|:---------|:---------|:--------|:----------|----------|---------------|-----------------|--------------|----------------|--------------------|----------------|
| Complex.js | 490 | 1199 | 725 | 473 | 1 | 60.55 | 3004.23 | 551.75 | 967508 | 102678 | 1070186 |
| countries-and-timezones | 106 | 217 | 188 | 29 | 0 | 86.64 | 1070.81 | 271.67 | 105828 | 23436 | 129264 |
| crawler-url-parser | 176 | 282 | 155 | 125 | 2 | 55.67 | 1641.14 | 609.47 | 386223 | 39107 | 425330 |
| delta | 462 | 767 | 636 | 100 | 31 | 86.96 | 2941.74 | 3523.73 | 890252 | 99014 | 989266 |
| image-downloader | 42 | 89 | 72 | 17 | 0 | 80.9 | 430.56 | 217.02 | 24655 | 9066 | 33721 |
| node-dirty | 154 | 275 | 191 | 74 | 10 | 73.09 | 1526.92 | 158.41 | 246248 | 33149 | 279397 |
| node-geo-point | 140 | 302 | 223 | 79 | 0 | 73.84 | 1411.09 | 896.55 | 316333 | 29968 | 346301 |
| node-jsonfile | 68 | 154 | 51 | 47 | 56 | 69.48 | 690.7 | 253.7 | 57516 | 14803 | 72319 |
| plural | 153 | 280 | 204 | 75 | 1 | 73.21 | 1521.13 | 116.82 | 265602 | 34155 | 299757 |
| pull-stream | 351 | 770 | 442 | 271 | 57 | 64.81 | 2496.65 | 765.8 | 208130 | 76714 | 284844 |
| q | 1051 | 2035 | 158 | 1792 | 85 | 11.94 | 5194.52 | 7179.06 | 2127655 | 220311 | 2347966 |
| spacl-core | 134 | 239 | 198 | 40 | 1 | 83.26 | 1351.07 | 698.44 | 162705 | 29365 | 192070 |
| zip-a-folder | 49 | 101 | 22 | 2 | 77 | 98.02 | 500.58 | 637.53 | 82457 | 10671 | 93128 |
| Total | 3376 | 6710 | 3265 | 3124 | 321 | - | 23781.14 | 15879.95 | 5841112 | 722437 | 6563549 |
## Experimental Parameters
  - Model: codellama-34b-instruct
  - Temperature: 0
  - Max Tokens: 250
  - Max Nr of Prompts: 2000
  - Template: template-full.hb
  - System Prompt: SystemPrompt-MutationTestingExpert.txt
  - Rate Limit: benchmark mode
  - Number of Attempts: 3


