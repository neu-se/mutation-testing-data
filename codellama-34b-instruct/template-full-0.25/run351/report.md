# Report (Precomputed mutators --concurrency 1)
| Project | #Prompts | #Mutants | #Killed | #Survived | #Timeout | MutationScore | LLMorpheus Time | Stryker Time | #Prompt Tokens | #Completion Tokens | #Total Tokens  |
|:--------|:---------|:---------|:--------|:----------|----------|---------------|-----------------|--------------|----------------|--------------------|----------------|
| Complex.js | 490 | 1195 | 737 | 457 | 1 | 61.76 | 3026.34 | 650.01 | 967508 | 101118 | 1068626 |
| countries-and-timezones | 106 | 215 | 189 | 26 | 0 | 87.91 | 1070.91 | 309.33 | 105828 | 23331 | 129159 |
| crawler-url-parser | 176 | 247 | 144 | 103 | 0 | 58.3 | 1644.86 | 811.88 | 386223 | 39215 | 425438 |
| delta | 462 | 776 | 647 | 100 | 29 | 87.11 | 2962.02 | 3896.15 | 890252 | 99274 | 989526 |
| image-downloader | 42 | 87 | 71 | 16 | 0 | 81.61 | 430.54 | 373.38 | 24655 | 9163 | 33818 |
| node-dirty | 154 | 274 | 162 | 100 | 12 | 63.5 | 1526.45 | 247.44 | 246248 | 32894 | 279142 |
| node-geo-point | 140 | 294 | 218 | 76 | 0 | 74.15 | 1421.09 | 935.39 | 316333 | 29830 | 346163 |
| node-jsonfile | 68 | 154 | 55 | 43 | 56 | 72.08 | 690.68 | 504.57 | 57516 | 14702 | 72218 |
| plural | 153 | 286 | 204 | 81 | 1 | 71.68 | 1521.32 | 151.42 | 265602 | 33298 | 298900 |
| pull-stream | 351 | 773 | 442 | 280 | 51 | 63.78 | 2497.56 | 1351.06 | 208130 | 76100 | 284230 |
| q | 1051 | 2002 | 146 | 1780 | 76 | 11.09 | 5341.32 | 13704.14 | 2127655 | 218805 | 2346460 |
| spacl-core | 134 | 228 | 193 | 35 | 0 | 84.65 | 1351.03 | 756.66 | 162705 | 28939 | 191644 |
| zip-a-folder | 49 | 98 | 24 | 3 | 71 | 96.94 | 500.57 | 1119.7 | 82457 | 10786 | 93243 |
| Total | 3376 | 6629 | 3232 | 3100 | 297 | - | 23984.69 | 24811.13 | 5841112 | 717455 | 6558567 |
## Experimental Parameters
  - Model: codellama-34b-instruct
  - Temperature: 0.25
  - Max Tokens: 250
  - Max Nr of Prompts: 2000
  - Template: template-full.hb
  - System Prompt: SystemPrompt-MutationTestingExpert.txt
  - Rate Limit: benchmark mode
  - Number of Attempts: 3


