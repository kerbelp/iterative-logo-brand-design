# Iterative Logo and Brand Design

An independent agent skill maintained by [kerbelp](https://github.com/kerbelp) for developing and refining logos and brand identities through exploration, feedback, and practical reproduction tests.

The workflow moves from a concise brief to concept exploration, selection, vector refinement, typography and color, then checks at actual icon sizes and on real applications. It asks for visible artifacts and preserves approved choices as the design evolves.

## Use it

Clone this repository:

```sh
git clone https://github.com/kerbelp/iterative-logo-brand-design.git
```

The repository root is the skill folder: [SKILL.md](SKILL.md) contains the workflow. Place the complete folder in the skills directory supported by your agent, or ask your agent to read and follow `SKILL.md` directly. Installation and skill discovery depend on the agent you use.

Start with a brief, for example:

> Use iterative-logo-brand-design to explore a logo for a neighborhood bicycle repair shop called Second Spin. It should feel friendly, practical, and durable. Explore three distinct directions, then help me choose one before refining it. It needs to work on a storefront, a social avatar, and a one-color repair tag.

For an existing identity, attach the current assets and explain what to preserve. The workflow calls for visual previews, editable SVG assets where appropriate, and size and color checks; the tools available to your agent determine which artifacts it can produce.

## Files

- [`SKILL.md`](SKILL.md) — the reusable workflow.
- [`agents/openai.yaml`](agents/openai.yaml) — agent interface metadata and a default prompt.
- [`assets/icon.svg`](assets/icon.svg) — the skill icon.
- [`LICENSE`](LICENSE) — MIT license.

## Inspiration

Allan Peters’ work inspired this independent workflow, alongside common professional identity-design practices. It is not his official method, a transcription of his material, or affiliated with or endorsed by Allan Peters or Peters Design Co. See [Peters Design Co](https://www.petersdesigncompany.com/) and his book, [Logos That Last](https://www.petersdesigncompany.com/book), for his own work.

## License

Released under the [MIT License](LICENSE). Linked third-party works remain the property of their respective owners.
