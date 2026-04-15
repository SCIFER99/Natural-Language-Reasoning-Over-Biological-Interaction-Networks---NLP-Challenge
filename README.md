# Natural-Language-Reasoning-Over-Biological-Interaction-Networks---NLP-Challenge
This was a Natural Language Processing (NLP) benchmark competition on who can generate the most accurate reasoning on a Biological dataset.

# Overview
This challenge evaluates the ability of AI systems to perform logical reasoning from natural language descriptions. Each example describes a biological interaction system in text. The description specifies entities (such as species, proteins, or microbial strains), rules governing their interactions, and a set of observed relationships.

The goal is to determine whether the system described in the text is logically consistent. In other words, does there exist a complete interaction network that satisfies all rules and observations described in the problem?

All inputs are provided as natural language prompts. To solve the task, models must read and interpret the text, extract the implied constraints, and reason about whether a valid system configuration exists.

These problems simulate real-world reasoning tasks where scientists analyze interaction systems described in textual reports. The benchmark therefore tests an AI system’s ability to:

* understand structured constraints expressed in natural language
* reason about relationships between entities
* detect contradictions in textual descriptions
* perform multi-step logical reasoning

The final output for each example is a binary decision:

* possible — a valid interaction network exists that satisfies all constraints
* impossible — the rules and observations lead to a contradiction

# This benchmark evaluates NLP-based reasoning over structured systems described in text, rather than direct reasoning over structured graph inputs.
