# Hi, I'm Pranati 👋

I build ML systems that extract reliable signals from complex, noisy data—whether that's decoding intent from neural activity, evaluating AI reasoning under adversarial conditions, or making sense of massive research corpora.

Currently: MS in CS at Columbia, working on neural decoding and neuro-inspired ML architectures. 
Previously: shipped production ML at Disney Streaming.

## Core research areas

🧠 Neural signal processing & BCIs
Building robust classifiers for physiological data where noise, artifacts, and confounds are the norm. Focus: turning messy EEG/eye-tracking signals into actionable predictions about human cognitive states.

🤖 AI robustness & evaluation
Testing whether AI systems maintain reliable reasoning under adversarial pressure, distribution shift, and edge cases. Focus: finding failure modes before they matter.

📚 Knowledge systems & retrieval
Building infrastructure for organizing and accessing complex information at scale. Focus: making large knowledge bases actually usable for both humans and AI systems.

---
### Selected projects
**Motor Intent Detection for BCIs**
Problem: Hybrid BCI systems can't distinguish voluntary movement from electrical stimulation feedback, creating dangerous false positives in rehabilitation robotics.
Solution: Multi-condition EEG classification pipeline (CSP+LDA, EEGNet, LSTM) trained on voluntary, imagined, stimulation-evoked, and passive movement data.
Impact: 51% → 83% specificity—the difference between a research demo and a system someone can rely on.

**Breaking Anti-Sycophancy**
Problem: Do anti-sycophancy defenses hold under coordinated social pressure from multiple agents?
Solution: Adversarial evaluation framework with 120 deliberation experiments testing honest reasoning against sycophantic flattery and intellectual pressure.
Finding: Adversarial agents achieve 70% manipulation success vs. 15% for sycophantic approaches—all flips occur immediately (round 1), revealing social proof as the primary attack vector.

**ArXivCode**
Problem: Research knowledge is fragmented across millions of papers—how do you make it searchable and usable at scale?
Solution: End-to-end pipeline for ingesting, indexing, and querying arXiv-scale corpora with LLM-driven retrieval and analysis.
Why it matters: Production-oriented design for handling noisy, high-volume scientific text—the same principles that apply to any large knowledge system.

**AI Slop Detector**
Problem: As AI-generated content floods the internet, how do you efficiently detect low-quality model outputs at scale?
Solution: Ensemble of four specialized small language models (1-3B params) fine-tuned with LoRA on AWS Trainium for content quality classification.
Impact: Order-of-magnitude cost reduction vs. large-model inference while maintaining detection accuracy.

---
### The through-line
All of these projects share a common challenge: building systems that work reliably when the data is messy, the stakes are high, and "mostly correct" isn't good enough.

BCIs: Neural signals are noisy, but the system has to distinguish intent from artifact
AI evaluation: Models can seem robust on benchmarks but fail under adversarial pressure
Knowledge systems: Research corpora are massive and unstructured, but retrieval has to be precise
Content quality: Detection needs to scale without burning budget on expensive models

I'm interested in the gap between what works in controlled settings and what works in the real world.

