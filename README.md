# Quantum Resonance Lab

Quantum Resonance Lab is a hands-on educational atlas of matter, energy, frequency, and time. Its learning paths, wave laboratory, atomic visualizations, frequency experiments, mathematical tools, and research notebook make complex physics concepts approachable. Conceptual simulations and octave-reduced tones should not be mistaken for precision measurements or actual atomic sounds.

**At a glance:** An interactive physics laboratory exploring waves, quantum states, atomic transitions, electromagnetic spectra, atomic clocks, octave mappings, and the mathematics of resonance.

---

# Quantum Resonance Lab — Version 1.0

**The Interactive Atlas of Matter, Energy, Waves & Time**

An interactive physics-learning application designed to prepare for a future scientifically grounded Atomic Synthesizer.

## Current implementation

The single-file `index.html` contains an Observatory, Learning Paths (10 introductory lessons), Wave Laboratory (two-wave superposition), electromagnetic Spectrum Navigator, Atomic Atlas, idealized hydrogen Quantum States diagram, Atomic Transitions, Atomic Clocks feedback illustration, Octave Laboratory with audible sine-wave preview, Mathematics Studio, navigable Knowledge Atlas, Discovery Challenges, locally saved Research Notebook, and Research Library.

The app uses HTML, CSS, JavaScript, SVG, Canvas, and Web Audio API. No external dependencies, account, backend, or API key.

## Launch

Open `index.html` in a modern browser. To publish with GitHub Pages, go to **Settings → Pages**, select **Deploy from a branch**, then choose `main` and `/ (root)`.

This repository was created as **private**; GitHub Pages availability depends on your plan and repository settings. A live website has not yet been verified.

## Scientific limitations

- Cesium-133's 9,192,631,770 Hz transition frequency is exact by SI definition.
- Other starter transition values are approximate or rounded. The full sourced 88-transition dataset and uncertainties are **not** yet implemented.
- The hydrogen energy diagram uses the idealized −13.6 eV/n² approximation, not precision spectroscopy.
- The wave display and clock-feedback illustration are conceptual models.
- Octave reduction is a mathematical mapping, not sound emitted by an atom.
- Audio precision depends on browser and hardware.
- Progress and notes use browser localStorage; this is **not encrypted** or synchronized.

## Scientific sources

- [NIST Atomic Spectra Database](https://physics.nist.gov/asd)
- [NIST Fundamental Constants](https://physics.nist.gov/cuu/Constants/)
- [BIPM SI Second](https://www.bipm.org/en/si-base-units/second)

## Development roadmap

1. Expand the complete 12-module curriculum and conceptual learning paths.
2. Curate scientifically verified atomic transitions with isotopes, state identifiers, uncertainty, and provenance.
3. Add Fourier, interference-over-time, probability-density, orbital, and spectral-line simulations.
4. Add adaptive learning, experiment recording, complete JSON backup/restore, and accessibility improvements.
5. Add automated tests, offline/PWA support, and full mobile browser testing.
6. Develop the separate Atomic Synthesizer using the validated transition dataset.

## License

MIT License — Copyright (c) 2026 Jared Thomas. See [LICENSE](LICENSE).

**Status:** Initial functional foundation. Browser-based testing and independent numerical validation have not yet been completed.
