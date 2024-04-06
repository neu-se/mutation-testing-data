# Report (Precomputed mutators --concurrency 1)
| Project | #Prompts | #Mutants | #Killed | #Survived | #Timeout | MutationScore | LLMorpheus Time | Stryker Time | #Prompt Tokens | #Completion Tokens | #Total Tokens  |
|:--------|:---------|:---------|:--------|:----------|----------|---------------|-----------------|--------------|----------------|--------------------|----------------|
| Complex.js | 490 | 185 | 120 | 65 | 0 | 64.86 | 2731.54 | 97.72 | 893966 | 14460 | 908426 |
| countries-and-timezones | 106 | 48 | 44 | 4 | 0 | 91.67 | 1071.22 | 73.08 | 89939 | 3087 | 93026 |
| crawler-url-parser | 176 | 67 | 49 | 18 | 0 | 73.13 | 1636.67 | 215.52 | 359498 | 5557 | 365055 |
| delta | 462 | 201 | 167 | 28 | 6 | 86.07 | 2659.93 | 910.49 | 820541 | 13472 | 834013 |
| image-downloader | 42 | 10 | 7 | 3 | 0 | 70 | 430.67 | 65.98 | 18348 | 1448 | 19796 |
| node-dirty | 154 | 44 | 24 | 18 | 2 | 59.09 | 1526.59 | 39.53 | 223071 | 4425 | 227496 |
| node-geo-point | 140 | 62 | 54 | 8 | 0 | 87.1 | 1411.43 | 204.76 | 295321 | 4217 | 299538 |
| node-jsonfile | 68 | 22 | 11 | 3 | 8 | 86.36 | 690.87 | 77.82 | 47346 | 1831 | 49177 |
| plural | 153 | 92 | 78 | 14 | 0 | 84.78 | 1521.52 | 48.57 | 241953 | 5075 | 247028 |
| pull-stream | 351 | 149 | 88 | 54 | 7 | 63.76 | 2382.28 | 245.31 | 156016 | 9287 | 165303 |
| q | 1051 | 401 | 38 | 350 | 13 | 12.72 | 4158.17 | 2697.98 | 1970359 | 30059 | 2000418 |
| spacl-core | 134 | 25 | 23 | 2 | 0 | 92 | 1351.47 | 85.42 | 142466 | 4013 | 146479 |
| zip-a-folder | 49 | 20 | 5 | 1 | 14 | 95 | 500.75 | 235.31 | 75033 | 1594 | 76627 |
| Total | 3376 | 1326 | 708 | 568 | 50 | - | 22073.11 | 4997.49 | 5333857 | 98525 | 5432382 |
## Experimental Parameters
  - Model: codellama-34b-instruct
  - Temperature: 0
  - Max Tokens: 250
  - Max Nr of Prompts: 2000
  - Template: template-basic.hb
  - System Prompt: SystemPrompt-MutationTestingExpert.txt
  - Rate Limit: benchmark mode
  - Number of Attempts: 3


