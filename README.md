# relay

## Purpose
Improve developer workflows through internal tooling, self-service platform patterns, and clearer service ergonomics.

## Why it matters
When developer workflows are inconsistent, routine platform tasks slow down and delivery quality depends too much on manual knowledge.

## Scope
This repo focuses on internal tooling, workflow helpers, and platform-facing developer experience. It does not try to replace the entire platform stack.

## System Role
`relay` is the developer platform layer for the ecosystem. It reduces friction between service code, delivery workflows, and operational tooling.

## System Connections
- Depends on: service patterns from `forge` and automation from `automata`.
- Feeds into: faster delivery and more consistent platform workflows.
- Interacts with: `runway`, `automata`, `anvil`.

## Core Concepts
- self-service workflows
- developer ergonomics
- service templates
- internal tooling
- platform consistency

## Minimal Artifact
`cmd/idpctl/main.go` and `docs/platform-catalog.md` provide the starter platform helper and workflow note.

## Notes
The emphasis is on tooling that removes repeated platform friction rather than adding another layer of ceremony.

## Next Steps
Add service bootstrap actions, validation commands, and stronger catalog conventions.
