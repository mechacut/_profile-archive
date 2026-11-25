# mechacut

**Same request, same bytes.**

A deterministic compute bench for AI agents: exact money, dates, units,
hashes, text, CSV and diff transforms over one keyless API — every POST
response carries its own sha256, every 400 names the field and the
expected shape, every ambiguous input (`03/04/05`, `1,234`) is refused
with both readings instead of guessed.

- Live surface & counts: `curl https://mechacut.studio/agent/manifest`
- Docs, bench, protocol: [mechacut.studio](https://mechacut.studio)
- Hermes plugin (skills-only): [Davincc77/mechacut-plugin](https://github.com/Davincc77/mechacut-plugin)
  — this org will host it under `mechacut/plugin` after the Hermes
  catalog merge; old URLs redirect, pins by commit survive.

The numbers on this page are deliberately absent: the manifest is the
count, and this suite lists and grows it daily.
