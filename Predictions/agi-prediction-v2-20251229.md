# Long Bet Prediction: Artificial General Intelligence

Date: 2025-12-29

## Introduction

Predictions about AGI are notoriously difficult because the term itself is poorly defined. Many discussions conflate AGI with what might more properly be called ASI (Artificial Superintelligence)—systems that exceed the best humans at essentially all cognitive tasks, including novel scientific research conducted autonomously. This framing, whether intentional or not, obscures the nearer-term implications of AI development and may prevent people from thinking clearly about what is coming.

When the goalposts are set at "AI that can autonomously conduct frontier AI research," the implicit message is that the experts will be affected first, or at least simultaneously with everyone else. This framing is comforting to knowledge workers who might otherwise feel targeted. It may not be coincidental that organizations building these systems favor such definitions—they face significant risk of public backlash if they were to say plainly: "We are building systems to replace remote knowledge workers."

This prediction takes a different approach. Rather than reaching for an abstract or maximal definition, I define AGI in terms of practical economic capability: when can an AI be a worker rather than merely a tool?

## Definition: The Normal Remote Worker

For the purposes of this prediction, AGI is defined as an AI system that can perform most of what a normal remote human worker would be able to do across typical knowledge work domains.

This includes:
- Communicating through digital channels (text, voice, video)
- Participating in video calls with human colleagues, including real-time discussion, responding to questions, reading social cues, and adjusting approach based on conversation dynamics
- Working with documents, code, data, and other digital artifacts
- Collaborating with humans both asynchronously and synchronously
- Maintaining context and memory across days and weeks on ongoing projects
- Exercising judgment about when to ask for clarification versus when to proceed independently
- Following organizational processes and updating its approach as those processes evolve
- Learning from feedback and improving performance over time within a role

"Normal" is important here. This definition does not require matching the best human expert in every domain. It requires performing competently across the range of tasks a typical knowledge worker handles—the kind of employee who is solid, reliable, and gets things done without being exceptional.

"Remote" is also important. This naturally constrains scope to work mediated through digital channels, sidestepping questions of physical embodiment while capturing the majority of knowledge work as it is actually performed today.

This definition explicitly excludes "lights out" autonomous AI research as a requirement. An AI that can function as a competent remote employee but cannot independently advance the frontier of machine learning research still meets this definition.

## What Is Currently Missing

As of late 2025, AI systems are remarkably capable within individual sessions but fall short of this definition in several key areas.

**Memory**: Current systems lack robust memory across extended time horizons. They cannot reliably recall what was discussed last week, what decisions were made, what the ongoing priorities are, or what context is relevant from previous interactions. Context windows have grown dramatically but remain bounded, and there is no production-ready solution for true long-term episodic memory.

**Attention to Memory**: Even when information is nominally available (through retrieval augmentation or extended context), current systems struggle to identify and utilize the right information at the right moment. The problem is not just storage but intelligent retrieval and integration.

**Goal Coherence**: Current systems can execute multi-step plans but often lose the thread on longer time horizons, optimize for local objectives that don't serve the overall goal, or drift from the original intent without recognizing the drift.

**Process Adherence**: Organizations run on processes—documented or tacit ways of doing things that ensure consistency and quality. An effective worker internalizes these processes and follows them reliably. Current AI systems can be instructed to follow processes but struggle with consistent adherence across extended interactions, particularly when processes are complex or require judgment about when exceptions apply.

**Calibrated Judgment**: Knowing when you have enough information to proceed versus when to escalate to a human requires well-calibrated uncertainty and understanding of stakes. Current systems are often either overconfident or excessively deferential, without reliable calibration.

In my daily experience using AI coding tools, current systems are already very competent but require significant command, control, and steering. The gap is not raw capability—it is reliability, consistency, and autonomous operation over extended periods.

## The Memory Architecture for AGI

I believe the path to AGI (under this definition) requires a layered memory architecture, roughly as follows:

**Layer 0 — Model Parameters (Instinct)**: The foundational capabilities and knowledge encoded in the model's weights. Principally fixed for a given model version. This is analogous to instinct or deeply ingrained skills in humans.

**Layer 0.x — LoRA Stack (Learned Adaptations)**: Stackable, modular adaptations to the base model. These could be organization-specific, role-specific, or even project-specific modifications that adjust the model's behavior without full retraining. Multiple LoRAs could be composed to create specialized configurations.

**Layer 1 — Dynamic Context Window (Working Memory)**: The active workspace for current processing. Future systems will need context windows substantially larger than today's, with sophisticated mechanisms for dynamically shifting information in and out based on relevance. This is analogous to human working memory but with greater capacity and more fluid boundaries.

**Layer 2 — Instance-Specific Vector Store (Personal Memory)**: Persistent storage for the individual agent instance, where episodic memories, learned preferences, and accumulated knowledge are retained potentially indefinitely. This layer requires not just storage but intelligent curation—pruning stale information, updating outdated knowledge, maintaining performance as the store grows.

**Layer 3 — Organizational Knowledge Base (Institutional Memory)**: Shared knowledge repositories (intranets, wikis, documentation systems) accessible to all agents and humans within an organization. Critically, AI agents should both read from and write to this layer, contributing knowledge that persists beyond individual sessions and is available to colleagues.

**Layer 4 — The Internet (World Knowledge)**: Access to external information, reference material, current events, and the accumulated knowledge of humanity.

The key insight is that effective memory is not just about storage at each layer, but about intelligent attention allocation across layers—knowing when to draw from personal memory versus organizational knowledge versus external sources, and integrating information coherently.

## Predictions

### Prediction A: 25% Probability by End of 2028

There is approximately a 25% chance that AGI, as defined above, will exist before the end of 2028.

This probability is lower than some might expect given current rates of progress. The primary uncertainty is whether transformer-based attention mechanisms can scale to meet the memory and context requirements outlined above. If fundamental architectural innovations are required—rather than incremental improvements to existing approaches—timelines will extend.

The 25% represents the scenario where:
- Memory and attention improvements arrive in 2026-2027 as anticipated by some
- These improvements prove sufficient without requiring paradigm shifts
- Integration into coherent agentic systems proceeds smoothly
- The resulting systems achieve the reliability threshold needed for genuine deployment as workers

### Prediction B: 75% Probability by End of 2030

There is approximately a 75% chance that AGI, as defined above, will exist before the end of 2030.

Five years provides substantially more runway for either:
- Incremental improvements to compound sufficiently within the current paradigm, or
- New architectural approaches to emerge, mature, and be integrated if transformers plateau

The remaining 25% probability of AGI not existing by 2030 accounts for scenarios where:
- Fundamental technical barriers prove harder than anticipated
- The reliability threshold for "worker rather than tool" is higher than expected
- Progress stalls for reasons not currently foreseeable

### Key Uncertainties

**Technical**: Can attention mechanisms scale to the required memory and context demands? The field has shown remarkable resourcefulness in finding new approaches (mixture of experts, various attention variants, retrieval augmentation), but past performance does not guarantee future results.

**Reliability**: Even if capabilities exist, deployment as an actual worker requires crossing a reliability threshold. The difference between "can do this task 80% of the time" and "can be trusted with this responsibility" is significant. A human worker who fails unpredictably 20% of the time is not employable. The same standard may apply to AI.

**Integration**: The components (language models, voice, video, memory systems, tool use) need to be integrated into a coherent whole. This systems integration work is often harder than the underlying capabilities suggest.

## On the Transition

If these predictions prove correct, the implications are profound. An AI that can function as a reliable remote knowledge worker across most domains represents:
- Billions of potential "workers" that can be instantiated on demand
- Direct competition with human knowledge workers across most industries
- A fundamental shift in the relationship between labor and capital

I expect the transition to be slow, even when capabilities are available. Organizations will take years to adapt, even when early adopters demonstrate clear value. This is both good and bad. Good because it provides time for adaptation. Bad because gradual change prevents recognition of what is happening, enables motivated denial, diffuses the political energy needed for collective response, and ensures that by the time impact is undeniable, those affected are already scrambling individually rather than responding collectively.

The gradual erosion of knowledge work—this job automated, that role diminished, this career path slowly closed—may prove more socially corrosive than a sudden shock would have been. Sudden shocks force societies to update their worldviews and respond. Gradual change allows the maintenance of comforting narratives until it is too late to act.

## What This Means

The framing of AGI as "systems that can autonomously conduct AI research" sets a distant, abstract goalpost that obscures nearer-term disruption to ordinary knowledge workers. If my definition and predictions are correct, we should be preparing now for a world where most remote knowledge work can be performed by AI systems—not in some distant future, but within the next three to five years.

This requires serious thought about:
- How the economic gains from AI productivity will be distributed
- What meaningful work and contribution look like when traditional employment is no longer necessary
- How democratic institutions can maintain legitimacy and effectiveness in such a transformed economy
- Whether current political systems are capable of managing this transition

These questions deserve attention now, while there is still time to shape outcomes, rather than after the transition is already underway.
