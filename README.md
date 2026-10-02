## Hi, I'm Filip 👋

Machine learning engineer and DevRel working on model inference: making models fast and helping developers use them. Also into philosophy and art, part-time fashion model.

### Recent work
At [Superlinked](https://github.com/superlinked/sie), as a founding member of technical staff, here are some public contributions:

- **[TopK-Embed-V1 in SIE](https://github.com/superlinked/sie/pull/417)** - I added two multi-vector embedding models (0.8B and 2B) to [SIE v0.9.0](https://github.com/superlinked/sie/releases/tag/v0.9.0), Superlinked's open-source inference engine. Fused GPU kernels, CUDA graphs and padding-free batches make them 1.5 to 1.6× faster than the vendor's pipeline. One query takes 6 ms instead of 81 ms. The top search results stay the same. I also [fixed a bug](https://github.com/superlinked/sie/pull/416) that made full batches of large outputs fail in the cluster.
- **[SIE](https://github.com/superlinked/sie)** - SIE runs small models for agents. I contributed to the project and also led developer growth and adoption and more than doubled its GitHub stars in five months.

I co-authored a paper on [FlashNorm](https://arxiv.org/abs/2407.09577).FlashNorm merges the RMSNorm weights into the next linear layer, so transformers run faster.
- Open source contributions in [transformer-tricks](https://github.com/OpenMachine-ai/transformer-tricks), I merged [10+ pull requests](https://github.com/OpenMachine-ai/transformer-tricks/pulls?q=is%3Apr+author%3Afm1320+is%3Amerged). They add [GPU benchmarks](https://github.com/OpenMachine-ai/transformer-tricks/blob/main/notebooks/flashNorm_gpu_benchmark.ipynb), Gemma 4 support, and a guide to use FlashNorm with your own model. With FlashNorm, Llama-3.2-1B runs 12.77% faster in Hugging Face Transformers.


### Talks and writing
- **Weight Folding, CUDA Streams, and the Bug That Made My Model Speak Backwards** - AI Engineer World's Fair 2026 · [video](https://youtu.be/c1hGBoWw20A)
- **The Small Model Infrastructure Nobody Built (So We Did)** - AI Engineer Europe 2026 · [video](https://youtu.be/qdh_x-uRs9g)
- **One GPU, Four Retrieval Modes: Multi-Model Search Serving** - Berlin Buzzwords 2026 · [video](https://youtu.be/f76pKDzPRFQ)
- **From BM25 to Mixture-of-Encoders** - Haystack EU 2025 · [video](https://www.youtube.com/watch?v=RPgz_nQs-3w)
- **What Actually Makes Embedding Model Inference Fast?** - [article](https://filipmakraduli.substack.com/p/what-actually-makes-embedding-model)

### Earlier open source
- **[langchain-superlinked](https://github.com/superlinked/langchain-superlinked)** - PyPI package with a custom Superlinked mixture-of-encoders retriever for LangChain
- **[Superlinked x LlamaIndex](https://llamahub.ai/l/retrievers/llama-index-retrievers-superlinked)** - A custom LlamaIndex retriever that uses Superlinked
- **[AdalFlow](https://github.com/SylphAI-Inc/AdalFlow)** - Contributor to the library for building and optimizing LLM task pipelines: multimodal OpenAI support, the integrations page, and RAG and text-splitter tutorials

### Before that
- **[Mood-based song recommender](https://youtu.be/WIBtZa7mcCs)** - Transformer models and vector search to recommend Spotify songs by mood (Qdrant Vector Space Talks)
- Data science and ML roles in retail, fintech and biomedical AI


### Reach me
[LinkedIn](https://www.linkedin.com/in/filipmakraduli/), [X-Twitter](https://x.com/f_makraduli), [Substack](https://filipmakraduli.substack.com)
