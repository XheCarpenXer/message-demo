
# **DLDSS v1.0: Deterministic Local DAG State System**
### *The Foundation for Serverless, Multi-Context, and Sovereign AI Systems*

**Author:** James Chapman (@XheCarpenXer)

---

## 🚀 The Vision

**DLDSS (Deterministic Local DAG State System)** is a client-native architecture designed to eliminate the "Cloud Tax." It enables shared, deterministic state across multiple execution contexts—such as browser tabs, web workers, and peers—without requiring a central server, database, or external API.

This repository serves as a live demonstration of **DLDSS v1.0**, proving that high-speed collaboration and strong data integrity can exist entirely at the edge.

---

## 🌐 Live Demo: Experience Serverless Sync

Open the demo in two separate browser tabs and observe the system in action:

- Instant synchronization  
- Zero network latency  
- No backend or server dependency  

---

## 🛠 How It Works (Core Architecture)

Traditional web applications rely on a centralized "source of truth."  
DLDSS inverts this model by making the **local device the authority**.

### 🔹 Append-Only Event DAG
All application state is represented as an immutable sequence of events organized in a **Directed Acyclic Graph (DAG)**.

### 🔹 Intra-Device Broadcast
State is synchronized across execution contexts using the **BroadcastChannel API**, enabling real-time, zero-latency updates between tabs and workers.

### 🔹 Deterministic Replay
Each node reconstructs application state by replaying the same event log, guaranteeing identical outcomes across all contexts.

### 🔹 Local-First Persistence
All data is stored locally using **localStorage** or **IndexedDB**, ensuring user ownership and offline capability.

---

## 🧬 Road to v2.0: Sovereign AI

DLDSS v1.0 is the foundation for a broader evolution into a **Globally Distributed AI Substrate**.

### 🔹 Deterministic AI
AI inference outputs are treated as immutable events within the DAG, making them reproducible, verifiable, and auditable.

### 🔹 Peer-to-Peer Synchronization
Cross-device state replication is enabled via **WebRTC**, allowing direct communication without centralized infrastructure.

### 🔹 Privacy by Architecture
Data and AI models remain local to the user’s device—never requiring transmission to external servers.

---

## ⚖️ Licensing

This project is released under the **DLDSS Dual License v1.0**:

- **Free for Personal & Research Use**  
  Use, experiment, and build for non-commercial purposes.

- **Commercial License Required**  
  Required for SaaS platforms, enterprise deployments, or revenue-generating applications.

**Copyright (c) 2026 James Chapman. All rights reserved.**

---

## 🤝 Connect & Collaborate

This system represents five years of independent research and development toward a **sovereign, local-first internet**.

If you're a developer, researcher, or investor interested in decentralized systems or local-first AI, let’s connect:

- **LinkedIn:** James Chapman  xhecarpenxer@gmail.com
- **GitHub:** [@XheCarpenXer](https://github.com/XheCarpenXer)

---
