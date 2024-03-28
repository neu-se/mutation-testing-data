# Report (Precomputed mutators --concurrency 1)
| Project | #Prompts | #Mutants | #Killed | #Survived | #Timeout | MutationScore | LLMorpheus Time | Stryker Time | #Prompt Tokens | #Completion Tokens | #Total Tokens  |
|:--------|:---------|:---------|:--------|:----------|----------|---------------|-----------------|--------------|----------------|--------------------|----------------|
| Complex.js | 490 | 1166 | 714 | 452 | 0 | 61.23 | 3065.41 | 611.71 | 967508 | 100190 | 1067698 |
| countries-and-timezones | 106 | 221 | 192 | 29 | 0 | 86.88 | 1070.87 | 313.43 | 105828 | 22897 | 128725 |
| crawler-url-parser | 176 | 310 | 173 | 137 | 0 | 55.81 | 1643.05 | 1045.88 | 386223 | 39148 | 425371 |
| delta | 462 | 792 | 668 | 89 | 35 | 88.76 | 3028.61 | 4054.65 | 890252 | 99121 | 989373 |
| image-downloader | 42 | 82 | 54 | 28 | 0 | 65.85 | 430.56 | 496.08 | 24655 | 8793 | 33448 |
| node-dirty | 154 | 288 | 173 | 104 | 11 | 63.89 | 1527.72 | 252.26 | 246248 | 33054 | 279302 |
| node-geo-point | 140 | 309 | 230 | 79 | 0 | 74.43 | 1411.09 | 1060.5 | 316333 | 28836 | 345169 |
| node-jsonfile | 68 | 152 | 53 | 38 | 61 | 75 | 690.68 | 520.06 | 57516 | 14997 | 72513 |
| plural | 153 | 285 | 215 | 70 | 0 | 75.44 | 1522.17 | 146.72 | 265602 | 33944 | 299546 |
| pull-stream | 351 | 784 | 463 | 270 | 51 | 65.56 | 2517.82 | 1365.08 | 208130 | 75400 | 283530 |
| q | 1051 | 2020 | 166 | 1774 | 80 | 12.18 | 5232.53 | 13865.94 | 2127655 | 217305 | 2344960 |
| spacl-core | 134 | 257 | 221 | 35 | 1 | 86.38 | 1351.05 | 848.71 | 162705 | 28593 | 191298 |
| zip-a-folder | 49 | 103 | 29 | 5 | 69 | 95.15 | 500.59 | 1105.81 | 82457 | 10544 | 93001 |
| Total | 3376 | 6769 | 3351 | 3110 | 308 | - | 23992.15 | 25686.83 | 5841112 | 712822 | 6553934 |
## Experimental Parameters
  - Model: codellama-34b-instruct
  - Temperature: 0.5
  - Max Tokens: 250
  - Max Nr of Prompts: 2000
  - Template: template-full.hb
  - System Prompt: SystemPrompt-MutationTestingExpert.txt
  - Rate Limit: benchmark mode
  - Number of Attempts: 3


