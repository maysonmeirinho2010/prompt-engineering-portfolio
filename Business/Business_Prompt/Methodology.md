# Design Methodology: Late Package Apology

## Design Goal

I wanted to make a fast way for small business owners to write nice apology emails so customers don't stay mad.

---

## Design Approach: Structure and Technique

**Structure I used:** C-A-R-E (Context, Action, Result, Example)

**Why this structure fits my task:**
- It gives the AI all the facts it needs (Context and Action).
- The "Result" tells the AI how the customer should feel at the end.

**Technique I used:** Few-shot

**Why this technique fits my task:**
I used few-shot because it is hard to explain the exact "nice" tone I wanted. Giving it one quick example of a good apology helped the AI copy that style perfectly.

---

## Part-by-Part Justification

| Part | What I put here | Why the prompt needs it |
|------|-----------------|-------------------------|
| Context | Who is involved (Company and Customer) | So the AI knows who is sending and receiving the email. |
| Action | Write an apology email with a discount | It tells the AI exactly what job to do. |
| Result | Make the customer feel respected | It helps the AI pick the right friendly words. |
| Example| A sample apology sentence | It shows the AI exactly what tone to copy. |

---

## Testing and Iteration

**Baseline I compared against:**$0
