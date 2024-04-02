# Report (Precomputed mutators --concurrency 1)
| Project | #Prompts | #Mutants | #Killed | #Survived | #Timeout | MutationScore | LLMorpheus Time | Stryker Time | #Prompt Tokens | #Completion Tokens | #Total Tokens  |
|:--------|:---------|:---------|:--------|:----------|----------|---------------|-----------------|--------------|----------------|--------------------|----------------|
| Complex.js | 490 | 969 | 587 | 382 | 0 | 60.58 | 3511.86 | 522.92 | 960545 | 96846 | 1057391 |
| countries-and-timezones | 106 | 203 | 160 | 43 | 0 | 78.82 | 1073.78 | 299 | 104291 | 22090 | 126381 |
| crawler-url-parser | 176 | 220 | 118 | 102 | 0 | 53.64 | 1664.52 | 748.35 | 384404 | 32721 | 417125 |
| delta | 462 | 660 | 500 | 126 | 34 | 80.91 | 3343.71 | 3332.02 | 882477 | 88421 | 970898 |
| image-downloader | 42 | 64 | 41 | 23 | 0 | 64.06 | 440.52 | 362.2 | 24140 | 7972 | 32112 |
| node-dirty | 154 | 203 | 120 | 77 | 6 | 62.07 | 1532.4 | 164.86 | 244297 | 26801 | 271098 |
| node-geo-point | 140 | 258 | 178 | 80 | 0 | 68.99 | 1436.26 | 842.23 | 318251 | 28074 | 346325 |
| node-jsonfile | 68 | 135 | 56 | 32 | 47 | 76.3 | 692.85 | 440.06 | 56273 | 12731 | 69004 |
| plural | 153 | 232 | 171 | 61 | 0 | 73.71 | 1525.78 | 117.87 | 261626 | 25198 | 286824 |
| pull-stream | 351 | 687 | 398 | 245 | 44 | 64.34 | 2725.42 | 1227.21 | 204431 | 70751 | 275182 |
| q | 1051 | 1660 | 116 | 1477 | 67 | 11.02 | 6622.34 | 11507.75 | 2103232 | 194705 | 2297937 |
| spacl-core | 134 | 157 | 134 | 22 | 1 | 85.99 | 1359.32 | 532.62 | 162695 | 26100 | 188795 |
| zip-a-folder | 49 | 78 | 27 | 42 | 9 | 46.15 | 500.56 | 463.12 | 81279 | 9118 | 90397 |
| Total | 3376 | 5526 | 2606 | 2712 | 208 | - | 26429.32 | 20560.21 | 5787941 | 641528 | 6429469 |
## Experimental Parameters
  - Model: mixtral-8x7b-instruct
  - Temperature: 0
  - Max Tokens: 250
  - Max Nr of Prompts: 2000
  - Template: template-full.hb
  - System Prompt: SystemPrompt-MutationTestingExpert.txt
  - Rate Limit: benchmark mode
  - Number of Attempts: 3


