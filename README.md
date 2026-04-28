# n8n-nodes-piperun

PipeRun CRM integration for n8n.

This package includes a declarative `Piperun` node generated from the PipeRun OpenAPI schema, plus credential support for token authentication.

## Included Nodes

- `Piperun` (`nodes/Piperun/`)
- `GithubIssues` (`nodes/GithubIssues/`) - example node from starter
- `Example` (`nodes/Example/`) - starter boilerplate node

## Authentication

PipeRun requires sending your user token in the `token` HTTP header for each API request.  
See official docs: [PipeRun API Authentication](https://developers.pipe.run/reference/autentica%C3%A7%C3%A3o).

In n8n, configure the `PipeRun API` credential (`piperunApi`) and paste your token.

## Development

### Prerequisites

- Node.js 22+
- npm or pnpm

### Install

```bash
npm install
```

### Run in dev mode

```bash
npm run dev
```

### Build

```bash
npm run build
```

### Lint

```bash
npm run lint
```

## Package Metadata

- Package: `n8n-nodes-piperun`
- Homepage: [https://github.com/LesserWords/n8n-nodes-piperun](https://github.com/LesserWords/n8n-nodes-piperun)
- License: MIT

## Notes

- The `Piperun` node uses OpenAPI-driven property generation (`@devlikeapro/n8n-openapi-node`).
- The repository still contains starter example nodes (`Example`, `GithubIssues`) for reference.
