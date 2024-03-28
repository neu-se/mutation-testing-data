# Report (Precomputed mutators --concurrency 1)
| Project | #Prompts | #Mutants | #Killed | #Survived | #Timeout | MutationScore | LLMorpheus Time | Stryker Time | #Prompt Tokens | #Completion Tokens | #Total Tokens  |
|:--------|:---------|:---------|:--------|:----------|----------|---------------|-----------------|--------------|----------------|--------------------|----------------|
| Complex.js | 490 | 1199 | 724 | 474 | 1 | 60.47 | 3000.46 | 630 | 967508 | 102314 | 1069822 |
| countries-and-timezones | 106 | 217 | 188 | 29 | 0 | 86.64 | 1070.9 | 314.35 | 105828 | 23438 | 129266 |
| crawler-url-parser | 176 | 283 | 157 | 126 | 0 | 55.48 | 1644.58 | 1051.08 | 386223 | 39105 | 425328 |
| delta | 462 | 765 | 633 | 100 | 32 | 86.93 | 3006.51 | 3795.29 | 890252 | 98978 | 989230 |
| image-downloader | 42 | 89 | 72 | 17 | 0 | 80.9 | 430.54 | 376.08 | 24655 | 9186 | 33841 |
| node-dirty | 154 | 275 | 161 | 102 | 12 | 62.91 | 1526.69 | 247.49 | 246248 | 33089 | 279337 |
| node-geo-point | 140 | 302 | 223 | 79 | 0 | 73.84 | 1411.05 | 1003.93 | 316333 | 30010 | 346343 |
| node-jsonfile | 68 | 154 | 49 | 48 | 57 | 68.83 | 690.67 | 478.93 | 57516 | 14803 | 72319 |
| plural | 153 | 281 | 205 | 75 | 1 | 73.31 | 1521.23 | 148.33 | 265602 | 34082 | 299684 |
| pull-stream | 351 | 770 | 441 | 272 | 57 | 64.68 | 2492.02 | 1392.68 | 208130 | 76599 | 284729 |
| q | 1051 | 2035 | 159 | 1793 | 83 | 11.89 | 5296.2 | 14072.49 | 2127655 | 220395 | 2348050 |
| spacl-core | 134 | 239 | 197 | 41 | 1 | 82.85 | 1351.09 | 802.3 | 162705 | 29334 | 192039 |
| zip-a-folder | 49 | 100 | 23 | 3 | 74 | 97 | 500.56 | 1155.04 | 82457 | 10764 | 93221 |
| Total | 3376 | 6709 | 3232 | 3159 | 318 | - | 23942.50 | 25467.99 | 5841112 | 722097 | 6563209 |
## Experimental Parameters
  - Model: codellama-34b-instruct
  - Temperature: 0
  - Max Tokens: 250
  - Max Nr of Prompts: 2000
  - Template: template-full.hb
  - System Prompt: SystemPrompt-MutationTestingExpert.txt
  - Rate Limit: benchmark mode
  - Number of Attempts: 3


