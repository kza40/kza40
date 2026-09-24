# Hey, I'm Kiarash 👋

CS student at SFU (graduating December 2026). Right now I'm building **[Mylos](https://getmylos.com)**, an AI voice receptionist that books and reschedules appointments for small businesses. It's live with 3 pilot shops. I'm also doing directed-studies research with Dr. Arrvindh Shriraman on whether frontier-LLM feedback can teach a 7B model to write correct, faster CUDA kernels.

Before that I spent the summer as an SDE intern at Amazon building production agentic systems, which got me genuinely curious about how these systems fail and what it takes to make them safer and more steerable. Most of my current work comes back to that: evaluation harnesses, failure replay, guardrails.

Outside of that I like to experiment and invent. On the side I'm working on getting a closed-loop agentic driving assistant to run on edge hardware, trying to get the reasoning and sensor pipeline to work reliably on a Jetson Orin Nano.

---

## Projects

**FlowPilot** *(in progress)* - Closed-loop agentic assistant on a Jetson Orin Nano. Maps sensor inputs to real-time lane-change decisions with safety interlocks and human-override controls. The interesting part was figuring out where to draw the confidence thresholds so it actually fails safely.

**[VirtualMemoryAssistant](https://github.com/kza40/VirtualMemoryAssistant)** - RAG pipeline that indexes camera frames into FAISS for natural-language retrieval. Built with CLIP + Ollama on edge hardware. Learned a lot about how much prompt framing affects output quality on multimodal queries.

**[PowerLine-Defect-Detector](https://github.com/kza40/PowerLine-Defect-Detector)** - Computer vision pipeline using YOLOv8 to detect insulator defects in aerial drone imagery. 85%+ mAP, FastAPI inference server at 15+ FPS on CPU.

**[Parabix SIMD](https://github.com/kza40/SIMD_AudioNormalization)** - C++ SIMD prototype for the Parabix open-source framework. 5-8x throughput over scalar baselines, a lot of gdb time to get there.

---

## Background

- **Mylos** (Aug 2026 – present) - Founder & backend engineer. Multi-tenant FastAPI backend on Cloud Run for a voice agent, 800+ tests, and an LLM eval harness (25 scenarios, simulated callers + LLM judge) that took the call pass rate from 76% to 99%
- **SFU** (Sep 2026 – present) - Undergraduate researcher. Turned 18,000+ open-source PyTorch modules into executable GPU benchmark tasks for training LLMs to write CUDA kernels
- **Amazon** (Summer 2026) - SDE Intern. Multi-agent system on AWS (Claude, Bedrock AgentCore, custom MCP tools) that cut reconciliation investigations from 4-5 hours to under 10 minutes; adopted by a 22-person accounting org and won the People's Choice Award at the Amazon-wide Global AI Solutions Expo
- **Delta-Q Technologies** - Embedded software on EV charging systems, ETL pipelines for 1,500+ IoT units
- **SFU Satellite Team** - Ground control platform processing 200+ packets/sec with real-time anomaly detection

---

Python · C++ · TypeScript · PyTorch · CUDA · FAISS · FastAPI · PostgreSQL · AWS · Cloud Run · Docker · Linux

📬 [kza40@sfu.ca](mailto:kza40@sfu.ca) · 🌐 [kiarashzamani.com](https://kiarashzamani.com)