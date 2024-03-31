# Report (Precomputed mutators --concurrency 1)
| Project | #Prompts | #Mutants | #Killed | #Survived | #Timeout | MutationScore | LLMorpheus Time | Stryker Time | #Prompt Tokens | #Completion Tokens | #Total Tokens  |
|:--------|:---------|:---------|:--------|:----------|----------|---------------|-----------------|--------------|----------------|--------------------|----------------|
| Complex.js | 490 | 1018 | 640 | 378 | 0 | 62.87 | 3021.09 | 531.51 | 967508 | 100183 | 1067691 |
| countries-and-timezones | 106 | 207 | 177 | 30 | 0 | 85.51 | 1070.89 | 297.61 | 105828 | 23229 | 129057 |
| crawler-url-parser | 176 | 252 | 178 | 74 | 0 | 70.63 | 1642.94 | 776.31 | 386223 | 36920 | 423143 |
| delta | 462 | 679 | 564 | 83 | 32 | 87.78 | 2984.22 | 3374.88 | 890252 | 96698 | 986950 |
| image-downloader | 42 | 75 | 56 | 17 | 2 | 77.33 | 430.54 | 435.23 | 24655 | 9024 | 33679 |
| node-dirty | 154 | 267 | 155 | 103 | 9 | 61.42 | 1528.77 | 227.23 | 246248 | 32731 | 278979 |
| node-geo-point | 140 | 263 | 198 | 65 | 0 | 75.29 | 1411.05 | 858.36 | 316333 | 29774 | 346107 |
| node-jsonfile | 68 | 141 | 60 | 25 | 56 | 82.27 | 690.66 | 494.3 | 57516 | 14127 | 71643 |
| plural | 153 | 308 | 245 | 60 | 3 | 80.52 | 1521.3 | 172.76 | 265602 | 32844 | 298446 |
| pull-stream | 351 | 741 | 457 | 237 | 47 | 68.02 | 2481.7 | 1251.69 | 208130 | 73022 | 281152 |
| q | 1051 | 1868 | 130 | 1652 | 86 | 11.56 | 5205.03 | 13013.51 | 2127655 | 214495 | 2342150 |
| spacl-core | 134 | 224 | 202 | 21 | 1 | 90.63 | 1351.07 | 731.4 | 162705 | 27723 | 190428 |
| zip-a-folder | 49 | 102 | 28 | 1 | 73 | 99.02 | 500.58 | 1168.69 | 82457 | 10656 | 93113 |
| Total | 3376 | 6145 | 3090 | 2746 | 309 | - | 23839.84 | 23333.48 | 5841112 | 701426 | 6542538 |
## Experimental Parameters
  - Model: codellama-34b-instruct
  - Temperature: 1
  - Max Tokens: 250
  - Max Nr of Prompts: 2000
  - Template: template-full.hb
  - System Prompt: SystemPrompt-MutationTestingExpert.txt
  - Rate Limit: benchmark mode
  - Number of Attempts: 3


