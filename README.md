# Hey, I'm Kiarash 👋

CS student at SFU (graduating December 2026). Right now I'm building **[Mylos](https://getmylos.com)**, an AI voice receptionist that books and reschedules appointments for small businesses. It's live with 3 pilot shops. I'm also doing directed-studies research with Dr. Arrvindh Shriraman on whether LoRA fine-tuning can teach a 7B model to write correct, faster CUDA kernels.

Before that I spent the summer as an SDE intern at Amazon building production agentic systems, which got me genuinely curious about how these systems fail and what it takes to make them safer and more steerable. Most of my current work comes back to that: evaluation harnesses, failure replay, guardrails.

Outside of that I like to experiment and invent. On the side I'm working on getting a closed-loop agentic driving assistant to run on edge hardware, trying to get the reasoning and sensor pipeline to work reliably on a Jetson Orin Nano.

---

## Projects

**[FlowPilot](https://github.com/kza40/FlowPilot)** *(in progress)* - Agentic lane-change assistant for a Jetson Orin Nano. Built so far: a multi-sensor ingestion layer (camera, LiDAR, radar, IMU) with timestamp synchronization, plus a latency benchmarking harness. Next up: the reasoning loop and the safety interlocks with human override.

**[VisualMemoryAssistant](https://github.com/kza40/VisualMemoryAssistant)** - Retrieval pipeline for a Jetson Orin Nano that indexes camera frames into FAISS with CLIP and answers questions like "where did I leave my keys?" with Moondream2. Unit-tested in CI; on-device benchmarks are next. Learned a lot about how much prompt framing affects output quality on multimodal queries.

**[PowerLine-Defect-Detector](https://github.com/kza40/PowerLine-Defect-Detector)** - Computer vision pipeline using YOLOv8 to detect insulator defects in aerial drone imagery. 81% mAP50 on 1,000+ images, served through a FastAPI inference server with load testing.

**[Parabix SIMD](https://github.com/kza40/SIMD_AudioNormalization)** - C++ SIMD prototype for the Parabix open-source framework. 5-8x throughput over scalar baselines, a lot of gdb time to get there.

---

## Background

- **Mylos** (Aug 2026 – present) - Founder & backend engineer. Multi-tenant FastAPI backend on Cloud Run for a voice agent, 800+ tests, and an LLM eval harness (25 scenarios, simulated callers + LLM judge) that took the call pass rate from 76% to 99%
- **SFU** (Sep 2026 – present) - Undergraduate researcher (directed studies, Dr. Arrvindh Shriraman). LoRA fine-tuning a 7B open model to write correct, faster GPU kernels; built the benchmarking, training, and evaluation pipeline end to end
- **Amazon** (Summer 2026) - SDE Intern. Multi-agent system on AWS (Claude, Bedrock AgentCore, custom MCP tools) that cut reconciliation investigations from 4-5 hours to under 10 minutes; adopted by a 22-person accounting org and won the People's Choice Award at the Amazon-wide Global AI Solutions Expo
- **Delta-Q Technologies** - Embedded software on EV charging systems, ETL pipelines for 1,500+ IoT units
- **SFU Satellite Team** - Ground control platform processing 200+ packets/sec with real-time anomaly detection

---

Python · C++ · TypeScript · PyTorch · CUDA · LoRA fine-tuning (Unsloth, Hugging Face Transformers) · vLLM · LLM evals (LLM-as-judge) · Claude / Bedrock AgentCore · MCP · FAISS · FastAPI · PostgreSQL · AWS · Cloud Run · Docker · Linux

Research, Mylos, and Amazon code are private; happy to walk through any of it in an interview.

📬 [kza40@sfu.ca](mailto:kza40@sfu.ca) · 🌐 [kiarashzamani.com](https://kiarashzamani.com)