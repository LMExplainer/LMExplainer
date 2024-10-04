---
layout: project_page
permalink: /xplainllm

title: "XplainLLM: A Knowledge-Augmented Dataset for Reliable Grounded Explanations in LLMs"

authors:
  - "<a href='https://chen-zichen.github.io/'>Zichen Chen</a><sup>1</sup>, <a href='https://scholar.google.com/citations?user=jEOSgcUAAAAJ'>Jianda Chen</a><sup>2</sup>, <a href='https://sites.cs.ucsb.edu/~ambuj/'>Ambuj K. Singh</a><sup>1</sup>, <a href='https://sites.cs.ucsb.edu/~sra/index.html'>Misha Sra</a><sup>1</sup>"
 

affiliations:
    - <sup>1</sup> University of California, Santa Barbara
    - <sup>2</sup> Nanyang Technological University, Singapore


paper: https://arxiv.org/abs/2311.08614
# video: https://www.youtube.com/results?search_query=turing+machine
code: https://github.com/chen-zichen/XplainLLM_dataset
data: https://github.com/chen-zichen/XplainLLM_dataset
---

<!-- Using HTML to center the abstract -->
<div class="columns is-centered has-text-centered">
    <div class="column is-four-fifths">
        <h2>Abstract</h2>
        <div class="content has-text-justified">
Large Language Models (LLMs) have achieved remarkable success in natural language tasks, yet understanding their reasoning processes remains a significant challenge. We address this by introducing XplainLLM, a dataset accompanying an explanation framework designed to enhance LLM transparency and reliability.
Our dataset comprises 24,204 instances where each instance interprets the LLM's reasoning behavior using knowledge graphs (KGs) and graph attention networks (GAT), and includes explanations of LLMs such as the decoder-only Llama-3 and the encoder-only RoBERTa. 
XplainLLM also features a framework for generating grounded explanations and the <i>debugger-scores</i> for multidimensional quality analysis. Our explanations include <i>why-choose</i> and <i>why-not-choose</i> components, <i>reason-elements</i>, and <i>debugger-scores</i> that collectively illuminate the LLM's reasoning behavior.  
Our evaluations demonstrate XplainLLM's potential to reduce hallucinations and improve grounded explanation generation in LLMs. XplainLLM is a resource for researchers and practitioners to build trust and verify the reliability of LLM outputs.
        </div>
    </div>
</div>

---

> Note: This webpage is under construction. Please check back later for more updates.

<!-- ## Background
The paper "On Computable Numbers, with an Application to the Entscheidungsproblem" was published by Alan Turing in 1936. In this groundbreaking paper, Turing introduced the concept of a universal computing machine, now known as the Turing machine.

## Objective
Turing's main objective in this paper was to investigate the notion of computability and its relation to the Entscheidungsproblem (the decision problem), which is concerned with determining whether a given mathematical statement is provable or not.


## Key Ideas
1. Turing first presented the concept of a "computable number," which refers to a number that can be computed by an algorithm or a definite step-by-step process.
2. He introduced the notion of a Turing machine, an abstract computational device consisting of an infinite tape divided into cells and a read-write head. The machine can read and write symbols on the tape, move the head left or right, and transition between states based on a set of rules.
3. Turing demonstrated that the set of computable numbers is enumerable, meaning it can be listed in a systematic way, even though it is not necessarily countable.
4. He proved the existence of non-computable numbers, which cannot be computed by any Turing machine.
5. Turing showed that the Entscheidungsproblem is undecidable, meaning there is no algorithm that can determine, for any given mathematical statement, whether it is provable or not.

![Turing Machine](/static/image/Turing_machine.png)

*Figure 1: A representation of a Turing Machine. Source: [Wiki](https://en.wikipedia.org/wiki/Turing_machine).*

## Table: Comparison of Computable and Non-Computable Numbers

| Computable Numbers | Non-Computable Numbers |
|-------------------|-----------------------|
| Rational numbers, e.g., 1/2, 3/4 | Transcendental numbers, e.g., π, e |
| Algebraic numbers, e.g., √2, ∛3 | Non-algebraic numbers, e.g., √2 + √3 |
| Numbers with finite decimal representations | Numbers with infinite, non-repeating decimal representations |

He used the concept of a universal Turing machine to prove that the set of computable functions is recursively enumerable, meaning it can be listed by an algorithm.

## Significance
Turing's paper laid the foundation for the theory of computation and had a profound impact on the development of computer science. The Turing machine became a fundamental concept in theoretical computer science, serving as a theoretical model for studying the limits and capabilities of computation. Turing's work also influenced the development of programming languages, algorithms, and the design of modern computers. -->

## Citation
```
@article{chen2023xplainllm,
  title={XplainLLM: A Knowledge-Augmented Dataset for Reliable Grounded Explanations in LLMs},
  author={Chen, Zichen and Chen, Jianda and Singh, Ambuj and Sra, Misha},
  journal={arXiv preprint arXiv:2311.08614v2},
  year={2023}
}
```
