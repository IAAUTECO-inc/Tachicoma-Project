# Project Tachikoma (formerly Lemonade)
## Sovereign Infrastructure for Inclusive Robotics & Social AI

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](LICENSE)
[![OpenChain](https://img.shields.io/badge/OpenChain-ISO%2FIEC%205230-green)](https://www.openchainproject.org/)
[![OS](https://img.shields.io/badge/OS-Winterhold--BSD-black)](https://github.com/IAAUTECO-inc/winterhold)

### Overview
Project Tachikoma is the hardware-software orchestration layer of the **IA_AUT_ECO** ecosystem. It provides the high-level cognitive and motor interfaces for assistive robotics, operating strictly within the **AEGIS Governance Framework**. 

Designed for long-term resilience, Tachikoma ensures that assistive technology remains an autonomous "Common," free from extraterritorial cloud dependencies.

### Key Architectural Pillars
- **Layer 1 Orchestration:** Native integration with Winterhold OS (Hardened FreeBSD).
- **Deterministic Vision:** Semantic processing via the AEGIS-Hearthfire core.
- **Zero-Cloud Mandate:** Local-first inference to guarantee user privacy and safety.
- **Interoperability:** Modular interfaces in C++ and Go for real-time robotic control.

### OpenChain Compliance
This project adheres to the ISO/IEC 5230 standard. Every contribution is tracked, and every dependency is audited to ensure a clean and sovereign supply chain.

### Getting Started
```bash
git clone [https://github.com/IAAUTECO-inc/tachikoma.git](https://github.com/IAAUTECO-inc/tachikoma.git)
cd tachikoma
make build-hardened


# Lemonade SDK Documentation

This documentation has moved to our main documentation site.

## Lemonade Server

For the Lemonade Server (OpenAI-compatible HTTP server for local LLMs), see:

**[Lemonade Server Documentation →](https://lemonade-server.ai/docs/)**

## lemonade-eval CLI

For the `lemonade-eval` CLI (benchmarking, accuracy evaluation, and model preparation), see:

**[lemonade-eval Documentation →](./eval/README.md)**

<!--This file was originally licensed under Apache 2.0. It has been modified.
Modifications Copyright (c) 2025 AMD-->
