# nexum-chat-realtime-api

A minimal TypeScript Socket.IO server using Bun and Express. The main entry is [src/index.ts](src/index.ts) which exposes an Express `app` and a Socket.IO `io` server. Key symbols you may inspect:

- [`app`](src/index.ts) — Express application instance
- [`server`](src/index.ts) — HTTP server created from `app`
- [`io`](src/index.ts) — Socket.IO server
- [`PORT`](src/index.ts) — configured port (falls back to 3001)

See project metadata in [package.json](package.json) and TypeScript config in [tsconfig.json](tsconfig.json).

## Prerequisites

- Bun installed (https://bun.sh)

## Install (dependencies + dev)

Run from the repository root:

```sh
# install deps declared in [package.json](http://_vscodecontentref_/0)
bun install

# ensure TypeScript is available for type checking (peer dep)
bun add -d typescript@latest
```
