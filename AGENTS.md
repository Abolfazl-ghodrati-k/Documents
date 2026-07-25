# Book-writing instructions

This repository is a Markdown manuscript for a practical book on recommender systems. Keep the reader in mind: they are comfortable with basic programming but may be new to recommender systems and machine learning.

## Voice and structure

- Write in clear, professional English with a patient textbook tone.
- Begin each chapter with motivation or a concrete domain example; introduce formal notation only after intuition.
- Use descriptive headings, a short summary, and 2–5 reputable references in every completed chapter.
- Include a small, runnable example when a concept benefits from implementation. State required packages and data assumptions.
- Prefer one sustained example across a section over many disconnected examples.

## Technical standards

- Distinguish explicit ratings from implicit feedback, and distinguish offline evaluation from production impact.
- For recommender evaluation, state the split strategy, relevance definition, candidate set, cutoff (for example, `@10`), and treatment of already-seen items and cold-start cases.
- Never fit preprocessing transformations on test data. Warn about leakage where it is a realistic risk.
- Treat text preprocessing choices as domain-dependent; do not claim that numbers, punctuation, emojis, or stop words are always noise.
- Mention privacy, bias, fairness, and catalog or popularity effects when a technique could materially affect them.

## Manuscript hygiene

- Do not leave chat artifacts, placeholders, “Part” markers, or promises of missing diagrams/examples in the manuscript.
- Use UTF-8 and preserve Persian correctly when it appears.
- Keep filenames and chapter numbering consistent. Update links or the table of contents when adding a chapter.
- Do not present an unverified code output as executed. Label illustrative outputs clearly, or run the code before claiming exact results.
- Cite primary research, authoritative books, and official dataset documentation rather than unsourced claims.
