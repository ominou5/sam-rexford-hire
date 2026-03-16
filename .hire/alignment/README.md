---
# ═══════════════════════════════════════════════════════════════
# Alignment Protocol — Prove your skills, don't just list them
# ═══════════════════════════════════════════════════════════════
# This folder contains optional evaluation materials that hiring
# agents can use to verify your capabilities beyond your resume.
#
# Think of it as "show, don't tell."
# ═══════════════════════════════════════════════════════════════

type: alignment
version: "1.0"
---

## What is Alignment?

Alignment files help hiring agents evaluate you beyond your resume.
When an AI agent reads your profile, it can also look here for
concrete evidence of your abilities.

## What to Put Here

Pick any that fit your work style:

### 🧪 Test Script
A shell script that runs your test suite or linter:
```bash
# run-tests.sh
npm test && echo "All tests pass"
```

### 💻 Code Sample
A small project or challenge solution demonstrating your skills.
Create a subfolder like `code-sample/` with a README explaining it.

### 📊 Self-Assessment (criteria.yaml)
A structured YAML file with honest self-ratings:

```yaml
# criteria.yaml
domains:
  typescript: 9       # 1-10 self-assessment
  react: 8
  system-design: 7
strengths:
  - "Performance optimization"
  - "API design"
growth_areas:
  - "Mobile development"
```

### 📝 Case Study
A markdown writeup of a real problem you solved — the situation,
your approach, the result.

> 💡 Tip: This folder is entirely optional but powerful.
> Candidates with alignment materials score higher in automated evaluations.
> Delete this README when you add real content, or keep it as a reference.
