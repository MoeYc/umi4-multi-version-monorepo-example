# umi4-multi-version-monorepo-example

umi monorepo multi-version coexistence test

### Usage

```bash
  pnpm dev
```

Open `localhost:{8001..8006}`:

 - `8001`: umi 3.4.20
 - `8002`: umi 3.5.30

 - `8003`: umi 4.0.8
 - `8004`: umi 4.0.0-canary.20220720.1

 - `8005`: max 4.0.8
 - `8006`: max 4.0.0-canary.20220720.1

P.S. Only versions after `4.0.0-canary.20220720.1` are available for monorepo.
