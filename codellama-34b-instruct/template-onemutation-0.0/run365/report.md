# Report (Precomputed mutators --concurrency 1)
| Project | #Prompts | #Mutants | #Killed | #Survived | #Timeout | MutationScore | LLMorpheus Time | Stryker Time | #Prompt Tokens | #Completion Tokens | #Total Tokens  |
|:--------|:---------|:---------|:--------|:----------|----------|---------------|-----------------|--------------|----------------|--------------------|----------------|
| Complex.js | 490 | 406 | 245 | 161 | 0 | 60.34 | 2784.11 | 210.86 | 927818 | 39567 | 967385 |
| countries-and-timezones | 106 | 79 | 65 | 14 | 0 | 82.28 | 1071.07 | 117.59 | 97242 | 8518 | 105760 |
| crawler-url-parser | 176 | 86 | 50 | 36 | 0 | 58.14 | 1636.44 | 292.18 | 371967 | 15504 | 387471 |
| delta | 462 | 266 | 221 | 37 | 8 | 86.09 | 2676.03 | 1251.08 | 852830 | 37401 | 890231 |
| image-downloader | 42 | 34 | 26 | 8 | 0 | 76.47 | 430.61 | 139.23 | 21253 | 3459 | 24712 |
| node-dirty | 154 | 99 | 55 | 41 | 3 | 58.59 | 1526.39 | 77.95 | 233774 | 12906 | 246680 |
| node-geo-point | 140 | 104 | 74 | 30 | 0 | 71.15 | 1411.29 | 330.28 | 304993 | 11192 | 316185 |
| node-jsonfile | 68 | 57 | 18 | 18 | 21 | 68.42 | 690.81 | 183.43 | 52008 | 5846 | 57854 |
| plural | 153 | 100 | 70 | 30 | 0 | 70 | 1521.37 | 54.03 | 253209 | 13450 | 266659 |
| pull-stream | 351 | 280 | 165 | 95 | 20 | 66.07 | 2400.61 | 499.06 | 179699 | 30228 | 209927 |
| q | 1051 | 703 | 46 | 630 | 27 | 10.38 | 4195.04 | 4866.38 | 2042524 | 82318 | 2124842 |
| spacl-core | 134 | 80 | 63 | 17 | 0 | 78.75 | 1351.3 | 271.81 | 151851 | 10803 | 162654 |
| zip-a-folder | 49 | 39 | 19 | 17 | 3 | 56.41 | 500.63 | 219.06 | 78488 | 4405 | 82893 |
| Total | 3376 | 2333 | 1117 | 1134 | 82 | - | 22195.70 | 8512.94 | 5567656 | 275597 | 5843253 |
## Experimental Parameters
  - Model: codellama-34b-instruct
  - Temperature: 0
  - Max Tokens: 250
  - Max Nr of Prompts: 2000
  - Template: template-onemutation.hb
  - System Prompt: SystemPrompt-MutationTestingExpert.txt
  - Rate Limit: benchmark mode
  - Number of Attempts: 3


