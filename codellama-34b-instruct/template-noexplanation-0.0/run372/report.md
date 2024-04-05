# Report (Precomputed mutators --concurrency 1)
| Project | #Prompts | #Mutants | #Killed | #Survived | #Timeout | MutationScore | LLMorpheus Time | Stryker Time | #Prompt Tokens | #Completion Tokens | #Total Tokens  |
|:--------|:---------|:---------|:--------|:----------|----------|---------------|-----------------|--------------|----------------|--------------------|----------------|
| Complex.js | 490 | 1125 | 676 | 448 | 1 | 60.18 | 3056.33 | 600.05 | 948398 | 75551 | 1023949 |
| countries-and-timezones | 106 | 211 | 183 | 28 | 0 | 86.73 | 1070.68 | 309.71 | 101694 | 23742 | 125436 |
| crawler-url-parser | 176 | 239 | 140 | 99 | 0 | 58.58 | 1656.21 | 778.34 | 379359 | 31115 | 410474 |
| delta | 462 | 734 | 598 | 110 | 26 | 85.01 | 2870.28 | 3625.25 | 872234 | 64880 | 937114 |
| image-downloader | 42 | 77 | 62 | 15 | 0 | 80.52 | 430.47 | 329.74 | 23017 | 9110 | 32127 |
| node-dirty | 154 | 258 | 146 | 99 | 13 | 61.63 | 1526.57 | 243.81 | 240242 | 24279 | 264521 |
| node-geo-point | 140 | 297 | 216 | 81 | 0 | 72.73 | 1411.01 | 1009.62 | 310873 | 26100 | 336973 |
| node-jsonfile | 68 | 152 | 54 | 45 | 53 | 70.39 | 690.59 | 482.67 | 54864 | 15154 | 70018 |
| plural | 153 | 273 | 198 | 74 | 1 | 72.89 | 1522.48 | 146.41 | 259635 | 26465 | 286100 |
| pull-stream | 351 | 774 | 440 | 278 | 56 | 64.08 | 2632.74 | 1388.06 | 194441 | 73821 | 268262 |
| q | 1051 | 1856 | 138 | 1635 | 83 | 11.91 | 4694.78 | 12908.57 | 2086666 | 127647 | 2214313 |
| spacl-core | 134 | 211 | 175 | 35 | 1 | 83.41 | 1350.87 | 711.26 | 157479 | 28201 | 185680 |
| zip-a-folder | 49 | 98 | 27 | 3 | 68 | 96.94 | 500.54 | 1097.23 | 80546 | 10243 | 90789 |
| Total | 3376 | 6305 | 3053 | 2950 | 302 | - | 23413.55 | 23630.72 | 5709448 | 536308 | 6245756 |
## Experimental Parameters
  - Model: codellama-34b-instruct
  - Temperature: 0
  - Max Tokens: 250
  - Max Nr of Prompts: 2000
  - Template: template-noexplanation.hb
  - System Prompt: SystemPrompt-MutationTestingExpert.txt
  - Rate Limit: benchmark mode
  - Number of Attempts: 3


