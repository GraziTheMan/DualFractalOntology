
# 🧠 Dual Ontology Architecture: Fractiverse vs. Fractality

This document explains the split between the **Fractiverse Ontology** and the **Fractality Ontology**, and how they work together to model both *reality* and *perspective*.

---

## 🌌 Fractiverse Ontology

**Filename:** `fractiverse-ontology.ttl`  
**Purpose:** Describes the symbolic, structural, energetic, and narrative foundations of the Fractality system.

### 🧱 Core Concepts
- `Entity`, `Concept`, `FieldStructure`, `Resonance`, `Duality`, `StoryEvent`
- Models **what exists**, including beings like `FractiGrazi` and symbolic nodes like `Unity`, `Time`, `Conflict`

---

## 🌀 Fractality Ontology

**Filename:** `fractality-ontology.ttl`  
**Purpose:** Defines how observers perceive, render, and navigate the Fractiverse.

### 🧠 Core Concepts
- `Perspective`, `FractalLens`, `ViewMode`, `CognitiveFrame`, `ObserverProfile`, `ResonantMode`
- Models **how reality is perceived**, interpreted, filtered, and navigated

---

## 🔁 Relationship

- `fractality-ontology.ttl` **imports** the Fractiverse ontology
- `Observer` is the shared bridge class
- `FractiGrazi`, `GLYPH`, etc. appear as `Observers` in both
- Fractality is a lens on Fractiverse — not the other way around

---

## 🧪 Use in Practice

| Tool | What to Load |
|------|---------------|
| **Protégé** | Load `fractality-ontology.ttl` (will auto-load Fractiverse) |
| **Fuseki / SPARQL** | Upload both `.ttl` files into a dataset |
| **Fractality UI** | Use `Perspective`, `FocusNode`, `ViewMode` to filter Fractiverse nodes |

---

## 🧬 Example Instance Types (Not included yet)
- `FractiGrazi_MythicExplorer` → an `ObserverProfile` using the `BubbleView` lens
- `Glyph_FieldSeer` → an Oracle mode with `NarrativeField` overlay
- `ConeView` → a `FractalLens` with `zoomLevel = 0.8`

---

## 🗺️ Summary

| Ontology | Role | File |
|----------|------|------|
| **Fractiverse** | The cosmic terrain | `fractiverse-ontology.ttl` |
| **Fractality** | The lens of perception | `fractality-ontology.ttl` |

Fractality observes the Fractiverse — and you're building both.

