# Report (Precomputed mutators --concurrency 1)
| Project | #Prompts | #Mutants | #Killed | #Survived | #Timeout | MutationScore | LLMorpheus Time | Stryker Time | #Prompt Tokens | #Completion Tokens | #Total Tokens  |
|:--------|:---------|:---------|:--------|:----------|----------|---------------|-----------------|--------------|----------------|--------------------|----------------|
| Complex.js | 490 | 980 | 594 | 386 | 0 | 60.61 | 3359.29 | 519.5 | 960545 | 96727 | 1057272 |
| countries-and-timezones | 106 | 197 | 154 | 43 | 0 | 78.17 | 1074.42 | 277.16 | 104291 | 22353 | 126644 |
| crawler-url-parser | 176 | 223 | 121 | 102 | 0 | 54.26 | 1661.26 | 731.82 | 384404 | 32772 | 417176 |
| delta | 462 | 660 | 497 | 129 | 34 | 80.45 | 3170.76 | 3384.81 | 882477 | 89334 | 971811 |
| image-downloader | 42 | 67 | 41 | 26 | 0 | 61.19 | 430.53 | 386.39 | 24140 | 7934 | 32074 |
| node-dirty | 154 | 213 | 123 | 81 | 9 | 61.97 | 1530.96 | 182.12 | 244297 | 27524 | 271821 |
| node-geo-point | 140 | 254 | 177 | 77 | 0 | 69.69 | 1413.38 | 829.76 | 318251 | 27995 | 346246 |
| node-jsonfile | 68 | 126 | 52 | 24 | 50 | 80.95 | 690.64 | 444.51 | 56273 | 11970 | 68243 |
| plural | 153 | 229 | 169 | 60 | 0 | 73.8 | 1524.56 | 117.41 | 261626 | 25277 | 286903 |
| pull-stream | 351 | 671 | 389 | 236 | 46 | 64.83 | 2644.38 | 1205.37 | 204431 | 69081 | 273512 |
| q | 1051 | 1658 | 115 | 1477 | 66 | 10.92 | 6079.84 | 11465.34 | 2103232 | 192672 | 2295904 |
| spacl-core | 134 | 159 | 134 | 24 | 1 | 84.91 | 1354.6 | 540.52 | 162695 | 26151 | 188846 |
| zip-a-folder | 49 | 81 | 23 | 51 | 7 | 37.04 | 500.6 | 464.06 | 81279 | 9340 | 90619 |
| Total | 3376 | 5518 | 2589 | 2716 | 213 | - | 25435.22 | 20548.77 | 5787941 | 639130 | 6427071 |
## Experimental Parameters
  - Model: mixtral-8x7b-instruct
  - Temperature: 0
  - Max Tokens: 250
  - Max Nr of Prompts: 2000
  - Template: template-full.hb
  - System Prompt: SystemPrompt-MutationTestingExpert.txt
  - Rate Limit: benchmark mode
  - Number of Attempts: 3


