# Hudu Compute Cost site content

## Site content

- Audience: Japan. Japanese is served at `/`; English is served at `/en/`.
- Publication boundary: assumption-led JPY planning values and guidance only; no provider price retrieval, authentication, billing, purchasing, or advice.

## Local verification

```bash
pnpm install --offline --frozen-lockfile
pnpm validate:content
pnpm typecheck
pnpm test
pnpm build
```

Run `pnpm dev` only as a foreground loopback preview and stop it with Ctrl+C.
