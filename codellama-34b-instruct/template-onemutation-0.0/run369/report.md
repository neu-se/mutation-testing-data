# Report (Precomputed mutators --concurrency 1)
| Project | #Prompts | #Mutants | #Killed | #Survived | #Timeout | MutationScore | LLMorpheus Time | Stryker Time | #Prompt Tokens | #Completion Tokens | #Total Tokens  |
|:--------|:---------|:---------|:--------|:----------|----------|---------------|-----------------|--------------|----------------|--------------------|----------------|
| Complex.js | 490 | 401 | 241 | 160 | 0 | 60.1 | 2820.16 | 211.48 | 916945 | 39061 | 956006 |
| countries-and-timezones | 106 | 79 | 66 | 13 | 0 | 83.54 | 1071.1 | 117.43 | 97242 | 8548 | 105790 |
| crawler-url-parser | 176 | 85 | 50 | 35 | 0 | 58.82 | 1636.46 | 288.17 | 371967 | 15519 | 387486 |
| delta | 462 | 267 | 222 | 37 | 8 | 86.14 | 2686.73 | 1239.88 | 852830 | 37432 | 890262 |
| image-downloader | 42 | 34 | 26 | 8 | 0 | 76.47 | 430.69 | 142.46 | 21253 | 3475 | 24728 |
| node-dirty | 154 | 99 | 55 | 41 | 3 | 58.59 | 1536.37 | 75.72 | 233774 | 12869 | 246643 |
| node-geo-point | 140 | 104 | 74 | 30 | 0 | 71.15 | 1411.33 | 338.8 | 304993 | 11209 | 316202 |
| node-jsonfile | 68 | 57 | 18 | 18 | 21 | 68.42 | 690.78 | 183.73 | 52008 | 5845 | 57853 |
| plural | 153 | 101 | 71 | 30 | 0 | 70.3 | 1521.35 | 54.18 | 253209 | 13392 | 266601 |
| pull-stream | 351 | 280 | 165 | 95 | 20 | 66.07 | 2398.19 | 499.73 | 179699 | 30182 | 209881 |
| q | 1051 | 704 | 45 | 632 | 27 | 10.23 | 4188.82 | 4807.59 | 2042524 | 82120 | 2124644 |
| spacl-core | 134 | 80 | 63 | 17 | 0 | 78.75 | 1351.23 | 272.94 | 151851 | 10813 | 162664 |
| zip-a-folder | 49 | 39 | 19 | 17 | 3 | 56.41 | 500.64 | 222.35 | 78488 | 4405 | 82893 |
| Total | 3376 | 2330 | 1115 | 1133 | 82 | - | 22243.85 | 8454.46 | 5556783 | 274870 | 5831653 |
## Experimental Parameters
  - Model: codellama-34b-instruct
  - Temperature: 0
  - Max Tokens: 250
  - Max Nr of Prompts: 2000
  - Template: template-onemutation.hb
  - System Prompt: SystemPrompt-MutationTestingExpert.txt
  - Rate Limit: benchmark mode
  - Number of Attempts: 3


