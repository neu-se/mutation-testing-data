# Report (Precomputed mutators --concurrency 1)
| Project | #Prompts | #Mutants | #Killed | #Survived | #Timeout | MutationScore | LLMorpheus Time | Stryker Time | #Prompt Tokens | #Completion Tokens | #Total Tokens  |
|:--------|:---------|:---------|:--------|:----------|----------|---------------|-----------------|--------------|----------------|--------------------|----------------|
| Complex.js | 490 | 185 | 120 | 65 | 0 | 64.86 | 2730.17 | 96.67 | 893966 | 14460 | 908426 |
| countries-and-timezones | 106 | 48 | 44 | 4 | 0 | 91.67 | 1071.19 | 73.83 | 89939 | 3086 | 93025 |
| crawler-url-parser | 176 | 67 | 49 | 18 | 0 | 73.13 | 1636.65 | 205.98 | 359498 | 5577 | 365075 |
| delta | 462 | 200 | 166 | 28 | 6 | 86 | 2659.91 | 887.25 | 820541 | 13475 | 834016 |
| image-downloader | 42 | 10 | 7 | 3 | 0 | 70 | 430.71 | 65.63 | 18348 | 1449 | 19797 |
| node-dirty | 154 | 43 | 24 | 17 | 2 | 60.47 | 1526.6 | 38.47 | 223071 | 4500 | 227571 |
| node-geo-point | 140 | 62 | 54 | 8 | 0 | 87.1 | 1411.44 | 197.24 | 295321 | 4217 | 299538 |
| node-jsonfile | 68 | 22 | 11 | 3 | 8 | 86.36 | 690.88 | 78.16 | 47346 | 1831 | 49177 |
| plural | 153 | 92 | 78 | 14 | 0 | 84.78 | 1522.37 | 47.69 | 241953 | 5075 | 247028 |
| pull-stream | 351 | 149 | 88 | 54 | 7 | 63.76 | 2382.2 | 245.09 | 156016 | 9290 | 165306 |
| q | 1051 | 402 | 38 | 351 | 13 | 12.69 | 4154.13 | 2691.66 | 1970359 | 30055 | 2000414 |
| spacl-core | 134 | 25 | 23 | 2 | 0 | 92 | 1351.41 | 83.75 | 142466 | 4013 | 146479 |
| zip-a-folder | 49 | 20 | 5 | 1 | 14 | 95 | 500.72 | 232.15 | 75033 | 1594 | 76627 |
| Total | 3376 | 1325 | 707 | 568 | 50 | - | 22068.38 | 4943.57 | 5333857 | 98622 | 5432479 |
## Experimental Parameters
  - Model: codellama-34b-instruct
  - Temperature: 0
  - Max Tokens: 250
  - Max Nr of Prompts: 2000
  - Template: template-basic.hb
  - System Prompt: SystemPrompt-MutationTestingExpert.txt
  - Rate Limit: benchmark mode
  - Number of Attempts: 3


