# Test Alpine

#### How to replicate the error

1. Start on the `working-0.5.4` branch
2. `pnpm install && pnpm build`, note how it works
3. Change to the `broken-1.0.0` branch
4. `pnpm install && pnpm build`, note how it doesnt work
5. Check the PR that I have showing the diff between the two branches.

