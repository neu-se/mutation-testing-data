# Report (Precomputed mutators --concurrency 1)
| Project | #Prompts | #Mutants | #Killed | #Survived | #Timeout | MutationScore | LLMorpheus Time | Stryker Time | #Prompt Tokens | #Completion Tokens | #Total Tokens  |
|:--------|:---------|:---------|:--------|:----------|----------|---------------|-----------------|--------------|----------------|--------------------|----------------|
| Complex.js | 490 | 1028 | 648 | 379 | 1 | 63.13 | 3090.47 | 545.31 | 967508 | 101516 | 1069024 |
| countries-and-timezones | 106 | 186 | 156 | 30 | 0 | 83.87 | 1070.88 | 268.04 | 105828 | 23041 | 128869 |
| crawler-url-parser | 176 | 278 | 202 | 76 | 0 | 72.66 | 1786.52 | 902.86 | 377644 | 36825 | 414469 |
| delta | 462 | 698 | 583 | 83 | 32 | 88.11 | 3134.68 | 3531.25 | 877266 | 93814 | 971080 |
| image-downloader | 42 | 75 | 53 | 22 | 0 | 70.67 | 430.55 | 457.54 | 24655 | 9002 | 33657 |
| node-dirty | 154 | 246 | 150 | 84 | 12 | 65.85 | 1526.84 | 215.86 | 246248 | 32721 | 278969 |
| node-geo-point | 140 | 273 | 213 | 60 | 0 | 78.02 | 1411.05 | 897.39 | 316333 | 29494 | 345827 |
| node-jsonfile | 68 | 132 | 50 | 22 | 60 | 83.33 | 710.73 | 477.34 | 57516 | 14447 | 71963 |
| plural | 153 | 299 | 229 | 69 | 1 | 76.92 | 1533.27 | 157.43 | 265602 | 31993 | 297595 |
| pull-stream | 351 | 743 | 461 | 235 | 47 | 68.37 | 2504.2 | 1268.62 | 208130 | 73625 | 281755 |
| q | 1051 | 1899 | 147 | 1671 | 81 | 12.01 | 5355.1 | 13120.09 | 2127655 | 213824 | 2341479 |
| spacl-core | 134 | 218 | 180 | 38 | 0 | 82.57 | 1351.04 | 679.82 | 162705 | 28574 | 191279 |
| zip-a-folder | 49 | 96 | 54 | 38 | 4 | 60.42 | 500.58 | 493.11 | 82457 | 10747 | 93204 |
| Total | 3376 | 6171 | 3126 | 2807 | 238 | - | 24405.91 | 23014.66 | 5819547 | 699623 | 6519170 |
## Experimental Parameters
  - Model: codellama-34b-instruct
  - Temperature: 1
  - Max Tokens: 250
  - Max Nr of Prompts: 2000
  - Template: template-full.hb
  - System Prompt: SystemPrompt-MutationTestingExpert.txt
  - Rate Limit: benchmark mode
  - Number of Attempts: 3


