# Report (Precomputed mutators --concurrency 1)
| Project | #Prompts | #Mutants | #Killed | #Survived | #Timeout | MutationScore | LLMorpheus Time | Stryker Time | #Prompt Tokens | #Completion Tokens | #Total Tokens  |
|:--------|:---------|:---------|:--------|:----------|----------|---------------|-----------------|--------------|----------------|--------------------|----------------|
| Complex.js | 490 | 406 | 244 | 162 | 0 | 60.1 | 2757 | 215 | 927818 | 39486 | 967304 |
| countries-and-timezones | 106 | 79 | 66 | 13 | 0 | 83.54 | 1091.07 | 116.98 | 97242 | 8527 | 105769 |
| crawler-url-parser | 176 | 86 | 50 | 36 | 0 | 58.14 | 1636.38 | 300.85 | 371967 | 15532 | 387499 |
| delta | 462 | 267 | 222 | 37 | 8 | 86.14 | 2681 | 1235.39 | 852830 | 37383 | 890213 |
| image-downloader | 42 | 34 | 26 | 8 | 0 | 76.47 | 460.67 | 139.42 | 21253 | 3476 | 24729 |
| node-dirty | 154 | 99 | 55 | 41 | 3 | 58.59 | 1526.36 | 75.52 | 233774 | 12907 | 246681 |
| node-geo-point | 140 | 104 | 74 | 30 | 0 | 71.15 | 1411.28 | 327.69 | 304993 | 11211 | 316204 |
| node-jsonfile | 68 | 57 | 18 | 18 | 21 | 68.42 | 730.85 | 184.62 | 52008 | 5779 | 57787 |
| plural | 153 | 100 | 70 | 30 | 0 | 70 | 1521.3 | 53.73 | 253209 | 13418 | 266627 |
| pull-stream | 351 | 280 | 164 | 96 | 20 | 65.71 | 2397.86 | 497.98 | 179699 | 30310 | 210009 |
| q | 1051 | 703 | 46 | 630 | 27 | 10.38 | 4204.99 | 4839.22 | 2042524 | 82262 | 2124786 |
| spacl-core | 134 | 80 | 63 | 17 | 0 | 78.75 | 1351.25 | 273.58 | 151851 | 10809 | 162660 |
| zip-a-folder | 49 | 39 | 19 | 17 | 3 | 56.41 | 500.62 | 219.57 | 78488 | 4403 | 82891 |
| Total | 3376 | 2334 | 1117 | 1135 | 82 | - | 22270.63 | 8479.55 | 5567656 | 275503 | 5843159 |
## Experimental Parameters
  - Model: codellama-34b-instruct
  - Temperature: 0
  - Max Tokens: 250
  - Max Nr of Prompts: 2000
  - Template: template-onemutation.hb
  - System Prompt: SystemPrompt-MutationTestingExpert.txt
  - Rate Limit: benchmark mode
  - Number of Attempts: 3


