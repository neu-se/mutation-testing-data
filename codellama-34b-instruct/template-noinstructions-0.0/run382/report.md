# Report (Precomputed mutators --concurrency 1)
| Project | #Prompts | #Mutants | #Killed | #Survived | #Timeout | MutationScore | LLMorpheus Time | Stryker Time | #Prompt Tokens | #Completion Tokens | #Total Tokens  |
|:--------|:---------|:---------|:--------|:----------|----------|---------------|-----------------|--------------|----------------|--------------------|----------------|
| Complex.js | 490 | 1137 | 696 | 440 | 1 | 61.3 | 3378.96 | 601.89 | 953788 | 104940 | 1058728 |
| countries-and-timezones | 106 | 218 | 174 | 44 | 0 | 79.82 | 1080.75 | 325.94 | 102860 | 23502 | 126362 |
| crawler-url-parser | 176 | 246 | 134 | 112 | 0 | 54.47 | 1660.11 | 741.99 | 381295 | 38801 | 420096 |
| delta | 462 | 759 | 612 | 115 | 32 | 84.85 | 3233.82 | 3810.62 | 877316 | 99525 | 976841 |
| image-downloader | 42 | 84 | 69 | 15 | 0 | 82.14 | 430.46 | 361.68 | 23479 | 8905 | 32384 |
| node-dirty | 154 | 262 | 149 | 102 | 11 | 61.07 | 1531.35 | 234.89 | 241936 | 33044 | 274980 |
| node-geo-point | 140 | 306 | 230 | 76 | 0 | 75.16 | 1410.9 | 1014.28 | 312413 | 28969 | 341382 |
| node-jsonfile | 68 | 148 | 45 | 51 | 52 | 65.54 | 690.54 | 466.32 | 55612 | 14598 | 70210 |
| plural | 153 | 261 | 189 | 71 | 1 | 72.8 | 1523.06 | 136.58 | 261318 | 34492 | 295810 |
| pull-stream | 351 | 779 | 465 | 248 | 66 | 68.16 | 2606.22 | 1436.07 | 198302 | 74135 | 272437 |
| q | 1051 | 1958 | 137 | 1728 | 93 | 11.75 | 5921.2 | 13597.41 | 2098227 | 218214 | 2316441 |
| spacl-core | 134 | 187 | 155 | 31 | 1 | 83.42 | 1350.81 | 585.65 | 158953 | 29520 | 188473 |
| zip-a-folder | 49 | 97 | 26 | 4 | 67 | 95.88 | 500.48 | 1078.08 | 81085 | 10745 | 91830 |
| Total | 3376 | 6442 | 3081 | 3037 | 324 | - | 25318.66 | 24391.40 | 5746584 | 719390 | 6465974 |
## Experimental Parameters
  - Model: codellama-34b-instruct
  - Temperature: 0
  - Max Tokens: 250
  - Max Nr of Prompts: 2000
  - Template: template-noinstructions.hb
  - System Prompt: SystemPrompt-MutationTestingExpert.txt
  - Rate Limit: benchmark mode
  - Number of Attempts: 3


