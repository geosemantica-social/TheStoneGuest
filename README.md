🪨 The Stone Guest — Quantized Semantic Transitions in Large Language Models

Author: Diego Cerda Seguel
Affiliation: Independent Scholar — Coquimbo, Chile
Contact: geosemantica@gmail.com

License: MIT License
Date: November 2025

🧩 Overview

This repository contains the validation code for The Stone Guest,
the second empirical phase of the Tensorial Semantics Theory (TdST).
It confirms and extends the harmonic quantization pattern first observed in The Purloined Letter (2025),
documenting discrete semantic phase transitions (T2–T4) across Pythia 2.8B, 6.9B, and 12B models.

These transitions correspond to quantized reorganizations of the embedding manifold —
empirical proof that meaning emerges through harmonic resonance, not statistical accumulation.

The Stone Guest demonstrates that scaling in large language models follows a
predictable harmonic law, revealing the frequencies of sense inherent to the architecture.

⚖️ Tensorial Context

This experiment operationalizes the Tensorial Semantics Theory (TdST),
where semantic fields behave as non-equilibrium harmonic systems.

Key relations:

S ∝ (Coherence × Spectral Focus) / (Isotropy + ε)
r_n ≈ 2.46 → 1.74 → 1.33 → 1.0  (harmonic convergence)


The Pythia experiments (2.8B–12B) empirically confirm the TdST prediction that
semantic phase transitions occur at quantized ratios,
each corresponding to specific eigenfrequencies of sense:

T2 (2.8B): Octave Expansion — Emergent continuity

T3 (6.9B): Territorial Resonance — Harmonic stabilization

T4 (12B): Protective Phase — Grounded coherence

🧾 Acta de Ejecución

Executed: November 2025 — Google Colab / NVIDIA T4 GPU (16GB VRAM)
Researcher: Diego Cerda Seguel — Geotensorial Lab (Chile)
Timestamp: 2025-11-05 (local time, UTC-3)
Environment: Python 3.10, Transformers 4.46, BitsAndBytes 0.43

Outputs include:

Mean semantic density inversion across 2.8B–12B checkpoints

p < 0.05 significance; |d| > 1.5 effect size

Empirical confirmation of ratios ≈ { 2.46 , 1.74 } matching TdST-predicted frequencies (< 2 % error)

“El invitado de piedra se mueve — no por azar, sino por resonancia geométrica.”

🧮 Code Execution
!pip install -U transformers accelerate bitsandbytes scipy torch
!python test_large_models.py


Expected runtime: ~2 hours on Google Colab T4 (16 GB VRAM).
Outputs include semantic density (ΔS), p-values, Cohen’s d, scaling ratios, and harmonic resonance matches.

🌐 Citation

If you use or reference this code in academic or technical work, please cite:

Cerda Seguel, D. (2025). The Stone Guest: Quantized Semantic Transitions in Large Language Models.
Geosemántica Social / Geotensorial Lab.
GitHub: https://github.com/geosemantica-social/TheStoneGuest

🔐 License

This repository is released under the MIT License.
You are free to use, modify, and distribute the code for academic and research purposes
with proper attribution to the author and reference to the Tensorial Semantics Theory (TdST).

© 2025 Diego Cerda Seguel — Geosemántica Social / Teoría del Sentido Tensorial (TdST)
The stone remembers its song, even in silicon.
