# Contributing to the Senior Consulting Intelligence System

Thank you for your interest in contributing. This system is designed to grow through real-world use — better prompts, sharper outputs, and new chains discovered in practice.

---

## What You Can Contribute

### 1. Improve an Existing Agent
If a skill produces output that could be sharper, more structured, or better suited to a specific context — raise an issue or submit a pull request with the improved prompt logic.

### 2. Add an Example Output
The most valuable contributions are **real examples** — a sanitised output from running a skill against an actual (anonymised) challenge. See `examples/` for the format.

### 3. Propose a New Chain
If you've discovered a skill sequence that works particularly well for a specific scenario, document it in `chains/CHAINS.md` format and raise a PR.

### 4. Suggest a New Skill
If there's a consulting use case not covered by the existing 11 skills, raise a GitHub Issue with:
- The skill name and tagline
- When to use it (trigger phrases)
- What the output should look like
- Which existing skills it pairs with

### 5. Fix Documentation
Typos, unclear instructions, broken formatting — all welcome.

---

## How to Contribute

1. **Fork** this repository
2. **Create a branch** — `git checkout -b improve/skill-name` or `git checkout -b add/example-output`
3. **Make your changes**
4. **Commit** with a clear message — `git commit -m "Improve DIE output structure for ambiguous decisions"`
5. **Push** — `git push origin your-branch-name`
6. **Open a Pull Request** — describe what changed and why

---

## Contribution Standards

- **No hallucinated examples** — all example outputs must be based on real (anonymised) usage
- **Leadership-ready quality bar** — outputs should be ready to walk into a meeting without editing
- **Preserve the behaviour standards** — every agent must always produce a recommendation; never end with "it depends" without a clear position
- **Match the tone** — peer-level, not academic; direct, not hedged

---

## Raising Issues

Use GitHub Issues for:
- A skill that produces poor output for a specific input type
- A missing chain that would be useful
- A new skill proposal
- Documentation that is unclear or incorrect

Please include:
- Which skill or chain is affected
- What input you used (anonymised)
- What you expected vs. what you got

---

## Questions

Open a GitHub Discussion or raise an Issue tagged `question`.
