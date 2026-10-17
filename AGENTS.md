# Pryntor GPU procurement gate

Before proposing **new paid GPU compute**, follow the company policy: https://docs.google.com/document/d/1oRi8PG4VPBw08cCllV5fwEHGAUgD1PM9pgdLCb9D4qE/edit and the versioned Markdown at https://github.com/LLoliwe/agent-spend-proof/blob/main/docs/GPU_COST_GATE.md .

Use https://gpu.context.dev for **read-only** price discovery only when a job is demonstrably GPU-bound. Compare direct vendor offers, real availability, actual configuration, credits/CPU alternatives and total cost per successful run. Record in PRY-223. No self-hosting, billing, procurement, cloud activation, or unverified savings claims. Preserve existing QA and project controls.

## Optional Pryntor Anatomy visualization capability (PRY-225)

Anatomy is an opt-in, MIT-licensed agent skill for interactive isometric SVG/WebGL and experimental 3D technical explainers. It is **not** a mandatory production/runtime dependency.

- Canonical skill/installer: https://github.com/LLoliwe/Anthropic-skills/tree/main/skills/pryntor-anatomy
- Pinned official source: `wheresryan22/anatomy@e9488296a44211c42701ff71705b7901470ec78f`
- Only for an actual visual explainer task, in an appropriate checkout: `bash /path/to/Anthropic-skills/skills/pryntor-anatomy/install.sh .`
- Never silently install at startup, overwrite existing agent skills, buy cloud/GPU compute, upload private inputs or publish to a public community gallery.
- Technical diagrams need mathematically correct models, browser and screenshot QA, keyboard/reduced-motion/accessibility review. They are not engineering certification or safety evidence.
- Record actual per-project installation and checks before claiming deployment. Source and remaining gates: https://linear.app/pryntor/issue/PRY-225.
