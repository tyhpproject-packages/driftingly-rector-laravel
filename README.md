<!-- tyhp-readme:start -->
# tyhpdef/driftingly-rector-laravel

Tyhp type definitions for `driftingly/rector-laravel` `2.6.2`.

```bash
composer require --dev tyhpdef/driftingly-rector-laravel:2.6.2
```

This is a metapackage. Composer also installs `tyhpdef/driftingly-rector-laravel-impl` (type files).
Require **this** name, not `tyhpdef/driftingly-rector-laravel-impl`.

See https://tyhplang.com.

## Maintain `driftingly/rector-laravel`? Ship the types yourself

If you are a Packagist maintainer of `driftingly/rector-laravel`, you can take over these
types.

Copy `_tyhpdef/` from **`tyhpdef/driftingly-rector-laravel-impl`** (Apache-2.0; keep the `NOTICE`).
Then either:

1. **Bundle** the files in `driftingly/rector-laravel` and set `extra.tyhp.package` on
   that `composer.json`, plus
   `"replace": { "tyhpdef/driftingly-rector-laravel": "self.version" }`, or
2. **Publish a sibling** types package under your vendor, versioned with
   `driftingly/rector-laravel` (same `X.Y.Z`). Set `extra.tyhp.package` there,
   `require` `driftingly/rector-laravel` with a real constraint,
   `"replace": { "tyhpdef/driftingly-rector-laravel": "self.version" }`, and set
   `extra.tyhp.tyhpdef` on `driftingly/rector-laravel` to your sibling’s Composer name.

Ship that to Packagist first, then open an issue:

https://github.com/tyhpproject/tyhp-runtime-src/issues/new?template=tyhpdef-ownership.yml

We verify Packagist ownership and that the types parse and cover the PHP
API, then stop publishing community tags for those versions. We do not
transfer the `tyhpdef/driftingly-rector-laravel` Packagist name.

Full process: `TYHPDEF_OWNERSHIP.md` in
https://github.com/tyhpproject/tyhp-runtime-src
<!-- tyhp-readme:end -->
