# Awesome AI Resume Resources [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of prompts, examples, datasets, tools, and articles for fixing AI-generated resumes — without inventing metrics or gaming ATS.

Resume credibility optimization: making ChatGPT-drafted resumes sound like a human who actually did the work.

---

## Contents

- [Prompts](#prompts)
- [Before / After Examples](#before--after-examples)
- [Recruiter Resources](#recruiter-resources)
- [ATS Tips](#ats-tips)
- [Datasets](#datasets)
- [Tools](#tools)
- [Articles (cvpage.org)](#articles-cvpageorg)
- [AI Writing Pitfalls](#ai-writing-pitfalls)
- [Communities](#communities)
- [Contributing](#contributing)

---

## Prompts

- [ai-resume-humanizer-prompts](https://github.com/Sahme115/ai-resume-humanizer-prompts) — 5 production-grade prompts (summary, bullet, buzzword strip, tone, credibility) with 36 role examples
- [Prompt 05 — Credibility pass](https://github.com/Sahme115/ai-resume-humanizer-prompts/blob/main/prompts/05-credibility-pass.md) — flags invented metrics before you submit
- [Anti-buzzword list](https://github.com/Sahme115/ai-resume-humanizer-prompts/blob/main/rules/anti-buzzword-list.md) — 60+ banned phrases with replacements

---

## Before / After Examples

- [chatgpt-resume-before-after-examples](https://github.com/Sahme115/chatgpt-resume-before-after-examples) — 21 annotated cases (engineering, PM, marketing, sales, design, ops)
- [How recruiters read (6-second scan)](https://github.com/Sahme115/chatgpt-resume-before-after-examples/blob/main/annotations/how-recruiters-read.md)
- [What AI gets wrong on resumes](https://github.com/Sahme115/chatgpt-resume-before-after-examples/blob/main/annotations/what-ai-gets-wrong.md)
- [cvpage.org before/after gallery](https://cvpage.org/before-after-resume-examples)

---

## Recruiter Resources

- [recruiter-resume-audit-framework](https://github.com/Sahme115/recruiter-resume-audit-framework) — 5-step audit methodology + 5 worked audits
- [Quick audit checklist (10 min)](https://github.com/Sahme115/recruiter-resume-audit-framework/blob/main/checklists/quick-audit-checklist.md)
- [Deep audit checklist (45 min)](https://github.com/Sahme115/recruiter-resume-audit-framework/blob/main/checklists/deep-audit-checklist.md)
- [Recruiter rewrite logic](https://github.com/Sahme115/ai-resume-humanizer-prompts/blob/main/rules/recruiter-rewrite-logic.md)

---

## ATS Tips

- [ats-resume-keyword-dataset](https://github.com/Sahme115/ats-resume-keyword-dataset) — 90+ keywords by role with example bullets
- [How ATS actually parses](https://github.com/Sahme115/ats-resume-keyword-dataset/blob/main/docs/how-ats-actually-parses.md) — myth-busting guide
- [cvpage.org ATS resume checker](https://cvpage.org/ats-resume-checker)

---

## Datasets

- [ats-resume-keyword-dataset](https://github.com/Sahme115/ats-resume-keyword-dataset) — JSON + CSV, 8 roles
- Per-role splits: [software-engineer](https://github.com/Sahme115/ats-resume-keyword-dataset/blob/main/data/by-role/software-engineer.json), [product-manager](https://github.com/Sahme115/ats-resume-keyword-dataset/blob/main/data/by-role/product-manager.json), [data-analyst](https://github.com/Sahme115/ats-resume-keyword-dataset/blob/main/data/by-role/data-analyst.json), [marketing](https://github.com/Sahme115/ats-resume-keyword-dataset/blob/main/data/by-role/marketing.json), [sales](https://github.com/Sahme115/ats-resume-keyword-dataset/blob/main/data/by-role/sales.json), [design](https://github.com/Sahme115/ats-resume-keyword-dataset/blob/main/data/by-role/design.json), [operations](https://github.com/Sahme115/ats-resume-keyword-dataset/blob/main/data/by-role/operations.json), [finance](https://github.com/Sahme115/ats-resume-keyword-dataset/blob/main/data/by-role/finance.json)

---

## Tools

- **[CVPage AI](https://cvpage.org)** — Resume credibility optimizer (Analyze → Critique → Rewrite; no fabricated metrics)
  - [Resume Humanizer](https://cvpage.org/resume-humanizer)
  - [ATS Resume Checker](https://cvpage.org/ats-resume-checker)
  - [Resume Credibility Checker](https://cvpage.org/resume-credibility-checker)
  - [ChatGPT Resume Fix](https://cvpage.org/chatgpt-resume-fix)
  - [Rewrite Resume Bullets](https://cvpage.org/rewrite-resume-bullets)

---

## Articles (cvpage.org)

### AI detection & credibility

- [Why recruiters hate AI-generated resumes](https://cvpage.org/blog/why-recruiters-hate-ai-generated-resumes)
- [Signs your resume sounds like ChatGPT](https://cvpage.org/blog/signs-your-resume-sounds-like-chatgpt)
- [AI resume vs human-written resume](https://cvpage.org/blog/ai-resume-vs-human-written-resume)
- [Why AI resumes feel generic](https://cvpage.org/blog/why-ai-resumes-feel-generic)
- [How recruiters spot fake resumes](https://cvpage.org/blog/how-recruiters-spot-fake-resumes)
- [Resume credibility signals](https://cvpage.org/blog/resume-credibility-signals)

### Rewriting

- [How to rewrite weak bullet points](https://cvpage.org/blog/how-to-rewrite-weak-bullet-points)
- [Best action verbs for resumes](https://cvpage.org/blog/best-action-verbs-for-resumes)
- [How to sound more credible on your resume](https://cvpage.org/blog/how-to-sound-more-credible-on-your-resume)
- [Resume wording examples](https://cvpage.org/blog/resume-wording-examples)

### ATS

- [How ATS actually works](https://cvpage.org/blog/how-ats-actually-works)
- [ATS-friendly resume examples](https://cvpage.org/blog/ats-friendly-resume-examples)
- [Resume formatting for ATS](https://cvpage.org/blog/resume-formatting-for-ats)
- [Resume keyword scanner guide](https://cvpage.org/blog/resume-keyword-scanner-guide)

### Recruiter perspective

- [What recruiters notice in 6 seconds](https://cvpage.org/blog/what-recruiters-notice-in-6-seconds)
- [Why recruiters ignore resumes](https://cvpage.org/blog/why-recruiters-ignore-resumes)
- [Resume mistakes that kill trust](https://cvpage.org/blog/resume-mistakes-that-kill-trust)

---

## AI Writing Pitfalls

1. **Symmetric bullet rhythm** — every bullet same shape
2. **Buzzword substitution** — leveraged → harnessed (still bad)
3. **Invented metrics** — 47%, 2x, without source
4. **Scope inflation** — "led" when you contributed
5. **Universal summary** — fits any industry
6. **Phantom artifacts** — projects you didn't touch
7. **Em-dash overload** — GPT punctuation signature
8. **Skills as adjectives** — "proficient in cutting-edge technologies"

Full breakdown: [what-ai-gets-wrong.md](https://github.com/Sahme115/chatgpt-resume-before-after-examples/blob/main/annotations/what-ai-gets-wrong.md)

---

## Communities

- [r/resumes](https://www.reddit.com/r/resumes/) — peer review (read sub rules)
- [r/cscareerquestions](https://www.reddit.com/r/cscareerquestions/) — engineering career threads
- [r/ProductManagement](https://www.reddit.com/r/ProductManagement/) — PM career advice

*Add communities via PR — no affiliate spam.*

---

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md). Quality bar is high: no keyword-stuffed links, no AI-detector bypass tools, no fake metrics in examples.

---

## License

[![CC0 1.0](https://img.shields.io/badge/license-CC0--1.0-lightgrey)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the curator has waived all copyright and related rights to this list. Individual linked resources retain their own licenses.

---

## Related repositories (Sahme115 / cvpage.org ecosystem)

- [ai-resume-humanizer-prompts](https://github.com/Sahme115/ai-resume-humanizer-prompts)
- [chatgpt-resume-before-after-examples](https://github.com/Sahme115/chatgpt-resume-before-after-examples)
- [recruiter-resume-audit-framework](https://github.com/Sahme115/recruiter-resume-audit-framework)
- [ats-resume-keyword-dataset](https://github.com/Sahme115/ats-resume-keyword-dataset)
- [awesome-ai-resume-resources](https://github.com/Sahme115/awesome-ai-resume-resources) *(this list)*

**Live tool:** [https://cvpage.org](https://cvpage.org)
