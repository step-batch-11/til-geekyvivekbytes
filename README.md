# TIL — Today I Learned

This repository is a **daily learning journal**.

It is not a diary. It is not a status report. It is a place to **think clearly
about what you are learning**.

You will write **one short entry per day**.

---

## Daily Workflow

Every working day, do the following:

```sh
deno task til
```

This will generate a Markdown file for today inside the `logs/` folder based on
today's date.

Then:

1. Open the generated file
2. Fill it in honestly
3. Commit and push

That’s it.

---

## Rules

- Write **at most 15 minutes**
- Prefer **clarity over completeness**
- Questions are more valuable than answers
- Be specific
- Do not copy from notes or slides

This journal is for **you**, not for performance.

---

## File Structure

```
.
├── logs/                # Daily entries (one file per day)
├── scripts/
│   └── generate_til.js  # Template generator
├── deno.json
└── README.md
```

Each log file is named by date:

```
YYYY-MM-DD.md
```

Example:

```
2026-01-02.md
```

---

## The Template

Each daily entry has the same structure:

- **Today I Learned** Things that _clicked_ today.

- **Still Confusing** Things that almost make sense but don’t yet.

- **Questions to Chase** Questions worth thinking about later.

- **Tiny Experiments (Optional)** Small ideas to try out.

- **One-Sentence Summary** Why today was useful.

Follow the prompts. Do not add new sections.

---

## Frontmatter

Each file starts with metadata:

- `date`, `day`, `week` are auto-generated
- Update `topics` based on what you studied
- `mood` is optional but encouraged

Example:

```yaml
topics:
  - arrays
  - closures
mood: focused
```

---

## Committing

Commit **once per day**.

Example:

```sh
git add .
git commit -m "TIL: 2026-01-02"
git push
```

Do not batch multiple days into one commit.

---

## Missing Days

Missing files are visible.

That is intentional.

No explanations required — just continue the next day.

---

## Final Notes

This journal will be most useful **weeks later**, not today.

Write so that:

- Future you understands
- You can see how your thinking changed
- You can trace confusion → clarity

Keep it simple. Be consistent.
