# Mirror

> *See clearly. Choose consciously.*

---

# 🧠 Product Overview

Mirror is an AI reflection system designed to help users understand their emotional patterns, recurring behaviors, and internal narratives through structured conversational interaction.

Instead of providing advice, Mirror focuses on:
- reflection
- pattern recognition
- emotional clarity
- conscious choice-making

The system is built around a conversational architecture where **UX = intelligence**.

---

# 🧩 Core Design Principle

> The product is not a chatbot.  
> The product is a reflection engine.

Each interaction is designed to surface:
- emotional states
- behavioral patterns
- cognitive loops
- unmet needs

---

# 🧭 Feature Map

## Daily Use — Real-time emotional input

### Ouch
Capture raw emotional states.

- User inputs: feelings, sensations, internal tension
- AI role: help label and clarify emotion without interpretation
- Output: emotional articulation + soft reflection

---

### Oops
Process situational emotional triggers.

- User inputs: specific events or interactions
- AI role: deconstruct the event into emotional components
- Output: trigger → reaction mapping

---

### Tell Me More
Deep conversational exploration.

- User inputs: topic or emotional thread
- AI role: guided inquiry through layered questioning
- Output: deeper understanding of underlying patterns

---

## Understanding Yourself — Pattern recognition layer

### Unpack
Baseline emotional exploration without context.

- explores internal tendencies
- identifies emotional defaults
- builds initial psychological profile (non-clinical)

---

### In-Sight
Structured reflection engine.

- aggregates insights across sessions
- surfaces emerging themes
- converts conversations into patterns

---

### Again
Recurrence detection system.

- identifies repeating emotional loops
- connects past interactions
- highlights behavioral cycles

---

### Red Flag
Gentle risk awareness layer.

- detects potentially harmful dynamics
- surfaces blind spots
- maintains non-judgmental tone

---

## Growth — Behavioral evolution layer

### Undo
Reframing past reactions.

- explores alternative interpretations
- introduces new response options
- supports cognitive flexibility

---

### Reparent
Self-compassion + emotional support layer.

- addresses unmet emotional needs
- provides grounding responses
- supports inner-child style reflection (non-clinical framing)

---

### Anyway...
Micro-practice system for daily integration.

- short reflective exercises
- emotional regulation prompts
- habit reinforcement through awareness

---

## Reflection — Long-term identity layer

### Lore
Personal narrative construction.

- stores meaningful insights over time
- builds coherent self-understanding
- creates reflective identity snapshots

---

### Spiral *(future feature)*
Longitudinal emotional evolution mapping.

- visualizes change over time
- tracks emotional and behavioral trajectories
- highlights transformation patterns

---

# 🧠 Data & Memory Philosophy

Mirror does NOT store raw conversations as primary value.

Instead it extracts:
- emotional signals
- recurring themes
- behavioral loops
- relational patterns

### Stored data types:
- emotional states
- triggers
- recurring patterns
- cognitive loops
- user-defined reflections

### Not stored:
- full transcripts
- unnecessary personal detail
- deterministic judgments

---

# ⚙️ System Architecture (High-Level)

```text
User Input
   ↓
Conversation Engine (LLM)
   ↓
Pattern Extractor
   ↓
Memory Layer (Postgres)
   ↓
Insight Generator
   ↓
Reflection Output