## Hi, I'm Filip 👋

Machine learning engineer and DevRel working on model inference: making models fast and helping developers use them. Also into philosophy and art, part-time fashion model.

### Recent work
At [Superlinked](https://github.com/superlinked/sie), as a founding member of technical staff, some public contributions:

- **[TopK-Embed-V1 in SIE](https://github.com/superlinked/sie/pull/417)** - Shipped two multi-vector embedding models (0.8B and 2B, Qwen3.5 with linear attention) in [SIE v0.9.0](https://github.com/superlinked/sie/releases/tag/v0.9.0), Superlinked's open-source inference engine. Padding-free batching, fused GPU kernels and CUDA graphs reached 1.5 to 1.6× the vendor's throughput and cut single-query latency from 81 ms to 6 ms, with identical top results. Also fixed a [cluster transport bug](https://github.com/superlinked/sie/pull/416) that made full batches of wide multi-vector outputs fail.
- **[SIE](https://github.com/superlinked/sie)** - Small-model inference for search, retrieval and agents: [16 merged pull requests](https://github.com/superlinked/sie/pulls?q=is%3Apr+author%3Afm1320+is%3Amerged), and helped more than double its GitHub stars in five months.
- **[FlashNorm](https://arxiv.org/abs/2407.09577)** - Co-author of _FlashNorm: Fast Normalization for Transformers_, which folds the RMSNorm weights into the next linear layer. My [GPU benchmark](https://github.com/OpenMachine-ai/transformer-tricks/blob/main/notebooks/flashNorm_gpu_benchmark.ipynb) overlaps the normalization with the matrix multiply using CUDA streams and a custom Triton kernel: +12 to 14% at Llama-7B scale on an NVIDIA T4.

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
