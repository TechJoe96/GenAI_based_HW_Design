# GenAI based HW Design

**Ecosystem** is a collection of AI-powered tools designed to support *hardware designers, computer architects, and verification engineers* across the full chip development lifecycle — from ideation and learning, to RTL generation, verification, and reasoning.

This repository introduces four core components:

- **Chip-Chat** – Your interactive hardware design mentor  
- **Auto Chip** – Automated chip and RTL generation  
- **Veritas** – Intelligent hardware verification assistant  
- **VeriThoughts** – Formal reasoning and explainability for hardware

Together, they aim to make chip design more **accessible, correct, and efficient**.

---

## Chip-Chat

**Chip-Chat** is an AI-powered conversational assistant specialized in **computer architecture, digital design, VLSI, and AI hardware**.

### Background & Research

The idea of using large language models (LLMs) for hardware design assistance stems from recent research highlighting how LLMs can support *design space exploration* and *code assistance* in hardware flows. One foundational concept around using conversational LLMs in hardware design workflows was discussed by Blocklove et al., where prompt-based interaction aids iterative RTL design and architecture exploration, demonstrating proof-of-concept for an AI-guided design loop. :contentReference[oaicite:0]{index=0}

> **Reference**: Blocklove et al., *LLM-Assisted Design Space Exploration (“Chip Chat”)* — illustrates how conversational AI can aid RTL and architectural tasks. :contentReference[oaicite:1]{index=1}

### Example use cases

- Learning pipelining, cache coherence, or systolic arrays  
- Debugging Verilog/SystemVerilog testbenches  
- Translating architecture ideas into implementable RTL

**Chip-Chat acts as your always-available hardware mentor.**

---

## Auto Chip

**Auto Chip** focuses on **automated hardware generation** — transforming high-level intent into concrete hardware artifacts.

### Background & Research

Automated RTL and hardware generation using intelligent agents and LLMs is an active research area. For example, *Spec2RTL-Agent* demonstrates how multi-agent systems can reduce human intervention in RTL generation workflows with agentic reasoning and adaptive refinement, highlighting the potential for automation in real designs. :contentReference[oaicite:2]{index=2}

> **Reference**: Yu, Liu, et al., *Spec2RTL-Agent: Automated Hardware Code Generation from Complex Specifications using LLM Agent Systems*. :contentReference[oaicite:3]{index=3}

### Example use cases

- Auto-generating a systolic array from matrix dimensions  
- Creating parameterized FSMs or pipelines  
- Rapid prototyping of accelerators for research or coursework

**Auto Chip reduces boilerplate and accelerates hardware iteration.**

---

## Veritas

**Veritas** is an AI assistant dedicated to **hardware verification and correctness**.

### Background & Research

Verification remains a bottleneck in hardware design; LLMs and AI are being explored to help automate and improve RTL verification flows. Surveys and studies show the potential of LLMs to handle complex aspects of simulation, assertion generation, and verification automation, identifying key challenges and opportunities. :contentReference[oaicite:4]{index=4}

> **Reference**: Abdollahi, *Hardware Design and Verification with Large Language Models* — a comprehensive survey discussing LLM-aided verification. :contentReference[oaicite:5]{index=5}

### Example use cases

- Writing a clean testbench for a CPU pipeline  
- Debugging mismatches between RTL and reference models  
- Generating assertions for protocol compliance

**Veritas ensures your hardware works as intended — not just once, but always.**

---

## VeriThoughts

**VeriThoughts** focuses on **reasoning, explainability, and formal thinking in hardware design**.

### Research Paper

One core reference for VeriThoughts is:

> **VeriThoughts: Enabling Automated Verilog Code Generation using Reasoning and Formal Verification**  
> Patrick Yubeaton, Andre Nakkab, Weihua Xiao, Luca Collini, Ramesh Karri, Chinmay Hegde, Siddharth Garg (2025). arXiv.  
> *This paper introduces VeriThoughts, a dataset and benchmark framework grounded in formal verification methods to evaluate reasoning-augmented Verilog code generation.* :contentReference[oaicite:6]{index=6}

This work highlights the importance of combining *reasoning and formal verification* to generate more correct hardware from high-level prompts.

### Example use cases

- Understanding why a pipeline hazard resolution works  
- Explaining correctness of cache protocols  
- Teaching formal reasoning to beginners

**VeriThoughts makes hardware correctness understandable, not mysterious.**


