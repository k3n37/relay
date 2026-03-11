# relay

Starter internal platform repository for service ergonomics, developer self-service, and golden paths.

## Purpose

Shape the platform layer that helps engineers provision, validate, and operate services with less friction.

## Role in the ecosystem

- Consumes ideas from `forge`
- Uses helpers from `automation-tools` and `devops-toolkit`
- Supports `orbit` and `saas-platform`

## Status

Starter platform repo with a simple self-service catalog model.

## Tech stack

- Go
- Markdown

## Structure

```text
relay/
├── cmd/
│   └── idpctl/
│       └── main.go
├── docs/
│   └── platform-catalog.md
├── .editorconfig
├── .gitignore
├── README.md
├── ROADMAP.md
└── go.mod
```

## Getting started

```bash
go run ./cmd/idpctl catalog
```

## Related repositories

- `forge`
- `automation-tools`
- `devops-toolkit`
- `orbit`

## Future direction

Evolve toward self-service workflows and service discoverability without trying to replace every platform tool.
