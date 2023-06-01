# Neurosymbolic Dialogue System
A task-oriented dialog system infused with neurosymbolic rules.
When evaluated on MultiWOZ 2.2, the proposed dual-system increases task success rate by **16%**, significantly improving generation consistency and coherence.

<img src="algorithm.png" width="800"/>

- Only restaurant and hotel domains are currently supported. However, the approach can be extended to all domains in MultiWOZ by introducing new rules.
- It would be interesting to see if we can use GPT-4's in-context learning to generate reliable rules for new domains.

See our [technical report](report.pdf) for algorithms/models and evaluations.
