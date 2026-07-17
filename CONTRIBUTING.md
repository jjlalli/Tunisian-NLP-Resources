# Contributing

This is a living inventory of Tunisian Arabic (`aeb`) NLP resources. Additions and corrections are welcome.

## How to add a resource

1. Pick the right file: text datasets/lexicons/benchmarks → `README.md`; speech → `SPEECH.md`; models → `MODELS.md`; people/labs/orgs → `PEOPLE.md`. If it exists but can't be downloaded, keep it in the list with an honest access tag (`[paywalled]`, `[on request]`, or `[paper only]`) and link the official access route.
2. Use the existing entry format:
   - A heading with a markdown link to the canonical source (GitHub / HuggingFace / paper / repo).
   - Bullets: type, year, creators, size, one-to-three-line description.
   - An access tag: `[open]`, `[gated]`, `[on request]`, `[paywalled]`, or `[paper only]`.
   - A paper link if there is one.
3. Only link URLs you have actually verified. Do not invent links.
4. If a resource is pan-Arabic or Maghrebi and includes Tunisian only as one part, say so and describe the Tunisian portion.

## Verification standard

Every entry should be traceable to a real page: a repository, a dataset card, a paper, or a catalog record. If Tunisian coverage is uncertain, keep the item but flag the uncertainty rather than dropping or overstating it.

## Scope

Tunisian Arabic (Derja / Tounsi, ISO 639-3 `aeb`), in Arabic script and in Arabizi/Latin script, across text and speech. Modern Standard Arabic and other dialects are out of scope except where a resource contains a Tunisian portion.
