# Report (Precomputed mutators --concurrency 1)
| Project | #Prompts | #Mutants | #Killed | #Survived | #Timeout | MutationScore | LLMorpheus Time | Stryker Time | #Prompt Tokens | #Completion Tokens | #Total Tokens  |
|:--------|:---------|:---------|:--------|:----------|----------|---------------|-----------------|--------------|----------------|--------------------|----------------|
| Complex.js | 490 | 1190 | 716 | 474 | 0 | 60.17 | 3025.7 | 617.91 | 967508 | 101251 | 1068759 |
| countries-and-timezones | 106 | 221 | 191 | 29 | 1 | 86.88 | 1070.86 | 333.07 | 105828 | 23224 | 129052 |
| crawler-url-parser | 176 | 279 | 158 | 121 | 0 | 56.63 | 1686.57 | 939.88 | 386223 | 39014 | 425237 |
| delta | 462 | 775 | 634 | 105 | 36 | 86.45 | 3020.99 | 3992.69 | 890252 | 99683 | 989935 |
| image-downloader | 42 | 85 | 68 | 17 | 0 | 80 | 430.56 | 347.98 | 24655 | 9059 | 33714 |
| node-dirty | 154 | 269 | 152 | 105 | 12 | 60.97 | 1526.16 | 227.18 | 246248 | 32693 | 278941 |
| node-geo-point | 140 | 312 | 229 | 83 | 0 | 73.4 | 1411.04 | 1057.16 | 316333 | 29723 | 346056 |
| node-jsonfile | 68 | 160 | 58 | 36 | 66 | 77.5 | 690.68 | 565.63 | 57516 | 14528 | 72044 |
| plural | 153 | 296 | 232 | 63 | 1 | 78.72 | 1521.1 | 156.75 | 265602 | 34049 | 299651 |
| pull-stream | 351 | 789 | 466 | 268 | 55 | 66.03 | 2516.94 | 1385.89 | 208130 | 75071 | 283201 |
| q | 1051 | 2033 | 152 | 1784 | 97 | 12.25 | 5280.14 | 14131.09 | 2127655 | 217911 | 2345566 |
| spacl-core | 134 | 262 | 223 | 38 | 1 | 85.5 | 1350.99 | 879.83 | 162705 | 28767 | 191472 |
| zip-a-folder | 49 | 100 | 45 | 50 | 5 | 50 | 510.57 | 542.42 | 82457 | 10709 | 93166 |
| Total | 3376 | 6771 | 3324 | 3173 | 274 | - | 24042.30 | 25177.48 | 5841112 | 715682 | 6556794 |
## Experimental Parameters
  - Model: codellama-34b-instruct
  - Temperature: 0.5
  - Max Tokens: 250
  - Max Nr of Prompts: 2000
  - Template: template-full.hb
  - System Prompt: SystemPrompt-MutationTestingExpert.txt
  - Rate Limit: benchmark mode
  - Number of Attempts: 3


