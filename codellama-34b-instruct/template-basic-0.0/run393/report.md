# Report (Precomputed mutators --concurrency 1)
| Project | #Prompts | #Mutants | #Killed | #Survived | #Timeout | MutationScore | LLMorpheus Time | Stryker Time | #Prompt Tokens | #Completion Tokens | #Total Tokens  |
|:--------|:---------|:---------|:--------|:----------|----------|---------------|-----------------|--------------|----------------|--------------------|----------------|
| Complex.js | 490 | 184 | 119 | 65 | 0 | 64.67 | 2730.22 | 96.64 | 893966 | 14459 | 908425 |
| countries-and-timezones | 106 | 48 | 43 | 5 | 0 | 89.58 | 1071.13 | 74.16 | 89939 | 3112 | 93051 |
| crawler-url-parser | 176 | 67 | 49 | 18 | 0 | 73.13 | 1636.64 | 206.03 | 359498 | 5556 | 365054 |
| delta | 462 | 201 | 167 | 28 | 6 | 86.07 | 2659.88 | 897.06 | 820541 | 13471 | 834012 |
| image-downloader | 42 | 10 | 7 | 3 | 0 | 70 | 430.66 | 65.63 | 18348 | 1449 | 19797 |
| node-dirty | 154 | 44 | 24 | 18 | 2 | 59.09 | 1526.57 | 38.82 | 223071 | 4425 | 227496 |
| node-geo-point | 140 | 62 | 54 | 8 | 0 | 87.1 | 1411.45 | 200.23 | 295321 | 4217 | 299538 |
| node-jsonfile | 68 | 22 | 11 | 3 | 8 | 86.36 | 690.84 | 77.61 | 47346 | 1831 | 49177 |
| plural | 153 | 91 | 78 | 13 | 0 | 85.71 | 1556.64 | 47.7 | 238779 | 5029 | 243808 |
| pull-stream | 351 | 149 | 88 | 54 | 7 | 63.76 | 2382.19 | 247.28 | 156016 | 9288 | 165304 |
| q | 1051 | 402 | 38 | 351 | 13 | 12.69 | 4156.62 | 2695.05 | 1970359 | 30071 | 2000430 |
| spacl-core | 134 | 25 | 23 | 2 | 0 | 92 | 1351.45 | 84.84 | 142466 | 4008 | 146474 |
| zip-a-folder | 49 | 20 | 5 | 1 | 14 | 95 | 500.75 | 235.51 | 75033 | 1594 | 76627 |
| Total | 3376 | 1325 | 706 | 569 | 50 | - | 22105.04 | 4966.56 | 5330683 | 98510 | 5429193 |
## Experimental Parameters
  - Model: codellama-34b-instruct
  - Temperature: 0
  - Max Tokens: 250
  - Max Nr of Prompts: 2000
  - Template: template-basic.hb
  - System Prompt: SystemPrompt-MutationTestingExpert.txt
  - Rate Limit: benchmark mode
  - Number of Attempts: 3


