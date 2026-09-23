# Aligned AI Stack

Research on how people form beliefs about AI, decide when to rely on it, and respond when it is wrong.

I am [Shreyan Biswas](https://github.com/shreyan2020), a PhD researcher in Human-Centered AI at TU Delft. This organization brings together study software, analysis, and experimental tools from my research and collaborations.

## Research direction

AI systems can perform differently across tasks, languages, and situations. People have to decide what to expect from the system, what to check, and when to act on its advice. Those decisions are shaped by their previous experience with AI and by how the interface presents evidence and errors.

The question connecting this work is: **How can we support informed reliance on AI when its performance is uneven and people's beliefs about it carry across interactions?**

The working argument of my thesis is that **human oversight needs to be evaluated across a sequence of interactions**. Experience in one context can shape reliance in another. Reported beliefs and reliance decisions capture different parts of that process. An interface can improve the accuracy of a decision without reliably improving the reasons a person gives for it.

This motivates evaluating assistance through connected measures of experience, reported belief, reliance, and decision quality, including when AI advice is wrong. The design aim is to help people assess, question, and correct AI assistance.

## Published studies

| Study | What it contributes |
| --- | --- |
| [“Hi, I’m Molly, Your Virtual Interviewer!”](https://doi.org/10.1609/hcomp.v12i1.31596) · HCOMP 2024 | Examines how virtual interviewer identity and participant characteristics relate to interview experience. It situates perceptions of AI within a social context. |
| [Mind the Gap!](https://doi.org/10.1145/3706598.3713201) · CHI 2025 | Tests whether experience with an LLM in one language affects reliance in another. Lower performance in one language reduced subsequent reliance across languages. |
| [Belief Updating and Delegation](https://doi.org/10.1145/3772318.3790775) · CHI 2026 | Follows beliefs and reliance across three tasks in a preregistered study with 240 participants and 7,200 trials. Expectations carry across tasks, and subjective beliefs about AI accuracy strongly predict delegation. |
| [The Belief Update Gate](https://doi.org/10.1145/3834580.3838740) · HCOMP 2026 | Reanalyzes the same trials by separating whether a reported belief changes from how much it changes. An unchanged report alone cannot establish that no learning occurred. |
| [AI at the Front Lines of Platform Governance](https://doi.org/10.1145/3805689.3812301) · FAccT 2026 | Compares forms of AI support for illegal-content reporting with 450 participants. Evaluative assistance improved provision-level accuracy under error, but neither assistance form reliably improved written explanations. |

Together, these studies connect **experience, belief, reliance, and the quality of the resulting decision**. They motivate evaluating an interface across repeated use, measuring people's beliefs separately from their actions, and checking whether assistance helps when the AI makes mistakes.

The [Beyond the Traceback](https://arxiv.org/abs/2608.20896) poster (HCOMP 2026) extends the design questions to adaptive explanations of programming errors.

## Public prototypes

| Repository | Current scope |
| --- | --- |
| [ai-guard](https://github.com/aligned-ai-stack/ai-guard) | Experiments comparing attacker, defender, and judge configurations, with conversation traces, token use, and timing. A testbed for studying model behavior under adversarial interaction. |
| [skill-aware-viber](https://github.com/aligned-ai-stack/skill-aware-viber) | An Aider-based debugging prototype that uses cues in a user's request to offer explanation and verification guidance. Its skill labels are heuristic. |

These prototypes explore design and evaluation questions arising from the research. Their effectiveness needs to be established for each intended use.

## Research materials

The organization also holds private study applications and analyses for multilingual co-writing, multi-task belief updating, and the belief-update-gate follow-up. Further experiments examine error propagation between agents and simulated participants for testing study workflows. Published papers above provide the public account of the completed studies; code and data availability varies by project.

Each repository documents its own setup and current state. For questions about the research or collaboration, contact [s.biswas@tudelft.nl](mailto:s.biswas@tudelft.nl).

[Google Scholar](https://scholar.google.com/citations?user=1IWhpKUAAAAJ&hl=en) · [TU Delft](https://www.wis.ewi.tudelft.nl/biswas)
