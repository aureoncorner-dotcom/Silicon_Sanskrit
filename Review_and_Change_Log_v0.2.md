# Review and change log · v0.2

## Scope decision

The two supplied files describe separate projects and were not merged:

- `GQG card.docx` is working material for a typed visual language for witness-relative quotient constructions.
- `Qubit-Sutras_MASTER (1).md` is a pedagogical-poetic field guide to quantum information.

Version 0.2 therefore contains two coordinated but independent revisions: a compact GQG Core Card and the Qubit Sutras v0.2 master.

## GQG source review

The supplied DOCX was a 5,266-word transcript rather than a finished card. It contained 1,406 paragraphs, 514 empty paragraphs, no semantic headings or real tables, literal LaTeX/JSON/DSL in proportional body text, process residue, and a near-exact 1,015-word duplicate.

The strongest defensible contribution was preserved:

> GQG is a typed specification language for witness-relative quotient constructions. The AST owns the semantics; glyphs are renderings.

The speculative cross-domain Hamiltonian, measurement-as-quotient, universal-isomorphism, and combined-algebra claims were treated as non-goals rather than doctrine.

### GQG v0.2 improvements

- Reduced the transcript to a neutral, auditable core card.
- Declared `Set` as the normative v0.2 profile.
- Made the typed pipeline explicit: `CAT → SRC → WIT → OBS → EQV → QUO → (IMG) → {DSC, REF, (CPL)}`.
- Separated source equality, observational equivalence, quotient equality, and post-completion equality.
- Renamed ambiguous `CMP` to `CPL` for completion.
- Made quotient–image comparison conditional outside `Set`.
- Typed the aggregate observation, quotient map, and parity example explicitly.
- Required a checked descent certificate whenever a source operation is induced on a quotient.
- Corrected the failed parity example in quotient terms.
- Made refinement direction testable: finer quotient → coarser quotient.
- Rejected a Dedekind completion in bare `Set` unless order and completion structure are declared.
- Demoted prime products to unordered feature metadata; canonical JSON/AST owns identity.
- Added static diagnostic codes, an implementation milestone, accessibility requirements, and a canonical pipeline diagram.
- Marked the compact JSON as illustrative until expression AST nodes, stable identifiers, and canonicalization are specified.
- Produced semantic Markdown, an editable DOCX, a reusable SVG/PNG diagram, and a visually checked two-page tagged English PDF with 9-point body and table text.
- Exposed source provenance in the card: the supplied GQG material did not specify an author or license.

## Qubit Sutras source review

The manuscript has a distinctive voice and a strong historical disclaimer. The main v0.1 blockers were technical overstatement, inconsistent rendering lanes, one broken BB84 table, malformed closing math, pseudo-table headers, nonportable Devanagari commands inside LaTeX, heading hierarchy, and references to companion files that were not supplied.

### Qubit Sutras v0.2 improvements

- Advanced front matter to a dated v0.2 release.
- Added a reading contract: technical prose/equations govern; Sanskrit-register verse is a modern mnemonic; field glosses are analogies.
- Renamed “Monkey gloss” to “Field gloss” throughout.
- Standardized technical equations to conventional `|0⟩`, `|1⟩`, and `|ψ⟩` notation while retaining Sanskrit in the poetic lane.
- Repaired the heading hierarchy to one document title, chapter headings, and chapter sections.
- Removed the duplicated opening divider and malformed trailing CNOT/Bell-state fragment.
- Repaired all three malformed Markdown table headers.
- Rebuilt the BB84 state-encoding table and corrected the `+`/`×` basis symbol.
- Required an authenticated classical channel in BB84 and clarified that errors support a security bound; they do not identify a specific intruder.
- Qualified E91 and device-independent claims: Bell violation is evidence used by a protocol proof, not a complete security certificate by itself.
- Added the distinction between ordinary min-entropy and smooth conditional min-entropy for cryptographic QRNG.
- Added the independence limitation of the textbook von Neumann extractor.
- Corrected the VQE relation to the variational upper bound `E_VQE ≥ E_0`.
- Qualified Grover’s gain as an oracle-query speedup and noted oracle/data-loading/implementation costs.
- Corrected the exact `N=4` Grover example: a classical uniform-target average of 2.5 queries and one ideal Grover iteration with unit success probability.
- Corrected Josephson-junction language: the junction supplies circuit nonlinearity; it is not itself the whole qubit or a threshold detector.
- Qualified no-cloning, measurement, unitarity, information-preservation, teleportation, and repeater claims.
- Renamed the quantum-network “timeline” as one possible development path.
- Added ten foundational technical references.
- Disclosed that the named machine-readable companion files were not supplied and could not be synchronized in this pass.

## Validation performed

- Verified balanced display-math fences, one manuscript H1 title, and repaired nested outlines.
- Checked table structure and removal of blank pseudo-headers.
- Checked that transcript residue and the duplicated GQG block do not appear in v0.2.
- Confirmed the GQG PDF has two nonblank landscape pages, English language metadata, a structure tree, and no visible clipping; visually inspected both pages.
- Reopened the generated DOCX and verified its H1/H2 hierarchy, tables, code styling, embedded diagram with alternative text, landscape section, dates, document statistics, and source text.

## Remaining editorial limits

- A Sanskritist should review the Sanskrit and mixed-language glosses before a formal language edition.
- The Qubit Sutras manuscript remains intentionally expansive; a later v0.3 could reduce repetition and add chapter-level learning targets, prerequisites, worked checks, and “where the analogy breaks” boxes.
- The referenced YAML/JSONL/appendix companions should be supplied or regenerated before calling the machine layer synchronized.
- The supplied GQG material did not state an author or license; v0.2 records that absence rather than inventing attribution or permissions.
- GQG v0.2 is a language-design specification, not an implemented parser or a novelty claim. The next technical milestone is a `Set`-profile parser, AST validator, and renderer exercised on the parity example.

## Technical anchors used for the correction pass

- Bennett *et al.*, quantum teleportation: <https://doi.org/10.1103/PhysRevLett.70.1895>
- Grover, unstructured search: <https://arxiv.org/abs/quant-ph/9605043>
- Koch *et al.*, transmon circuit nonlinearity: <https://doi.org/10.1103/PhysRevA.76.042319>
- Shor and Preskill, BB84 security: <https://arxiv.org/abs/quant-ph/0003004>
- Ekert, entanglement-based QKD: <https://doi.org/10.1103/PhysRevLett.67.661>
- Pironio *et al.*, Bell-certified randomness: <https://doi.org/10.1038/nature09008>
- Peruzzo *et al.*, VQE: <https://doi.org/10.1038/ncomms5213>
- Briegel *et al.*, quantum repeaters: <https://doi.org/10.1103/PhysRevLett.81.5932>
