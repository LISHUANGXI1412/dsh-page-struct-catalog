# dsh-page-struct-catalog

DSH Community Market catalog source for LISHUANGXI1412 plugins:

- [`dsh-page-struct`](https://www.npmjs.com/package/dsh-page-struct)
- [`dsh-memory-local`](https://www.npmjs.com/package/dsh-memory-local)

## Add to DSH

Market → Sources → add this manifest URL:

```text
https://lishuangxi1412.github.io/dsh-page-struct-catalog/source.json
```

Then Market → Discover → search **Page Structure** or **Local Memory** → Install.

## Files

- `source.json` — catalog source manifest
- `v1/plugins` — catalog page (the endpoint must end with `/v1/plugins`)
- `v1/plugins.json` — same page with a `.json` suffix for direct inspection

Both packages are published on npm with `dsh.bundle.patch`.
