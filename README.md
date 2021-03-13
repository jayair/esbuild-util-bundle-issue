# esbuild-util-bundle-issue

Run

``` bash
$ npx esbuild lib/index.ts --bundle --format=cjs --platform=node --outdir=. --tsconfig=tsconfig.json --metafile=meta.json
```

The `meta.json` doesn't include the `util/` import.
