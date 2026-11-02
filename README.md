<h1 align="center">Hi, I'm Sujit Noronha 👋</h1>
<h3 align="center">Machine Learning Engineer — Voice AI · LLM Post-Training · Inference Optimization · Evals</h3>

<p align="center">
  <a href="https://sujitnoronha.github.io">Portfolio</a> ·
  <a href="https://www.linkedin.com/in/sujitnoronha">LinkedIn</a> ·
  <a href="mailto:sujitnoronha@outlook.com">Email</a>
</p>

---

I build production AI systems end to end — from fine-tuning and evaluating multimodal LLMs to shipping the low-latency infrastructure they run on. Currently **Founding ML Engineer @ [Kidco.AI](https://kidco.ai)**, where I work on real-time, LLM-powered character conversations for kids: speech pipelines, guardrails, and latency optimization on GCP.

MS in Artificial Intelligence, UC Santa Cruz.

## 🔬 Recent work

### [Structured Prompting vs. Self-Training for Audio Reasoning](https://github.com/sujitnoronha/audio_reasoning_interspeech)
**Interspeech 2026.** A systematic comparison of prompt engineering, automated prompt optimization (DSPy MIPROv2), and reinforced self-training (ReST + LoRA) for audio reasoning under tight data and compute budgets, using Qwen3-Omni-30B on the MMAR benchmark. Structured reasoning prompts beat everything else: **+4.9 points over baseline (67.1 → 72.0)** at zero training cost.

### [Blind Deference: Authority-Driven Sycophancy in LLMs](https://github.com/sujitnoronha/llm_sycophancy_probing)
**Oral presentation @ BayLearn 2026** (keynotes that year: Andrew Ng, Azalia Mirhoseini of Ricursive Intelligence, Ion Stoica). A diagnostic benchmark probing how persona authority makes models capitulate in multi-turn conversations — 21,000+ conversations across 10 domains and 8 open-weight models. Introduces the **Authority Vulnerability Index (AVI)**: from near-immune (Qwen3-30B, Llama-3.3-70B) to highly vulnerable (Gemma-3-12B), with reasoning-trained models 77% less vulnerable than standard RLHF models. One-command harness: run it on your own model via vLLM or OpenRouter.

### [VoiceCheck — end-to-end testing for voice agents](https://github.com/sujitnoronha/voicecheck)
Write a YAML scenario; VoiceCheck synthesizes real audio, streams it through a real transport (**LiveKit / Daily / VAPI / Retell**), captures the agent's reply, and grades every turn with 13 evaluators — latency, tone, prompt leaks, roleplay consistency. Ships with a CLI, pytest integration, and a self-hosted dashboard. 357 tests passing.

### [OLMo-1B Instruction Tuning & Pruning](https://github.com/sujitnoronha/olmo_instruction_tuning)
Fine-tuned OLMo-1B across instruction datasets with MLflow tracking, evaluated on MMLU / HellaSwag / SIQA / PIQA / HotpotQA, and explored unstructured pruning at 20–50% parameter reduction.

## 🛠️ Earlier projects I still like

- [**karpathy_makemore**](https://github.com/sujitnoronha/karpathy_makemore) & [**gpt_implementation**](https://github.com/sujitnoronha/gpt_implementation) — n-grams → WaveNet → Transformer → GPT, all from scratch
- [**CLIP_deepfashion**](https://github.com/sujitnoronha/CLIP_deepfashion) — contrastive image↔text retrieval for fashion search
- [**Disaster_Chat_Agent**](https://github.com/sujitnoronha/Disaster_Chat_Agent) — tool-calling agent grounded in live disaster data

## ⚙️ Tools I reach for

`Python` · `PyTorch` · `Transformers` · `vLLM` · `DSPy` · `LoRA/PEFT` · `LiveKit` · `GCP / Vertex AI` · `Cloud Run` · `Docker` · `Kubernetes` · `MLflow` · `ONNX / TFLite / int8 quantization`

## 🌱 Currently exploring

Mechanistic interpretability of tool-calling behavior, audio-native reasoning models, and better evaluation harnesses for conversational agents.

---

<p align="center">
  <em>Open to research collaborations in voice AI, multimodal LLMs, and evals — <a href="mailto:sujitnoronha@outlook.com">say hi</a>.</em>
</p>
