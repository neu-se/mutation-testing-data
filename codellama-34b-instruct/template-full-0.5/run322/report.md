# Report (Precomputed mutators --concurrency 1)
| Project | #Prompts | #Mutants | #Killed | #Survived | #Timeout | MutationScore | LLMorpheus Time | Stryker Time | #Prompt Tokens | #Completion Tokens | #Total Tokens  |
|:--------|:---------|:---------|:--------|:----------|----------|---------------|-----------------|--------------|----------------|--------------------|----------------|
| Complex.js | 490 | 1186 | 725 | 461 | 0 | 61.13 | 3058.33 | 648.14 | 967508 | 100962 | 1068470 |
| countries-and-timezones | 106 | 224 | 197 | 27 | 0 | 87.95 | 1070.88 | 328.85 | 105828 | 23165 | 128993 |
| crawler-url-parser | 176 | 297 | 173 | 124 | 0 | 58.25 | 1645.45 | 966.36 | 386223 | 38649 | 424872 |
| delta | 462 | 791 | 660 | 92 | 39 | 88.37 | 2954.29 | 4010.15 | 890252 | 97995 | 988247 |
| image-downloader | 42 | 80 | 68 | 12 | 0 | 85 | 430.57 | 330.02 | 24655 | 9182 | 33837 |
| node-dirty | 154 | 283 | 161 | 110 | 12 | 61.13 | 1528.13 | 239.77 | 246248 | 32568 | 278816 |
| node-geo-point | 140 | 305 | 239 | 66 | 0 | 78.36 | 1411.08 | 1024.88 | 316333 | 29330 | 345663 |
| node-jsonfile | 68 | 160 | 51 | 42 | 67 | 73.75 | 690.67 | 543.04 | 57516 | 14833 | 72349 |
| plural | 153 | 289 | 225 | 64 | 0 | 77.85 | 1522.09 | 148.56 | 265602 | 33906 | 299508 |
| pull-stream | 351 | 806 | 490 | 255 | 61 | 68.36 | 2509.37 | 1433.54 | 208130 | 75574 | 283704 |
| q | 1051 | 2028 | 141 | 1801 | 86 | 11.19 | 5254.98 | 13947.69 | 2127655 | 216579 | 2344234 |
| spacl-core | 134 | 252 | 212 | 39 | 1 | 84.52 | 1351.03 | 834.35 | 162705 | 29103 | 191808 |
| zip-a-folder | 49 | 103 | 27 | 5 | 71 | 95.15 | 500.6 | 1144.5 | 82457 | 10347 | 92804 |
| Total | 3376 | 6804 | 3369 | 3098 | 337 | - | 23927.47 | 25599.85 | 5841112 | 712193 | 6553305 |
## Experimental Parameters
  - Model: codellama-34b-instruct
  - Temperature: 0.5
  - Max Tokens: 250
  - Max Nr of Prompts: 2000
  - Template: template-full.hb
  - System Prompt: SystemPrompt-MutationTestingExpert.txt
  - Rate Limit: benchmark mode
  - Number of Attempts: 3


