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

1. Go to the [Issues tab](https://github.com/zhus-on-first/c-style-guide/issues) and click **New Issue**
2. Complete the required template
4. Add the label `new-proposal`

---

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
| `bugs-and-changes` | Something in the guide is wrong, outdated, or unclear |
| `new-proposal` | Suggest a new entry to any section of the guide |
| `question` | Have a question? Use Discussions instead |
| `under discussion` | Active debate, not yet resolved |
| `adopted` | Merged into the guide |
| `wontfix` | Considered and decided against — kept for reference |

| `good first issue` | Good entry point for new contributors |

---

## Style for the guide itself

- Assume no prior C experience beyond 593
- Keep rationale to less than four sentences
- Always include a minimal code example for pitfalls and conventions sections
- Use the Issue templates to guide you
- Use fenced code blocks with `c` as the language identifier

~~~markdown
```c
int *p;   // example
```
~~~

---

## Issues vs. Discussions

| Use an Issue when... | Use a Discussion when... |
|---|---|
| You want to propose a specific change | You have a question about C or the guide |
| You found something wrong in the guide | You want to think out loud before making a proposal |
| A convention needs to be added | You want to share something useful you found |
| Something is unclear or misleading | You're not sure if something belongs in the guide |

Not sure which to use? Start with a Discussion. It can always be converted to an Issue later.