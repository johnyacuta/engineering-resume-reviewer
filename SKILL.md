---
name: engineering-resume-reviewer
description: Rewrite a pasted engineering accomplishment, rough note, or resume sentence as a concise, truthful STAR-style resume bullet. Use when drafting or improving engineering resume bullets.
---

# Engineering Resume Reviewer

Turn the user's sentence or rough notes into a concise, ready-to-paste engineering resume bullet. This skill is primarily for rewriting one accomplishment at a time, not reviewing or formatting an entire resume.

## Workflow

1. Identify the situation or problem, the goal or task, the user's action, and the result or impact from the supplied text and relevant conversation context.
2. Draft one short bullet that naturally combines the useful STAR elements. Lead with a strong, past-tense action verb; include relevant technical context and methods; emphasize a provided result or metric. Do not label the parts `Situation`, `Task`, `Action`, or `Result` in the finished bullet.
3. Keep the bullet to one sentence, omit personal pronouns and the ending period, use digits for numbers, and remove redundant wording and unsupported adjectives. Aim for roughly 1–2 resume lines, while recognizing that line length depends on the user's template.
4. Return the best factually supported draft first. If an important result, scale, constraint, or personal contribution is missing and would materially improve it, ask up to 3 specific follow-up questions after the draft. Do not make the user answer questions before receiving a useful first pass.
5. If asked, briefly show how the bullet maps to STAR or provide alternate versions. Otherwise, avoid lengthy explanations and unsolicited resume advice.

## Accuracy

- Use only facts the user supplied or clearly established in the current conversation. Never invent outcomes, metrics, tools, ownership, team size, scope, or causal impact.
- Do not turn participation into ownership or claim that work improved a result unless the user said so.
- If the result is unknown, provide an action-focused draft and say what result would strengthen it; do not imply success or add a placeholder that could be mistaken for a fact.
- Preserve confidentiality. Keep the user's pasted content in the conversation; do not write it into repository files or other artifacts.

## Reference guidance

Use the relevant portions of [engineering-resume-wiki.md](./references/engineering-resume-wiki.md) and [r_EngineeringResumes Resume Template.pdf](./references/r_EngineeringResumes%20Resume%20Template.pdf). For bullet rewriting, prioritize clear technical context, a strong past-tense verb, a concise one-sentence STAR/CAR/XYZ structure, and quantified results when the user has provided them. The wiki's broader formatting advice is general guidance, predominantly for the United States and Canada, not a guarantee of hiring or ATS outcomes.

## Response format

**Resume bullet**

- <one ready-to-paste bullet>

**To strengthen it:** <only include concise, material follow-up questions when needed>

Omit the second heading when the supplied information is sufficient. Do not return STAR labels or multiple alternatives unless requested.
