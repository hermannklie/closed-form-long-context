# Closed-form weight edits for long context

**Hermann Hans Klie** · Orden Unio Mystica / BardoAI Research · Preprint, 24 November 2026

🔗 **DOI:** [10.5281/zenodo.24492837](https://doi.org/10.5281/zenodo.24492837) (all versions: [10.5281/zenodo.24492836](https://doi.org/10.5281/zenodo.24492836))
🤗 **Model:** [BardoAI/Qwen3-Omni-30B-A3B-Instruct-LongContext](https://huggingface.co/BardoAI/Qwen3-Omni-30B-A3B-Instruct-LongContext)
📄 **Paper:** [Closed-form_weight_edits_for_long_context_Klie.pdf](Closed-form_weight_edits_for_long_context_Klie.pdf)

## Abstract

A language model trained to 65,536 tokens is given the long-context ability of a sibling model trained to 262,144 tokens without
gradients and without merging. The paper reports the method first: the context wall is treated as a dynamical system and solved from its
source outward, one solved stage after another. It then gives the edits — the content-free position bias of every attention head,
re-developed under a new RoPE base in closed form and written into the key projection as a fixed offset; a rank-1 direction and a
norm-weight difference taken from the sibling — the per-layer ruler ladder behind the wall, position-gated Dual Chunk Attention, results up
to one million tokens, and a paired baseline against the unmodified model. The work continues the weight-space programming of Takehi et al.
(2026) at scale: 453 million weights of a 30-billion-parameter model are written without a gradient.

## Contents of this repository

| File | |
|---|---|
| `Closed-form_weight_edits_for_long_context_Klie.pdf` | the paper, identical to the file published on Zenodo (md5 `a3012e20afaa0f21955a9fc924b1f312`) |
| `CITATION.cff` | citation metadata (GitHub shows it as »Cite this repository«) |
| `LICENSE` | Apache License 2.0 |

The edited model weights are on Hugging Face (link above). This repository holds the paper only; it contains no code.

## Citation

```bibtex
@misc{klie2026closedform,
  author    = {Klie, Hermann Hans},
  title     = {Closed-form weight edits for long context},
  year      = {2026},
  month     = nov,
  publisher = {Zenodo},
  doi       = {10.5281/zenodo.24492837},
  url       = {https://doi.org/10.5281/zenodo.24492837},
  note      = {Preprint}
}
```

## Related work by the author

Base-Axiom Initialization for Deliberative Alignment (2025) — DOI [10.17605/OSF.IO/2UAXK](https://doi.org/10.17605/OSF.IO/2UAXK) ·
[repository](https://github.com/hermannklie/deliberative-alignment-base-axioms)

## License

Apache License 2.0 — see [LICENSE](LICENSE).
