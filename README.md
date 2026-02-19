# Claude Solo Founder Skills

Production-grade **Claude Code skills** designed for:

- Solo founders shipping fast  
- Startup engineers making real decisions  
- Builders who want execution speed **without losing rigor**

Most prompt libraries optimize for writing code faster.  
This project optimizes for something rarer:

> **Better product and engineering decisions.**

---

# What Are Claude Skills?

Claude Code skills are **Markdown playbooks** that Claude automatically loads to guide:

- reasoning  
- workflows  
- safety checks  
- structured outputs  

Think of them as:

> **Reusable decision engines for real-world builders.**

After installation, Claude will **automatically apply the right skill** when you ask normal questions.

---

# Included Skills (v1)

## Decision Intelligence
- **Build vs Buy Decision Engine**  
- Should-We-Build-This Evaluator  
- Refactor-vs-Ship Framework  
- Kill-the-Feature Analyzer  

## Founder Execution
- MVP Scoper  
- Ship-in-7-Days Planner  
- Growth Experiment Designer  
- Pricing Strategy Engine *(coming soon)*  

## Production Engineering
- Incident Commander  
- Blameless Postmortem Writer  
- Rollback Decision Framework  
- Observability Gap Detector *(coming soon)*  

## AI Builder Toolkit
- Eval Dataset Generator  
- Prompt Regression Tester  
- Token Cost Optimizer  
- Hallucination Risk Detector  

Each skill is:

- **Decision-oriented**
- **Structured and repeatable**
- Written at a **senior engineer / founder quality bar**
- Designed for **real startup scenarios**, not toy prompts

---

# How to Install

## Using npx (recommended)

```bash
npx skills add pratikshadake/claude-solo-founder-skills
```

## Global install

```bash
git clone https://github.com/pratikshadake/claude-solo-founder-skills
cp -r claude-solo-founder-skills/skills ~/.claude/skills/
```

## Project-local install
```bash
git clone https://github.com/pratikshadake/claude-solo-founder-skills
cp -r claude-solo-founder-skills/skills ./.claude/skills/
```

Claude will automatically detect and use the skills.

## How to Use

Just ask normal questions:

```
Should we build our own billing system or use Stripe?
Scope an MVP for an AI travel planner.
Design a growth experiment to increase signups.
```

Claude will automatically apply the relevant skill.

You can also explicitly invoke one:

```
Use the Build vs Buy Decision Engine.
```

## Examples

See real decision walkthroughs in:

```
examples/
```

These demonstrate:

- realistic startup context
- transparent reasoning
- structured outputs
- founder-level recommendations

## Philosophy

In real startups:

- the decision matters more than the syntax
- the scope matters more than the speed
- the focus determines survival

This repository exists to improve:

- clarity of thinking for builders under pressure.

## Contributing

High-quality contributions are welcome.

Before submitting a PR, ensure the skill is:

- Real-world useful (not a prompt toy)
- Decision-focused
- Clearly structured
- Written at senior quality bar

Please open an issue first to discuss new ideas.

## License

- MIT — free to use, modify, and distribute.
