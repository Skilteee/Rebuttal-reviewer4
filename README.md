**Table R.8.** Finetuning Llama2-7B on Alpaca GPT-4 dataset and then evaluation.
|           | MT-Bench |  MMLU | GPU hours |
|-----------|:--------:|:-----:|:---------:|
| Zero-shot |   3.93   | 45.87 |     -     |
| MeZO      |   4.59   | 45.22 |    100%   |
| HiZOO     |   4.64   | 45.42 |    92%    |
| DiZOO     |   **4.79**   | **45.91** |    **78%**    |

**Table R.9.** Finetuning Llama3-8B on Alpaca GPT-4 dataset and then evaluation.
|           | MT-Bench |  MMLU(5 shot) | GPU hours |
|-----------|:--------:|:-----:|:---------:|
| Zero-shot |   5.46   | 65.20 |     -     |
| MeZO      |   5.89   | 65.08 |    100%   |
| HiZOO     |   5.93   | 65.20 |    95%    |
| DiZOO     |   **6.15**   | **65.42** |    **83%**    |

