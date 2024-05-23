---
layout: default
---
Join our discord <a href="https://discord.gg/fjqSbGDn">here</a> !

<p style='text-align: justify;'>
Training high-performing large language models (LLMs) from scratch is a notoriously expensive and difficult task, costing hundreds of millions of dollars in compute alone. These pretrained LLMs, however, can cheaply and easily be adapted to new tasks via fine-tuning, leading to a proliferation of models that suit specific use cases. Recent work has shown that specialized fine-tuned models can be rapidly **merged** to combine capabilities and generalize to new skills. 
</p>

<br>

This raises the question: given a new suite of desired skills and design parameters, is it necessary to fine-tune or train yet another LLM from scratch, or can similar existing models be re-purposed for a new task with the right selection or merging procedure? 

<br>





<p style='text-align: justify;'>

The LLM Merging challenge aims to spur the development and evaluation of methods for merging and reusing existing models to form stronger new models without needing additional training. Specifically, the competition focuses on merging existing publicly-released expert models from Huggingface, using only minimal compute and additional parameters. The goal will be to develop merged models that outperform existing models and existing merging baselines. Submissions will be judged based on the average accuracy on a set of held-out multiple-choice evaluation tasks. 
To make the competition as accessible as possible and ensure that the merging procedures are more efficient than fine-tuning, we will enforce a compute budget and focus on merging models with fewer than 8B parameters. A starter kit with all necessary materials (baseline implementations, requirements, the evaluation script, etc.) will be released on May 1st. 
</p>

More details will be released soon!
