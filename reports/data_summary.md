# Data summary

## BIRD Mini-Dev (SQLite), 500 questions
BIRD labels difficulty as simple / moderate / challenging (not easy / moderate / hard).

- challenging: 102
- moderate: 250
- simple: 148

Average schema length (tiktoken cl100k_base): 786 tokens per database (11 databases), 833 tokens per question.

## HotpotQA distractor dev, 7405 questions

- bridge: 5918
- comparison: 1487

## Samples (seed 42)
- data/bird_sample_150.json: 44 simple, 75 moderate, 31 challenging
- data/hotpot_sample_150.json: 120 bridge, 30 comparison
