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
The initial version of the dataset contains 50 short stories.

# Download SGE
The single file to download the entire data is [prompt_story.json](prompt_story.json).

# Paper
Details of data construction and performance analyses are available in our companion paper:

- Avi Bleiweiss. *Commonsense Knowledge Transfer from Authored to Prompt-based
Generated Short Stories*. In BShalem, 2024.

