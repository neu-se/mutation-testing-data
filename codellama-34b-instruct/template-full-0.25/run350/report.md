# Report (Precomputed mutators --concurrency 1)
| Project | #Prompts | #Mutants | #Killed | #Survived | #Timeout | MutationScore | LLMorpheus Time | Stryker Time | #Prompt Tokens | #Completion Tokens | #Total Tokens  |
|:--------|:---------|:---------|:--------|:----------|----------|---------------|-----------------|--------------|----------------|--------------------|----------------|
| Complex.js | 490 | 1200 | 729 | 471 | 0 | 60.75 | 3029.62 | 629.66 | 967508 | 100540 | 1068048 |
| countries-and-timezones | 106 | 223 | 198 | 25 | 0 | 88.79 | 1070.85 | 314.98 | 105828 | 23186 | 129014 |
| crawler-url-parser | 176 | 269 | 163 | 106 | 0 | 60.59 | 1777.23 | 867.78 | 386223 | 38916 | 425139 |
| delta | 462 | 752 | 608 | 110 | 34 | 85.37 | 2978.88 | 3758.68 | 890252 | 99176 | 989428 |
| image-downloader | 42 | 85 | 67 | 18 | 0 | 78.82 | 430.55 | 366.05 | 24655 | 9223 | 33878 |
| node-dirty | 154 | 271 | 163 | 96 | 12 | 64.58 | 1528.73 | 237.16 | 246248 | 32776 | 279024 |
| node-geo-point | 140 | 311 | 243 | 68 | 0 | 78.14 | 1411.08 | 1021.61 | 316333 | 29301 | 345634 |
| node-jsonfile | 68 | 158 | 50 | 54 | 54 | 65.82 | 690.69 | 485.24 | 57516 | 14071 | 71587 |
| plural | 153 | 283 | 213 | 68 | 2 | 75.97 | 1521.09 | 154.2 | 265602 | 33560 | 299162 |
| pull-stream | 351 | 772 | 450 | 265 | 57 | 65.67 | 2503.6 | 1383.12 | 208130 | 76551 | 284681 |
| q | 1051 | 1980 | 144 | 1756 | 80 | 11.31 | 5379.31 | 13584.78 | 2127655 | 217699 | 2345354 |
| spacl-core | 134 | 225 | 194 | 30 | 1 | 86.67 | 1350.98 | 739.03 | 162705 | 29184 | 191889 |
| zip-a-folder | 49 | 95 | 36 | 53 | 6 | 44.21 | 500.57 | 531.1 | 82457 | 10753 | 93210 |
| Total | 3376 | 6624 | 3258 | 3120 | 246 | - | 24173.18 | 24073.39 | 5841112 | 714936 | 6556048 |
## Experimental Parameters
  - Model: codellama-34b-instruct
  - Temperature: 0.25
  - Max Tokens: 250
  - Max Nr of Prompts: 2000
  - Template: template-full.hb
  - System Prompt: SystemPrompt-MutationTestingExpert.txt
  - Rate Limit: benchmark mode
  - Number of Attempts: 3


