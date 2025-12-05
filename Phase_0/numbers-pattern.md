# Number Patterns

I started this DSA journey from the absolute basics, which naturally led me to numbers and the patterns they form.  
So today, I focused on understanding how numbers change from one step to the next, and why certain sequences behave the way they do.

---

## Understanding simple additive patterns

Some sequences change by adding the same number every time.  
These are the easiest kind of patterns to spot.

Example:  
2, 5, 8, 11, 14 …

Here the jump is +3 each time.

This kind of pattern is basically:  
**next number = previous number + constant difference**

It sounds obvious, but noticing the difference quickly is a skill on its own.

---

## When numbers grow by multiplication

Some patterns don’t grow by adding — they grow by multiplying.

Example:  
3 → 6 → 12 → 24 → 48

Here the number doubles each time (×2).

This idea is called a **ratio**, and it helps identify geometric patterns.

---

## Patterns that mix both ideas (multiply + then add)

These look a little tricky at first but become easy once you catch the rhythm.

Example:  
4 → 9 → 19 → 39 → 79 → 159

If you look closely:
- 4 × 2 + 1 = 9  
- 9 × 2 + 1 = 19  
- 19 × 2 + 1 = 39  

So the rule becomes:  
**multiply by 2, then add 1**

This type shows up surprisingly often in algorithms, especially in recursion or tree-related problems.

---

## Increasing multipliers (a pattern I found interesting)

Some patterns don’t use the same multiplier every time — it keeps increasing.

Example:  
2 → 4 → 12 → 48 → 240 → 1440

The multipliers go like this:  
×2, ×3, ×4, ×5, ×6 …

Once you catch that idea, the rest becomes predictable.

---

## Recurrence-style patterns (using previous terms)

These grow very fast and feel a bit mathematical at first, but the logic is simple:

Example:  
2, 3, 6, 18, 108, 1944 …

Here each term is the product of the previous two terms.

This isn’t something you usually see in school math, but it appears in recursion and DP, so getting used to it early feels helpful.

---

## A small reflection

While doing these, I noticed that my first instinct was to over-explain.  
But patterns are actually easier to express in short rules:

- “+3 every step”  
- “×2”  
- “×2 + 1”  
- “multiply by increasing integers”

Short rules make the idea clearer and easier to communicate.

---

## One thing I corrected today

At first, whenever I saw a sequence, I tried to describe the entire logic in long sentences.  
Now I try to simplify it to one clean idea.

---

## If you're practicing along (5 small questions)

In case someone else is learning from this repo later on — or if I revisit these notes myself — here are a few small pattern problems to try. These are simple warm-ups, nothing scary.  
Try to keep each question under **1–2 minutes** just to build quick pattern sense.

1. 5, 10, 15, 20, … → what comes next?
2. 3, 9, 27, 81, … → say the rule in one short line.
3. 7, 14, 28, 56, 112, … → what pattern do you notice?
4. 1, 4, 9, 16, 25, … → identify what kind of sequence this is.
5. 10, 7, 4, 1, … → find the rule and predict the next term.

These are intentionally easy — the goal is just to train your eyes to notice changes quickly.
