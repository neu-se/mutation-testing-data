# Report (Precomputed mutators --concurrency 1)
| Project | #Prompts | #Mutants | #Killed | #Survived | #Timeout | MutationScore | LLMorpheus Time | Stryker Time | #Prompt Tokens | #Completion Tokens | #Total Tokens  |
|:--------|:---------|:---------|:--------|:----------|----------|---------------|-----------------|--------------|----------------|--------------------|----------------|
| Complex.js | 490 | 1002 | 637 | 365 | 0 | 63.57 | 3024.06 | 525.74 | 967508 | 98687 | 1066195 |
| countries-and-timezones | 106 | 198 | 177 | 21 | 0 | 89.39 | 1070.86 | 293.27 | 105828 | 23318 | 129146 |
| crawler-url-parser | 176 | 269 | 173 | 96 | 0 | 64.31 | 1644.85 | 845.43 | 386223 | 36638 | 422861 |
| delta | 462 | 727 | 611 | 85 | 31 | 88.31 | 2948.43 | 3663.87 | 890252 | 96381 | 986633 |
| image-downloader | 42 | 78 | 70 | 8 | 0 | 89.74 | 430.52 | 274.68 | 24655 | 9228 | 33883 |
| node-dirty | 154 | 245 | 136 | 97 | 12 | 60.41 | 1526.11 | 216.05 | 246248 | 31882 | 278130 |
| node-geo-point | 140 | 259 | 194 | 65 | 0 | 74.9 | 1411.07 | 852.26 | 316333 | 29152 | 345485 |
| node-jsonfile | 68 | 146 | 68 | 14 | 64 | 90.41 | 690.73 | 549.73 | 57516 | 13670 | 71186 |
| plural | 153 | 295 | 236 | 58 | 1 | 80.34 | 1521.17 | 153.33 | 265602 | 31946 | 297548 |
| pull-stream | 351 | 740 | 443 | 248 | 49 | 66.49 | 2506.18 | 1294.61 | 208130 | 72667 | 280797 |
| q | 1051 | 1941 | 147 | 1707 | 87 | 12.06 | 5178.82 | 13300.53 | 2127655 | 213258 | 2340913 |
| spacl-core | 134 | 225 | 196 | 29 | 0 | 87.11 | 1351.08 | 743.18 | 162705 | 27865 | 190570 |
| zip-a-folder | 49 | 94 | 28 | 4 | 62 | 95.74 | 500.55 | 1038.21 | 82457 | 10518 | 92975 |
| Total | 3376 | 6219 | 3116 | 2797 | 306 | - | 23804.43 | 23750.89 | 5841112 | 695210 | 6536322 |
## Experimental Parameters
  - Model: codellama-34b-instruct
  - Temperature: 1
  - Max Tokens: 250
  - Max Nr of Prompts: 2000
  - Template: template-full.hb
  - System Prompt: SystemPrompt-MutationTestingExpert.txt
  - Rate Limit: benchmark mode
  - Number of Attempts: 3


