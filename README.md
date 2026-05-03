# SKILL: /stylistics

Extract prescriptive style guides from text files using systematic linguistic analysis.

## TL;DR

```bash
npx skills add eXtremeProgramming-cn/stylistics
```

Then in your AI client:

```
/stylistics extract article.md
```

Then apply the style guide to write new text:

```
Read article.style.md and following its rules exactly,
write a 2000-word article about {your topic}.
```

## Usage

```
/stylistics extract article.md              # → article.style.md
/stylistics extract article.md -o guide.md  # custom output path
```

## Output

The generated style guide contains:

**Part I: Analytical Summary** — corpus overview and key stylistic observations

**Part II: Prescriptive Style Guide** — actionable rules organized by the 7 levels of language:
- **Level 1**: Graphology — typography, punctuation, layout
- **Level 2**: Phonology — rhythm, tempo, sound patterns
- **Level 3**: Morphology — word formation, nominalization
- **Level 4**: Lexis — vocabulary, semantic fields, register, collocations
- **Level 5**: Grammar and Syntax — sentence patterns, transitivity, voice/modality
- **Level 6**: Semantics — meaning patterns, presupposition, figurative language
- **Level 7**: Pragmatics and Discourse — stance, cohesion, citation, document structure

**Part III: Quick Reference Checklists** — pre-writing, self-editing, style violations

**Appendix: Approved Vocabulary by Domain**

Every rule uses imperative language ("Use...", "Avoid...", "Prefer...") and includes authentic examples from the source text.

## Applying a Style Guide

To write new text in the extracted style, reference the generated guide in your prompt:

```
Read the style guide in article.style.md. Following its rules exactly,
write a 2000-word article about {your topic}.
```

## Methodology

The analysis examines texts across 7 levels of language (graphology, phonology, morphology, lexis, grammar/syntax, semantics, pragmatics/discourse) with transitivity, point of view, speech representation, and register integrated into the relevant levels. The full methodology is included in the skill's reference materials.

The analytical framework draws on Paul Simpson, *Stylistics: A Resource Book for Students* (Routledge, 2014).

## License

GPL-3.0
