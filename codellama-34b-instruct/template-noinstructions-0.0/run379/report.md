# Report (Precomputed mutators --concurrency 1)
| Project | #Prompts | #Mutants | #Killed | #Survived | #Timeout | MutationScore | LLMorpheus Time | Stryker Time | #Prompt Tokens | #Completion Tokens | #Total Tokens  |
|:--------|:---------|:---------|:--------|:----------|----------|---------------|-----------------|--------------|----------------|--------------------|----------------|
| Complex.js | 490 | 1137 | 696 | 440 | 1 | 61.3 | 3324.82 | 606.13 | 953788 | 104909 | 1058697 |
| countries-and-timezones | 106 | 218 | 174 | 44 | 0 | 79.82 | 1070.79 | 314.67 | 102860 | 23502 | 126362 |
| crawler-url-parser | 176 | 246 | 134 | 112 | 0 | 54.47 | 1673.87 | 789.35 | 381295 | 38816 | 420111 |
| delta | 462 | 759 | 610 | 117 | 32 | 84.58 | 3186.56 | 3835.89 | 877316 | 99463 | 976779 |
| image-downloader | 42 | 84 | 70 | 14 | 0 | 83.33 | 430.46 | 362.97 | 23479 | 8961 | 32440 |
| node-dirty | 154 | 260 | 146 | 103 | 11 | 60.38 | 1530.82 | 229.51 | 241936 | 33036 | 274972 |
| node-geo-point | 140 | 306 | 230 | 76 | 0 | 75.16 | 1410.92 | 1035.06 | 312413 | 28975 | 341388 |
| node-jsonfile | 68 | 148 | 45 | 51 | 52 | 65.54 | 691.16 | 471.51 | 55612 | 14598 | 70210 |
| plural | 153 | 261 | 189 | 71 | 1 | 72.8 | 1523.31 | 142.93 | 261318 | 34484 | 295802 |
| pull-stream | 351 | 781 | 467 | 248 | 66 | 68.25 | 2610.16 | 1428.74 | 198302 | 74195 | 272497 |
| q | 1051 | 1960 | 137 | 1728 | 95 | 11.84 | 5806.23 | 13570.79 | 2098227 | 218057 | 2316284 |
| spacl-core | 134 | 188 | 156 | 31 | 1 | 83.51 | 1350.78 | 598.84 | 158953 | 29457 | 188410 |
| zip-a-folder | 49 | 97 | 26 | 4 | 67 | 95.88 | 500.5 | 1065.03 | 81085 | 10694 | 91779 |
| Total | 3376 | 6445 | 3080 | 3039 | 326 | - | 25110.38 | 24451.42 | 5746584 | 719147 | 6465731 |
## Experimental Parameters
  - Model: codellama-34b-instruct
  - Temperature: 0
  - Max Tokens: 250
  - Max Nr of Prompts: 2000
  - Template: template-noinstructions.hb
  - System Prompt: SystemPrompt-MutationTestingExpert.txt
  - Rate Limit: benchmark mode
  - Number of Attempts: 3


