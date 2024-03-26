# Report (Precomputed mutators)
| Project | #Prompts | #Mutants | #Killed | #Survived | #Timeout | MutationScore | LLMorpheus Time | Stryker Time | #Prompt Tokens | #Completion Tokens | #Total Tokens  |
|:--------|:---------|:---------|:--------|:----------|----------|---------------|-----------------|--------------|----------------|--------------------|----------------|
| Complex.js | 490 | 1199 | 725 | 473 | 1 | 60.55 | 3182.18 | 508.17 | 967508 | 102558 | 1070066 |
| countries-and-timezones | 106 | 217 | 188 | 29 | 0 | 86.64 | 1070.88 | 262.56 | 105828 | 23444 | 129272 |
| crawler-url-parser | 176 | 286 | 158 | 128 | 0 | 55.24 | 1638.02 | 627.51 | 386223 | 39196 | 425419 |
| delta | 462 | 766 | 636 | 99 | 31 | 87.08 | 2919.05 | 3466.64 | 890252 | 99066 | 989318 |
| image-downloader | 42 | 90 | 73 | 17 | 0 | 81.11 | 430.58 | 217.2 | 24655 | 9155 | 33810 |
| node-dirty | 154 | 275 | 203 | 61 | 11 | 77.82 | 1526.9 | 159.08 | 246248 | 33077 | 279325 |
| node-geo-point | 140 | 302 | 223 | 79 | 0 | 73.84 | 1439.48 | 896.83 | 316333 | 29989 | 346322 |
| node-jsonfile | 68 | 154 | 49 | 48 | 57 | 68.83 | 690.7 | 255.93 | 57516 | 14844 | 72360 |
| plural | 153 | 279 | 203 | 75 | 1 | 73.12 | 1521.1 | 116.18 | 265602 | 34172 | 299774 |
| pull-stream | 351 | 769 | 439 | 272 | 58 | 64.63 | 2483.42 | 772.01 | 208130 | 76634 | 284764 |
| q | 1051 | 2035 | 158 | 1793 | 84 | 11.89 | 5319.07 | 7133.48 | 2127655 | 220444 | 2348099 |
| spacl-core | 134 | 239 | 199 | 39 | 1 | 83.68 | 1351.03 | 682.23 | 162705 | 29302 | 192007 |
| zip-a-folder | 49 | 100 | 48 | 45 | 7 | 55 | 500.59 | 439.41 | 82457 | 10729 | 93186 |
| Total | 3376 | 6711 | 3302 | 3158 | 251 | - | 24073.00 | 15537.23 | 5841112 | 722610 | 6563722 |
## Experimental Parameters
  - Model: codellama-34b-instruct
  - Temperature: 0
  - Max Tokens: 250
  - Max Nr of Prompts: 2000
  - Template: template-full.hb
  - System Prompt: SystemPrompt-MutationTestingExpert.txt
  - Rate Limit: benchmark mode
  - Number of Attempts: 3


