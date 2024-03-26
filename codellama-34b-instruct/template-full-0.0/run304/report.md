# Report (Precomputed mutators)
| Project | #Prompts | #Mutants | #Killed | #Survived | #Timeout | MutationScore | LLMorpheus Time | Stryker Time | #Prompt Tokens | #Completion Tokens | #Total Tokens  |
|:--------|:---------|:---------|:--------|:----------|----------|---------------|-----------------|--------------|----------------|--------------------|----------------|
| Complex.js | 490 | 1197 | 725 | 471 | 1 | 60.65 | 3008.1 | 499.12 | 967508 | 102412 | 1069920 |
| countries-and-timezones | 106 | 217 | 188 | 29 | 0 | 86.64 | 1070.96 | 225.53 | 105828 | 23426 | 129254 |
| crawler-url-parser | 176 | 284 | 157 | 127 | 0 | 55.28 | 1640.71 | 614.74 | 386223 | 39183 | 425406 |
| delta | 462 | 766 | 634 | 100 | 32 | 86.95 | 2964.7 | 3432.91 | 890252 | 98950 | 989202 |
| image-downloader | 42 | 89 | 72 | 17 | 0 | 80.9 | 430.56 | 216.5 | 24655 | 9079 | 33734 |
| node-dirty | 154 | 275 | 185 | 81 | 9 | 70.55 | 1527.07 | 151.99 | 246248 | 33142 | 279390 |
| node-geo-point | 140 | 302 | 223 | 79 | 0 | 73.84 | 1411.08 | 888.77 | 316333 | 29910 | 346243 |
| node-jsonfile | 68 | 154 | 49 | 48 | 57 | 68.83 | 690.72 | 251 | 57516 | 14850 | 72366 |
| plural | 153 | 279 | 203 | 75 | 1 | 73.12 | 1521.13 | 117.62 | 265602 | 34114 | 299716 |
| pull-stream | 351 | 770 | 440 | 273 | 57 | 64.55 | 2477.8 | 752.94 | 208130 | 76559 | 284689 |
| q | 1051 | 2035 | 160 | 1792 | 83 | 11.94 | 5158.95 | 7168.64 | 2127655 | 220428 | 2348083 |
| spacl-core | 134 | 238 | 198 | 39 | 1 | 83.61 | 1351.07 | 697.23 | 162705 | 29285 | 191990 |
| zip-a-folder | 49 | 100 | 23 | 3 | 74 | 97 | 500.57 | 632.19 | 82457 | 10711 | 93168 |
| Total | 3376 | 6706 | 3257 | 3134 | 315 | - | 23753.42 | 15649.18 | 5841112 | 722049 | 6563161 |
## Experimental Parameters
  - Model: codellama-34b-instruct
  - Temperature: 0
  - Max Tokens: 250
  - Max Nr of Prompts: 2000
  - Template: template-full.hb
  - System Prompt: SystemPrompt-MutationTestingExpert.txt
  - Rate Limit: benchmark mode
  - Number of Attempts: 3


