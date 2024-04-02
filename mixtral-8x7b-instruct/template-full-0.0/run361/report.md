# Report (Precomputed mutators --concurrency 1)
| Project | #Prompts | #Mutants | #Killed | #Survived | #Timeout | MutationScore | LLMorpheus Time | Stryker Time | #Prompt Tokens | #Completion Tokens | #Total Tokens  |
|:--------|:---------|:---------|:--------|:----------|----------|---------------|-----------------|--------------|----------------|--------------------|----------------|
| Complex.js | 490 | 989 | 608 | 381 | 0 | 61.48 | 3372.45 | 520.01 | 960545 | 98260 | 1058805 |
| countries-and-timezones | 106 | 196 | 157 | 39 | 0 | 80.1 | 1071.57 | 285.14 | 104291 | 22228 | 126519 |
| crawler-url-parser | 176 | 211 | 114 | 97 | 0 | 54.03 | 1669.78 | 698.95 | 384404 | 32771 | 417175 |
| delta | 462 | 666 | 509 | 123 | 34 | 81.53 | 3199.74 | 3398.17 | 882477 | 89050 | 971527 |
| image-downloader | 42 | 65 | 42 | 23 | 0 | 64.62 | 432.08 | 378.08 | 24140 | 8005 | 32145 |
| node-dirty | 154 | 209 | 125 | 76 | 8 | 63.64 | 1554.61 | 185.18 | 242671 | 26837 | 269508 |
| node-geo-point | 140 | 257 | 180 | 77 | 0 | 70.04 | 1416.99 | 850.15 | 318251 | 28316 | 346567 |
| node-jsonfile | 68 | 129 | 56 | 27 | 46 | 79.07 | 740.68 | 431.76 | 56273 | 12101 | 68374 |
| plural | 153 | 232 | 174 | 58 | 0 | 75 | 1546.99 | 120.7 | 261626 | 25293 | 286919 |
| pull-stream | 351 | 694 | 402 | 243 | 49 | 64.99 | 2660.01 | 1259.31 | 204431 | 70142 | 274573 |
| q | 1051 | 1609 | 114 | 1423 | 72 | 11.56 | 6149.24 | 11173.93 | 2103232 | 188223 | 2291455 |
| spacl-core | 134 | 158 | 135 | 22 | 1 | 86.08 | 1416.02 | 534.7 | 162695 | 26751 | 189446 |
| zip-a-folder | 49 | 86 | 32 | 46 | 8 | 46.51 | 500.53 | 489.08 | 81279 | 9372 | 90651 |
| Total | 3376 | 5501 | 2648 | 2635 | 218 | - | 25730.69 | 20325.16 | 5786315 | 637349 | 6423664 |
## Experimental Parameters
  - Model: mixtral-8x7b-instruct
  - Temperature: 0
  - Max Tokens: 250
  - Max Nr of Prompts: 2000
  - Template: template-full.hb
  - System Prompt: SystemPrompt-MutationTestingExpert.txt
  - Rate Limit: benchmark mode
  - Number of Attempts: 3


