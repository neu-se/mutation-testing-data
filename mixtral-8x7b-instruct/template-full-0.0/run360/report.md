# Report (Precomputed mutators --concurrency 1)
| Project | #Prompts | #Mutants | #Killed | #Survived | #Timeout | MutationScore | LLMorpheus Time | Stryker Time | #Prompt Tokens | #Completion Tokens | #Total Tokens  |
|:--------|:---------|:---------|:--------|:----------|----------|---------------|-----------------|--------------|----------------|--------------------|----------------|
| Complex.js | 490 | 962 | 589 | 373 | 0 | 61.23 | 3756.38 | 507.41 | 960545 | 96072 | 1056617 |
| countries-and-timezones | 106 | 205 | 166 | 39 | 0 | 80.98 | 1080.09 | 296.25 | 104291 | 22693 | 126984 |
| crawler-url-parser | 176 | 234 | 130 | 104 | 0 | 55.56 | 1697.04 | 762.88 | 384404 | 33495 | 417899 |
| delta | 462 | 680 | 516 | 128 | 36 | 81.18 | 3636.95 | 3476.06 | 882477 | 90094 | 972571 |
| image-downloader | 42 | 69 | 46 | 23 | 0 | 66.67 | 430.46 | 387.36 | 24140 | 8238 | 32378 |
| node-dirty | 154 | 191 | 111 | 72 | 8 | 62.3 | 1665.69 | 159.16 | 234503 | 24705 | 259208 |
| node-geo-point | 140 | 247 | 166 | 81 | 0 | 67.21 | 1497.29 | 833.16 | 315891 | 27864 | 343755 |
| node-jsonfile | 68 | 132 | 54 | 32 | 46 | 75.76 | 691.9 | 425.95 | 56273 | 12371 | 68644 |
| plural | 153 | 226 | 166 | 60 | 0 | 73.45 | 1583.06 | 115.03 | 259916 | 25067 | 284983 |
| pull-stream | 351 | 678 | 386 | 248 | 44 | 63.42 | 2802.21 | 1201.97 | 204431 | 70423 | 274854 |
| q | 1051 | 1643 | 112 | 1460 | 71 | 11.14 | 7003.28 | 11371.39 | 2103232 | 192284 | 2295516 |
| spacl-core | 134 | 157 | 134 | 22 | 1 | 85.99 | 1369.93 | 534.67 | 162695 | 26484 | 189179 |
| zip-a-folder | 49 | 78 | 24 | 44 | 10 | 43.59 | 506.29 | 470.28 | 81279 | 9124 | 90403 |
| Total | 3376 | 5502 | 2600 | 2686 | 216 | - | 27720.57 | 20541.57 | 5774077 | 638914 | 6412991 |
## Experimental Parameters
  - Model: mixtral-8x7b-instruct
  - Temperature: 0
  - Max Tokens: 250
  - Max Nr of Prompts: 2000
  - Template: template-full.hb
  - System Prompt: SystemPrompt-MutationTestingExpert.txt
  - Rate Limit: benchmark mode
  - Number of Attempts: 3


