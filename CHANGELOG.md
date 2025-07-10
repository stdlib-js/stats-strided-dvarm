# CHANGELOG

> Package changelog.

<section class="release" id="unreleased">

## Unreleased (2025-07-10)

<section class="features">

### Features

-   [`5cee2da`](https://github.com/stdlib-js/stdlib/commit/5cee2da95c8513cc438a5f87d2bc413c96ff7ca1) - add `stats/strided/dvarm`

</section>

<!-- /.features -->

<section class="breaking-changes">

### BREAKING CHANGES

-   [`7e9ce86`](https://github.com/stdlib-js/stdlib/commit/7e9ce86fc343a49f7f24387493e6eb78f9693282): switch order of `mean` and `correction` parameters

    -   To migrate, users should swap `mean` and `correction` arguments.
        This change ensures that the `*varm*` function signatures follow
        similar conventions as found in binary APIs, such as those for
        computing the covariance, where the `mean` parameter immediately
        precedes the array argument.

</section>

<!-- /.breaking-changes -->

<section class="commits">

### Commits

<details>

-   [`5c78c73`](https://github.com/stdlib-js/stdlib/commit/5c78c731a6ec51fde6d0bdd28fb9831f03dfe0b5) - **bench:** fix invocation _(by Athan Reines)_
-   [`7e9ce86`](https://github.com/stdlib-js/stdlib/commit/7e9ce86fc343a49f7f24387493e6eb78f9693282) - **refactor:** reorder parameters _(by Athan Reines)_
-   [`5cee2da`](https://github.com/stdlib-js/stdlib/commit/5cee2da95c8513cc438a5f87d2bc413c96ff7ca1) - **feat:** add `stats/strided/dvarm` _(by Gururaj Gurram)_

</details>

</section>

<!-- /.commits -->

<section class="contributors">

### Contributors

A total of 2 people contributed to this release. Thank you to the following contributors:

-   Athan Reines
-   Gururaj Gurram

</section>

<!-- /.contributors -->

</section>

<!-- /.release -->

