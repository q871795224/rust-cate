# Details

Date : 2021-12-24 22:38:10

Directory d:\code\Rust crate\rand-master

Total : 101 files,  14641 codes, 5113 comments, 2523 blanks, all 22277 lines

[summary](results.md)

## Files
| filename | language | code | comment | blank | total |
| :--- | :--- | ---: | ---: | ---: | ---: |
| [.github/ISSUE_TEMPLATE/compile-issue.md](/.github/ISSUE_TEMPLATE/compile-issue.md) | Markdown | 11 | 0 | 6 | 17 |
| [.github/ISSUE_TEMPLATE/feature_request.md](/.github/ISSUE_TEMPLATE/feature_request.md) | Markdown | 12 | 0 | 7 | 19 |
| [.github/ISSUE_TEMPLATE/other.md](/.github/ISSUE_TEMPLATE/other.md) | Markdown | 7 | 0 | 4 | 11 |
| [.github/ISSUE_TEMPLATE/suggest-a-change.md](/.github/ISSUE_TEMPLATE/suggest-a-change.md) | Markdown | 17 | 0 | 12 | 29 |
| [.github/workflows/gh-pages.yml](/.github/workflows/gh-pages.yml) | YAML | 28 | 1 | 3 | 32 |
| [.github/workflows/test.yml](/.github/workflows/test.yml) | YAML | 191 | 6 | 11 | 208 |
| [CHANGELOG.md](/CHANGELOG.md) | Markdown | 536 | 0 | 162 | 698 |
| [README.md](/README.md) | Markdown | 118 | 0 | 41 | 159 |
| [SECURITY.md](/SECURITY.md) | Markdown | 50 | 0 | 20 | 70 |
| [benches/distributions.rs](/benches/distributions.rs) | Rust | 341 | 39 | 61 | 441 |
| [benches/generators.rs](/benches/generators.rs) | Rust | 139 | 7 | 19 | 165 |
| [benches/misc.rs](/benches/misc.rs) | Rust | 155 | 9 | 20 | 184 |
| [benches/seq.rs](/benches/seq.rs) | Rust | 165 | 11 | 25 | 201 |
| [benches/weighted.rs](/benches/weighted.rs) | Rust | 24 | 7 | 6 | 37 |
| [examples/monte-carlo.rs](/examples/monte-carlo.rs) | Rust | 19 | 25 | 8 | 52 |
| [examples/monty-hall.rs](/examples/monty-hall.rs) | Rust | 65 | 37 | 22 | 124 |
| [rand_chacha/CHANGELOG.md](/rand_chacha/CHANGELOG.md) | Markdown | 30 | 0 | 10 | 40 |
| [rand_chacha/README.md](/rand_chacha/README.md) | Markdown | 34 | 0 | 16 | 50 |
| [rand_chacha/src/chacha.rs](/rand_chacha/src/chacha.rs) | Rust | 465 | 110 | 63 | 638 |
| [rand_chacha/src/guts.rs](/rand_chacha/src/guts.rs) | Rust | 239 | 15 | 28 | 282 |
| [rand_chacha/src/lib.rs](/rand_chacha/src/lib.rs) | Rust | 17 | 10 | 7 | 34 |
| [rand_core/CHANGELOG.md](/rand_core/CHANGELOG.md) | Markdown | 78 | 0 | 16 | 94 |
| [rand_core/README.md](/rand_core/README.md) | Markdown | 58 | 0 | 24 | 82 |
| [rand_core/src/block.rs](/rand_core/src/block.rs) | Rust | 327 | 147 | 66 | 540 |
| [rand_core/src/error.rs](/rand_core/src/error.rs) | Rust | 159 | 49 | 21 | 229 |
| [rand_core/src/impls.rs](/rand_core/src/impls.rs) | Rust | 117 | 70 | 21 | 208 |
| [rand_core/src/le.rs](/rand_core/src/le.rs) | Rust | 34 | 13 | 10 | 57 |
| [rand_core/src/lib.rs](/rand_core/src/lib.rs) | Rust | 159 | 330 | 43 | 532 |
| [rand_core/src/os.rs](/rand_core/src/os.rs) | Rust | 35 | 40 | 11 | 86 |
| [rand_distr/CHANGELOG.md](/rand_distr/CHANGELOG.md) | Markdown | 53 | 0 | 10 | 63 |
| [rand_distr/README.md](/rand_distr/README.md) | Markdown | 42 | 0 | 16 | 58 |
| [rand_distr/benches/src/distributions.rs](/rand_distr/benches/src/distributions.rs) | Rust | 191 | 9 | 33 | 233 |
| [rand_distr/src/binomial.rs](/rand_distr/src/binomial.rs) | Rust | 233 | 76 | 40 | 349 |
| [rand_distr/src/cauchy.rs](/rand_distr/src/cauchy.rs) | Rust | 111 | 39 | 18 | 168 |
| [rand_distr/src/dirichlet.rs](/rand_distr/src/dirichlet.rs) | Rust | 135 | 36 | 16 | 187 |
| [rand_distr/src/exponential.rs](/rand_distr/src/exponential.rs) | Rust | 104 | 62 | 16 | 182 |
| [rand_distr/src/frechet.rs](/rand_distr/src/frechet.rs) | Rust | 140 | 27 | 19 | 186 |
| [rand_distr/src/gamma.rs](/rand_distr/src/gamma.rs) | Rust | 593 | 169 | 53 | 815 |
| [rand_distr/src/geometric.rs](/rand_distr/src/geometric.rs) | Rust | 148 | 56 | 33 | 237 |
| [rand_distr/src/gumbel.rs](/rand_distr/src/gumbel.rs) | Rust | 114 | 26 | 16 | 156 |
| [rand_distr/src/hypergeometric.rs](/rand_distr/src/hypergeometric.rs) | Rust | 312 | 62 | 47 | 421 |
| [rand_distr/src/inverse_gaussian.rs](/rand_distr/src/inverse_gaussian.rs) | Rust | 89 | 6 | 18 | 113 |
| [rand_distr/src/lib.rs](/rand_distr/src/lib.rs) | Rust | 108 | 92 | 14 | 214 |
| [rand_distr/src/normal.rs](/rand_distr/src/normal.rs) | Rust | 203 | 135 | 34 | 372 |
| [rand_distr/src/normal_inverse_gaussian.rs](/rand_distr/src/normal_inverse_gaussian.rs) | Rust | 86 | 6 | 16 | 108 |
| [rand_distr/src/pareto.rs](/rand_distr/src/pareto.rs) | Rust | 95 | 25 | 15 | 135 |
| [rand_distr/src/pert.rs](/rand_distr/src/pert.rs) | Rust | 101 | 36 | 13 | 150 |
| [rand_distr/src/poisson.rs](/rand_distr/src/poisson.rs) | Rust | 120 | 43 | 19 | 182 |
| [rand_distr/src/skew_normal.rs](/rand_distr/src/skew_normal.rs) | Rust | 186 | 48 | 23 | 257 |
| [rand_distr/src/triangular.rs](/rand_distr/src/triangular.rs) | Rust | 91 | 32 | 11 | 134 |
| [rand_distr/src/unit_ball.rs](/rand_distr/src/unit_ball.rs) | Rust | 24 | 21 | 4 | 49 |
| [rand_distr/src/unit_circle.rs](/rand_distr/src/unit_circle.rs) | Rust | 38 | 25 | 6 | 69 |
| [rand_distr/src/unit_disc.rs](/rand_distr/src/unit_disc.rs) | Rust | 22 | 20 | 4 | 46 |
| [rand_distr/src/unit_sphere.rs](/rand_distr/src/unit_sphere.rs) | Rust | 34 | 24 | 6 | 64 |
| [rand_distr/src/utils.rs](/rand_distr/src/utils.rs) | Rust | 56 | 53 | 12 | 121 |
| [rand_distr/src/weibull.rs](/rand_distr/src/weibull.rs) | Rust | 97 | 22 | 14 | 133 |
| [rand_distr/src/weighted_alias.rs](/rand_distr/src/weighted_alias.rs) | Rust | 375 | 94 | 56 | 525 |
| [rand_distr/src/ziggurat_tables.rs](/rand_distr/src/ziggurat_tables.rs) | Rust | 271 | 10 | 3 | 284 |
| [rand_distr/src/zipf.rs](/rand_distr/src/zipf.rs) | Rust | 257 | 84 | 34 | 375 |
| [rand_distr/tests/pdf.rs](/rand_distr/tests/pdf.rs) | Rust | 136 | 17 | 27 | 180 |
| [rand_distr/tests/sparkline.rs](/rand_distr/tests/sparkline.rs) | Rust | 103 | 15 | 11 | 129 |
| [rand_distr/tests/uniformity.rs](/rand_distr/tests/uniformity.rs) | Rust | 53 | 7 | 6 | 66 |
| [rand_distr/tests/value_stability.rs](/rand_distr/tests/value_stability.rs) | Rust | 320 | 26 | 37 | 383 |
| [rand_pcg/CHANGELOG.md](/rand_pcg/CHANGELOG.md) | Markdown | 30 | 0 | 11 | 41 |
| [rand_pcg/README.md](/rand_pcg/README.md) | Markdown | 28 | 0 | 15 | 43 |
| [rand_pcg/src/lib.rs](/rand_pcg/src/lib.rs) | Rust | 14 | 28 | 5 | 47 |
| [rand_pcg/src/pcg128.rs](/rand_pcg/src/pcg128.rs) | Rust | 155 | 94 | 34 | 283 |
| [rand_pcg/src/pcg128cm.rs](/rand_pcg/src/pcg128cm.rs) | Rust | 96 | 65 | 22 | 183 |
| [rand_pcg/src/pcg64.rs](/rand_pcg/src/pcg64.rs) | Rust | 88 | 61 | 21 | 170 |
| [rand_pcg/tests/lcg128cmdxsm64.rs](/rand_pcg/tests/lcg128cmdxsm64.rs) | Rust | 62 | 3 | 13 | 78 |
| [rand_pcg/tests/lcg128xsl64.rs](/rand_pcg/tests/lcg128xsl64.rs) | Rust | 62 | 3 | 13 | 78 |
| [rand_pcg/tests/lcg64xsh32.rs](/rand_pcg/tests/lcg64xsh32.rs) | Rust | 55 | 3 | 13 | 71 |
| [rand_pcg/tests/mcg128xsl64.rs](/rand_pcg/tests/mcg128xsl64.rs) | Rust | 60 | 3 | 13 | 76 |
| [src/distributions/bernoulli.rs](/src/distributions/bernoulli.rs) | Rust | 123 | 71 | 21 | 215 |
| [src/distributions/distribution.rs](/src/distributions/distribution.rs) | Rust | 147 | 100 | 26 | 273 |
| [src/distributions/float.rs](/src/distributions/float.rs) | Rust | 194 | 84 | 35 | 313 |
| [src/distributions/integer.rs](/src/distributions/integer.rs) | Rust | 236 | 11 | 28 | 275 |
| [src/distributions/mod.rs](/src/distributions/mod.rs) | Rust | 37 | 174 | 8 | 219 |
| [src/distributions/other.rs](/src/distributions/other.rs) | Rust | 248 | 79 | 39 | 366 |
| [src/distributions/slice.rs](/src/distributions/slice.rs) | Rust | 41 | 67 | 10 | 118 |
| [src/distributions/uniform.rs](/src/distributions/uniform.rs) | Rust | 1,093 | 403 | 155 | 1,651 |
| [src/distributions/utils.rs](/src/distributions/utils.rs) | Rust | 322 | 47 | 61 | 430 |
| [src/distributions/weighted.rs](/src/distributions/weighted.rs) | Rust | 29 | 13 | 6 | 48 |
| [src/distributions/weighted_index.rs](/src/distributions/weighted_index.rs) | Rust | 310 | 97 | 47 | 454 |
| [src/lib.rs](/src/lib.rs) | Rust | 88 | 115 | 13 | 216 |
| [src/prelude.rs](/src/prelude.rs) | Rust | 14 | 18 | 3 | 35 |
| [src/rng.rs](/src/rng.rs) | Rust | 294 | 264 | 43 | 601 |
| [src/rngs/adapter/mod.rs](/src/rngs/adapter/mod.rs) | Rust | 5 | 8 | 4 | 17 |
| [src/rngs/adapter/read.rs](/src/rngs/adapter/read.rs) | Rust | 93 | 30 | 28 | 151 |
| [src/rngs/adapter/reseeding.rs](/src/rngs/adapter/reseeding.rs) | Rust | 222 | 122 | 43 | 387 |
| [src/rngs/mock.rs](/src/rngs/mock.rs) | Rust | 51 | 24 | 13 | 88 |
| [src/rngs/mod.rs](/src/rngs/mod.rs) | Rust | 15 | 97 | 8 | 120 |
| [src/rngs/small.rs](/src/rngs/small.rs) | Rust | 37 | 69 | 12 | 118 |
| [src/rngs/std.rs](/src/rngs/std.rs) | Rust | 53 | 25 | 21 | 99 |
| [src/rngs/thread.rs](/src/rngs/thread.rs) | Rust | 64 | 62 | 18 | 144 |
| [src/rngs/xoshiro128plusplus.rs](/src/rngs/xoshiro128plusplus.rs) | Rust | 80 | 22 | 17 | 119 |
| [src/rngs/xoshiro256plusplus.rs](/src/rngs/xoshiro256plusplus.rs) | Rust | 82 | 24 | 17 | 123 |
| [src/seq/index.rs](/src/seq/index.rs) | Rust | 477 | 125 | 77 | 679 |
| [src/seq/mod.rs](/src/seq/mod.rs) | Rust | 906 | 330 | 121 | 1,357 |
| [utils/redirect.html](/utils/redirect.html) | HTML | 1 | 0 | 1 | 2 |
| [utils/ziggurat_tables.py](/utils/ziggurat_tables.py) | Python | 58 | 43 | 25 | 126 |

[summary](results.md)