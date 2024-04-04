# Report (Precomputed mutators --concurrency 1)
| Project | #Prompts | #Mutants | #Killed | #Survived | #Timeout | MutationScore | LLMorpheus Time | Stryker Time | #Prompt Tokens | #Completion Tokens | #Total Tokens  |
|:--------|:---------|:---------|:--------|:----------|----------|---------------|-----------------|--------------|----------------|--------------------|----------------|
| Complex.js | 490 | 406 | 245 | 161 | 0 | 60.34 | 2754.08 | 218.66 | 927818 | 39566 | 967384 |
| countries-and-timezones | 106 | 79 | 66 | 13 | 0 | 83.54 | 1071.03 | 119.64 | 97242 | 8579 | 105821 |
| crawler-url-parser | 176 | 87 | 51 | 36 | 0 | 58.62 | 1636.41 | 281.15 | 371967 | 15525 | 387492 |
| delta | 462 | 266 | 221 | 37 | 8 | 86.09 | 2676.11 | 1249.77 | 852830 | 37449 | 890279 |
| image-downloader | 42 | 34 | 26 | 8 | 0 | 76.47 | 430.6 | 138.45 | 21253 | 3475 | 24728 |
| node-dirty | 154 | 98 | 55 | 40 | 3 | 59.18 | 1526.42 | 73.92 | 233774 | 12859 | 246633 |
| node-geo-point | 140 | 104 | 74 | 30 | 0 | 71.15 | 1411.28 | 329.4 | 304993 | 11210 | 316203 |
| node-jsonfile | 68 | 57 | 18 | 18 | 21 | 68.42 | 690.77 | 183.71 | 52008 | 5787 | 57795 |
| plural | 153 | 101 | 71 | 30 | 0 | 70.3 | 1521.36 | 53.81 | 253209 | 13434 | 266643 |
| pull-stream | 351 | 280 | 165 | 95 | 20 | 66.07 | 2397.58 | 499.25 | 179699 | 30160 | 209859 |
| q | 1051 | 703 | 46 | 630 | 27 | 10.38 | 4211.46 | 4819.77 | 2042524 | 82203 | 2124727 |
| spacl-core | 134 | 80 | 63 | 17 | 0 | 78.75 | 1361.19 | 269.34 | 151851 | 10818 | 162669 |
| zip-a-folder | 49 | 39 | 19 | 17 | 3 | 56.41 | 500.61 | 217.85 | 78488 | 4400 | 82888 |
| Total | 3376 | 2334 | 1120 | 1132 | 82 | - | 22188.90 | 8454.72 | 5567656 | 275465 | 5843121 |
## Experimental Parameters
  - Model: codellama-34b-instruct
  - Temperature: 0
  - Max Tokens: 250
  - Max Nr of Prompts: 2000
  - Template: template-onemutation.hb
  - System Prompt: SystemPrompt-MutationTestingExpert.txt
  - Rate Limit: benchmark mode
  - Number of Attempts: 3


