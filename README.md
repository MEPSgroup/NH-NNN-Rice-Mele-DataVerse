This readme file was generated on 2026-09-29 by Dario Bercioux

# GENERAL INFORMATION

* Title of Dataset: Replication Data for: Tuning topological phases and exceptional points in a non-Hermitian Rice-Mele model beyond nearest neighbors

* Abstract: Exceptional points are degeneracies characteristic of non-Hermitian operators, where eigenvalues and eigenvectors coalesce, rendering the Hamiltonian defective. We investigate the exceptional-point structure and topological properties of a generalized non-Hermitian Rice-Mele model with balanced gain and loss, as well as next-nearest-neighbor hopping. The system hosts only second-order exceptional points under both periodic and open boundary conditions. Under periodic boundary conditions, the exceptional points in parameter space lie on lines and ellipses that are independent of the next-nearest-neighbor hopping, since the latter enters the bulk Hamiltonian only as an identity contribution. Under open boundary conditions, this independence is broken: the next-nearest-neighbor hopping not only shifts the energy of existing exceptional points but also generates new ones, with a specific condition signaling a topological gap closing observed only in the open-boundary spectrum. At special parameter points, multiple simultaneous second-order exceptional points yield degenerate configurations whose degeneracy grows with system size. Exceptional point locations are identified numerically via the condition number of the eigenvector matrix and confirmed by Jordan decomposition. The topological phase diagram, computed via a winding number framework for non-Hermitian systems without symmetry protection, reveals sectors with zero, one, and two edge states; the bulk-boundary correspondence is confirmed, and the non-Hermitian skin effect is absent.

## CONTACT INFORMATION

## Author/Principal Investigator Information

Name: Dario Bercioux
ORCID: 0000-0003-4890-5776
Institution: Donostia International Physics Center
Address: Paseo Manuel de Lardizabal 4, Donostia, 20018, Spain
Email: dario.bercioux@dipc.org

## Author/Associate or Co-investigator Information

Name: Carolina Martínez-Strasser
ORCID: 0000-0002-5072-941X
Institution: Donostia International Physics Center
Address: Paseo Manuel de Lardizabal 4, Donostia, 20018, Spain
Email: cmartinez089@ikasle.ehu.eus

## Author/Associate or Co-investigator Information

Name: Nico Leumer
ORCID: 0000-0002-7762-9304
Institution: Department of Theoretical Physics, Wrocław University of Science and Technology
Address: Wybrzeże Wyspiańskiego 27, 50-370 Wrocław, Poland
Email: nico.leumer@pwr.edu.pl

##

* Date of data collection: 2026-05-29
* Geographic location of data collection: Donostia / San Sebastián, Spain
* Information about funding sources that supported the collection of the data:

    * Funder name: Spanish State Research Agency
    * Project identifier: Severo Ochoa Centres of Excellence Programme, grant CEX2024-001494-S, (DIPC)

    ######

    * Funder name: Spanish State Research Agency
    * Project identifier: PID2024-162933NB-I00 (QUILL)

    ######

    * Funder name: Department of Education of the Basque Government
    * Project identifier: PIBA_2023_1_0007 (STRAINER)

    ######

    * Funder name: Department of Education of the Basque Government and the Gipuzkoa Provincial Council
    * Project identifier: QUAN-000021-01

    ######

    * Funder name: BBVA Foundation
    * Project identifier: "Artificial Quantum Matter: From 2D Materials to Spin Lattice Systems" — Fundamentos Program 2024

    ######

    * Funder name: Transnational Common Laboratory
    * Project identifier: Quantum-ChemPhys


# ACKNOWLEDGEMENTS

We acknowledge the support from the Transnational Common Laboratory Quantum-ChemPhys, the Department of Education of the Basque Government through the project PIBA_2023_1_0007 (STRAINER), the financial support received from the IKUR Strategy under the collaboration agreement between the Ikerbasque Foundation and DIPC on behalf of the Department of Education of the Basque Government and the Gipuzkoa Provincial Council within the QUAN-000021-01 project, and the support from the Spanish MICINN-AEI through Project No. PID2024-162933NB-I00 (QUILL). We acknowledge support from the Severo Ochoa Centres of Excellence Programme, grant CEX2024-001494-S (DIPC). We acknowledge support from the project "Artificial Quantum Matter: From 2D Materials to Spin Lattice Systems" — BBVA Foundation Fundamentos Program 2024.


# SHARING/ACCESS INFORMATION

* Licenses/restrictions placed on the data: MIT License
* Dataset doi: [Filled by the data manager]
* Links to publications that cite or use the data:
    * [Filled by the data manager]
* Preprint: https://arxiv.org/abs/2606.24705
* Links to other publicly accessible locations of the data:
* Was data derived from another source?
    * No
* Recommended citation for this dataset: [Filled by the data manager]

**MIT License**

Copyright (c) 2026 C. Martínez-Strasser, D. Bercioux, N. Leumer

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.


# DATA & FILE OVERVIEW

## File List/Directory Tree:

```
dataset/
│
│   README.md
│   manuscript.pdf                                                           Submitted manuscript (PDF)
├── EPs Bulk_commented.nb                                                    Fig. 2
├── Numerical analysis of EP_no_output_commented.nb                         Fig. 3
└── Topology Eqs and figures of NH NNN Rice-Mele model_commented.nb        Figs. 4–5 and Appendix
```

Each notebook is based on the original working notebook with all key input cells preserved exactly. Explanatory English comments have been added as Text cells before each major code block, with section headings for navigation. Cached output cells are omitted (smaller files, faster to open).

| File | Figure(s) | Description |
|------|-----------|-------------|
| `EPs Bulk_commented.nb` | Fig. 2 | Exceptional points in the Bloch Hamiltonian: four-panel complex-energy plot at representative (t, γ) values |
| `Numerical analysis of EP_no_output_commented.nb` | Fig. 3 | EPs in finite chains: exact symbolic analysis for N = 2, 3, 4 unit cells; discriminant and Jordan decomposition; extended numerics for N = 9, 10 |
| `Topology Eqs and figures of NH NNN Rice-Mele model_commented.nb` | Figs. 4–5, Appendix | Phase maps (condition number, signed dIPR, edge-state count, GBZ winding number); eigenstate profiles at snap points; dIPR phase-transition curve; Riemann-sheet visualisations |
| `manuscript.pdf` | — | Manuscript PDF (submitted version); preprint at [arXiv:2606.24705](https://arxiv.org/abs/2606.24705) |


# METHODOLOGICAL INFORMATION

For the physical model, symmetry analysis, exceptional-point derivations, winding number framework, and dIPR definition, see the manuscript:

> C. Martínez-Strasser, D. Bercioux, N. Leumer, *Tuning topological phases and exceptional points in a non-Hermitian Rice–Mele model beyond nearest neighbors*, arXiv:2606.24705 — <https://arxiv.org/abs/2606.24705>

Key equation numbers referenced in the notebook comments:

| Equation | Content |
|----------|---------|
| Eq. (1) | Real-space tight-binding Hamiltonian |
| Eq. (2) | Bloch Hamiltonian H(k) |
| Eq. (3) | Non-Hermitian Rice–Mele matrix H_RM(k) |
| Eq. (4) | Bulk dispersion relation E±(k) |
| Eqs. (5)–(6) | Exceptional-point threshold conditions γc(k) |
| Eq. (9) | EP loci as ellipses in parameter space |
| Eq. (10) | Condition number definition (EP detection) |
| Eqs. (12)–(13) | Winding number formula |
| Eq. (18) | IPR and dIPR definitions |
| Eqs. (19)–(20) | Edge-state identification threshold |

## INSTALLATION

### Software requirements

The notebooks were created and tested with **Wolfram Mathematica 14.2**. They should be compatible with Mathematica 12.0 and later.

* Download: https://www.wolfram.com/mathematica/
* A paid license is required to evaluate (run) the notebooks.

### Wolfram Player (free viewer — no license required)

To **view** the notebooks without a Mathematica license, use **Wolfram Player**, a free application that opens and displays `.nb` files including all text, formatted mathematics, and pre-computed graphics.

* **Download Wolfram Player (free):** https://www.wolfram.com/player/
* Available for Windows, macOS, and Linux.
* Wolfram Player can display all notebook content and cached output cells.
* **Note:** Wolfram Player cannot evaluate (run) code cells. To reproduce figures from scratch, a full Mathematica license is required.

### Wolfram Engine (free, evaluation-capable)

An alternative for non-production use is **Wolfram Engine** (free), which can evaluate notebooks via the command line and pairs with Jupyter notebooks.

* **Download:** https://www.wolfram.com/engine/

## USAGE

### Notebook structure and run order

#### `EPs Bulk_commented.nb` — Fig. 2

Nine numbered sections, evaluated top to bottom:

| Section | Content |
|---------|---------|
| 1. Initialisation | Export path, options |
| 2. Non-Hermitian Bloch Hamiltonian | H(k) definition, dispersion |
| 3. Exceptional-point conditions | Analytic EP threshold γc(k) |
| 4. EP marker and helper functions | Condition number, contour utilities |
| 5–8. Panels A–D | Complex-energy spectra at four (t, γ) parameter points |
| 9. Final figure | `GraphicsGrid` combining all four panels into Fig. 2 |

#### `Numerical analysis of EP_no_output_commented.nb` — Fig. 3

**Important:** the first cell contains `Exit[]` as a safety guard — skip or disable it before running. Four sections, evaluated in order:

| Section | Content |
|---------|---------|
| Case N = 2 | Exact symbolic characteristic polynomial; Jordan form; EP conditions |
| Case N = 3 | Discriminant analysis; symbolic EP locus |
| Case N = 4 | Extended symbolic analysis |
| N = 9 & 10, m ≠ 0 | Numerical verification; Fig. 3 panels |

#### `Topology Eqs and figures of NH NNN Rice-Mele model_commented.nb` — Figs. 4–5, Appendix

The notebook is organised into four titled parts, each subdivided into chapters and sections:

**Part 1 — NH NNN Rice-Mele model** (setup and function definitions)

| Chapter / Section | Content |
|-------------------|---------|
| Parametrization → Sweeping parameters | Scan-axis variables (t1, m), grid resolution |
| Parametrization → Fixed parameters | Global values: εA = 0, εB = 3/2, Γ = 1, t2 = 1, nn = 40 |
| Plots general configuration | Colour schemes, font sizes, export options |
| Open-boundary Hamiltonian | `HOBCOriginal`: 2nn×2nn block-tridiagonal matrix |
| IPR and dIPR | `IPR`, `DSignBaiStyle`, `dIPRBaiStyle` (signed localisation measure) |
| Edge-state count | `edgeCountLabel`, IPR-threshold filter |
| GBZ helpers | `dzFunc`, `MbrFunc`, `MdegFunc` (complex detuning, branching and degeneracy points) |
| GBZ M-tracks | `analyticMTracks` (analytic continuation around BZ) |
| Sheet association | `sheetAssociationAnalytic` (Riemann sheet–point pairing) |
| Winding numbers | `WindingNumberCrossing`, `WjFuncFast`, `allWindingNumbersFast` |

**Part 2 — Fig. 4: properties computation** (parameter-space scans)

| Chapter | Content |
|---------|---------|
| Condition number matrix | ln(κ(U)) map: EP detection via ill-conditioned eigenvectors |
| IPR and dIPR | Signed dIPR map: edge localisation and chirality |
| Edge state count | Integer-encoded left/right edge-state map |
| GBZ winding (Module definitions + Compute winding) | W = W1 + W2 map over (t1, m) grid |
| Eigenstates | Eigenstate amplitude profiles at snap points (i)–(iii) |

**Part 3 — Fig. 4: properties plotting** (final assembled figure)

Assembles the four phase maps and three eigenstate panels into Fig. 4.

**Part 4 — Fig. 5: phase-transition computation and plotting**

Sweeps dIPR across the phase boundary; includes EP-line overlay, branch-point cache, and final dIPR phase-transition plot (Fig. 5).

**Appendix — M-Riemann spheres**

Visualises the two Riemann sheets of the characteristic M-variable at the snap points; exported separately.

### Snap points used in Fig. 4 eigenstate panels

| Label | (t1, m) | Winding numbers | Phase |
|-------|---------|-----------------|-------|
| (i) | (3/10, 1/10) | W1 = 1, W2 = 1, W = 2 | Two edge states |
| (ii) | (11/10, 3/10) | W1 = 1, W2 = 0, W = 1 | One edge state (sheet 1) |
| (iii) | (−3/4, 1/4) | W1 = 0, W2 = 1, W = 1 | One edge state (sheet 2) |

### Parameter conventions

| Symbol | Mathematica name | Description |
|--------|-----------------|-------------|
| εA, εB | `"εA"`, `"εB"` (Unicode keys) | Sublattice on-site energies |
| Γ | `"Γ"` (Unicode key) | Balanced gain/loss amplitude |
| t1 | `"t1"` | Nearest-neighbour hopping |
| t2 | `"t2"` | Next-nearest-neighbour (NNN) hopping |
| m | `"m"` | NNN on-site modulation |
| δIPRshift | `\[Delta]IPRshift` | Centre-of-mass shift for dIPR sign (= 0.5) |
| nn | `nn` | Number of unit cells in OBC chain (= 40) |
| nθ | `n\[Theta]` | BZ discretisation points for GBZ loop (= 400) |

**Important:** all parameter Associations use Unicode keys (`"εA"`, `"εB"`, `"Γ"`). ASCII alternatives (`"eA"`, `"eB"`, `"G"`) are not recognised.

### Reproducing results

| Result | Notebook | Part / Chapter | Typical runtime |
|--------|----------|----------------|-----------------|
| Fig. 2 (four spectral panels) | `EPs Bulk_commented.nb` | Sections 5–9 | < 2 min |
| Fig. 3 (EP locus, Jordan decomposition) | `Numerical analysis of EP_no_output_commented.nb` | All sections | < 5 min |
| Fig. 4 phase maps (condition number, dIPR, edge count, winding) | `Topology…_commented.nb` | Part 2, all chapters | minutes–hours[^1] |
| Fig. 4 eigenstate profiles | `Topology…_commented.nb` | Part 2, Chapter "Eigenstates" | < 1 min |
| Fig. 5 dIPR phase transition | `Topology…_commented.nb` | Part 4 | < 10 min |
| Appendix Riemann spheres | `Topology…_commented.nb` | Appendix part | < 5 min |

[^1]: Runtime depends on the grid resolution (`varXVals`, `varYVals`). A coarse 20×20 grid completes in minutes; the publication-quality grid may take several hours on a standard laptop. The winding-number scan uses 400-point BZ sampling (`n\[Theta]` = 400) and 60-digit working precision for the GBZ reference points.


---

*This README was prepared for DataVerse deposit. For questions, contact dario.bercioux@dipc.org.*
