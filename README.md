# Hi, I'm Madan Kumar 👋

> **Software engineer who ships across the whole stack.** I find and fix real bugs in the infrastructure the industry actually runs on.

I hunt for subtle correctness, security, and API-contract bugs by *reading the code* — then ship the fix with a regression test. So far that's **9 merged pull requests** into projects owned by **OpenAI, Meta, Microsoft, Google, Unsloth, Mistral, and pydantic**, with **50+ more in review** across 40+ organizations — in **Python, TypeScript, Java, Rust, and Go**.

No typo fixes. Every one below is a real defect with a reproduction and a test.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat&logo=rust&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)

## 🚀 Selected merged contributions

| Project | Org | What was broken |
|---|---|---|
| [openai-agents-python #3763](https://github.com/openai/openai-agents-python/pull/3763) | **OpenAI** | Chat Completions provider forwarded `top_logprobs` but never set `logprobs=True` → the API rejected it with a 400 (the Responses path handled it correctly). |
| [openai-agents-js #1451](https://github.com/openai/openai-agents-js/pull/1451) | **OpenAI** | Deserializing a `RunState` dropped token `usage` → resumed runs silently under-reported usage (a billing bug). |
| [xformers #1402](https://github.com/facebookresearch/xformers/pull/1402) | **Meta** | The attention profiler over-counted `softmax@V` FLOPs for non-square causal masks. |
| [DeepSpeed #8145](https://github.com/deepspeedai/DeepSpeed/pull/8145) | **Microsoft** | `DeepSpeedInferenceConfig` crashed on a legacy boolean MoE value that its own backward-compat path was meant to accept. |
| [timesfm #463](https://github.com/google-research/timesfm/pull/463) | **Google** | Quantile-flip invariance wasn't applied to the autoregressive branch → corrupted forecast bands past horizon 128 (mean/median hid it). |
| [carapaceproxy #614](https://github.com/diennea/carapaceproxy/pull/614) | **Security · Java** | Absolute-form request URIs bypassed a path-anchored ACL deny rule (CWE-436 / CWE-863) — an auth bypass. |
| [pydantic #13428](https://github.com/pydantic/pydantic/pull/13428) | **pydantic** | `__hash__` on `WithJsonSchema` / `Examples` ignored the `mode` value → hash collisions between distinct schemas. |
| [unsloth #7073](https://github.com/unslothai/unsloth/pull/7073) | **Unsloth** | `SyntheticDataKit.chunk_data` emitted chunks over the requested `max_tokens` limit. |
| [mistral-common #262](https://github.com/mistralai/mistral-common/pull/262) | **Mistral** | The `seed` field was dropped when bridging a `SpeechRequest` into the OpenAI request format. |

## 🔬 Currently in review

Open fixes at **NVIDIA · Apple · Anthropic · Google DeepMind · Hugging Face · Redis · Qdrant · Spotify · Supabase · scikit-learn · vLLM · IBM · MLflow · Nushell · OpenSearch** and more.

**[→ See all open pull requests](https://github.com/search?q=author%3Awinklemad+is%3Apr&type=pullrequests)**

## 🛠️ What I work in

- **Languages:** Python · TypeScript / JavaScript · Rust · Go · Java
- **Domains:** AI / ML infrastructure · LLM & agent tooling · databases · backend APIs · data engineering · systems · application security
- **How I work:** read the source → reproduce red → fix the whole bug *class* → prove it with a test → ship.

## 📫 Reach me

- 💻 GitHub: [@winklemad](https://github.com/winklemad)
- 💼 LinkedIn: [in/winklemad](https://www.linkedin.com/in/winklemad/)
- 🐦 X: [@winklemad](https://x.com/winklemad)
- ✉️ Email: winklemad@outlook.com

<!--
  ── Optional: uncomment to add live GitHub stats cards (they render on GitHub) ──
  ![Stats](https://github-readme-stats.vercel.app/api?username=winklemad&show_icons=true&hide_border=true)
  ![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=winklemad&layout=compact&hide_border=true)
-->
