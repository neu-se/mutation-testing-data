# Report (Precomputed mutators --concurrency 1)
| Project | #Prompts | #Mutants | #Killed | #Survived | #Timeout | MutationScore | LLMorpheus Time | Stryker Time | #Prompt Tokens | #Completion Tokens | #Total Tokens  |
|:--------|:---------|:---------|:--------|:----------|----------|---------------|-----------------|--------------|----------------|--------------------|----------------|
| Complex.js | 490 | 1192 | 721 | 471 | 0 | 60.49 | 3031.72 | 631.91 | 967508 | 102075 | 1069583 |
| countries-and-timezones | 106 | 227 | 200 | 27 | 0 | 88.11 | 1070.83 | 324.27 | 105828 | 23502 | 129330 |
| crawler-url-parser | 176 | 260 | 151 | 109 | 0 | 58.08 | 1642.15 | 835.28 | 386223 | 39240 | 425463 |
| delta | 462 | 765 | 619 | 109 | 37 | 85.75 | 2969.01 | 3912.89 | 890252 | 99383 | 989635 |
| image-downloader | 42 | 82 | 62 | 20 | 0 | 75.61 | 430.57 | 486.28 | 24655 | 9228 | 33883 |
| node-dirty | 154 | 267 | 158 | 97 | 12 | 63.67 | 1527.16 | 237.65 | 246248 | 32850 | 279098 |
| node-geo-point | 140 | 308 | 226 | 82 | 0 | 73.38 | 1411.1 | 1015.42 | 316333 | 28895 | 345228 |
| node-jsonfile | 68 | 151 | 48 | 47 | 56 | 68.87 | 690.64 | 496.41 | 57516 | 14557 | 72073 |
| plural | 153 | 279 | 212 | 66 | 1 | 76.34 | 1521.03 | 148.1 | 265602 | 33162 | 298764 |
| pull-stream | 351 | 773 | 443 | 277 | 53 | 64.17 | 2509.05 | 1370.63 | 208130 | 75917 | 284047 |
| q | 1051 | 2044 | 141 | 1822 | 81 | 10.86 | 5300.14 | 14131.12 | 2127655 | 218921 | 2346576 |
| spacl-core | 134 | 214 | 183 | 30 | 1 | 85.98 | 1351.01 | 712.33 | 162705 | 28809 | 191514 |
| zip-a-folder | 49 | 105 | 27 | 2 | 76 | 98.1 | 500.63 | 1266.61 | 82457 | 10707 | 93164 |
| Total | 3376 | 6667 | 3191 | 3159 | 317 | - | 23955.04 | 25568.90 | 5841112 | 717246 | 6558358 |
## Experimental Parameters
  - Model: codellama-34b-instruct
  - Temperature: 0.25
  - Max Tokens: 250
  - Max Nr of Prompts: 2000
  - Template: template-full.hb
  - System Prompt: SystemPrompt-MutationTestingExpert.txt
  - Rate Limit: benchmark mode
  - Number of Attempts: 3


