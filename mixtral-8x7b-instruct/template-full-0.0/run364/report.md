# Report (Precomputed mutators --concurrency 1)
| Project | #Prompts | #Mutants | #Killed | #Survived | #Timeout | MutationScore | LLMorpheus Time | Stryker Time | #Prompt Tokens | #Completion Tokens | #Total Tokens  |
|:--------|:---------|:---------|:--------|:----------|----------|---------------|-----------------|--------------|----------------|--------------------|----------------|
| Complex.js | 490 | 969 | 580 | 389 | 0 | 59.86 | 3649.24 | 528.79 | 960545 | 98038 | 1058583 |
| countries-and-timezones | 106 | 199 | 156 | 43 | 0 | 78.39 | 1087.49 | 295.42 | 104291 | 22259 | 126550 |
| crawler-url-parser | 176 | 212 | 117 | 95 | 0 | 55.19 | 1672.78 | 705.16 | 384404 | 32640 | 417044 |
| delta | 462 | 674 | 521 | 116 | 37 | 82.79 | 3494.16 | 3421.43 | 882477 | 90244 | 972721 |
| image-downloader | 42 | 66 | 42 | 24 | 0 | 63.64 | 430.5 | 378.73 | 24140 | 8213 | 32353 |
| node-dirty | 154 | 208 | 124 | 73 | 11 | 64.9 | 1530.34 | 197.97 | 244297 | 26982 | 271279 |
| node-geo-point | 140 | 258 | 176 | 82 | 0 | 68.22 | 1432.72 | 865 | 318251 | 28015 | 346266 |
| node-jsonfile | 68 | 121 | 50 | 25 | 46 | 79.34 | 702.02 | 419.4 | 56273 | 11348 | 67621 |
| plural | 153 | 232 | 177 | 55 | 0 | 76.29 | 1533.26 | 118.22 | 261626 | 25664 | 287290 |
| pull-stream | 351 | 678 | 390 | 242 | 46 | 64.31 | 2763.15 | 1206.16 | 204431 | 69471 | 273902 |
| q | 1051 | 1644 | 117 | 1455 | 72 | 11.5 | 6879.9 | 11339.61 | 2103232 | 191046 | 2294278 |
| spacl-core | 134 | 156 | 134 | 21 | 1 | 86.54 | 1409.48 | 527.44 | 162695 | 26807 | 189502 |
| zip-a-folder | 49 | 75 | 25 | 42 | 8 | 44 | 500.54 | 444.67 | 81279 | 9009 | 90288 |
| Total | 3376 | 5492 | 2609 | 2662 | 221 | - | 27085.58 | 20448.00 | 5787941 | 639736 | 6427677 |
## Experimental Parameters
  - Model: mixtral-8x7b-instruct
  - Temperature: 0
  - Max Tokens: 250
  - Max Nr of Prompts: 2000
  - Template: template-full.hb
  - System Prompt: SystemPrompt-MutationTestingExpert.txt
  - Rate Limit: benchmark mode
  - Number of Attempts: 3


