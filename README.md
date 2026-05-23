# Prompt Engineering — Fundamentals & Techniques

Personal notes and experiments from the **Prompt Engineering** course on Udemy.  
Built as a reference I'd actually go back to — not just a course archive.

**Course:** Prompt Engineering — Udemy &nbsp;|&nbsp; **Completed:** May 2026 &nbsp;|&nbsp; **Status:** ✅ Done

---

## Why This Matters for a Backend Engineer

As an AI Backend Engineer, you won't just call APIs — you'll write system prompts, design prompt pipelines, and debug when LLM output breaks your application logic.

Strong prompt engineering = fewer bugs, better outputs, lower token costs.

---

## Structure

```
prompt-engineering-fundamentals/
├── 01-foundations/
│   ├── Prompting Essentials.md          # Core concepts every prompt engineer needs
│   └── Best Practices and Templates.md  # Reusable patterns for real-world use
│
├── 02-prompting-techniques/
│   ├── Chain-of-thought Prompting.md    # Step-by-step reasoning prompts
│   ├── Role Prompting.md                # Personas, system roles, behaviour shaping
│   ├── Step-back Prompting.md           # Abstract reasoning before answering
│   └── chain-of-density-prompt.txt      # Iterative summarization technique
│
├── 03-reasoning-frameworks/
│   ├── Program-of-thought.md            # Code-assisted reasoning
│   ├── Skeleton-of-thought.md           # Parallel decoding for faster responses
│   └── Tree-of-Thought.md               # Branching reasoning paths
│
├── 04-hyperparameters/
│   ├── Prompt Hyperparameters.md        # Temperature, top-p, max tokens explained
│   └── Hyperparameter Tuning.md         # When and how to tune each parameter
│
├── 05-prompt-tuning/
│   └── Prompt Tuning.md                 # Soft prompting vs. few-shot vs. fine-tuning
│
└── 06-evaluation-and-testing/
    ├── Prompt AB Testing.md             # How to compare and iterate on prompts
    └── Prompt Evaluation.md             # Metrics and frameworks for scoring output
```

---

## Key Techniques at a Glance

| Technique | What it does | When to use |
|-----------|-------------|-------------|
| Zero-shot | Ask directly, no examples | Simple or general tasks |
| Few-shot | Provide examples in the prompt | Complex or format-specific outputs |
| Chain-of-thought | Ask model to reason step-by-step | Math, logic, multi-step problems |
| Role prompting | Assign a persona or system role | Production system prompts |
| Step-back prompting | Derive principles before answering | Abstract or domain-heavy questions |
| Tree-of-thought | Explore branching reasoning paths | Decision-making, planning |
| Program-of-thought | Use code as an intermediate reasoning step | Numerical reasoning, structured logic |

---

## Connection to Other Repos

This repo feeds directly into my ongoing AI Backend Engineer learning path:

| Repo | How prompt engineering applies |
|------|-------------------------------|
| [claude-api-java-backend](https://github.com/Skakarla2023/claude-api-java-backend) | System prompts + structured output in live API calls |
| [model-context-protocol-experiments](https://github.com/Skakarla2023/model-context-protocol-experiments) | Prompt design for MCP tool descriptions and agent flows |
| [ai-fluency-foundations](https://github.com/Skakarla2023/ai-fluency-foundations) | Understanding effective human-AI collaboration |

---

## Resources

- [Anthropic Prompt Engineering Guide](https://docs.anthropic.com/en/docs/build-with-claude/prompt-engineering/overview)
- [OpenAI Prompt Engineering Guide](https://platform.openai.com/docs/guides/prompt-engineering)
- [Learn Prompting (free)](https://learnprompting.org)

---

*Part of my AI Backend Engineer learning journey — Summer 2026*  
*Connect: [LinkedIn](https://linkedin.com/in/satwika-kakarla) · [GitHub](https://github.com/Skakarla2023)*
