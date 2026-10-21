# AGENTS.md

This repository is sccache: a Rust compiler cache, single crate, a fork of
mozilla/sccache (upstream remote "upstream"). Developer docs live in "docs/".
CI: ".github/workflows/ci.yml".

All agent-facing repo rules (tests, MSRV, cargo features, commit style) live in
the role prompts under ".zed/prompts/agents/". Each prompt carries only the
rules its role executes. Do not add rules here unless every agent needs them.

Replies to code reviewers are written by a human, never by an agent.
