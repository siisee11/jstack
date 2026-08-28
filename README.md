# jstack

A collection of j's skills for Codex and Cursor.

Each skill lives in its own directory under [skills/](./skills/). The first included skill is:

| Skill | Use it for |
| --- | --- |
| [unslop](./skills/unslop/) | Removing AI tells and adding a human voice to writing |

`unslop` is based on [pstack's unslop skill](https://github.com/cursor/plugins/tree/main/pstack/skills/unslop), with Korean-specific tuning added. The original English rules remain primary.

## Repository layout

Each skill is self-contained and can include its instructions and UI metadata:

```
jstack/
├── .cursor-plugin/
│   └── plugin.json
└── skills/
    └── unslop/
        ├── SKILL.md
        └── agents/
            └── openai.yaml
```

The plugin manifest points Cursor to the `skills/` directory, so additional skills can be added as sibling directories without changing the plugin shape.

## Install

Install the full collection for Codex:

```bash
npx skills add siisee11/jstack -a codex
```

Install only `unslop`:

```bash
npx skills add siisee11/jstack --skill unslop -a codex
```
