# Your company file

This repository is your business, written down: the rules your AI agents read
before they act, the decisions you have already made, and the record of what
was done under them.

It is ordinary markdown. You can read it without any tool, edit it in any
editor, and take it anywhere. Nothing here is locked to a service.

## Start here

1. **`ORG.md`** — what this business is. Replace it first; an agent that reads
   a template will behave like a template.
2. **`AUTHORITY.md`** — what an agent may never do without you. Read it
   properly once and change the limits that are wrong for you.
3. **`AUTHORING.md`** — how to write and review a change here without two
   files ending up disagreeing.
4. **`processes/daily-review.md`** — one process to start from, and
   `processes/index.md`, which is how work finds the right one.

## The folders

| Path | What lives there |
|---|---|
| `processes/` | how recurring work is done, and `index.md` routes to them |
| `records/` | the facts work cites: products, systems, reports |
| `lessons/` | what went wrong once and should not again |
| `decisions/` | your rulings, in your words, dated |
| `proposals/` | changes waiting on you |
| `roles/` | what each role may do |

Empty folders are on purpose. They are the shape to grow into, and an agent
reads the shape as an instruction about where things belong.

## Connecting it

Install Mainmind on this repository and it reads it on every push, so your
agents are never working from yesterday. It never writes here.

https://mainmind.app/start
