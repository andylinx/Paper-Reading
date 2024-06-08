### Understanding Information Storage and Transfer in Multi-modal Large Language Models

1. Raise a method that extends causal information tracing from pure language to the multi-modal setting.

​		e.g. What movie directed by the director in this photo has won a Golden Globe?

2. Though VQA-Constraints, find out that MLLMs rely on **MLP and self-attention blocks in much earlier layers** for information storage compared to LLMs whose mid-layer MLPs are more important.

3. A consistent small subset of visual tokens output by the vision encoder are responsible for transferring information from the image to these causal blocks.

通过有限制的VQA问题来探究MLLM的主要信息存储位置在浅层的MLP和自注意力block，且visual tokens的一个固定的子集占主导地位。

