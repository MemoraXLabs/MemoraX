# MemoraX Memory Layer — Spec v0.1

**The memory layer for long-horizon intelligence**

*For a high-level introduction and diagnostic question, see the [README](README.md).*

---

## 1. Purpose

MemoraX defines the missing layer in the AI stack that enables long-horizon intelligence.

Modern AI systems are episodic.  
They act, respond, and reset.

Long-horizon systems require something different:  
they must remain the same system as they learn, remember, and evolve over time.

That capability is not provided by:
- models  
- tools  
- vector stores  
- databases  
- retrieval pipelines  

MemoraX defines the memory layer that provides:
- persistent identity  
- continuity across sessions  
- compounding understanding  

---

## 2. Position in the AI Stack

MemoraX sits between models and agents.

- Models → reason  
- Tools → act  
- Storage → store  
- **MemoraX → persist identity across time**

Storage remembers data.  
**MemoraX remembers the system.**

---

## 3. Core Concepts

MemoraX defines three primitives.

### 3.1 Identity

An Identity represents a single continuous intelligent system.

An identity:
- persists across sessions  
- anchors all memory operations  
- remains stable as the system evolves  

Identity is not a user.  
It is not an account.  
It is the continuous self of an AI system.

---

### 3.2 Memory Objects

All memory in MemoraX is stored as **Memory Objects**.

Each memory object contains:
- `memory_id`  
- `identity_id`  
- `content`  
- `timestamp`  
- `confidence`  
- `source`  

Memory objects are not static logs.  
They are part of the system’s evolving self.

---

### 3.3 Continuity Graph

MemoraX stores memory in a **continuity graph**.

The graph represents:
- what the system knows  
- how it learned it  
- how its understanding has changed  

Memory is not only retrieved.  
It shapes future behavior.

---

## 4. Core Operations

MemoraX defines four operations:

- **WRITE**  
  Store new memory for an identity.

- **UPDATE**  
  Modify existing memory based on new experience.

- **MERGE**  
  Resolve conflicting memories into a coherent state.

- **READ**  
  Retrieve memory in the context of the identity’s history.

MemoraX memory is always interpreted through continuity.

---

## 5. Relationship to RAG and Storage

RAG retrieves documents.  
MemoraX maintains identity.

RAG answers questions.  
MemoraX shapes behavior.

RAG is stateless.  
**MemoraX is continuous.**

---

## 6. Relationship to Implementations

Systems such as:
- AgeMem  
- Mem0  
- Zep  
- Memento  

are implementations of memory.

MemoraX defines the abstraction that makes memory a **first-class layer** in long-horizon intelligence.

---

## 7. Why This Layer Exists

Without a memory layer:
- agents forget  
- identity collapses  
- learning resets  
- long-horizon tasks fail  

With MemoraX:
- systems accumulate experience  
- identity persists  
- understanding compounds  
- intelligence extends across time  

---

## 8. Status

MemoraX defines the **canonical memory layer** for long-horizon intelligence.

This document is the first formal specification of that layer.
