# Madan Kumar

<img src="./assets/header.svg" alt="A git diff patching 'Former Cyber Security Expert' into 'I read source and fix real bugs in the code the world runs on — 60 merged'" width="100%">

I read source and fix real bugs in the infrastructure the world runs on — **60 merged pull requests** across **48 organizations**, including **Anthropic · NVIDIA · Rust · OpenAI · Meta · Google · Prometheus · MongoDB · Apple · Docker · OpenTelemetry · Redis · Google DeepMind · Hugging Face · Mistral** and more, in Python, TypeScript, Go, Rust, Java, and C. No drive-by typo fixes: 58 are real defects, each reproduced red and shipped green with a test; the other two correct documentation that stated the wrong behaviour.

```diff
@@ a taste — one of the sixty @@
- cargo: a short closing fence consumed one byte past the dashes
+ track the dash count separately, so it can't split a multi-byte char   ✔ merged
```

## Where I work — across the AI-infrastructure stack

**🔌 Distributed systems & networking** — concurrency, RPC, fault tolerance, timeouts
`docker/cli` duplicate-network service panic · `carapaceproxy` absolute-form proxy auth-bypass (CWE-436/863) · `htop` process-scheduling flags — *gRPC-Go, Cloudflare, Prometheus in review*

**⚡ AI inference & serving** — batching, streaming, model serving, latency
`openai-agents-python` Chat-Completions logprobs · `DeepSpeed` inference-config crash · `keras` broadcast shape/dtype inference · `xformers` causal-attention FLOP accounting — *vLLM, SGLang in review*

**📊 Observability** — metrics, tracing, failure diagnosis
`prometheus` histogram `Compact` corrupting buckets · `opentelemetry-python` case-insensitive View instrument matching — *Grafana SDK in review*

**🗄️ Data infrastructure** — vector databases, storage, indexing, retrieval
`qdrant-client` ×2 local-mode filter/proto correctness · `txtai` IVFSparse ANN result ordering · `mongo-python-driver` Extended JSON · `haystack` round-trip serialization — *LanceDB, Chroma in review*

**🧠 ML systems** — distributed training, quantization, fine-tuning, model export
`NVIDIA/Megatron-LM` multimodal dataset modes · `timm` ×5 optimizer (AdafactorBigVision, SGDW) + factory + augmentation-pipeline correctness · `huggingface/peft` LoRA `layers_to_transform` · `coremltools` ×2 model-graph optimization · `timesfm` quantile inference — *llm-compressor quantization + pruning in review*

[![See all 60 fixes at winklemad.github.io](https://img.shields.io/badge/See_all_60_fixes_and_how_I_found_them-winklemad.github.io-1A9E57?style=for-the-badge&labelColor=0B0E13&logo=github&logoColor=white)](https://winklemad.github.io)

## GitHub stats

<p align="center">
  <a href="https://git.io/streak-stats">
    <img src="https://streak-stats.demolab.com?user=winklemad&theme=meta-light&date_format=j%20M%5B%20Y%5D&mode=weekly" alt="Madan Kumar's GitHub contribution streak">
  </a>
</p>

<p align="center">
  <img height="180" src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=winklemad&theme=transparent" alt="Madan Kumar's live GitHub stats">
  <img height="180" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=winklemad&theme=transparent" alt="Most-used languages across public repositories owned by winklemad">
</p>

<sub>Language totals reflect public code in repositories I own; my external OSS contributions span Python, TypeScript, Rust, Go, Java, and C.</sub>

## 📫 Reach me

<p>
  <a href="https://winklemad.github.io"><img src="https://img.shields.io/badge/Portfolio-1A9E57?style=flat-square&logo=githubpages&logoColor=white" alt="Portfolio"></a>
  <a href="https://www.linkedin.com/in/winklemad/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://x.com/winklemad"><img src="https://img.shields.io/badge/X-000000?style=flat-square&logo=x&logoColor=white" alt="X"></a>
  <a href="https://github.com/sponsors/winklemad"><img src="https://img.shields.io/badge/Sponsor-ea4aaa?style=flat-square&logo=githubsponsors&logoColor=white" alt="Sponsor"></a>
  <a href="mailto:winklemad@outlook.com"><img src="https://img.shields.io/badge/Email-0078D4?style=flat-square&logo=microsoftoutlook&logoColor=white" alt="Email"></a>
</p>
