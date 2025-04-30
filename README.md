# Play Your Part: Towards LLM role-playing agents that stick to their role

Large Language Models (LLMs) - neural networks trained as auto-regressive generative models on web-scale text datasets - can be prompted to perform various tasks, including dialogue, enabling natural, human-like interaction. To facilitate interaction with LLMs and prevent harmful behavior, complex prompts are crafted to shape the persona of the simulated character. This topic aims to address the issue of consistency and controllability in LLM agents within the challenging context of long-form interactions. We propose a dual-pronged approach. Firstly, we will explore metrics to identify and quantify deviations from desired behavior, along with the necessary evaluation sets to measure these metrics effectively. Secondly, we will delve into mitigating such deviations through the development of improved control techniques. Our methods will be based on gaining a deeper understanding of the mechanisms underlying role-playing and jailbreaking through modern mechanistic interpretability techniques, and the analysis of interaction dynamics using a model-based approach. Two applications involving long-form interaction and of significant practical relevance - multi-turn task-oriented dialogues and the simulation of doctor-patient interactions with diverse personas - will inform the design of our methods and serve as testbeds for their evaluation.

[More here](https://jsalt2025.fit.vut.cz/summer-workshop#play-your-part)


# Organization

The initial structure aims to avoid conflicts at this exploratory stage, we may revise it in the future.

The following repositories may be created:
 - **personas**: Defintion and generation of personas, scenarios and any contextual information for the dialogue generation
 - **dialogues**: Generatin of the dialogues doctor-patient themeselves
 - **evaluation**: Evaluation of dialogue quality
 - **analysis**: Code for mechanistic interpretability approaches and analysis of controlled cases aiming towards understanding agent implementation in LLMs
 
