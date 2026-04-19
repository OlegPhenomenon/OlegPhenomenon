# Hi, I'm Oleg 👋

Independent ML researcher based in Tallinn, Estonia. Backend engineer by day; in my own time I work on alternative architectures for language models — specifically at the intersection of **Hyperdimensional Computing (HDC)** and generative modelling.

## 🧠 Current research

### [HDC-Brain v14.1](https://github.com/OlegPhenomenon/hdc-brain) &nbsp;·&nbsp; [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.19653726.svg)](https://doi.org/10.5281/zenodo.19653726)

A 300M-parameter language model built on HDC primitives instead of standard transformer operations:

- **STE bipolar codebook** — ±1 token embeddings (16 MB vs 512 MB float32)
- **Multi-head binding attention** — 12K params/layer vs 67M in an equivalent transformer (5461× reduction)
- **Thought loops** — iterative K-pass reasoning through shared blocks
- **Parallel-scan HDC memory** — O(D) state, no KV-cache

Pretrained on 3B tokens of FineWeb-Edu; instruction-finetuned on 75M tokens from OpenHermes 2.5 / TULU-3 / Alpaca-GPT4 / Dolly / WizardLM. Full artefacts open:

- 📄 [Paper (Zenodo DOI)](https://doi.org/10.5281/zenodo.19653726)
- 💻 [Code (Apache 2.0)](https://github.com/OlegPhenomenon/hdc-brain)
- 🤗 [Base weights](https://huggingface.co/olegphenomenon/hdc-brain-v14.1-base) · [Instruction-tuned weights](https://huggingface.co/olegphenomenon/hdc-brain-v14.1-finetune-v3) (CC BY-NC 4.0)

## 🔧 What I work with

**ML:** PyTorch, SentencePiece, Hugging Face ecosystem, HDC / VSA
**Backend:** Ruby on Rails, Python, FastAPI, PostgreSQL, Docker
**Infra:** vast.ai / Lambda / RunPod for GPU, standard Linux / CI workflows

## 📫 Contact

- Email: oleg.phenomenon@gmail.com
- LinkedIn: [linkedin.com/in/olegphenomenon](www.linkedin.com/in/olegphenomenon) &nbsp;<sub>(check your actual URL and update)</sub>
- ORCID: [0009-0009-1303-3040](https://orcid.org/0009-0009-1303-3040)

Open to conversations with ML researchers and teams working on efficient architectures, HDC / VSA, or alternative LM designs.
