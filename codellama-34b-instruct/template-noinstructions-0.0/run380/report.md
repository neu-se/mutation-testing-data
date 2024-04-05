# Report (Precomputed mutators --concurrency 1)
| Project | #Prompts | #Mutants | #Killed | #Survived | #Timeout | MutationScore | LLMorpheus Time | Stryker Time | #Prompt Tokens | #Completion Tokens | #Total Tokens  |
|:--------|:---------|:---------|:--------|:----------|----------|---------------|-----------------|--------------|----------------|--------------------|----------------|
| Complex.js | 490 | 1137 | 696 | 440 | 1 | 61.3 | 3340.83 | 597.34 | 953788 | 105056 | 1058844 |
| countries-and-timezones | 106 | 218 | 174 | 44 | 0 | 79.82 | 1070.75 | 323.54 | 102860 | 23502 | 126362 |
| crawler-url-parser | 176 | 246 | 134 | 112 | 0 | 54.47 | 1659.88 | 803.01 | 381295 | 38801 | 420096 |
| delta | 462 | 759 | 611 | 116 | 32 | 84.72 | 3211.07 | 3830.91 | 877316 | 99521 | 976837 |
| image-downloader | 42 | 84 | 69 | 15 | 0 | 82.14 | 430.47 | 362.1 | 23479 | 8905 | 32384 |
| node-dirty | 154 | 260 | 146 | 103 | 11 | 60.38 | 1530.67 | 228.98 | 241936 | 33033 | 274969 |
| node-geo-point | 140 | 306 | 230 | 76 | 0 | 75.16 | 1410.92 | 997.9 | 312413 | 29053 | 341466 |
| node-jsonfile | 68 | 148 | 45 | 51 | 52 | 65.54 | 690.56 | 466.32 | 55612 | 14598 | 70210 |
| plural | 153 | 261 | 189 | 71 | 1 | 72.8 | 1522.82 | 141.8 | 261318 | 34484 | 295802 |
| pull-stream | 351 | 781 | 466 | 249 | 66 | 68.12 | 2609.79 | 1444.02 | 198302 | 74220 | 272522 |
| q | 1051 | 1957 | 137 | 1727 | 93 | 11.75 | 6945.19 | 13543.9 | 2098227 | 218309 | 2316536 |
| spacl-core | 134 | 187 | 155 | 31 | 1 | 83.42 | 1350.87 | 605.57 | 158953 | 29527 | 188480 |
| zip-a-folder | 49 | 97 | 26 | 4 | 67 | 95.88 | 500.5 | 1075.42 | 81085 | 10694 | 91779 |
| Total | 3376 | 6441 | 3078 | 3039 | 324 | - | 26274.32 | 24420.81 | 5746584 | 719703 | 6466287 |
## Experimental Parameters
  - Model: codellama-34b-instruct
  - Temperature: 0
  - Max Tokens: 250
  - Max Nr of Prompts: 2000
  - Template: template-noinstructions.hb
  - System Prompt: SystemPrompt-MutationTestingExpert.txt
  - Rate Limit: benchmark mode
  - Number of Attempts: 3


