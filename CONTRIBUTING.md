# Contributing to the 593 C Style Guide

Thank you for helping make this resource better for everyone in the cohort.

## Who can contribute

Any MCIT student. See the step-by-step instructions below.

## What belongs here

- C style and formatting conventions for CIS 593
- Corrections to existing conventions
- New common pitfalls discovered during assignments
- Updates to C vs. Java / C vs. Python comparisons
- Any other proposals for the guide

What does **not** belong here: assignment solutions, course content, anything that would violate Penn's academic integrity policy.

---

## How to propose a change

Proposals happen through **GitHub Issues** — not by directly editing the guide.

1. Go to the [Issues tab](../../issues) and click **New Issue**
2. Title it clearly: `Proposal: [short description]` — e.g. `Proposal: use this style instead of that style`
3. In the body, describe:
   - What you want to change or add
   - Why (rationale, course experience, reference if applicable)
   - Any alternatives you considered
4. Add the label `proposal`
5. Post a link to the Issue in the course slack channel to invite discussion

---s

## Conflict resolution

If there is disagreement on a proposal:

1. Discussion happens in the Issue comments — make your case there
2. **[TODO: need conflict resolution process]**

Once a decision is reached, note the outcome in the Issue and close it.

---

## How to submit a change (Pull Request)

Once a proposal has reached consensus in its Issue:

1. Fork the repo (or create a branch if you have write access)
2. Make your edit to the relevant file in `docs/`
3. Open a Pull Request and link it to the Issue: `Closes #[issue number]`
4. At least one other contributor should review and approve before merging

---

## Labels

| Label | Meaning |
|---|---|
| `proposal` | New convention or change under discussion |
| `under discussion` | Active debate, not yet resolved |
| `adopted` | Merged into the guide |
| `rejected` | Considered and decided against — kept for reference |
| `bug` | Something in the guide is wrong or misleading |
| `good first issue` | Good entry point for new contributors |
| `question` | Any general questions you have |

---

## Style for the guide itself

- Assume no prior C experience beyond 593
- Keep rationale to one or two sentences
- Always include a minimal code example for pitfalls and conventions sections
- Use fenced code blocks with `c` as the language identifier

~~~markdown
```c
int *p;   // example
```
~~~

---

## Questions?

Open an Issue with the label `question`, or post in the group chat.