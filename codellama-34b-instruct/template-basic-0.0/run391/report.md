# Report (Precomputed mutators --concurrency 1)
| Project | #Prompts | #Mutants | #Killed | #Survived | #Timeout | MutationScore | LLMorpheus Time | Stryker Time | #Prompt Tokens | #Completion Tokens | #Total Tokens  |
|:--------|:---------|:---------|:--------|:----------|----------|---------------|-----------------|--------------|----------------|--------------------|----------------|
| Complex.js | 490 | 184 | 119 | 65 | 0 | 64.67 | 2732.79 | 102.55 | 893966 | 14472 | 908438 |
| countries-and-timezones | 106 | 48 | 43 | 5 | 0 | 89.58 | 1071.27 | 72.88 | 89939 | 3113 | 93052 |
| crawler-url-parser | 176 | 67 | 49 | 18 | 0 | 73.13 | 1636.61 | 211.77 | 359498 | 5557 | 365055 |
| delta | 462 | 202 | 168 | 28 | 6 | 86.14 | 2667.43 | 897.69 | 820541 | 13458 | 833999 |
| image-downloader | 42 | 10 | 7 | 3 | 0 | 70 | 430.64 | 65.54 | 18348 | 1448 | 19796 |
| node-dirty | 154 | 44 | 24 | 18 | 2 | 59.09 | 1526.57 | 38.93 | 223071 | 4422 | 227493 |
| node-geo-point | 140 | 62 | 54 | 8 | 0 | 87.1 | 1411.51 | 203.69 | 295321 | 4218 | 299539 |
| node-jsonfile | 68 | 22 | 11 | 3 | 8 | 86.36 | 690.88 | 77.42 | 47346 | 1831 | 49177 |
| plural | 153 | 92 | 78 | 14 | 0 | 84.78 | 1521.47 | 47.92 | 241953 | 5075 | 247028 |
| pull-stream | 351 | 149 | 88 | 54 | 7 | 63.76 | 2382.21 | 245.17 | 156016 | 9288 | 165304 |
| q | 1051 | 401 | 38 | 350 | 13 | 12.72 | 4159.06 | 2700.88 | 1970359 | 30059 | 2000418 |
| spacl-core | 134 | 25 | 23 | 2 | 0 | 92 | 1351.31 | 85.36 | 142466 | 4007 | 146473 |
| zip-a-folder | 49 | 20 | 5 | 1 | 14 | 95 | 500.73 | 227.68 | 75033 | 1594 | 76627 |
| Total | 3376 | 1326 | 707 | 569 | 50 | - | 22082.48 | 4977.48 | 5333857 | 98542 | 5432399 |
## Experimental Parameters
  - Model: codellama-34b-instruct
  - Temperature: 0
  - Max Tokens: 250
  - Max Nr of Prompts: 2000
  - Template: template-basic.hb
  - System Prompt: SystemPrompt-MutationTestingExpert.txt
  - Rate Limit: benchmark mode
  - Number of Attempts: 3


