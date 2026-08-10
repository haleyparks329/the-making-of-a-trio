# Data

Place one legally obtained plain-text (`.txt`) copy of the first book in
`data/input/`. The analysis command automatically selects the first file by
filename. Source text and generated output are ignored by Git.

`data/output/friendship_timeline.json` is the stable preprocessing-to-
visualization contract. It is always produced by the deterministic pipeline
and may later be enriched by optional LLM interpretation without changing its
schema. Deterministic candidates are written to
`data/output/candidates.json` first, so retrieval can be inspected without an
LLM.

Never commit the source book text or generated excerpts.

## Committed demo provenance

`data/demo/friendship_timeline.demo.json` contains newly written, fictionalized
demonstration text. Its evidence excerpts are invented for this portfolio
artifact; they are not copied from the novel or generated from a source-book
file. Character and chapter references identify the subject of the analysis,
while the prose remains an original public-safe placeholder.
