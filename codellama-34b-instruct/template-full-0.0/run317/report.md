# Report (Precomputed mutators --concurrency 1)
| Project | #Prompts | #Mutants | #Killed | #Survived | #Timeout | MutationScore | LLMorpheus Time | Stryker Time | #Prompt Tokens | #Completion Tokens | #Total Tokens  |
|:--------|:---------|:---------|:--------|:----------|----------|---------------|-----------------|--------------|----------------|--------------------|----------------|
| Complex.js | 490 | 1199 | 726 | 472 | 1 | 60.63 | 3019.69 | 669.52 | 967508 | 102524 | 1070032 |
| countries-and-timezones | 106 | 216 | 187 | 29 | 0 | 86.57 | 1070.82 | 313.99 | 105828 | 23425 | 129253 |
| crawler-url-parser | 176 | 285 | 157 | 128 | 0 | 55.09 | 1641.2 | 958.26 | 386223 | 39160 | 425383 |
| delta | 462 | 767 | 636 | 100 | 31 | 86.96 | 3013.74 | 3867.52 | 890252 | 99031 | 989283 |
| image-downloader | 42 | 90 | 73 | 17 | 0 | 81.11 | 430.56 | 378.47 | 24655 | 9117 | 33772 |
| node-dirty | 154 | 275 | 161 | 102 | 12 | 62.91 | 1527.49 | 251.95 | 246248 | 33113 | 279361 |
| node-geo-point | 140 | 302 | 223 | 79 | 0 | 73.84 | 1451.19 | 1042.75 | 316333 | 29894 | 346227 |
| node-jsonfile | 68 | 154 | 49 | 48 | 57 | 68.83 | 690.66 | 479.95 | 57516 | 14803 | 72319 |
| plural | 153 | 280 | 204 | 75 | 1 | 73.21 | 1521.18 | 150.87 | 265602 | 34163 | 299765 |
| pull-stream | 351 | 771 | 441 | 273 | 57 | 64.59 | 2486.78 | 1384.03 | 208130 | 76520 | 284650 |
| q | 1051 | 2031 | 159 | 1788 | 84 | 11.96 | 5250.4 | 14006.76 | 2127655 | 220193 | 2347848 |
| spacl-core | 134 | 239 | 198 | 40 | 1 | 83.26 | 1350.99 | 808.62 | 162705 | 29297 | 192002 |
| zip-a-folder | 49 | 100 | 23 | 3 | 74 | 97 | 500.63 | 1171.49 | 82457 | 10705 | 93162 |
| Total | 3376 | 6709 | 3237 | 3154 | 318 | - | 23955.33 | 25484.18 | 5841112 | 721945 | 6563057 |
## Experimental Parameters
  - Model: codellama-34b-instruct
  - Temperature: 0
  - Max Tokens: 250
  - Max Nr of Prompts: 2000
  - Template: template-full.hb
  - System Prompt: SystemPrompt-MutationTestingExpert.txt
  - Rate Limit: benchmark mode
  - Number of Attempts: 3


