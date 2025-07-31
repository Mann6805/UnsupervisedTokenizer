# UnsupervisedTokenizer

Inspired by NLTK, this project explores a different way to split text into tokens — using unsupervised learning instead of rule-based logic.

## Why This?

Most tokenizers work well when the text is clean and predictable. But in the real world, text can be messy, inconsistent, and full of edge cases — from abbreviations like "Dr." to punctuation that changes meaning based on context.

The idea here is to see if a system can learn where token boundaries are by spotting patterns in how text behaves, without relying on predefined grammar or regular expressions.

## What It's Trying to Do

- Analyze how characters and words appear in natural language
- Detect patterns or shifts that might suggest where one token ends and another begins
- Build a tokenizer that learns from the data itself, rather than relying on fixed rules

## What's Planned

Here’s the plan:
- Gather and clean real-world text data
- Explore how token boundaries can be inferred statistically or structurally
- Use anomaly detection or sequence modeling to predict likely breakpoints
- Compare the result to standard tokenizers like NLTK

## Where Things Stand

The core idea is defined and early experimentation is in progress. The focus now is on identifying the signals that help distinguish true boundaries — without external labels or handcrafted logic.

## The Bigger Picture

This project is part of a broader effort to make NLP tools more flexible and adaptive. The goal is to reduce reliance on fixed rules and instead create systems that learn from data — even when the data is messy or unpredictable.
