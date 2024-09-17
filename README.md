# textlint-worker
Example of running textlint on Cloudflare Workers.

## Run
```bash
$ echo -n "TOD: test" | http :8787
```
-> NG

```bash
$ echo -n "TODO: test" | http :8787
```
-> OK

## Lint
```bash
$ pnpm biome check . --write 
```
## Deploy
```bash
$ pnpm run deploy
```
