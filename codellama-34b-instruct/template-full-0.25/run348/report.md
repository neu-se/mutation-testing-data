# Report (Precomputed mutators --concurrency 1)
| Project | #Prompts | #Mutants | #Killed | #Survived | #Timeout | MutationScore | LLMorpheus Time | Stryker Time | #Prompt Tokens | #Completion Tokens | #Total Tokens  |
|:--------|:---------|:---------|:--------|:----------|----------|---------------|-----------------|--------------|----------------|--------------------|----------------|
| Complex.js | 490 | 1197 | 730 | 466 | 1 | 61.07 | 3044.19 | 631.79 | 967508 | 101588 | 1069096 |
| countries-and-timezones | 106 | 219 | 181 | 38 | 0 | 82.65 | 1070.9 | 327.25 | 105828 | 23471 | 129299 |
| crawler-url-parser | 176 | 260 | 167 | 93 | 0 | 64.23 | 1646.3 | 818.05 | 386223 | 39000 | 425223 |
| delta | 462 | 781 | 642 | 111 | 28 | 85.79 | 2954.37 | 3844 | 890252 | 99341 | 989593 |
| image-downloader | 42 | 86 | 71 | 15 | 0 | 82.56 | 430.54 | 348.86 | 24655 | 9217 | 33872 |
| node-dirty | 154 | 279 | 175 | 93 | 11 | 66.67 | 1532.06 | 232.35 | 246248 | 32400 | 278648 |
| node-geo-point | 140 | 293 | 225 | 68 | 0 | 76.79 | 1708.63 | 961.35 | 291061 | 26301 | 317362 |
| node-jsonfile | 68 | 151 | 52 | 41 | 58 | 72.85 | 740.73 | 502.52 | 57516 | 14400 | 71916 |
| plural | 153 | 273 | 208 | 63 | 2 | 76.92 | 1537.89 | 149.38 | 265602 | 33182 | 298784 |
| pull-stream | 351 | 779 | 452 | 270 | 57 | 65.34 | 2522.38 | 1395.14 | 208130 | 76091 | 284221 |
| q | 1051 | 2050 | 153 | 1813 | 84 | 11.56 | 5294.8 | 14085.1 | 2127655 | 218620 | 2346275 |
| spacl-core | 134 | 223 | 187 | 36 | 0 | 83.86 | 1351.05 | 728.32 | 162705 | 29167 | 191872 |
| zip-a-folder | 49 | 97 | 24 | 4 | 69 | 95.88 | 500.56 | 1086.06 | 82457 | 10557 | 93014 |
| Total | 3376 | 6688 | 3267 | 3111 | 310 | - | 24334.40 | 25110.17 | 5815840 | 713335 | 6529175 |
## Experimental Parameters
  - Model: codellama-34b-instruct
  - Temperature: 0.25
  - Max Tokens: 250
  - Max Nr of Prompts: 2000
  - Template: template-full.hb
  - System Prompt: SystemPrompt-MutationTestingExpert.txt
  - Rate Limit: benchmark mode
  - Number of Attempts: 3


