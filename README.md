# LLM-fine-tuning
Fine tuning of local LLMs based on the deeplearning.ai course

The repository is built based on https://github.com/Ryota-Kawamura/Generative-AI-with-LLMs/

1. __summarizing_dialogue.ipynb__: Notebook showcases how you can get different outputs from an LLM based on prompt engineering. Furthermore, basic concepts like one-shot and few-shot inference are shown.

2. __fine_tuning_llm.ipynb__: This notebook showcases 2 techniques for fine-tuning LLMs:

    2a. __Instruction Fine Tuning__: This technique performs a full parameter tuning by taking a wide set of examples associated with the custom task at hand.

    2b. __Parameter Efficient Fine Tuning__: Fine tune the LLM using the LoRA technique to allow for a much smaller set of parameters to be fine-tuned. LoRA is not only much more faster but does not suffer from problems like catastrophic forgetting