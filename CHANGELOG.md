# CHANGELOG

> Package changelog.

<section class="release" id="unreleased">

## Unreleased (2025-12-18)

<section class="features">

### Features

-   [`6e539e7`](https://github.com/stdlib-js/stdlib/commit/6e539e715f29950ccc8384337d91e2b2ebf678e7) - add `complex/base/assert` namespace
-   [`95ee9a0`](https://github.com/stdlib-js/stdlib/commit/95ee9a0d45606e4b9c387366f36ba4fcea4adae5) - add `complex/base/assert/is-almost-same-value`
-   [`d0857d0`](https://github.com/stdlib-js/stdlib/commit/d0857d0faf6a6718ff9cd002f99184a20ca89278) - add `complex/base/assert/is-almost-equal`

</section>

<!-- /.features -->

<section class="bug-fixes">

### Bug Fixes

-   [`cf3f92e`](https://github.com/stdlib-js/stdlib/commit/cf3f92eddd20ec1a4106c8a34f7d7705a9a99dbc) - update include paths

</section>

<!-- /.bug-fixes -->

<section class="breaking-changes">

### BREAKING CHANGES

-   [`866b939`](https://github.com/stdlib-js/stdlib/commit/866b93963b9ba84407c36b19514aba6ab55489b8): remove `complex/base/assert/is-not-equal`

    -   To migrate, users should update their require/import paths to use
        `@stdlib/complex-float64/base/assert/is-not-equal` which provides the
        same API and implementation.

-   [`33db937`](https://github.com/stdlib-js/stdlib/commit/33db9374d77760cc20b4f025b6582af7138eda33): remove `complex/base/assert/is-not-equalf`

    -   To migrate, users should update their require/import paths to use
        `@stdlib/complex-float32/base/assert/is-not-equal` which provides the
        same API and implementation.

-   [`f6c3671`](https://github.com/stdlib-js/stdlib/commit/f6c3671093e29616c7da3347bb311ff8007daba4): remove `complex/base/assert/is-equalf`

    -   To migrate, users should update their require/import paths to use
        `@stdlib/complex-float32/base/assert/is-equal` which provides the
        same API and implementation.

-   [`155251c`](https://github.com/stdlib-js/stdlib/commit/155251c40cd609f0f667b98834ef3244c9621405): remove `complex/base/assert/is-same-value`

    -   To migrate, users should update their require/import paths to use
        `@stdlib/complex-float64/base/assert/is-same-value` which provides the
        same API and implementation.

-   [`fd52b0d`](https://github.com/stdlib-js/stdlib/commit/fd52b0da91cb5aa49d287b0ee984fd1e0063e6ab): remove `complex/base/assert/is-same-value-zero`

    -   To migrate, users should update their require/import paths to use
        `@stdlib/complex-float64/base/assert/is-same-value-zero` which provides the
        same API and implementation.

-   [`a391a4c`](https://github.com/stdlib-js/stdlib/commit/a391a4c422edfa112a686ccfee71390ae32f9edd): remove `complex/base/assert/is-same-value-zerof`

    -   To migrate, users should update their require/import paths to use
        `@stdlib/complex-float32/base/assert/is-same-value` which provides the
        same API and implementation.

-   [`de703af`](https://github.com/stdlib-js/stdlib/commit/de703afc520c9bae446c5b9de9357dc23e047647): remove `complex/base/assert` namespace

    -   To migrate, users should use the `complex/float32/base/assert` and
        `complex/float64/base/assert` namespaces.

-   [`91ac840`](https://github.com/stdlib-js/stdlib/commit/91ac840a8f3afd034c16b44ecc441949f70f422b): remove `complex/base/assert/is-same-valuef`

    -   To migrate, users should update their require/import paths to use
        `@stdlib/complex-float32/base/assert/is-same-value` which provides the
        same API and implementation.

-   [`0be60c5`](https://github.com/stdlib-js/stdlib/commit/0be60c5b5c2136ca09e4dfd2edd5efdaf3bb2423): remove `complex/base/assert/is-equal`

    -   To migrate, users should update their require/import paths to use
        `@stdlib/complex-float64/base/assert/is-equal` which provides the
        same API and implementation.

</section>

<!-- /.breaking-changes -->

<section class="commits">

### Commits

<details>

-   [`de9dec4`](https://github.com/stdlib-js/stdlib/commit/de9dec49411a9f71d800970e9324e87dca52098b) - **docs:** update namespace table of contents [(#9205)](https://github.com/stdlib-js/stdlib/pull/9205) _(by stdlib-bot)_
-   [`6e539e7`](https://github.com/stdlib-js/stdlib/commit/6e539e715f29950ccc8384337d91e2b2ebf678e7) - **feat:** add `complex/base/assert` namespace _(by Athan Reines)_
-   [`95ee9a0`](https://github.com/stdlib-js/stdlib/commit/95ee9a0d45606e4b9c387366f36ba4fcea4adae5) - **feat:** add `complex/base/assert/is-almost-same-value` _(by Athan Reines)_
-   [`de7678a`](https://github.com/stdlib-js/stdlib/commit/de7678a5abc59883ba8f0512c71bd0ceb352613b) - **test:** fix descriptions _(by Athan Reines)_
-   [`d0857d0`](https://github.com/stdlib-js/stdlib/commit/d0857d0faf6a6718ff9cd002f99184a20ca89278) - **feat:** add `complex/base/assert/is-almost-equal` _(by Athan Reines)_
-   [`866b939`](https://github.com/stdlib-js/stdlib/commit/866b93963b9ba84407c36b19514aba6ab55489b8) - **remove:** remove `complex/base/assert/is-not-equal` _(by Athan Reines)_
-   [`33db937`](https://github.com/stdlib-js/stdlib/commit/33db9374d77760cc20b4f025b6582af7138eda33) - **remove:** remove `complex/base/assert/is-not-equalf` _(by Athan Reines)_
-   [`f6c3671`](https://github.com/stdlib-js/stdlib/commit/f6c3671093e29616c7da3347bb311ff8007daba4) - **remove:** remove `complex/base/assert/is-equalf` _(by Athan Reines)_
-   [`155251c`](https://github.com/stdlib-js/stdlib/commit/155251c40cd609f0f667b98834ef3244c9621405) - **remove:** remove `complex/base/assert/is-same-value` _(by Athan Reines)_
-   [`fd52b0d`](https://github.com/stdlib-js/stdlib/commit/fd52b0da91cb5aa49d287b0ee984fd1e0063e6ab) - **remove:** remove `complex/base/assert/is-same-value-zero` _(by Athan Reines)_
-   [`a391a4c`](https://github.com/stdlib-js/stdlib/commit/a391a4c422edfa112a686ccfee71390ae32f9edd) - **remove:** remove `complex/base/assert/is-same-value-zerof` _(by Athan Reines)_
-   [`de703af`](https://github.com/stdlib-js/stdlib/commit/de703afc520c9bae446c5b9de9357dc23e047647) - **remove:** remove `complex/base/assert` namespace _(by Athan Reines)_
-   [`91ac840`](https://github.com/stdlib-js/stdlib/commit/91ac840a8f3afd034c16b44ecc441949f70f422b) - **remove:** remove `complex/base/assert/is-same-valuef` _(by Athan Reines)_
-   [`e20ba77`](https://github.com/stdlib-js/stdlib/commit/e20ba77de9ecf13d82630e3d88e014af0aed5a5b) - **docs:** update path _(by Athan Reines)_
-   [`32fd387`](https://github.com/stdlib-js/stdlib/commit/32fd3872225d598d3c29eeb1c837641a85d21364) - **docs:** update paths _(by Athan Reines)_
-   [`0be60c5`](https://github.com/stdlib-js/stdlib/commit/0be60c5b5c2136ca09e4dfd2edd5efdaf3bb2423) - **remove:** remove `complex/base/assert/is-equal` _(by Athan Reines)_
-   [`cf3f92e`](https://github.com/stdlib-js/stdlib/commit/cf3f92eddd20ec1a4106c8a34f7d7705a9a99dbc) - **fix:** update include paths _(by Athan Reines)_
-   [`75d4f83`](https://github.com/stdlib-js/stdlib/commit/75d4f83cb85610d23a04dc21a03f8075f6d3665f) - **refactor:** update require and include paths _(by Athan Reines)_

</details>

</section>

<!-- /.commits -->

<section class="contributors">

### Contributors

A total of 1 person contributed to this release. Thank you to this contributor:

-   Athan Reines

</section>

<!-- /.contributors -->

</section>

<!-- /.release -->

<section class="release" id="v0.2.1">

## 0.2.1 (2024-02-24)

No changes reported for this release.

</section>

<!-- /.release -->

<section class="release" id="v0.2.0">

## 0.2.0 (2024-02-14)

<section class="features">

### Features

-   [`2693e3b`](https://github.com/stdlib-js/stdlib/commit/2693e3b3f0382542a51fc57d78e9ab59e2dc0681) - update namespace TypeScript declarations [(#1287)](https://github.com/stdlib-js/stdlib/pull/1287)
-   [`5ca21f2`](https://github.com/stdlib-js/stdlib/commit/5ca21f212ae936776a49b61f4fc8d24c74877d03) - add `isSameValueZerof` to namespace
-   [`14d1d3d`](https://github.com/stdlib-js/stdlib/commit/14d1d3da0bd9dbee4e3b1268364acf227d1cfec1) - add `complex/base/assert/is-same-value-zerof`
-   [`7edde5e`](https://github.com/stdlib-js/stdlib/commit/7edde5e9f4126c2d11021323cfbf501219f32c00) - add `isSameValueZero` to namespace
-   [`9f459e9`](https://github.com/stdlib-js/stdlib/commit/9f459e9df86e092665a81c8b51b5c87d4d436bc7) - add `complex/base/assert/is-same-value-zero`
-   [`bb1ec6e`](https://github.com/stdlib-js/stdlib/commit/bb1ec6e76a828f09c412b7ae32118a530495622f) - add `isSameValuef` to namespace
-   [`35895a3`](https://github.com/stdlib-js/stdlib/commit/35895a393721b953a5d00219047a5d0417985520) - add `complex/base/assert/is-same-valuef`

</section>

<!-- /.features -->

<section class="commits">

### Commits

<details>

-   [`2693e3b`](https://github.com/stdlib-js/stdlib/commit/2693e3b3f0382542a51fc57d78e9ab59e2dc0681) - **feat:** update namespace TypeScript declarations [(#1287)](https://github.com/stdlib-js/stdlib/pull/1287) _(by stdlib-bot, Athan Reines)_
-   [`322d1ca`](https://github.com/stdlib-js/stdlib/commit/322d1cac1bb150c548b5ad3b3086acd8e74a7bbd) - **docs:** update namespace table of contents [(#1284)](https://github.com/stdlib-js/stdlib/pull/1284) _(by stdlib-bot, Philipp Burckhardt)_
-   [`442fbfc`](https://github.com/stdlib-js/stdlib/commit/442fbfc181ef5859b67bdfad43dbe998ad07783e) - **docs:** update Markdown stdlib package URLs [(#1274)](https://github.com/stdlib-js/stdlib/pull/1274) _(by stdlib-bot)_
-   [`14b7db2`](https://github.com/stdlib-js/stdlib/commit/14b7db2b102ce54a583b490554cbbdb4813aa62d) - **docs:** update link _(by Athan Reines)_
-   [`a3f3058`](https://github.com/stdlib-js/stdlib/commit/a3f3058c7660f81f0e83b35732fd7bf385ea9f0e) - **docs:** update link _(by Athan Reines)_
-   [`5ca21f2`](https://github.com/stdlib-js/stdlib/commit/5ca21f212ae936776a49b61f4fc8d24c74877d03) - **feat:** add `isSameValueZerof` to namespace _(by Athan Reines)_
-   [`14d1d3d`](https://github.com/stdlib-js/stdlib/commit/14d1d3da0bd9dbee4e3b1268364acf227d1cfec1) - **feat:** add `complex/base/assert/is-same-value-zerof` _(by Athan Reines)_
-   [`17a73cd`](https://github.com/stdlib-js/stdlib/commit/17a73cdf0cfa67d9b19c0922027fbb05dffd6053) - **docs:** fix copy _(by Athan Reines)_
-   [`4cf9064`](https://github.com/stdlib-js/stdlib/commit/4cf90647739905687707739bf44727d622c3cd3f) - **docs:** update note _(by Athan Reines)_
-   [`7edde5e`](https://github.com/stdlib-js/stdlib/commit/7edde5e9f4126c2d11021323cfbf501219f32c00) - **feat:** add `isSameValueZero` to namespace _(by Athan Reines)_
-   [`9f459e9`](https://github.com/stdlib-js/stdlib/commit/9f459e9df86e092665a81c8b51b5c87d4d436bc7) - **feat:** add `complex/base/assert/is-same-value-zero` _(by Athan Reines)_
-   [`01e4fb4`](https://github.com/stdlib-js/stdlib/commit/01e4fb4948cef7c6eb32ae195e1abb696e7f8e59) - **docs:** fix typo _(by Athan Reines)_
-   [`d2ce216`](https://github.com/stdlib-js/stdlib/commit/d2ce21614afceb840bc7d8aae4f398aa154fa2f9) - **docs:** fix typo _(by Athan Reines)_
-   [`bb1ec6e`](https://github.com/stdlib-js/stdlib/commit/bb1ec6e76a828f09c412b7ae32118a530495622f) - **feat:** add `isSameValuef` to namespace _(by Athan Reines)_
-   [`35895a3`](https://github.com/stdlib-js/stdlib/commit/35895a393721b953a5d00219047a5d0417985520) - **feat:** add `complex/base/assert/is-same-valuef` _(by Athan Reines)_
-   [`5ef4279`](https://github.com/stdlib-js/stdlib/commit/5ef42795874e36a4c08ad3dce6d9555b27c7b04d) - **docs:** fix description _(by Athan Reines)_
-   [`12f0c7e`](https://github.com/stdlib-js/stdlib/commit/12f0c7e26b231f785b1bc640691b0aa70243b673) - **refactor:** use base float64 utility _(by Athan Reines)_

</details>

</section>

<!-- /.commits -->

<section class="contributors">

### Contributors

A total of 2 people contributed to this release. Thank you to the following contributors:

-   Athan Reines
-   Philipp Burckhardt

</section>

<!-- /.contributors -->

</section>

<!-- /.release -->

<section class="release" id="v0.1.0">

## 0.1.0 (2024-01-17)

<section class="features">

### Features

-   [`f6ff2c1`](https://github.com/stdlib-js/stdlib/commit/f6ff2c14adc722b42e6a548835b1f7a3e8ca6de9) - add `isSameValue` to namespace
-   [`28a9723`](https://github.com/stdlib-js/stdlib/commit/28a97234bc4c69e7d384cd9b5b9a72d13a7ed66d) - add `complex/base/assert/is-same-value`
-   [`dc81423`](https://github.com/stdlib-js/stdlib/commit/dc814231dc13b326ee14a7b250dd76c919b1ad86) - add `isNotEqualf` to namespace
-   [`190fd03`](https://github.com/stdlib-js/stdlib/commit/190fd0318fe6d0c62300df3d5c8c053b784e9634) - add `complex/base/assert/is-not-equalf`
-   [`79dad80`](https://github.com/stdlib-js/stdlib/commit/79dad80ed450b07fbb37382bd33b197273bc0fff) - add `isNotEqual` to namespace
-   [`875311c`](https://github.com/stdlib-js/stdlib/commit/875311c68a4ea8e012242f57d4a27ace4f18c314) - add `complex/base/assert/is-not-equal`
-   [`c084c0b`](https://github.com/stdlib-js/stdlib/commit/c084c0b26456c92cda8dbe3f0bf93ae4c32260bf) - add `complex/base/assert`
-   [`59fb1e6`](https://github.com/stdlib-js/stdlib/commit/59fb1e66b6d1ed34cf97d8240840aa26ca1f2e44) - add `complex/base/assert/is-equalf`
-   [`02bad1a`](https://github.com/stdlib-js/stdlib/commit/02bad1a684640693a46819992f8935ffc7b203e1) - add `complex/base/assert/is-equal`

</section>

<!-- /.features -->

<section class="bug-fixes">

### Bug Fixes

-   [`07e2d74`](https://github.com/stdlib-js/stdlib/commit/07e2d747623f859101c8542655e76a61e8f742f2) - rename C APIs to align with `@stdlib/number-*` conventions
-   [`ed7fbf1`](https://github.com/stdlib-js/stdlib/commit/ed7fbf13dd9bddb93a5588bdaf5fa78ad7a68f99) - rename C APIs to align with `@stdlib/number-*` conventions
-   [`d7296b0`](https://github.com/stdlib-js/stdlib/commit/d7296b0cec2d377442b6ae03ae1b75b558860216) - update include path

</section>

<!-- /.bug-fixes -->

<section class="commits">

### Commits

<details>

-   [`39ff9ab`](https://github.com/stdlib-js/stdlib/commit/39ff9abe1bd64e8ecea833c40740c26df7fddc60) - **chore:** fix copyright year _(by Athan Reines)_
-   [`07e2d74`](https://github.com/stdlib-js/stdlib/commit/07e2d747623f859101c8542655e76a61e8f742f2) - **fix:** rename C APIs to align with `@stdlib/number-*` conventions _(by Athan Reines)_
-   [`ed7fbf1`](https://github.com/stdlib-js/stdlib/commit/ed7fbf13dd9bddb93a5588bdaf5fa78ad7a68f99) - **fix:** rename C APIs to align with `@stdlib/number-*` conventions _(by Athan Reines)_
-   [`e8283f2`](https://github.com/stdlib-js/stdlib/commit/e8283f28b3212456fd6179d94f0d0de8e195780e) - **style:** fix alignment _(by Athan Reines)_
-   [`f6ff2c1`](https://github.com/stdlib-js/stdlib/commit/f6ff2c14adc722b42e6a548835b1f7a3e8ca6de9) - **feat:** add `isSameValue` to namespace _(by Athan Reines)_
-   [`28a9723`](https://github.com/stdlib-js/stdlib/commit/28a97234bc4c69e7d384cd9b5b9a72d13a7ed66d) - **feat:** add `complex/base/assert/is-same-value` _(by Athan Reines)_
-   [`dc81423`](https://github.com/stdlib-js/stdlib/commit/dc814231dc13b326ee14a7b250dd76c919b1ad86) - **feat:** add `isNotEqualf` to namespace _(by Athan Reines)_
-   [`190fd03`](https://github.com/stdlib-js/stdlib/commit/190fd0318fe6d0c62300df3d5c8c053b784e9634) - **feat:** add `complex/base/assert/is-not-equalf` _(by Athan Reines)_
-   [`79dad80`](https://github.com/stdlib-js/stdlib/commit/79dad80ed450b07fbb37382bd33b197273bc0fff) - **feat:** add `isNotEqual` to namespace _(by Athan Reines)_
-   [`875311c`](https://github.com/stdlib-js/stdlib/commit/875311c68a4ea8e012242f57d4a27ace4f18c314) - **feat:** add `complex/base/assert/is-not-equal` _(by Athan Reines)_
-   [`38f7e94`](https://github.com/stdlib-js/stdlib/commit/38f7e94d05a500c6aae609e4b11232d5db35c08e) - **docs:** fix include path _(by Athan Reines)_
-   [`d7296b0`](https://github.com/stdlib-js/stdlib/commit/d7296b0cec2d377442b6ae03ae1b75b558860216) - **fix:** update include path _(by Athan Reines)_
-   [`c084c0b`](https://github.com/stdlib-js/stdlib/commit/c084c0b26456c92cda8dbe3f0bf93ae4c32260bf) - **feat:** add `complex/base/assert` _(by Athan Reines)_
-   [`59fb1e6`](https://github.com/stdlib-js/stdlib/commit/59fb1e66b6d1ed34cf97d8240840aa26ca1f2e44) - **feat:** add `complex/base/assert/is-equalf` _(by Athan Reines)_
-   [`02bad1a`](https://github.com/stdlib-js/stdlib/commit/02bad1a684640693a46819992f8935ffc7b203e1) - **feat:** add `complex/base/assert/is-equal` _(by Athan Reines)_

</details>

</section>

<!-- /.commits -->

<section class="contributors">

### Contributors

A total of 1 person contributed to this release. Thank you to this contributor:

-   Athan Reines

</section>

<!-- /.contributors -->

</section>

<!-- /.release -->

