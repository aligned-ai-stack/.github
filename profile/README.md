# Aligned AI Stack

Research on how people form beliefs about AI, decide when to rely on it, and respond when it is wrong.

I am [Shreyan Biswas](https://github.com/shreyan2020), a PhD researcher in Human-Centered AI at TU Delft. This organization brings together study software, analysis, and experimental tools from my research and collaborations.

## From capability to oversight

AI systems perform differently across tasks, languages, and situations. People encounter only part of that performance and have to decide what to expect, what to check, and when to act on the system's advice.

The question connecting my PhD research is: **How do people form beliefs about AI capabilities, use those beliefs when deciding whether to rely on AI, and evaluate its advice when performance is uncertain or uneven?**

My working thesis argument is that effective oversight requires attention to the connections between **evidence about AI performance, people's beliefs, their reliance decisions, and opportunities to check or challenge an outcome**. Problems at each connection can limit oversight. The studies examine different parts of this account; the synthesis brings them together as a framework for evaluating human–AI interaction.

The belief-updating and delegation studies form the empirical center. The multilingual study establishes a concrete problem of reliance carrying across contexts. The virtual-interviewer study situates interaction in a social setting. The content-reporting study examines how an interface supports judgment under AI error within a platform-governance workflow.

## Published studies

| Study | What it contributes |
| --- | --- |
| [“Hi, I’m Molly, Your Virtual Interviewer!”](https://doi.org/10.1609/hcomp.v12i1.31596) · HCOMP 2024 | Examines how virtual interviewer identity and participant characteristics relate to interview experience. It situates perceptions of AI within a social context. |
| [Mind the Gap!](https://doi.org/10.1145/3706598.3713201) · CHI 2025 | Tests whether experience with an LLM in one language affects reliance in another. Lower performance in one language reduced subsequent reliance across languages. |
| [Belief Updating and Delegation](https://doi.org/10.1145/3772318.3790775) · CHI 2026 | Follows beliefs and reliance across three tasks in a preregistered study with 240 participants and 7,200 trials. Expectations carry across tasks, and subjective beliefs about AI accuracy strongly predict delegation. |
| [The Belief Update Gate](https://doi.org/10.1145/3834580.3838740) · HCOMP 2026 | Reanalyzes the same trials by separating whether a reported belief changes from how much it changes. An unchanged report alone cannot establish that no learning occurred. |
| [AI at the Front Lines of Platform Governance](https://doi.org/10.1145/3805689.3812301) · FAccT 2026 | Compares forms of AI support for illegal-content reporting with 450 participants. Evaluative assistance improved provision-level accuracy under error, but neither assistance form reliably improved written explanations. |

## A working framework for oversight

The Human-Aligned AI Stack is a proposed framework for connecting the research to design and evaluation questions:

| Part of the framework | Question to examine |
| --- | --- |
| Capability evidence | What successes, failures, explanations, and task boundaries can a person observe? |
| Beliefs and revision | What does the person expect, what carries across contexts, and what changes after feedback? |
| Reliance and action | When does the person accept advice, check it, or act independently? |
| Support for oversight | What does the interface let the person inspect, report, or challenge, and how well does that support the task? |

These connections recur over time as actions produce further experience and feedback. The framework is a thesis synthesis, with different parts supported by different studies. It also identifies open questions about intervention and institutional follow-through.

The evaluation implications are concrete: report performance by context, measure beliefs and actions separately, distinguish unchanged belief reports from measured updating, and assess both decision accuracy and the quality of people's reasons when advice can be wrong.

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
