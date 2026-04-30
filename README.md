# stylistics

A Claude Code skill for extracting stylistic profiles from text files using systematic linguistic analysis.

## What It Does

Stylistics performs comprehensive stylistic analysis of any text file, examining it across 7 levels of language (graphology, phonology, morphology, lexis, grammar/syntax, semantics, pragmatics/discourse) and producing a prescriptive style guide that captures the writer's distinctive style.

The analysis also covers:
- Transitivity patterns (who does what to whom)
- Point of view and perspective
- Speech and thought representation
- Foregrounding and deviation
- Register and dialect

## Installation

```bash
npx skills add eXtremeProgramming-cn/stylistics
```

## Usage

### Extract a Style Profile

```
/stylistics extract article.md
```

Analyzes `article.md` and produces `article.style.md` alongside it.

### Specify Output Location

```
/stylistics extract article.md -o guides/article-guide.md
```

### Quick Profile (No Full Style Guide)

```
/stylistics extract article.md --profile
```

Produces a concise style profile without the full prescriptive style guide (Sections A–G).

## Output

The default output is a Markdown file containing:

1. **Source Information** — file, author, language, genre, word count
2. **Voice and Stance** — persona, reader relationship, epistemic stance, evaluative stance
3. **Sentence-Level Patterns** — types, complexity, openings, voice, coordination
4. **Vocabulary** — register, semantic fields, technical terms, nominalization, collocations
5. **Discourse Structure** — paragraph structure, cohesion, information flow, argumentation
6. **Distinctive Features** — table of notable stylistic characteristics with examples
7. **Transitivity Profile** — dominant process types, agency patterns, circumstances
8. **Prescriptive Style Guide** — actionable rules organized into:
   - **A**: Voice and Stance
   - **B**: Sentence-Level Patterns
   - **C**: Vocabulary and Word Choice
   - **D**: Paragraph and Discourse Structure
   - **E**: Citation and Attribution
   - **F**: Document Structure
   - **G**: Specific Constructions and Phrases

Every rule uses imperative language ("Use...", "Avoid...", "Prefer...") and includes authentic examples from the source text.

## Methodology

The analytical methodology draws on systematic linguistic stylistics:
- Hallidayan systemic-functional linguistics (transitivity, register)
- Leech and Short's stylistic analysis framework
- Narrative theory (focalization, speech representation)
- Corpus stylistics approaches

The full methodology is included in the skill's reference materials.

## License

GPL-3.0
