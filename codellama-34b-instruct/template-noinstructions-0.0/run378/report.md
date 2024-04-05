# Report (Precomputed mutators --concurrency 1)
| Project | #Prompts | #Mutants | #Killed | #Survived | #Timeout | MutationScore | LLMorpheus Time | Stryker Time | #Prompt Tokens | #Completion Tokens | #Total Tokens  |
|:--------|:---------|:---------|:--------|:----------|----------|---------------|-----------------|--------------|----------------|--------------------|----------------|
| Complex.js | 490 | 1137 | 696 | 440 | 1 | 61.3 | 3363.13 | 610.09 | 953788 | 104944 | 1058732 |
| countries-and-timezones | 106 | 218 | 174 | 44 | 0 | 79.82 | 1070.7 | 333.6 | 102860 | 23506 | 126366 |
| crawler-url-parser | 176 | 246 | 134 | 112 | 0 | 54.47 | 1668.12 | 865.68 | 381295 | 38817 | 420112 |
| delta | 462 | 759 | 612 | 115 | 32 | 84.85 | 3242.91 | 4060.5 | 877316 | 99522 | 976838 |
| image-downloader | 42 | 84 | 69 | 15 | 0 | 82.14 | 430.47 | 361.71 | 23479 | 8905 | 32384 |
| node-dirty | 154 | 260 | 146 | 103 | 11 | 60.38 | 1530.58 | 228.43 | 241936 | 33033 | 274969 |
| node-geo-point | 140 | 306 | 230 | 76 | 0 | 75.16 | 1410.89 | 1019.95 | 312413 | 28975 | 341388 |
| node-jsonfile | 68 | 148 | 45 | 51 | 52 | 65.54 | 690.55 | 469.01 | 55612 | 14598 | 70210 |
| plural | 153 | 261 | 189 | 71 | 1 | 72.8 | 1523.05 | 141.16 | 261318 | 34491 | 295809 |
| pull-stream | 351 | 781 | 467 | 248 | 66 | 68.25 | 2608.43 | 1433.25 | 198302 | 74144 | 272446 |
| q | 1051 | 1958 | 138 | 1726 | 94 | 11.85 | 5802.92 | 13526.38 | 2098227 | 218277 | 2316504 |
| spacl-core | 134 | 187 | 155 | 31 | 1 | 83.42 | 1350.79 | 626.46 | 158953 | 29519 | 188472 |
| zip-a-folder | 49 | 97 | 26 | 4 | 67 | 95.88 | 500.51 | 1087.03 | 81085 | 10694 | 91779 |
| Total | 3376 | 6442 | 3081 | 3036 | 325 | - | 25193.05 | 24763.25 | 5746584 | 719425 | 6466009 |
## Experimental Parameters
  - Model: codellama-34b-instruct
  - Temperature: 0
  - Max Tokens: 250
  - Max Nr of Prompts: 2000
  - Template: template-noinstructions.hb
  - System Prompt: SystemPrompt-MutationTestingExpert.txt
  - Rate Limit: benchmark mode
  - Number of Attempts: 3


