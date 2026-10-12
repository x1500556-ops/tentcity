# TENTCITY System Map

Four repos. One connected system. Plain language.

## The four pieces

| Repo | What it is | Its job |
|------|-----------|---------|
| **x-it** | The brain / OS | Xavier's own AI computer agent — chat, terminal, files, browser, sandbox. It does the work. |
| **TENTCITY hub** (this site) | The mall front door | Every tool, city, and offer lives here. The public face customers walk through. |
| **IMGCODE** | Tap-to-build | Code you tap, not type. You tap bricks in order; x-it executes the spec in its sandbox. |
| **Hoolulu Factory** | The backend engine | Governor, agents, autopilot loops. The machinery x-it calls on to do real work. |

## How they connect

```
                    ┌─────────────┐
                    │  TENTCITY    │  ← the mall front door (this site)
                    │    hub       │     customers enter here
                    └──────┬──────┘
                           │ powers
                    ┌──────▼──────┐
                    │    x-it     │  ← the brain / OS
                    │  (AI agent) │     chat · terminal · files · browser · sandbox
                    └──────┬──────┘
              ┌────────────┼────────────┐
              │ executes   │            │ calls tools
     ┌────────▼──────┐            ┌─────▼──────────┐
     │   IMGCODE     │            │ Hoolulu Factory │
     │ tap-to-build  │            │ backend engine  │
     │ specs → apps  │            │ gov · agents    │
     └───────────────┘            └────────────────┘
```

**In one sentence:** A customer walks into TENTCITY, x-it (the brain) figures out what they need, IMGCODE lets them tap it into existence, and the Hoolulu Factory's backend engine does the heavy lifting.

## Links

- x-it: https://github.com/xavierhoolulu13-dotcom/x-it
- TENTCITY hub: https://xavierhoolulu13-dotcom.github.io/tentcity/
- IMGCODE: https://github.com/xavierhoolulu13-dotcom/imgcode
- Hoolulu Factory: https://github.com/xavierhoolulu13-dotcom/hoolulu-factory
