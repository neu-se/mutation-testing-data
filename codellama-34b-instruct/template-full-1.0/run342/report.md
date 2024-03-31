# Report (Precomputed mutators --concurrency 1)
| Project | #Prompts | #Mutants | #Killed | #Survived | #Timeout | MutationScore | LLMorpheus Time | Stryker Time | #Prompt Tokens | #Completion Tokens | #Total Tokens  |
|:--------|:---------|:---------|:--------|:----------|----------|---------------|-----------------|--------------|----------------|--------------------|----------------|
| Complex.js | 490 | 987 | 611 | 376 | 0 | 61.9 | 3099.95 | 515 | 967508 | 99831 | 1067339 |
| countries-and-timezones | 106 | 164 | 145 | 19 | 0 | 88.41 | 1537.5 | 234.01 | 96352 | 19743 | 116095 |
| crawler-url-parser | 176 | 257 | 177 | 80 | 0 | 68.87 | 1643.69 | 843.29 | 386223 | 36746 | 422969 |
| delta | 462 | 701 | 596 | 75 | 30 | 89.3 | 3119.28 | 3448.69 | 890252 | 95930 | 986182 |
| image-downloader | 42 | 59 | 46 | 13 | 0 | 77.97 | 430.53 | 351.02 | 24655 | 8785 | 33440 |
| node-dirty | 154 | 268 | 164 | 96 | 8 | 64.18 | 1526.21 | 216.7 | 246248 | 31856 | 278104 |
| node-geo-point | 140 | 270 | 209 | 61 | 0 | 77.41 | 1422.53 | 877.31 | 316333 | 30037 | 346370 |
| node-jsonfile | 68 | 150 | 67 | 16 | 67 | 89.33 | 690.7 | 537.75 | 57516 | 14738 | 72254 |
| plural | 153 | 304 | 245 | 58 | 1 | 80.92 | 1521.12 | 159.03 | 265602 | 32288 | 297890 |
| pull-stream | 351 | 741 | 460 | 238 | 43 | 67.88 | 2659.93 | 1222.06 | 208130 | 73902 | 282032 |
| q | 1051 | 1894 | 169 | 1652 | 73 | 12.78 | 5264.59 | 12818.11 | 2127655 | 212677 | 2340332 |
| spacl-core | 134 | 205 | 173 | 32 | 0 | 84.39 | 1361.03 | 682.26 | 162705 | 27970 | 190675 |
| zip-a-folder | 49 | 84 | 23 | 4 | 57 | 95.24 | 500.58 | 908.74 | 82457 | 9890 | 92347 |
| Total | 3376 | 6084 | 3085 | 2720 | 279 | - | 24777.64 | 22813.97 | 5831636 | 694393 | 6526029 |
## Experimental Parameters
  - Model: codellama-34b-instruct
  - Temperature: 1
  - Max Tokens: 250
  - Max Nr of Prompts: 2000
  - Template: template-full.hb
  - System Prompt: SystemPrompt-MutationTestingExpert.txt
  - Rate Limit: benchmark mode
  - Number of Attempts: 3


