# Hi, I'm Pranati 👋

I work at the intersection of messy human data and intelligent systems, using ML to understand how humans and AI make decisions. I build pipelines that extract reliable signals from neural activity, evaluate reasoning under pressure, and structure large-scale, unstructured information.

**Currently:** MS in CS at Columbia (neural decoding, neuro-inspired ML)  
**Previously:** Shipped production ML at Disney Streaming


## Core Research Areas

- **🧠 Brain-Computer Interfaces & Decision Neuroscience:** Understanding human cognition and decision-making through neural and behavioral data, focusing on modeling and predicting outcomes from noisy, high-dimensional signals.
- **🤖 NeuroAI / Neuro-Inspired AI:** Investigating biologically-inspired principles for learning and memory to develop adaptive, resilient, and efficient ML systems. 
- **📚 AI Safety & Alignment:** Exploring robustness, failure modes, and pluralistic value alignment to ensure AI systems behave reliably and ethically across diverse real-world conditions.


## Selected Projects

### [Motor Intent Detection for BCIs](https://github.com/pranmod01/intent-detection)
Hybrid BCIs often confuse voluntary movement with stimulation feedback.  
**Solution:** Multi-condition EEG classifier (CSP + LDA, EEGNet, LSTM) trained on voluntary, imagined, stimulation-evoked, and passive movement data.  
**Impact:** Specificity improved 51% → 83% while maintaining ~85% sensitivity; added transfer learning from PhysioNet.

### [Breaking Anti-Sycophancy](https://github.com/pranmod01/anti-syco-detect)
Testing anti-sycophancy defenses under coordinated multi-agent pressure.  
**Solution:** 120 adversarial deliberation experiments; Streamlit dashboard; SYCON-Bench compatible.  
**Finding:** Coordinated adversaries flip model positions 70% of the time vs 15% for sycophantic agents; all flips occurred in round 1.

### [ArXivCode](https://github.com/ArXivCode/ArXivCode)
End-to-end pipeline for ingesting, indexing, and querying arXiv-scale corpora with LLM-driven retrieval.  
**Impact:** Production-ready design for handling high-volume, noisy scientific text.

### [AI Slop Detector](https://github.com/pranmod01/ai-slop-detector)
Detecting low-quality AI-generated content efficiently.  
**Solution:** Ensemble of small language models (1–3B) fine-tuned with LoRA on AWS Trainium.  
**Impact:** Order-of-magnitude cost reduction vs large-model inference while maintaining accuracy.


---

## Links

- Website: [https://pranmod01.github.io](https://pranmod01.github.io)  
- GitHub: [https://github.com/pranmod01](https://github.com/pranmod01)  
- Email: [pm3361@columbia.edu](mailto:pm3361@columbia.edu)
