# Project Name 

## Project Description 
A high-level overview of the project:
​​Large Language Models (LLMs) like GPT often undergo post-training to generate outputs that better align with human values and preferences. However, one unintended consequence of this process is that LLMs may develop a propensity for sycophancy; they may respond to a question based on learned user preferences to look favorable even if the answer is not objectively true.

Little research has been conducted to understand the internal mechanisms that induce this behavior within the model. In this project, we hope to discover internal representations of sycophantic behavior within the activation space by utilizing interpretability methods and techniques such as Difference in Means (DIM) and probing analysis. By applying causal interventions such as vector addition or ablation, we aim to test whether these representations are not only correlated with sycophancy but are causally responsible for it.

This work contributes to a deeper understanding of how fine-tuning objectives like RLHF may unintentionally reinforce sycophantic tendencies, and how geometric properties of model internals can be leveraged to detect, interpret, and potentially mitigate such alignment failures.

## Usage
Better training during RLHF and guide rails to prevent sycophantic behavior emerging during RLHF. Circuit break when vector/sycophantic behavior arises during prompt generation of LLMs.

## Setup and Installation
- [Installation](installation.md)
- [Onboarding Guide](onboarding.md)

## Known Issues 
- Multidirectional interpretability methods have yet to be explored. There are three papers that have shown that features are in dead multidimensional, with two papers providing methods of analysis. 
- Why RLHF contributes to sycophantic behavior, and internally how RLHF contributes to sycophantic behavior.


## Contributors
- Warrick Tsui
- Harsh Patel
- Rachel Chen
- Najma Sultani
- Evan Su
- Joseph Yu
- Ethan Qiu
- Sujoy Das
- Vincent Chang


## Important Links
Any additional information that isn't covered under the sections above


