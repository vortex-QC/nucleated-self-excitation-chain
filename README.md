# Nucleated Self-Excitation — The Reasoning Chain (Protein Paper Companion Repo)

This repository hosts, in citable and machine-readable form, the **six-step reasoning chain from the atomic level to nucleated self-excitation** — the derivation core of:

> Qin, Chao (2026). *Nucleated Self-Excitation: Conformational Propagation and Self-Sustained Excitation in Proteins, and a Universal Mechanism.* Zenodo. doi:10.5281/zenodo.23860530 (v1.2) · concept doi:10.5281/zenodo.23858233 (all versions) · CC-BY-4.0.

## The chain in one line

Conformational energy landscape (multiple minima + barriers) → **duality of the excited state** (a misfolded/excited molecule is simultaneously an attenuator, rate γ, and an exciter, rate β — the atomic definition of self-excitation) → rate ratio R=β/γ → **crossing one** (R>1: self-sustaining propagation; lag phase = pre-crossing accumulation; seed dose = forward shift of crossing time) → population coherence into macroscopic structure (the nucleation divide; R>1 necessary, not sufficient — barrier crossing layered on top) → cross-domain bridge (the same structure instantiated in chemical replication, ecology, epidemiology; R0=β/γ is the same quantity, not an analogy).

## Files

| File | Content |
|---|---|
| `reasoning_chain.md` | The six steps, verbatim from paper §2 (EN v1.2) |
| `reasoning_chain.json` | Machine-readable form: steps + statements + established basis, derived definitions (three-layer criterion), and the testable prediction with its first-round data check |

## Testable prediction (see `reasoning_chain.json`)

t_lag = [1/(β−γ)]·ln(N_det/S₀): lag linear in ln(seed dose) with mechanically interpretable slope. First-round check on four literature systems (prion RT-QuIC, IAPP 30%/70% DOPS, tau): log-linear in 4/4, ΔAIC≤−10 in 3/4, β−γ inversions all positive, independent cross-validation λ_theory/λ_fit = 1.23 (paper §4.1b).

## Related

- Companion paper (field-medium / wave form): doi:10.5281/zenodo.23858235 (concept) — inverse pass-through spectrum repo: `vortex-QC/inverse-pass-through-spectrum`
- Applied-empirical line (model cards): doi:10.5281/zenodo.23613761, doi:10.5281/zenodo.23610599

## License

CC-BY-4.0 (as the source paper). Author: Chao Qin (ORCID 0009-0006-2000-5644).
