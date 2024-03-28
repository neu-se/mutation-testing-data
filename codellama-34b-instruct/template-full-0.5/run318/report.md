# Report (Precomputed mutators --concurrency 1)
| Project | #Prompts | #Mutants | #Killed | #Survived | #Timeout | MutationScore | LLMorpheus Time | Stryker Time | #Prompt Tokens | #Completion Tokens | #Total Tokens  |
|:--------|:---------|:---------|:--------|:----------|----------|---------------|-----------------|--------------|----------------|--------------------|----------------|
| Complex.js | 490 | 1191 | 739 | 452 | 0 | 62.05 | 3016.85 | 592.07 | 967508 | 100627 | 1068135 |
| countries-and-timezones | 106 | 224 | 194 | 30 | 0 | 86.61 | 1070.93 | 319.44 | 105828 | 22932 | 128760 |
| crawler-url-parser | 176 | 298 | 166 | 108 | 24 | 63.76 | 1668.66 | 1244.64 | 386223 | 38920 | 425143 |
| delta | 462 | 769 | 642 | 93 | 34 | 87.91 | 2980.99 | 3869.42 | 890252 | 98347 | 988599 |
| image-downloader | 42 | 89 | 68 | 21 | 0 | 76.4 | 430.55 | 365.9 | 24655 | 8925 | 33580 |
| node-dirty | 154 | 277 | 158 | 107 | 12 | 61.37 | 1532.57 | 247.29 | 246248 | 32995 | 279243 |
| node-geo-point | 140 | 302 | 230 | 72 | 0 | 76.16 | 1411.06 | 1006.9 | 316333 | 29454 | 345787 |
| node-jsonfile | 68 | 153 | 51 | 43 | 59 | 71.9 | 720.71 | 494.61 | 57516 | 15051 | 72567 |
| plural | 153 | 289 | 219 | 69 | 1 | 76.12 | 1522.56 | 152.03 | 265602 | 33550 | 299152 |
| pull-stream | 351 | 796 | 465 | 278 | 53 | 65.08 | 2506.81 | 1378.63 | 208130 | 75239 | 283369 |
| q | 1051 | 2073 | 163 | 1823 | 87 | 12.06 | 5332.46 | 14311.02 | 2127655 | 217886 | 2345541 |
| spacl-core | 134 | 250 | 210 | 39 | 1 | 84.4 | 1351.01 | 850.39 | 162705 | 28919 | 191624 |
| zip-a-folder | 49 | 87 | 48 | 33 | 6 | 62.07 | 900.98 | 471.62 | 72362 | 9438 | 81800 |
| Total | 3376 | 6798 | 3353 | 3168 | 277 | - | 24446.14 | 25303.96 | 5831017 | 712283 | 6543300 |
## Experimental Parameters
  - Model: codellama-34b-instruct
  - Temperature: 0.5
  - Max Tokens: 250
  - Max Nr of Prompts: 2000
  - Template: template-full.hb
  - System Prompt: SystemPrompt-MutationTestingExpert.txt
  - Rate Limit: benchmark mode
  - Number of Attempts: 3


