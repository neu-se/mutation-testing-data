# Report (Precomputed mutators --concurrency 1)
| Project | #Prompts | #Mutants | #Killed | #Survived | #Timeout | MutationScore | LLMorpheus Time | Stryker Time | #Prompt Tokens | #Completion Tokens | #Total Tokens  |
|:--------|:---------|:---------|:--------|:----------|----------|---------------|-----------------|--------------|----------------|--------------------|----------------|
| Complex.js | 490 | 1042 | 667 | 374 | 1 | 64.11 | 3070.12 | 559.72 | 967508 | 100998 | 1068506 |
| countries-and-timezones | 106 | 202 | 183 | 19 | 0 | 90.59 | 1070.86 | 285.32 | 105828 | 22109 | 127937 |
| crawler-url-parser | 176 | 276 | 200 | 76 | 0 | 72.46 | 1644.31 | 872.8 | 386223 | 38267 | 424490 |
| delta | 462 | 744 | 639 | 71 | 34 | 90.46 | 2974.8 | 3703.16 | 890252 | 96594 | 986846 |
| image-downloader | 42 | 75 | 49 | 26 | 0 | 65.33 | 430.54 | 438.8 | 24655 | 8660 | 33315 |
| node-dirty | 154 | 260 | 145 | 100 | 15 | 61.54 | 1527.36 | 248.76 | 246248 | 31479 | 277727 |
| node-geo-point | 140 | 259 | 205 | 54 | 0 | 79.15 | 1411.07 | 843.77 | 316333 | 29660 | 345993 |
| node-jsonfile | 68 | 143 | 56 | 24 | 63 | 83.22 | 690.69 | 512.58 | 57516 | 14276 | 71792 |
| plural | 153 | 303 | 242 | 60 | 1 | 80.2 | 1521.47 | 156.91 | 265602 | 32805 | 298407 |
| pull-stream | 351 | 752 | 456 | 238 | 58 | 68.35 | 2495.1 | 1354.27 | 208130 | 73802 | 281932 |
| q | 1051 | 1879 | 130 | 1659 | 90 | 11.71 | 5350.94 | 13107.5 | 2127655 | 213504 | 2341159 |
| spacl-core | 134 | 240 | 221 | 19 | 0 | 92.08 | 1351.11 | 811.62 | 162705 | 28193 | 190898 |
| zip-a-folder | 49 | 96 | 38 | 3 | 55 | 96.88 | 500.61 | 968.74 | 82457 | 10354 | 92811 |
| Total | 3376 | 6271 | 3231 | 2723 | 317 | - | 24038.98 | 23863.95 | 5841112 | 700701 | 6541813 |
## Experimental Parameters
  - Model: codellama-34b-instruct
  - Temperature: 1
  - Max Tokens: 250
  - Max Nr of Prompts: 2000
  - Template: template-full.hb
  - System Prompt: SystemPrompt-MutationTestingExpert.txt
  - Rate Limit: benchmark mode
  - Number of Attempts: 3


