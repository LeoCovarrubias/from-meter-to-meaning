# From Meter to Meaning

A reading of the *State of Tokenomics 2026* report, set beside the FinOps Foundation's argument that Tokenomics and FinOps for AI are two projections of the same work. Documented as a short research paper.

This is not original primary research. It is an interpretation of a published industry survey (472 responses across 11 industries, Release Candidate 1.0, 23 September 2026) and of one piece of FinOps Foundation commentary. The report is authored by the Tokenomics Foundation (a Linux Foundation project); the FinOps Foundation links to it and has published commentary on the relationship between the two disciplines.

## The paper

[PDF](paper/paper.pdf) · [LaTeX source](paper/paper.tex)

**Abstract.** Organizations now consume AI through many models in many places, and most can see a fair part of what they spend. Yet roughly three in four cannot confidently show a business outcome to the CFO, and the largest single challenge respondents name is proving value, not paying less. This text argues that the unit of account has outrun the unit of value: the difficulty has migrated from measuring consumption to measuring consequence.

## Three readings

1. **Cardinality.** 96% use a model provider directly, 87% consume tokens through a cloud, 64% use embedded AI, and about a third run edge or private AI. Nearly one in five already use at least one of Deepseek, Qwen, Kimi or GLM.
2. **Visibility is not value.** 53% are moderately or very confident in their AI spend visibility (39% + 14%), but only 26% are moderately or very confident in proving outcomes to the CFO (17% + 9%).
3. **Meaning, not price.** 43% name proving value or ROI as their biggest challenge; only 7% name cost or pricing complexity. Asked what they want from providers, 4% say cheaper prices.

## Practice principles

1. Treat the token as an instrument, not an objective.
2. Instrument attribution before optimization.
3. Name an owner, and name one on purpose.
4. Adopt shared data standards (for example FOCUS) early.
5. Hold both projections: FinOps for AI and Tokenomics.

## Methodological note

No original data is used. All figures are cited indirectly from the sources in the paper's references. The source report is a Release Candidate and contains internal inconsistencies (revenue totals that do not reconcile, an ambiguous confidence statistic, an undefined metric by company size); the paper lists them in Section 6 and avoids relying on the affected figures. Correlations in the report (for example, 3.7x for defined ownership, 4x for routers) are self-reported associations, not demonstrated causes.

This text is an independent reading and is not affiliated with, or endorsed by, the Tokenomics Foundation or the FinOps Foundation.

## Build

```bash
cd paper
latexmk -pdf paper.tex
```

## License

MIT, see [LICENSE](LICENSE).
