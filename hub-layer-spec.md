# TENTCITY Hub Layer — build spec v1

## The layer (one clean cut)

```
TENTCITY          the mall — what Xavier sees and taps
   │
X-IT              the building's OS — chat, tools, terminal, files,
                  browser, sandbox, approvals, audit
   │
AGENTS · APPS · SYSTEMS   specialized — stay specialized
```

## Rules

1. **x-it never swallows a tool.** It launches, controls, and monitors — the tool keeps its own job.
2. **Every store gets one door.** The hub links out; the tool lives where it lives (repo, vault, machine).
3. **Talk is the interface.** Xavier talks → x-it (or Muse) routes → specialized system does the work → result comes back.
4. **Menehunes are the workers.** Small skilled builders, each with its own computer, registered in the worker registry (next build), dispatched through x-it.
5. **Nothing outbound without the tap.** The hub asks, Xavier taps, then it moves. Same law as everywhere else.

## Build order

1. ✅ Hub v1 — the front door (tentcity-hub-v1.html)
2. x-it permanent home — kill the temp-sandbox deaths (Chromebook / Rool / VPS)
3. Menehune worker registry — first worker definition → first container → approvals
4. Store wiring — rent-a-human-808, Aiden, GPT808 get real doors
5. Lanikai apartment — first city store, proves the loop

## What "done" looks like

Xavier opens one link, talks, things get built. He never sees a repo unless he wants to.
