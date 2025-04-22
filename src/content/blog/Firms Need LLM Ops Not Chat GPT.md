---
title: Firms Need LLM Ops Not Chat GPT
description: If you can't measure something, how do you know its helping?
pubDate: 2023-07-03
share: "true"
---
TLDR: Chat GPT responses have inherent unpredictability. To manage this, you need to understand it. For that you need ML/LLM Ops


At this point there are 3 groups of people: 
1) People who use Generative AI every day
2) People who are thinking of it
3) People who are tired of hearing about it

Dread it. Run from it. Gen AI talking points appear all the same. 

To avoid following the bandwagon, I've been spending the past several months working with LLMs. I've written summarizers, 



Going from PoC to production ready system though, that's not as easy.

I have been using Gen AI extensively since Chat GPT showed up. I regret not having taken a look at it sooner. 




Sources: 
https://twitter.com/swyx/status/1672686090589990912

Anrej Karpathy saying: you should work on AI agents.
Then also saying: "... large class of problems that I think are very easy, to imagine, very easy to build demos for, but are actually extremely hard to make products out of."
![[Pasted image 20230704110058.png|Pasted image 20230704110058.png]]

![[Pasted image 20230704105656.png|Pasted image 20230704105656.png]]


Similarly: 

"we were all hacking together at the AGI house which is a collective of a very talented AI researchers data scientists machine learning engineers and we all spent a Saturday trying to hack together um some cool projects all involving agents so for some contexts um we uh everyone on the team has tried agents and we've all come to the conclusion that they suck uh it's just

![[Pasted image 20230704120558.png|Pasted image 20230704120558.png]]

![[Pasted image 20230704120630.png|Pasted image 20230704120630.png]]

https://github.com/tensorchord/Awesome-LLMOps#llmops
https://cyces.co/blog/llmops-explained
https://github.com/deepset-ai/haystack/discussions

Logging
https://github.com/whylabs/langkit
https://whylogs.readthedocs.io/en/latest/

Automated Test cases
https://github.com/promptfoo/promptfoo

Prompt Evaluation
https://www.ianww.com/blog/2023/05/21/prompt-engineering-framework

YC Batch winter 23
https://www.ignorance.ai/p/analyzing-over-100-ai-startups-from-yc

112 out of 266 companies were AI/ML related
## Why do we need a system?

Mitchell Hashimoto [coined](https://mitchellh.com/writing/prompt-engineering-vs-blind-prompting) the term _blind prompting_ to describe the default trial-and-error approach to prompt engineering. If Twitter and Hacker News are any indication, this is what most of us are doing today.



https://explodinggradients.com/all-about-evaluating-large-language-models

https://eugeneyan.com/writing/abstractive/

https://huyenchip.com/2023/04/11/llm-engineering.html

https://www.theregister.com/2023/08/07/chatgpt_stack_overflow_ai/
https://github.com/tensorchord/Awesome-LLMOps

https://huyenchip.com/2023/08/16/llm-research-open-challenges.html

- [Survey of Hallucination in Natural Language Generation](https://arxiv.org/abs/2202.03629) (Ji et al., 2022)
- [How Language Model Hallucinations Can Snowball](https://arxiv.org/abs/2305.13534) (Zhang et al., 2023)
- [A Multitask, Multilingual, Multimodal Evaluation of ChatGPT on Reasoning, Hallucination, and Interactivity](https://arxiv.org/abs/2302.04023) (Bang et al., 2023)
- [Contrastive Learning Reduces Hallucination in Conversations](https://arxiv.org/abs/2212.10400) (Sun et al., 2022)
- [Self-Consistency Improves Chain of Thought Reasoning in Language Models](https://arxiv.org/abs/2203.11171) (Wang et al., 2022)
- [SelfCheckGPT: Zero-Resource Black-Box Hallucination Detection for Generative Large Language Models](https://arxiv.org/abs/2303.08896) (​​Manakul et al., 2023)
- A simple example of fact-checking and hallucination by [NVIDIA’s NeMo-Guardrails](https://github.com/NVIDIA/NeMo-Guardrails/blob/main/examples/grounding_rail/README.md#grounding-fact-checking-and-hallucination)
https://wandb.ai/ayush-thakur/llm-eval-sweep/reports/How-to-Evaluate-Compare-and-Optimize-LLM-Systems--Vmlldzo0NzgyMTQz#2.-human-annotation,-a.k.a.-supervised-evaluation

https://kth.diva-portal.org/smash/get/diva2:1787721/FULLTEXT01.pdf

https://kth.diva-portal.org/smash/get/diva2:1787721/FULLTEXT01.pdfz

3.1.2 Evaluation Design The process of designing the zero-shot evaluation involved two key steps: 
1. Designing and conducting initial testing of evaluation questions to assess model performance. 
2. Finalizing a set of binary questions to evaluate whether the generated summaries fulfill the requirements based on the desired summary definition.
![[Pasted image 20231113161459.png|Pasted image 20231113161459.png]]

https://www.oreilly.com/radar/what-we-learned-from-a-year-of-building-with-llms-part-i/