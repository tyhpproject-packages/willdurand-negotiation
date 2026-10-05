<!-- tyhp-readme:start -->
# tyhpdef/willdurand-negotiation

Tyhp type definitions for `willdurand/negotiation` `3.1.0`.

```bash
composer require --dev tyhpdef/willdurand-negotiation:3.1.0
```

This is a metapackage. Composer also installs `tyhpdef/willdurand-negotiation-impl` (type files).
Require **this** name, not `tyhpdef/willdurand-negotiation-impl`.

See https://tyhplang.com.

## Maintain `willdurand/negotiation`? Ship the types yourself

If you are a Packagist maintainer of `willdurand/negotiation`, you can take over these
types.

Copy `_tyhpdef/` from **`tyhpdef/willdurand-negotiation-impl`** (Apache-2.0; keep the `NOTICE`).
Then either:

1. **Bundle** the files in `willdurand/negotiation` and set `extra.tyhp.package` on
   that `composer.json`, plus
   `"replace": { "tyhpdef/willdurand-negotiation": "self.version" }`, or
2. **Publish a sibling** types package under your vendor, versioned with
   `willdurand/negotiation` (same `X.Y.Z`). Set `extra.tyhp.package` there,
   `require` `willdurand/negotiation` with a real constraint,
   `"replace": { "tyhpdef/willdurand-negotiation": "self.version" }`, and set
   `extra.tyhp.tyhpdef` on `willdurand/negotiation` to your sibling’s Composer name.

Ship that to Packagist first, then open an issue:

https://github.com/tyhpproject/tyhp-runtime-src/issues/new?template=tyhpdef-ownership.yml

We verify Packagist ownership and that the types parse and cover the PHP
API, then stop publishing community tags for those versions. We do not
transfer the `tyhpdef/willdurand-negotiation` Packagist name.

Full process: `TYHPDEF_OWNERSHIP.md` in
https://github.com/tyhpproject/tyhp-runtime-src
<!-- tyhp-readme:end -->
