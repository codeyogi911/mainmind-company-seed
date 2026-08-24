---
title: Authoring
id: org-authoring
---
# Authoring

Read this before changing anything in this repository that an agent will read
later. It exists to stop two files quietly disagreeing — which is how an
operator ends up guessing, and how you end up surprised.

## The rules that matter most

1. **One fact, one home.** Never copy a rule into a second file. Link to where
   it already lives. Two copies drift, and the day they disagree nobody knows
   which one is the rule.
2. **Write for someone who was not there.** A file has to make sense on its
   own, months later, to a reader who never saw the conversation that produced
   it.
3. **A process says what it does and what it may do.** Never restate
   `AUTHORITY.md` inside a process. The process grants; this file's ceiling
   still applies on top. That is the whole point of the split.
4. **Say when a fact might go stale.** Prices, lead times, and anything a
   supplier told you: write down when you learned it.
5. **One purpose per file.** If you cannot say in a sentence why the file
   exists, it is two files.

## Before you approve a change

Read the actual diff, and answer these. Any "no" sends it back.

1. **Is it true?** Claims match the sources they cite.
2. **Is anything lost?** Every rule and exception that was there is still
   there, or its removal is deliberate and said out loud.
3. **Does it contradict anything?** Check it against every file that governs:
   `AUTHORITY.md`, `ORG.md`, a past ruling in `decisions/`, a fact in
   `records/`, and any other process covering the same work. This is the
   question that catches the expensive mistakes. If two files now disagree,
   fix it here — not at three in the morning when an agent is mid-task.
4. **Does something else already do this?** A second file doing a job the
   first one already did reads perfectly clean in a diff. Ask what already
   does this, not just whether the words are new.
5. **Is it authorised?** A change to `AUTHORITY.md`, `ORG.md` or anything in
   `processes/` is yours to rule on. An operator drafts it; you approve it.

## Writing a process

Every process answers, in this order:

- **What it is for** — in the words someone would actually use to ask for it,
  because that is what routes work here.
- **When to use it**, and when not to.
- **What this process lets an operator do** — the permission it grants, in
  plain words. Always there, including when the answer is "nothing beyond
  `AUTHORITY.md`". Writing the nothing is what shows you decided it.
- **The steps.**
- **How you know it is done.**

## When nothing fits

If a task matches no process, that absence is the finding. Say so, do the
smallest honest version of the task inside existing permission, and leave
behind a draft of the process you wished you had found. `processes/index.md`
names where that rule lives, in its `unmatched:` field, so it sits in one place
instead of being scattered through prose an agent has to notice.
