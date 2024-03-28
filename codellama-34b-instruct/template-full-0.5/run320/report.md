# Report (Precomputed mutators --concurrency 1)
| Project | #Prompts | #Mutants | #Killed | #Survived | #Timeout | MutationScore | LLMorpheus Time | Stryker Time | #Prompt Tokens | #Completion Tokens | #Total Tokens  |
|:--------|:---------|:---------|:--------|:----------|----------|---------------|-----------------|--------------|----------------|--------------------|----------------|
| Complex.js | 490 | 1182 | 730 | 452 | 0 | 61.76 | 3080.04 | 618.08 | 967508 | 102242 | 1069750 |
| countries-and-timezones | 106 | 222 | 199 | 23 | 0 | 89.64 | 1070.88 | 311.67 | 105828 | 22556 | 128384 |
| crawler-url-parser | 176 | 284 | 166 | 117 | 1 | 58.8 | 1645.9 | 965.22 | 386223 | 38423 | 424646 |
| delta | 462 | 760 | 621 | 104 | 35 | 86.32 | 2992.7 | 3820.99 | 890252 | 99184 | 989436 |
| image-downloader | 42 | 85 | 60 | 25 | 0 | 70.59 | 430.53 | 500.27 | 24655 | 9240 | 33895 |
| node-dirty | 154 | 279 | 166 | 101 | 12 | 63.8 | 1527.92 | 252.6 | 246248 | 32911 | 279159 |
| node-geo-point | 140 | 269 | 211 | 58 | 0 | 78.44 | 1740.11 | 890.54 | 289389 | 26285 | 315674 |
| node-jsonfile | 68 | 150 | 54 | 39 | 57 | 74 | 690.7 | 487.19 | 57516 | 14355 | 71871 |
| plural | 153 | 293 | 208 | 84 | 1 | 71.33 | 1677.14 | 158.69 | 249979 | 30944 | 280923 |
| pull-stream | 351 | 813 | 476 | 278 | 59 | 65.81 | 2510.3 | 1455.39 | 208130 | 75369 | 283499 |
| q | 1051 | 2057 | 143 | 1838 | 76 | 10.65 | 5453.21 | 14010.8 | 2127655 | 217999 | 2345654 |
| spacl-core | 134 | 260 | 217 | 42 | 1 | 83.85 | 1351.08 | 861.29 | 162705 | 28654 | 191359 |
| zip-a-folder | 49 | 114 | 31 | 4 | 79 | 96.49 | 500.56 | 1278.26 | 82457 | 10677 | 93134 |
| Total | 3376 | 6768 | 3282 | 3165 | 321 | - | 24671.07 | 25610.99 | 5798545 | 708839 | 6507384 |
## Experimental Parameters
  - Model: codellama-34b-instruct
  - Temperature: 0.5
  - Max Tokens: 250
  - Max Nr of Prompts: 2000
  - Template: template-full.hb
  - System Prompt: SystemPrompt-MutationTestingExpert.txt
  - Rate Limit: benchmark mode
  - Number of Attempts: 3


