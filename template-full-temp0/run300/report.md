# Report (Precomputed mutators)
| Project | #Prompts | #Mutants | #Killed | #Survived | #Timeout | MutationScore | LLMorpheus Time | Stryker Time | #Prompt Tokens | #Completion Tokens | #Total Tokens  |
|:--------|:---------|:---------|:--------|:----------|----------|---------------|-----------------|--------------|----------------|--------------------|----------------|
| Complex.js | 490 | 1200 | 726 | 473 | 1 | 60.58 | 3051.55 | 518.6 | 967508 | 102446 | 1069954 |
| countries-and-timezones | 106 | 217 | 188 | 29 | 0 | 86.64 | 1070.91 | 267.41 | 105828 | 23442 | 129270 |
| crawler-url-parser | 176 | 286 | 158 | 128 | 0 | 55.24 | 1640.44 | 595.25 | 386223 | 39184 | 425407 |
| delta | 462 | 767 | 636 | 100 | 31 | 86.96 | 2927.26 | 3480.47 | 890252 | 99017 | 989269 |
| image-downloader | 42 | 90 | 73 | 17 | 0 | 81.11 | 430.57 | 210.8 | 24655 | 9131 | 33786 |
| node-dirty | 154 | 275 | 229 | 35 | 11 | 87.27 | 1526.26 | 152 | 246248 | 33128 | 279376 |
| node-geo-point | 140 | 303 | 224 | 79 | 0 | 73.93 | 1411.14 | 886.12 | 316333 | 29816 | 346149 |
| node-jsonfile | 68 | 154 | 50 | 47 | 57 | 69.48 | 690.66 | 260.06 | 57516 | 14844 | 72360 |
| plural | 153 | 280 | 204 | 75 | 1 | 73.21 | 1521.21 | 120.19 | 265602 | 34097 | 299699 |
| pull-stream | 351 | 770 | 441 | 272 | 57 | 64.68 | 2486.08 | 749.02 | 208130 | 76607 | 284737 |
| q | 1051 | 2034 | 158 | 1792 | 84 | 11.9 | 5155.16 | 7179.77 | 2127655 | 220474 | 2348129 |
| spacl-core | 134 | 240 | 199 | 40 | 1 | 83.33 | 1351.02 | 705.64 | 162705 | 29290 | 191995 |
| zip-a-folder | 49 | 100 | 25 | 1 | 74 | 99 | 500.68 | 695.73 | 82457 | 10705 | 93162 |
| Total | 3376 | 6716 | 3311 | 3088 | 317 | - | 23762.94 | 15821.06 | 5841112 | 722181 | 6563293 |
## Experimental Parameters
  - Model: codellama-34b-instruct
  - Temperature: 0
  - Max Tokens: 250
  - Max Nr of Prompts: 2000
  - Template: template-full.hb
  - System Prompt: SystemPrompt-MutationTestingExpert.txt
  - Rate Limit: benchmark mode
  - Number of Attempts: 3


