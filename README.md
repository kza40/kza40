# Hey, I'm Kiarash 👋

CS student at SFU. This summer I'm at Amazon building production agentic systems, which got me genuinely curious about how these systems fail and what it takes to make them safer and more steerable.

Outside of that I like to experiment and invent. Right now I'm working on getting a closed-loop agentic driving assistant to run on edge hardware, trying to get the reasoning and sensor pipeline to work reliably on a Jetson Orin Nano.

---

## Projects

**FlowPilot** *(in progress)* - Closed-loop agentic assistant on a Jetson Orin Nano. Maps sensor inputs to real-time lane-change decisions with safety interlocks and human-override controls. The interesting part was figuring out where to draw the confidence thresholds so it actually fails safely.

**[VirtualMemoryAssistant](https://github.com/kza40/VirtualMemoryAssistant)** - RAG pipeline that indexes camera frames into FAISS for natural-language retrieval. Built with CLIP + Ollama on edge hardware. Learned a lot about how much prompt framing affects output quality on multimodal queries.

**[PowerLine-Defect-Detector](https://github.com/kza40/PowerLine-Defect-Detector)** - Computer vision pipeline using YOLOv8 to detect insulator defects in aerial drone imagery. 85%+ mAP, FastAPI inference server at 15+ FPS on CPU.

**[Parabix SIMD](https://github.com/kza40/SIMD_AudioNormalization)** - C++ SIMD prototype for the Parabix open-source framework. 5-8x throughput over scalar baselines, a lot of gdb time to get there.

---

## Background

- **Amazon** (Summer 2026) - SDE Intern, agentic AI systems: prompt architecture, MCP, A2A protocol design, guardrail research
- **Delta-Q Technologies** - Embedded software on EV charging systems, ETL pipelines for 1,500+ IoT units
- **SFU Satellite Team** - Ground control platform processing 200+ packets/sec with real-time anomaly detection

---

Python · C++ · PyTorch · CUDA · FAISS · React · FastAPI · Docker · Linux

📬 [kza40@sfu.ca](mailto:kza40@sfu.ca) · 🌐 [kiarashzamani.com](https://kiarashzamani.com)