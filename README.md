# AMwithLlama3

## Abstract
An end-to-end argument mining (AM) pipeline takes a text as input and provides the argumentative structure of this text as output, by identifying and classifying the argument units and relations within it. Here, we consider an LLM fine-tuning approach to AM. We model the three sub-tasks of the AM pipeline as text generation tasks. We fine-tune classical and quantized versions of LLaMA--3, the most capable open-source model available, on the benchmark Persuasive Essays (PE) dataset. We consider various contextual and structural fine-tuning modalities, where the AM sub-tasks are modeled either at the paragraph or at the essay level, with or without inclusion of additional markup tags. We achieve state-of-the-art results on all three sub-tasks, with significant improvements over previous benchmarks.


