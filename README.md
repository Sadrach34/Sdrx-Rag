<div align="center">
  
```
                                  ███████╗██████╗ ██████╗ ██╗  ██╗
                                  ██╔════╝██╔══██╗██╔══██╗╚██╗██╔╝
                                  ███████╗██║  ██║██████╔╝ ╚███╔╝ 
                                  ╚════██║██║  ██║██╔══██╗ ██╔██╗ 
                                  ███████║██████╔╝██║  ██║██╔╝ ██╗
                                  ╚══════╝╚═════╝ ╚═╝  ╚═╝╚═╝  ╚═╝
```

# sadrach34 / sdrx-Rag

**Local AI · RAG · Tool-driven system** — experimental local intelligence system focused on real utility.

![](https://img.shields.io/github/last-commit/Sadrach34/sdrx-Rag?style=for-the-badge\&color=cba6f7\&labelColor=1e1e2e\&logo=git\&logoColor=cdd6f4)
![](https://img.shields.io/github/stars/Sadrach34/sdrx-Rag?style=for-the-badge\&color=f38ba8\&labelColor=1e1e2e\&logo=starship\&logoColor=cdd6f4)
![](https://img.shields.io/github/repo-size/Sadrach34/sdrx-Rag?style=for-the-badge\&color=a6e3a1\&labelColor=1e1e2e\&logo=files\&logoColor=cdd6f4)

</div>

---

<div align="center">
  <h2>· overview ·</h2>
</div>

**sdrx-Rag** is a local-first AI system designed to go beyond simple chat.

The goal is not to replicate ChatGPT, but to build a **controlled, extensible system** that can:

* interact with real data (files, system, projects)
* use tools deterministically
* maintain long-term memory
* switch between models dynamically
* execute structured tasks instead of generating raw text

This project follows a **tool-driven + RAG-based architecture**, where the model is only responsible for reasoning, not execution.

---

<div align="center">
  <h2>· goals ·</h2>
</div>

* Build a **useful local AI**, not a generic chatbot
* Keep **full control over execution flow** (no blind autonomy)
* Ensure **model-agnostic design** (swap models anytime)
* Implement **memory that actually matters** (not just chat history)
* Enable **real actions** via tools (files, system, automation)

---

<div align="center">
  <h2>· architecture (simplified) ·</h2>
</div>

```
User Input
   ↓
Router (rules + fallback to LLM)
   ↓
LLM (planning only)
   ↓
Structured Output (JSON)
   ↓
Executor (deterministic)
   ↓
Tools (files, system, memory)
   ↓
Memory (RAG)
   ↓
Response
```

---

<div align="center">
  <h2>· stack ·</h2>
</div>

* Local LLM runtime (via Ollama)
* RAG memory system (Chroma or similar)
* Python as orchestration layer
* JSON-based structured execution
* Optional: Redis for short-term state

---

<div align="center">
  <h2>· current status ·</h2>
</div>

> 🚧 **This project is in early development.**

Core ideas are being tested and refined.
Expect breaking changes, incomplete features, and rapid iteration.

---

<div align="center">
  <h2>· contributing ·</h2>
</div>

Contributions are welcome.

If you want to:

* improve architecture
* add tools
* optimize memory
* experiment with agent systems

Open an issue or contact me directly.

---

<div align="center">
  <h2>· support ·</h2>
</div>

If you find this project interesting or useful, you can support it by:

* contributing code
* sharing ideas
* reporting issues

You can also donate if you want to support development.

---

<div align="center">
  <h2>· contact ·</h2>
</div>

* GitHub: [https://github.com/Sadrach34](https://github.com/Sadrach34)
* Email: *jdiego0805+dev@gmail.com*

> I respond faster on GitHub.

---

<div align="center">
  <h2>· philosophy ·</h2>
</div>

This project is built around a simple idea:

> **AI should assist execution, not replace control.**

---

## License
