# OpenVero 🕊️

> **The Open Standard for Multilingual AI Text Detection & Calibrated Truth.**  
> *Spec-driven detectors. Modular language packs (ISO 639-3). Zero monolith memory overhead.*

---

### 🌐 The Problem We Solve
Traditional AI detectors load multi-gigabyte models into memory and rely on brittle global offset patches—forcing a Chinese or Spanish user to pay an 8 GB RAM tax for English-centric neural weights.

**OpenVero shifts the paradigm:**
* 📦 **Language Pack as the Core Abstraction**: 1 Language = 1 Lightweight Distributable Pack (`openvero-lang-<iso>`). Load only what you scan.
* 🃏 **Everything is a Card**: Detectors, corpora, language packs, and benchmarks are versioned via strict JSON Schemas aligned with Hugging Face conventions.
* 🔌 **Zero-Python Registration**: Community engines connect seamlessly via standard Python `pip entry-points`.

---

### 🧱 The OpenVero Trinity
