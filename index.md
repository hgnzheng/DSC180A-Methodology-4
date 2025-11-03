---
# A simple front matter block helps Jekyll build this page.
layout: default
title: "Methodology 5 — Task 2"
---

# DSC 180A – Methodology Assignment 5 (Task 2)

**Name & UCSD Email:** Hargen Zheng — yoz018@ucsd.edu

**Section & Mentor:** Section A06 — Hao Zhang

---

**1. What is the most interesting topic covered in your domain this quarter?**  
I think the scaling law of dense language models is interesting. It tells that if we scale up the compute, we will see decreased loss for the final trained language model. The fit scaling law helps us make informed decisions about model design given our compute budget. That's pretty cool.

**2. Describe a potential investigation you would like to pursue for your Quarter 2 Project.**  
In quarter 1 we are training a language model from scratch on 8xB200 GPUs, with the aim of low perplexity. However, the current landscape of language modeling moves far beyond minimizing perplexity, but improving models' abilities to solve complex downstream tasks. I think agentic tool use is pretty popular, and I can potentially train a model that can perform really good on specific agent task(s), such as web browsing, etc.

**3. What is a potential change you’d make to the approach taken in your current Quarter 1 Project?**  
Framework would be similar, but I definitely need to spend more time building evaluation pipeline for the project, as the evaluation would be less straightforward than simply calculating the perplexity. 

**4. What other techniques would you be interested in using in your project?**  
I'm interested in incorporating reinforcement learning training, just because how successful it already is when applied to a variety of difficult tasks. I'm interested in using HuggingFace's TRL library for the process.

---