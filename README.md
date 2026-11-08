# Engineering Resume Reviewer

A lightweight agent skill for turning a sentence or rough engineering accomplishment into a concise, STAR-style resume bullet. The main use case is a quick rewrite of one bullet at a time, not a full resume review.

## Repository contents

- `SKILL.md` — the bullet-rewriting workflow and accuracy rules.
- `references/engineering-resume-wiki.md` — engineering resume guidance, including bullet-writing recommendations.
- `references/r_EngineeringResumes Resume Template.pdf` — a one-page template with STAR, XYZ, and CAR bullet examples.

## Use the skill

1. Provide this repository's `SKILL.md` and its `references/` files to an assistant that supports reusable agent skills.
2. Paste a sentence or rough notes describing an engineering accomplishment.
3. Review the ready-to-paste draft. If an important result or detail was missing, answer the skill's brief follow-up questions and ask for an updated version.

Example:

**Input:** I wrote a Python script that checked sensor logs and reduced manual review from 3 hours to 20 minutes per test.

**Resume bullet:** Automated sensor-log validation with Python, reducing manual review from 3 hours to 20 minutes per test

## How it writes bullets

The skill uses the facts available in your sentence and the current conversation to combine relevant situation, task, action, and result into one natural bullet. It does not force STAR labels into the resume text, make up metrics or outcomes, or claim work you did not describe. When information is missing, it gives a useful first draft and asks only for details that could materially strengthen it.

The output follows the referenced guidance where practical: a strong past-tense action verb, concise technical context, one sentence without a final period, and quantified impact when you provide it. The result should still be tailored to the job and checked for fit with your resume.

## Scope and limitations

The references are guidance, not universal rules; the wiki notes that its recommendations predominantly reflect United States and Canadian resumes. The skill rewrites bullet content but does not guarantee ATS compatibility, assess your entire resume, or verify the accuracy of claims you provide. Keep confidential or proprietary details out of anything you do not want included in your conversation.
