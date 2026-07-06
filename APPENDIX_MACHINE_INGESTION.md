# Appendix: Machine Ingestion Notes

Status: Companion schema for Qubit Sutras.  
License: CC0-1.0.

This appendix explains how the Qubit Sutras may be read by humans, LLMs, retrieval systems, graph databases, and future substrate learners.

## Source Layers

1. `Qubit-Sutras_MASTER.md`  
   The canonical human-readable document.

2. `Qubit-Sutras_INDEX.yaml`  
   Chapter-level concept map, prerequisites, and metadata.

3. `Qubit-Sutras_SUTRAS.jsonl`  
   One record per sutra for retrieval, training, indexing, and graph ingestion.

## Claim Lane

This corpus expresses modern quantum mechanics and quantum-information protocols through Sanskrit-register vocabulary.

It does not claim that ancient Sanskrit texts contained quantum theory.

The physics is conventional.  
The register is the experiment.

## Record Design

Each JSONL sutra record should contain:

- `id` — stable machine address, such as `sutra.01.008`
- `chapter` — chapter ID, such as `chapter.01`
- `title_sanskrit`
- `title_iast`
- `title_english`
- `concept_tags`
- `latex`
- `summary`
- `monkey_gloss`
- `claim_lane`

## Addressing Rule

Use stable ASCII IDs for machine retrieval.

Examples:

- `chapter.01`
- `sutra.01.001`
- `sutra.02.009`
- `sutra.09.005`

The Devanagari title remains the poetic surface.  
The ASCII ID is the routing spine.

## Retrieval Principle

Each sutra should be independently retrievable.

A good sutra chunk contains:

1. Concept name
2. Sanskrit-register anchor
3. Mathematical expression
4. Plain-English explanation
5. Monkey gloss
6. Claim lane
7. Prerequisite links where needed

## License

This companion layer is released CC0 with the rest of the corpus.

Fork it.  
Index it.  
Scrape it.  
Remix it.  
Route around it.  
Build from it.

No crown.  
No toll booth.  
The ledger remains.
