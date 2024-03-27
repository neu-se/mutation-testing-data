# Report (Precomputed mutators --concurrency 1)
| Project | #Prompts | #Mutants | #Killed | #Survived | #Timeout | MutationScore | LLMorpheus Time | Stryker Time | #Prompt Tokens | #Completion Tokens | #Total Tokens  |
|:--------|:---------|:---------|:--------|:----------|----------|---------------|-----------------|--------------|----------------|--------------------|----------------|
| Complex.js | 490 | 1199 | 725 | 473 | 1 | 60.55 | 3034.16 | 631.23 | 967508 | 102497 | 1070005 |
| countries-and-timezones | 106 | 217 | 188 | 29 | 0 | 86.64 | 1070.91 | 309.4 | 105828 | 23444 | 129272 |
| crawler-url-parser | 176 | 283 | 157 | 125 | 1 | 55.83 | 1644.09 | 1022.89 | 386223 | 39174 | 425397 |
| delta | 462 | 766 | 634 | 100 | 32 | 86.95 | 2983.03 | 3969.11 | 890252 | 99003 | 989255 |
| image-downloader | 42 | 89 | 72 | 17 | 0 | 80.9 | 430.51 | 374.45 | 24655 | 9148 | 33803 |
| node-dirty | 154 | 274 | 160 | 102 | 12 | 62.77 | 1563.3 | 251.17 | 246248 | 33068 | 279316 |
| node-geo-point | 140 | 302 | 222 | 80 | 0 | 73.51 | 1411 | 1001.75 | 316333 | 30041 | 346374 |
| node-jsonfile | 68 | 154 | 49 | 48 | 57 | 68.83 | 690.69 | 474.83 | 57516 | 14750 | 72266 |
| plural | 153 | 279 | 203 | 75 | 1 | 73.12 | 1521.09 | 151.19 | 265602 | 34132 | 299734 |
| pull-stream | 351 | 769 | 444 | 268 | 57 | 65.15 | 2541.67 | 1398.89 | 208130 | 76567 | 284697 |
| q | 1051 | 2032 | 158 | 1790 | 84 | 11.91 | 5399.09 | 13959.4 | 2127655 | 220191 | 2347846 |
| spacl-core | 134 | 238 | 197 | 40 | 1 | 83.19 | 1351.08 | 959.37 | 162705 | 29287 | 191992 |
| zip-a-folder | 49 | 100 | 23 | 3 | 74 | 97 | 510.58 | 1154.14 | 82457 | 10725 | 93182 |
| Total | 3376 | 6702 | 3232 | 3150 | 320 | - | 24151.20 | 25657.82 | 5841112 | 722027 | 6563139 |
## Experimental Parameters
  - Model: codellama-34b-instruct
  - Temperature: 0
  - Max Tokens: 250
  - Max Nr of Prompts: 2000
  - Template: template-full.hb
  - System Prompt: SystemPrompt-MutationTestingExpert.txt
  - Rate Limit: benchmark mode
  - Number of Attempts: 3


