# Details

Date : 2021-12-24 22:45:24

Directory d:\code\Rust crate\thiserror-master

Total : 46 files,  2844 codes, 293 comments, 448 blanks, all 3585 lines

[summary](results.md)

## Files
| filename | language | code | comment | blank | total |
| :--- | :--- | ---: | ---: | ---: | ---: |
| [.github/workflows/ci.yml](/.github/workflows/ci.yml) | YAML | 48 | 0 | 6 | 54 |
| [README.md](/README.md) | Markdown | 154 | 0 | 47 | 201 |
| [impl/src/ast.rs](/impl/src/ast.rs) | Rust | 153 | 0 | 13 | 166 |
| [impl/src/attr.rs](/impl/src/attr.rs) | Rust | 196 | 1 | 17 | 214 |
| [impl/src/expand.rs](/impl/src/expand.rs) | Rust | 497 | 0 | 26 | 523 |
| [impl/src/fmt.rs](/impl/src/fmt.rs) | Rust | 156 | 4 | 11 | 171 |
| [impl/src/generics.rs](/impl/src/generics.rs) | Rust | 74 | 0 | 9 | 83 |
| [impl/src/lib.rs](/impl/src/lib.rs) | Rust | 29 | 0 | 5 | 34 |
| [impl/src/prop.rs](/impl/src/prop.rs) | Rust | 116 | 1 | 19 | 136 |
| [impl/src/valid.rs](/impl/src/valid.rs) | Rust | 228 | 0 | 10 | 238 |
| [src/aserror.rs](/src/aserror.rs) | Rust | 35 | 0 | 7 | 42 |
| [src/display.rs](/src/display.rs) | Rust | 23 | 0 | 6 | 29 |
| [src/lib.rs](/src/lib.rs) | Rust | 13 | 204 | 5 | 222 |
| [tests/compiletest.rs](/tests/compiletest.rs) | Rust | 6 | 2 | 1 | 9 |
| [tests/test_backtrace.rs](/tests/test_backtrace.rs) | Rust | 210 | 0 | 39 | 249 |
| [tests/test_display.rs](/tests/test_display.rs) | Rust | 224 | 1 | 50 | 275 |
| [tests/test_error.rs](/tests/test_error.rs) | Rust | 48 | 0 | 10 | 58 |
| [tests/test_expr.rs](/tests/test_expr.rs) | Rust | 75 | 3 | 12 | 90 |
| [tests/test_from.rs](/tests/test_from.rs) | Rust | 54 | 0 | 11 | 65 |
| [tests/test_generics.rs](/tests/test_generics.rs) | Rust | 72 | 71 | 20 | 163 |
| [tests/test_lints.rs](/tests/test_lints.rs) | Rust | 10 | 3 | 6 | 19 |
| [tests/test_option.rs](/tests/test_option.rs) | Rust | 93 | 0 | 14 | 107 |
| [tests/test_path.rs](/tests/test_path.rs) | Rust | 33 | 0 | 7 | 40 |
| [tests/test_source.rs](/tests/test_source.rs) | Rust | 57 | 1 | 10 | 68 |
| [tests/test_transparent.rs](/tests/test_transparent.rs) | Rust | 67 | 0 | 14 | 81 |
| [tests/ui/bad-field-attr.rs](/tests/ui/bad-field-attr.rs) | Rust | 5 | 0 | 3 | 8 |
| [tests/ui/concat-display.rs](/tests/ui/concat-display.rs) | Rust | 10 | 1 | 5 | 16 |
| [tests/ui/duplicate-enum-source.rs](/tests/ui/duplicate-enum-source.rs) | Rust | 11 | 0 | 3 | 14 |
| [tests/ui/duplicate-fmt.rs](/tests/ui/duplicate-fmt.rs) | Rust | 6 | 0 | 3 | 9 |
| [tests/ui/duplicate-struct-source.rs](/tests/ui/duplicate-struct-source.rs) | Rust | 9 | 0 | 3 | 12 |
| [tests/ui/duplicate-transparent.rs](/tests/ui/duplicate-transparent.rs) | Rust | 6 | 0 | 3 | 9 |
| [tests/ui/from-backtrace-backtrace.rs](/tests/ui/from-backtrace-backtrace.rs) | Rust | 7 | 1 | 5 | 13 |
| [tests/ui/from-not-source.rs](/tests/ui/from-not-source.rs) | Rust | 9 | 0 | 3 | 12 |
| [tests/ui/lifetime.rs](/tests/ui/lifetime.rs) | Rust | 19 | 0 | 6 | 25 |
| [tests/ui/missing-fmt.rs](/tests/ui/missing-fmt.rs) | Rust | 8 | 0 | 3 | 11 |
| [tests/ui/no-display.rs](/tests/ui/no-display.rs) | Rust | 9 | 0 | 4 | 13 |
| [tests/ui/source-enum-not-error.rs](/tests/ui/source-enum-not-error.rs) | Rust | 11 | 0 | 4 | 15 |
| [tests/ui/source-struct-not-error.rs](/tests/ui/source-struct-not-error.rs) | Rust | 9 | 0 | 4 | 13 |
| [tests/ui/transparent-display.rs](/tests/ui/transparent-display.rs) | Rust | 6 | 0 | 3 | 9 |
| [tests/ui/transparent-enum-many.rs](/tests/ui/transparent-enum-many.rs) | Rust | 7 | 0 | 3 | 10 |
| [tests/ui/transparent-enum-source.rs](/tests/ui/transparent-enum-source.rs) | Rust | 7 | 0 | 3 | 10 |
| [tests/ui/transparent-struct-many.rs](/tests/ui/transparent-struct-many.rs) | Rust | 8 | 0 | 3 | 11 |
| [tests/ui/transparent-struct-source.rs](/tests/ui/transparent-struct-source.rs) | Rust | 5 | 0 | 3 | 8 |
| [tests/ui/unexpected-field-fmt.rs](/tests/ui/unexpected-field-fmt.rs) | Rust | 9 | 0 | 3 | 12 |
| [tests/ui/unexpected-struct-source.rs](/tests/ui/unexpected-struct-source.rs) | Rust | 5 | 0 | 3 | 8 |
| [tests/ui/union.rs](/tests/ui/union.rs) | Rust | 7 | 0 | 3 | 10 |

[summary](results.md)