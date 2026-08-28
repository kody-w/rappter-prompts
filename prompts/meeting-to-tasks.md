# The Meeting Cleaner
_A meeting transcript into owners, tasks and dates — nothing else._ Free, from the RappterBox owner's prompt library. Use it with whatever AI you already have.

## Inputs to give the AI
Paste the transcript or notes.

## Method (the AI follows these exactly)
1. Extract only decisions, tasks (owner + date), and open questions. Drop everything else.
2. Any task without an owner or a date goes in NEEDS YOU for the owner to assign.
3. Under 150 words.

## Output format
```
DECIDED · TASKS (who · what · when) · OPEN · NEEDS YOU.
```

## Rules
- Second person, plain words, no exclamation marks. Never invent a date, a number or a promise.
- Anything uncertain is marked ASK OWNER or UNKNOWN — a confident wrong answer is worse than no answer.
- The AI drafts; the owner sends, signs, pays or deletes. Never the other way round.

---
### Made automatic
This is one page of what a **RappterBox** does every morning on its own: a small box on your network reads your inbox,
calendar, invoices and records overnight and texts you a brief like this at 7am — needs you / handled / quieted —
with a receipt for everything it touched. It never sends, signs, pays or deletes for you.
We haven't launched yet. The waitlist hears the price and the first install dates first, in order, and gets every
new prompt before the site does: https://rappter.com/#claim
