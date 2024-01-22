# sge
SGE: a dataset of open-ended stories generated from genre-directed prompts on a generative pretrained transformer model.

# What is SGE?
A collection of language generated short stories from a genre-directed textual prompt on GPT2 with the goal of evaluating generation quality.

The dataset is formatted as a collection of json objects, each defines a prompt-story pair and a genre identification (one of fiction, comedy, fantasy, mystery, and romance) as shown in the following sample:

```json
{
    "prompt": ["p..."],
    "story": ["s..."],
    "genre": ["fiction"],
    "id": ["1"],
  },
```
