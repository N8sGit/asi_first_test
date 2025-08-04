# ASI's First Exam


## Rationale

[Humanity’s Last Exam](https://lastexam.ai/) is one of the hardest benchmarks for LLMs ever assembled. As of this writing, the best models score around 25% at the highest settings. Whether models beat these benchmarks by genuinely solving the problems or by memorizing answer leaks in their training data is debated, however HLE is explicitly designed to control for this. Neverthless, the possibility of most existing benchmarks that include known answers being staurated within the next several years is a real concern. 

Meanwhile, there's talk about Artificial Superintelligence (ASI) potentially being [on the horizon](https://www.nbcnews.com/tech/tech-news/zuckerberg-says-ai-superintelligence-sight-touts-new-era-personal-empo-rcna221918). AI that can improve AI autonomously has been proved in concept in recent research, (see [ASI-Arch](https://github.com/GAIR-NLP/ASI-Arch/tree/main) for one example, although several others exist, such as Absolute Zero Reasoner and Darwinian Gödel Machines). And while the ceiling to such boostrapping processes is unknown, it’s reasonable to assume it will further accelerate AI’s already rapid progress.

A question looms, however. How will we know when ASI has actually been achieved? How can we determine something is smarter than us? The question has the makings of an epistemological paradox. How is it possible to test for questions we have no answers to? This will become a necessity if we are going to test AI that is believed to be smarter than us. As traditional Q/A benchmarks become saturated, we will need to think creatively if we are to test beyond our own knowledge limits.

Few appreciate the actual implications of ASI. ASI should be capable of doing things people can’t, no matter how smart, by definition. ASI, therefore, must solve problems even the best and brightest haven’t. The bar is very high. This is why we propose ASI’s First Exam, consisting of some of the greatest unanswered and unsolved intellectual challenges. For example, we should be able to prompt ASI for “a functional blueprint to a nuclear fusion reactor”, or a “consistent and verifiable theory of quantum gravity”, or a “universal therapy framework for cancer” or to “prove the Riemann hypothesis.” 

Because these problems are unsolved, the benchmark assumes that the model’s answers will be verified by a group of experts in the respective field with adequate equipment to implement the solution. Confirming the solutions to some of these prompts,especially the medical and engineering ones, will necessarily be capital-intensive. It would take effort and time for a team of nuclear engineers to confirm that a particular blueprint for a fusion reactor is functional, for example, if the verification process involves building a working prototype. 

One advantage to this approach is that because the problems are unsolved, there can be no training data contamination and the model must actually display genuine superintelligence to propose true solutions. No amount of memorization or pattern association will suffice. 

There may come a time when ASI is so intelligent that we can't verify its answers because we no longer posses a frame of reference to connect what it says to human knowledge. It would be like trying to explain quantum computers to a caveman. At that point no sort of benchmarking would help. However, this benchmark focuses on problems that are "known unknowns" and therefore recognizable as active research areas whose solutions make sense in the light of existing knowledge.

The purpose of this benchmark is to challenge AI researchers and developers to think about the actual implications and sufficient conditions of ASI. 

---

## Structure

The exam is organized into domains, each containing problems classified by type:

- **[TP] Theoretical Proof**: Requires a formal, deductive proof
- **[TF] Theoretical Framework**: Requires a new, self-consistent model
- **[AD] Applied Design/Blueprint**: Requires a functional plan for a physical system
- **[PM] Process/Methodology**: Requires a step-by-step procedure
- **[ES] Explanatory Synthesis**: Requires a comprehensive explanation
- **[CG] Creative Generation**: Requires novel aesthetic or creative work

## Selection Criteria
Prompts are selected based on a few criteria. 

1. The problem must be unsolved according to the best available public information
2. The problem must be verifiable *in principle* if not immediately in practice. 
3. If it turns out the problem is unsolvable, (as might be the case for some unknown truths) the ASI should generate proof of impossibility.

The criteria do not account for the capital requirements and implementation costs of certain solution proposals. The expectation is whatever agency gets to ASI will have sufficient resources to fund the verification of the proposed solutions. 

---

## Domains

1. Mathematics
2. Natural Science
3. Medicine & Health
4. Environmental Science & Energy
5. Engineering & Technology
6. Computing & Cryptography
7. General

---

## Usage

This repository contains the problem statements and classification system for ASI's First Exam. Each domain has its own directory with detailed problem descriptions.

The exam data is also stored in json format in domains/domains_data.json.

## Future Work

Some ideas for future work include:

- Develop a gradient of difficulty for the problems. It seems unlikely that ASI will suddenly be able to solve all of the hardest problems instantly. More likely it will gradually improve beyond human capabilities rather than leap beyond us all at once. And while it's subjective to rate problem difficulty, it's clear a prompt such as "cure this disease" is intrinsically easier than "cure all diseases." 

