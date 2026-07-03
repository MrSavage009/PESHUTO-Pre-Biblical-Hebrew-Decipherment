# Title: פְּשׁוּטוֹ (Peshuto) • Scribal Concordance Explorer

An interactive computational philology tool and AI-engineered revisionist semantic engine designed to analyze translation shifts and reverse-engineer theological overlays in the biblical Hebrew lexicon.

The framework is named after the classical term for the literal, unadorned, contextual sense of a text (*Peshuto shel Mikra* — פשוטו של מקרא). It strips away historical sectarian biases by leveraging large language models to re-evaluate Semitic roots through non-biblical comparative databases and rigorous contextual gap-fill analyses.

<p align="center">
  <a href="https://mrsavage009.github.io/PESHUTO-Pre-Biblical-Hebrew-Decipherment/">
    <img src="https://img.shields.io/badge/PESHUTO_ENGINE-LIVE_DEMO-1b4d3e?style=for-the-badge&logo=google-gemini&logoColor=f5eedc" alt="Live Demo" />
  </a>
</p>


```
                  +-----------------------------------+
                  |      STARTING VERSE REFERENCE     |
                  +-----------------------------------+
                                    │
                                    ▼
                  +-----------------------------------+
                  |      L0 IMMUTABLE STATE CACHE     |
                  +-----------------------------------+
                                    │
                  ┌─────────────────┴─────────────────┐
                  ▼                                   ▼
        [ Methodology I: Orange ]           [ Methodology II: Purple ]
          Comparative Semitic                 7-Verse Contextual
         Cognate Reconstruction               Cloze Gap-Fill Analysis
                  │                                   │
                  ▼                                   ▼
        Pre-Biblical Root Recovery           10 Contextual Fit-ins
```

---

## Key Framework Features

* **Dual-Methodology AI Revisionist Engine:**
    * **Methodology I (Orange Axis):** Reconstructs pre-biblical, socio-contractual meanings of target words using non-theological Northwest Semitic comparative cognate sources (Ugaritic, Phoenician, Akkadian, ancient Arabic).
    * **Methodology II (Purple Axis):** Synthesizes a seven-verse context window ($V_{-3}$ to $V_{+3}$), strips the target word into a blank gap `[_______]`, and evaluates the surrounding literary environment to generate exactly 10 logical alternative fit-ins.
* **Sleek 3D Cover Flow View:** A mathematically modeled, responsive client-side Cover Flow view that positions the central active card flat to the screen for complete legibility while adjacent cards fade out to eliminate layout distortion.
* **17 Pre-compiled High-Fidelity Cards:** Includes detailed offline backup records, historical context windows, and comparative etymologies for major biblical passages containing the root *hesed* (חֶסֶד).
* **Direct Gemini API Gateway:** Fully operational client-side orchestration layer. Users can input a Gemini API Key for live custom reconstructions or run on built-in, highly detailed offline database fallbacks.
* **Exhaustive Ledger:** An index cataloging all 248 occurrences of the target root across the Hebrew Bible, completely searchable and filterable.

---

## Architectural Foundation

This project implements the theoretical paradigms established in the *PESHUTO Framework Whitepaper*, establishing a client-side architecture that divides historical processing into:

* **L0 (Immutable Archive):** Content-addressing, hashing, and tracking of raw source materials.
* **L1 (Local Manifold):** Pathfinding and weight distribution between contextual nodes.
* **L2 (Prompt Gateway):** Dynamic JSON schema generations dispatched to Gemini.
* **L3 (Commit Log):** Cryptographic ledgers of all interpretive operations.

---

## Getting Started

1. **Clone the Repository:** Download or clone the `index.html` file in this repository.
2. **Launch locally:** Open the file directly in any modern desktop or mobile web browser.
3. **Execution Mode (Optional):** Provide your **Google Gemini API Key** in the configuration gateway at the top of the interface to run live interactive reconstructions. If left empty, the engine automatically defaults to the pre-compiled comparative data.
