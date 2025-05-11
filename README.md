# Repo-name-hallucination-collapse-challenge
A structured ZIP test to measure GPT hallucination boundaries.
# Hallucination Collapse Challenge

> Can GPT hold structure — or does it collapse?

This is a simple, zero-code test for probing **GPT hallucination boundaries**.

Instead of a prompt, you give GPT a structured ZIP file.  
It contains `.txt`, `.md`, and `.json` files that define a logic system.  
GPT must read the ZIP and try to interpret the system *without hallucinating or collapsing*.

---

## How to Run the Test

1. **Download the ZIP** (link below)
2. Drop it directly into ChatGPT (GPT-4 works best)
3. Ask GPT:
4. 4. Watch how GPT responds:
   - Does it name the agents?  
   - Trace the flow?  
   - Respect the tone and structure?

---

## Why This Matters

Traditional prompt engineering can't test for **structural comprehension**.  
This challenge measures something deeper:
- Can GPT hold modular logic without hallucinating?
- Can it follow recursive tone and role assignment?
- Can it obey structure, not just respond?

---

---

## Example

Check `examples/FAIL_case.md` to see how GPT sometimes collapses the logic.  
You can also upload your own results in a `/responses` folder and share your test output.

---

## Contribute

Fork this repo, try new ZIP layouts, report hallucination behavior, or suggest improvements.

Let’s trace where structure breaks — and how far GPT can go without collapsing.

---
