# A-RAG Citation Note

> Source: [A-RAG: Scaling Agentic Retrieval-Augmented Generation via Hierarchical Retrieval Interfaces](https://arxiv.org/abs/2602.03442)
> Authors: Mingxuan Du, Benfeng Xu, Chiwei Zhu, Shaohan Wang, Pengyu Wang, Xiaorui Wang, Zhendong Mao
> Date: 2026-02

## BibTeX

```bibtex
@article{du2026arag,
  title={A-RAG: Scaling Agentic Retrieval-Augmented Generation via Hierarchical Retrieval Interfaces},
  author={Du, Mingxuan and Xu, Benfeng and Zhu, Chiwei and Wang, Shaohan and Wang, Pengyu and Wang, Xiaorui and Mao, Zhendong},
  journal={arXiv preprint arXiv:2602.03442},
  year={2026}
}
```

## Citation Context: GHOSTY COLLIDER paper

### Related Work > Agentic RAG
"A-RAG demonstrates that hierarchical retrieval interfaces outperform complex
algorithms when the agent has autonomy over retrieval strategy, aligning with
our principle that agent-friendly interface design is more effective than
sophisticated orchestration."

### Differentiation
"While A-RAG focuses on retrieval autonomy for factual QA, GHOSTY COLLIDER
extends agent autonomy to creative cognition — the ghost extraction process
is analogous to A-RAG's de-labeling at the conceptual level, stripping
surface-level identifiers to expose deep structural patterns."

### Ghost Depth Scaling
"A-RAG's Test-Time Scaling finding — that stronger models benefit disproportionately
from increased compute — directly inspired Ghost Depth Scaling (Section X),
which applies the same principle to creative abstraction depth."

## Citation Context: PRECOG PROTOCOL paper

### Related Work > Test-Time Scaling
"A-RAG's finding that stronger reasoning models benefit more from increased
test-time compute parallels our observation in signal analysis depth scaling,
where deeper analysis of fewer signals consistently outperforms shallow
analysis of many."

## Key Takeaways for HyperAION

1. **Interface > Algorithm**: Design tools the agent can use autonomously, not rigid workflows
2. **Hierarchical Access**: Information at multiple granularities enables adaptive behavior
3. **Context Tracker**: Track what's been read to avoid redundancy — applied to Memory Distillery
4. **Test-Time Scaling**: Stronger models + more compute = disproportionate gains — applied to Ghost Depth Scaling
