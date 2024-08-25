# Tokenizer git repo -  repo helps to understand the tokenizers for LLM.
- majorly used method is [Byte Pair Encoding](https://en.wikipedia.org/wiki/Byte_pair_encoding)

## Why tokenizer is important?
- Why can't LLM spell words? Tokenization.
- Why can't LLM do super simple string processing tasks like reversing a string? Tokenization.
- Why is LLM worse at non-English languages (e.g. Japanese)? Tokenization.
- Why is LLM bad at simple arithmetic? Tokenization.
- Why did GPT-2 have more than necessary trouble coding in Python? Tokenization.
- Why did my LLM abruptly halt when it sees the string "<|endoftext|>"? Tokenization.
- What is this weird warning I get about a "trailing whitespace"? Tokenization.
- Why the LLM break if I ask it about "SolidGoldMagikarp"? Tokenization.
- Why should I prefer to use YAML over JSON with LLMs? Tokenization.
- Why is LLM not actually end-to-end language modeling? Tokenization.
- What is the real root of suffering? Tokenization.

## Expand tokenizer?
- To expand the existing tokenizer need lot of training data to get to meaning full embedding vector from random initialization.
- Always recommended to go with the tokenizer which have the character related to your language already into it.
  - e.g. gemma 7B tokenizer have 0.09% of the characters from the Telagu language (no combination/merging), still it is best to take it and ahead rather than expanding the tokenizer.


## In this repo
- tokeniser_Gemma_7B.ipynb
  - Analyse the tokenizer for Telagu, Hindi, Tamil, Chinese languages.



## References
- [Andrej Karpathy LLM Tokenization](https://youtu.be/zduSFxRajkE?t=6711)
- [Practical LLM by Ramsri](https://www.youtube.com/watch?v=HYmcb_DMDTs&t=874s)