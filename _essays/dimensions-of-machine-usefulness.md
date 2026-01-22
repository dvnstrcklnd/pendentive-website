---
layout: article
title: "Dimensions of Machine Usefulness in Science"
subtitle: "A framework for evaluating AI-enabled science by human capability expansion"
excerpt: "Existing frameworks for self-driving laboratories measure progress by how much human involvement can be removed. This essay proposes an alternative: measuring AI-enabled science by the new human capabilities it creates, not the human tasks it eliminates."
nav: writing
---

### Acemoglu and Johnson on Machine Usefulness

In *Power and Progress: Our Thousand-Year Struggle Over Technology and Prosperity* (2023), economists Daron Acemoglu and Simon Johnson argue that technological progress does not automatically produce broad-based prosperity. What matters is *how* technologies are deployed. They distinguish between genuinely useful technologies—which augment human capabilities, create new tasks for humans to perform, and generate productivity gains that flow broadly—and "so-so automation," which displaces workers without creating commensurate new value. Self-checkout kiosks are their canonical example: they eliminate cashier jobs but don't dramatically improve the shopping experience, primarily shifting labor costs from corporations to customers while degrading service quality. The question for any new technology is not "can it replace human labor?" but "does it expand what humans can do, and who benefits?"

### The Problem with Autonomy Frameworks

Existing frameworks for self-driving laboratories measure progress by how much human involvement can be removed. The highest levels describe labs where humans "merely serve the needs" of the machine or "set a research direction" and walk away.

These frameworks share two questionable assumptions:

**First, they conflate technical achievement with value creation.** "Can the machine do this without human intervention?" is a different question from "Does this advance science, create new human capabilities, or generate broad-based benefit?" History suggests technologies that maximize human displacement often create what Acemoglu and Johnson call "so-so automation"—systems that substitute for human labor at roughly equivalent performance while redistributing value rather than creating it.

**Second, they impose false linearity.** Autonomy frameworks present progress as a single journey from Level 0 to Level 5, where each stage subsumes the previous. But the actual landscape of useful scientific tools is multidimensional. SnapGene—software that externalizes and disciplines molecular biologists' reasoning about DNA constructs—is enormously valuable without being "higher" on any autonomy scale. It's not "Level 2" waiting to become "Level 4." It's excellent along dimensions that autonomy frameworks don't measure at all.

This framework proposes an alternative: measuring AI-enabled science by the **new human capabilities it creates**, not the human tasks it eliminates—and recognizing that these capabilities vary along multiple independent dimensions, not a single axis.

---

## The Six Dimensions of Machine Usefulness in Science

A tool may score high on some dimensions and low on others. There is no implied progression—excellence along one dimension does not require or lead to excellence along others.

### 1. Friction Reduction

**Can we do the same work with less effort?**

*Characteristics:*

- Scientists do the same work, but with less friction
- Primary value: time savings, reduced drudgery
- Human judgment remains central to all decisions

*Examples:*

- Automated pipetting that executes human-designed protocols
- Data visualization tools that format results for human interpretation
- Literature search that surfaces relevant papers faster

*Evaluation question:* Would removing this tool change *what* science gets done, or just *how fast*?

*Risk:* Can become so-so automation if it primarily displaces workers without enabling new science.

---

### 2. Reach Extension

**Can we access experimental territory that was previously impractical?**

*Characteristics:*

- Scientists can now do things that were previously impractical
- Opens new experimental territory rather than accelerating existing work
- Human judgment guides direction; machine extends reach

*Examples:*

- High-throughput screening that makes combinatorial exploration feasible
- Robotic manipulation of hazardous or extreme-condition samples
- Continuous monitoring that captures dynamics humans would miss

*Evaluation question:* Are scientists asking questions they wouldn't have asked before?

*Value creation:* New experimental territory creates new opportunities for insight, new specializations, new translational pathways—new human tasks.

---

### 3. Pattern Surfacing

**Can we perceive structures we couldn't see before?**

*Characteristics:*

- Identifies patterns, correlations, or anomalies across scales humans can't process
- Outputs require human interpretation to become knowledge
- Creates new objects for human reasoning

*Examples:*

- Dimensionality reduction revealing clusters in high-dimensional data
- Anomaly detection flagging unexpected results for human investigation
- Cross-dataset integration connecting disparate findings

*Evaluation question:* Does this generate hypotheses that surprise domain experts?

*Value creation:* New patterns create new questions, new subfields, new interpretive expertise—humans become specialists in making sense of machine-surfaced structure.

---

### 4. Repertoire Expansion

**Can we access expertise that was previously siloed or tacit?**

*Characteristics:*

- Aggregates expertise that no single human possesses
- Makes implicit knowledge explicit and executable
- Enables non-experts to leverage expert-level protocols

*Examples:*

- LLM-assisted protocol generation drawing on literature-wide best practices
- Cross-domain suggestion systems (e.g., recombinase biochemistry → cloning optimization)
- Troubleshooting assistants encoding accumulated lab wisdom

*Evaluation question:* Can a competent scientist now do what previously required rare specialized expertise?

*Value creation:* Democratizes capability, lowers barriers to entry, creates demand for new integrative roles (people who can combine newly-accessible techniques in novel ways). The human task shifts from *possessing* rare expertise to *combining* newly-accessible capabilities.

---

### 5. Judgment Amplification

**Can we make better decisions under complexity?**

*Characteristics:*

- Handles complexity, uncertainty, or scale beyond human cognitive limits
- Human values, priorities, and risk tolerance remain upstream
- Machine provides decision support, not decision replacement

*Examples:*

- Experimental design optimization under complex constraints
- Uncertainty quantification that makes honest confidence intervals tractable
- Scenario modeling that reveals consequences of strategic choices

*Evaluation question:* Are scientists making *better* decisions, or just *faster* ones?

*Value creation:* Creates demand for humans skilled in specifying values, interpreting tradeoffs, and exercising judgment at higher levels of abstraction. The hard problems remain human problems.

---

### 6. Cognitive Scaffolding

**Can we reason more reliably and share that reasoning?**

*Characteristics:*

- Externalizes and disciplines human reasoning
- Makes thinking visible, revisable, and transmissible
- Prevents errors by structuring cognition, not by replacing it

*Examples:*

- SnapGene: visualization and planning tools that ensure scientists know the full properties of the DNA they're working with
- Electronic lab notebooks that create records as a byproduct of planning
- Version control systems that make the history of reasoning accessible

*Evaluation question:* Does this make individual reasoning more robust *and* make that reasoning shareable across people and time?

*Value creation:* Knowledge accumulates rather than dissipating. Errors get caught earlier. Expertise becomes teachable. The human task shifts from *remembering* to *reasoning*.

---

## How This Framework Differs

| Dimension | Autonomy Frameworks | Machine Usefulness Framework |
| :---- | :---- | :---- |
| **Structure** | Linear levels (0→5) | Independent dimensions |
| **Measures progress by** | Human removal | Human capability expansion |
| **Ideal end state** | Machine "in charge" | Humans doing things previously impossible |
| **Treats human involvement as** | Limitation to minimize | Source of value to cultivate |
| **Success criterion** | Can it run without us? | Can we do more with it? |
| **Economic model** | Substitution | Complementarity |
| **Evaluates tools by** | Position on single axis | Profile across multiple dimensions |

---

## Implications for Investment and Policy

### Favor complementarity over substitution

Prioritize systems where human and machine capabilities are genuinely different and mutually enabling, not where machines do what humans do slightly better.

### Beware throughput metrics

"10x more experiments" is only valuable if the experiments are worth running. Throughput divorced from insight is infrastructure, not progress.

### Invest in translation layers

The specification bottleneck—translating human intent into machine-executable instructions—is where the most leverage likely lies. Natural language interfaces, better protocol languages, and intent-to-execution pipelines create capability broadly.

### Fund the interpretive infrastructure

As machines surface more patterns, the bottleneck shifts to human sense-making. Invest in visualization, explanation, and education alongside automation.

### Ask distributional questions

Who benefits? If primarily capital owners and elite institutions, the case for public investment weakens. If early-career scientists, under-resourced labs, and patients, the case strengthens.

---

## Conclusion

The autonomy framing asks: "How much can we remove the human?" and measures progress along a single axis from full human involvement to full machine control.

The machine usefulness framing asks: "How much more can the human do?" and recognizes that capability expansion happens along multiple independent dimensions. A tool like SnapGene can be transformative without being "autonomous" at all. An LLM conversation can provide Repertoire Expansion and Cognitive Scaffolding without Reach Extension or Judgment Amplification.

This reframing matters because it changes what we optimize for. The autonomy framing risks creating sophisticated infrastructure that concentrates benefit and displaces workers without commensurate productivity gains—so-so automation dressed up as progress. The machine usefulness framing aims for technologies that expand human capability, create new tasks, and generate broad-based benefit.

The best AI-enabled science will be measured not by how autonomous the lab becomes, but by what scientists—and ultimately, all of us—can do that we couldn't do before.
