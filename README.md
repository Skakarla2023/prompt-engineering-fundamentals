# Prompt Engineering — Fundamentals & Techniques

Learning journal for the **Prompt Engineering** course on Udemy.  
Focus: mastering the art of communicating with LLMs effectively to get precise, reliable, and high-quality outputs.

---

## About This Repo

Prompt engineering is the foundation of everything in AI development.  
Before touching APIs or building agents, you need to deeply understand how to *talk* to an LLM.  
This repo captures my notes, experiments, and reusable prompt templates as I go through the course.

**Course:** Prompt Engineering — Udemy  
**Started:** <!22-05-2026>  
**Status:** 🟡 In Progress

---

## Why This Matters for a Backend Engineer

As an AI Backend Engineer, you won't just call APIs — you'll write system prompts, design prompt pipelines, and debug when LLM output breaks your application logic. Strong prompt engineering = fewer bugs, better outputs, lower token costs.

---

## Structure

```
prompt-engineering-fundamentals/
├── notes/
│   ├── 01-how-llms-work.md           # Tokens, context windows, temperature
│   ├── 02-basic-prompting.md         # Zero-shot, few-shot prompting
│   ├── 03-roles-and-personas.md      # System prompts, role assignment
│   ├── 04-chain-of-thought.md        # CoT, step-by-step reasoning
│   ├── 05-output-formatting.md       # JSON output, structured responses
│   ├── 06-prompt-chaining.md         # Multi-step prompt pipelines
│   ├── 07-common-mistakes.md         # What NOT to do + fixes
│   └── 08-advanced-techniques.md     # ReAct, self-consistency, etc.
├── templates/
│   ├── system-prompt-template.md     # Reusable system prompt structure
│   ├── json-output-prompt.md         # Prompts that return clean JSON
│   ├── summarization-prompt.md       # For summarizing documents/text
│   └── classification-prompt.md      # For categorizing inputs
├── experiments/
│   ├── temperature-tests.md          # What changes at 0 vs 0.5 vs 1.0
│   ├── few-shot-examples.md          # Side-by-side few-shot comparisons
│   └── bad-vs-good-prompts.md        # Before/after prompt improvements
└── interview-prep/
    └── prompt-engineering-qa.md      # Interview Q&A on prompt engineering
```

---

## Progress Tracker

| Module | Topic | Status |
|--------|-------|--------|
| 01 | How LLMs work (tokens, context, temperature) | ⬜ Not started |
| 02 | Basic prompting — zero-shot & few-shot | ⬜ Not started |
| 03 | Roles, personas & system prompts | ⬜ Not started |
| 04 | Chain-of-thought reasoning | ⬜ Not started |
| 05 | Structured & JSON output formatting | ⬜ Not started |
| 06 | Prompt chaining & pipelines | ⬜ Not started |
| 07 | Common mistakes & how to fix them | ⬜ Not started |
| 08 | Advanced techniques | ⬜ Not started |

> Update status: ⬜ Not started → 🟡 In progress → ✅ Done

---

## Key Techniques Learned

> I'll update this as I go through the course.

| Technique | What it does | When to use |
|-----------|-------------|-------------|
| Zero-shot | Ask directly, no examples | Simple tasks |
| Few-shot | Provide examples in prompt | Complex or specific formats |
| Chain-of-thought | Ask model to reason step-by-step | Math, logic, multi-step problems |
| System prompt | Set role and behaviour upfront | All production use cases |
| JSON mode | Force structured output | Backend API integrations |

---

## Prompt Templates

Reusable templates I've built and tested — stored in `/templates`.

- `system-prompt-template.md` — base structure for any system prompt
- `json-output-prompt.md` — reliably returns structured JSON
- `summarization-prompt.md` — clean document summarizer
- `classification-prompt.md` — categorize any input

---

## Interview Prep

Questions I can answer confidently after this course:

- [ ] What is prompt engineering and why does it matter?
- [ ] What's the difference between zero-shot and few-shot prompting?
- [ ] How does temperature affect LLM output?
- [ ] What is chain-of-thought prompting?
- [ ] How do you get an LLM to reliably return JSON?
- [ ] What are common prompt injection risks in a backend system?
- [ ] How do you reduce hallucinations through prompting?

---

## Key Learnings

> I'll update this section with my biggest takeaways.

-

---

## Connection to Other Repos

This repo feeds directly into my other learning repos:

| Repo | How prompt engineering applies |
|------|-------------------------------|
| [claude-api-java-backend](https://github.com/Skakarla2023/claude-api-java-backend) | System prompts + output formatting in API calls |
| [model-context-protocol-experiments](https://github.com/Skakarla2023/model-context-protocol-experiments) | Prompt design for MCP tool descriptions |
| [ai-fluency-foundations](https://github.com/Skakarla2023/ai-fluency-foundations) | Understanding effective AI collaboration |

---

## Resources

- [Anthropic Prompt Engineering Guide](https://docs.anthropic.com/en/docs/build-with-claude/prompt-engineering/overview)
- [OpenAI Prompt Engineering Guide](https://platform.openai.com/docs/guides/prompt-engineering)
- [Learn Prompting (free)](https://learnprompting.org)

---

*Part of my AI Backend Engineer learning journey — Summer 2026*  
*Connect: [LinkedIn](https://linkedin.com/in/satwika-kakarla) · [GitHub](https://github.com/Skakarla2023)*
