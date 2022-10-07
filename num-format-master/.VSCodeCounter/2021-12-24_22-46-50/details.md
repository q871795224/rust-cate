# Details

Date : 2021-12-24 22:46:50

Directory d:\code\Rust crate\num-format-master

Total : 62 files,  10307 codes, 794 comments, 836 blanks, all 11937 lines

[summary](results.md)

## Files
| filename | language | code | comment | blank | total |
| :--- | :--- | ---: | ---: | ---: | ---: |
| [.travis.yml](/.travis.yml) | YAML | 19 | 0 | 1 | 20 |
| [CHANGELOG.md](/CHANGELOG.md) | Markdown | 69 | 0 | 22 | 91 |
| [CONTRIBUTING.md](/CONTRIBUTING.md) | Markdown | 49 | 0 | 23 | 72 |
| [README.md](/README.md) | Markdown | 161 | 0 | 55 | 216 |
| [num-format-benches/README.md](/num-format-benches/README.md) | Markdown | 3 | 0 | 2 | 5 |
| [num-format-benches/benches/bench_usize.rs](/num-format-benches/benches/bench_usize.rs) | Rust | 89 | 0 | 6 | 95 |
| [num-format-benches/python/bench.py](/num-format-benches/python/bench.py) | Python | 11 | 0 | 4 | 15 |
| [num-format-benches/src/lib.rs](/num-format-benches/src/lib.rs) | Rust | 0 | 0 | 2 | 2 |
| [num-format-dev/README.md](/num-format-dev/README.md) | Markdown | 3 | 0 | 2 | 5 |
| [num-format-dev/src/create_module.rs](/num-format-dev/src/create_module.rs) | Rust | 229 | 60 | 42 | 331 |
| [num-format-dev/src/lib.rs](/num-format-dev/src/lib.rs) | Rust | 25 | 1 | 4 | 30 |
| [num-format-dev/src/main.rs](/num-format-dev/src/main.rs) | Rust | 12 | 0 | 4 | 16 |
| [num-format-dev/src/parse_data.rs](/num-format-dev/src/parse_data.rs) | Rust | 95 | 12 | 21 | 128 |
| [num-format-dev/src/rustfmt.rs](/num-format-dev/src/rustfmt.rs) | Rust | 18 | 2 | 5 | 25 |
| [num-format-dev/src/utils/format.rs](/num-format-dev/src/utils/format.rs) | Rust | 12 | 0 | 3 | 15 |
| [num-format-dev/src/utils/grouping.rs](/num-format-dev/src/utils/grouping.rs) | Rust | 40 | 0 | 7 | 47 |
| [num-format-dev/src/utils/mod.rs](/num-format-dev/src/utils/mod.rs) | Rust | 4 | 0 | 2 | 6 |
| [num-format-windows/README.md](/num-format-windows/README.md) | Markdown | 9 | 0 | 4 | 13 |
| [num-format-windows/build.rs](/num-format-windows/build.rs) | Rust | 31 | 0 | 6 | 37 |
| [num-format-windows/src/lib.rs](/num-format-windows/src/lib.rs) | Rust | 6 | 10 | 2 | 18 |
| [num-format-windows/wrapper.h](/num-format-windows/wrapper.h) | C++ | 1 | 0 | 1 | 2 |
| [num-format/README.md](/num-format/README.md) | Markdown | 161 | 0 | 55 | 216 |
| [num-format/src/buffer.rs](/num-format/src/buffer.rs) | Rust | 177 | 36 | 35 | 248 |
| [num-format/src/constants.rs](/num-format/src/constants.rs) | Rust | 20 | 4 | 5 | 29 |
| [num-format/src/custom_format.rs](/num-format/src/custom_format.rs) | Rust | 123 | 38 | 24 | 185 |
| [num-format/src/custom_format_builder.rs](/num-format/src/custom_format_builder.rs) | Rust | 120 | 26 | 16 | 162 |
| [num-format/src/error.rs](/num-format/src/error.rs) | Rust | 119 | 8 | 19 | 146 |
| [num-format/src/error_kind.rs](/num-format/src/error_kind.rs) | Rust | 74 | 17 | 22 | 113 |
| [num-format/src/format.rs](/num-format/src/format.rs) | Rust | 11 | 13 | 2 | 26 |
| [num-format/src/grouping.rs](/num-format/src/grouping.rs) | Rust | 7 | 5 | 1 | 13 |
| [num-format/src/impls.rs](/num-format/src/impls.rs) | Rust | 3 | 0 | 1 | 4 |
| [num-format/src/impls/integers.rs](/num-format/src/impls/integers.rs) | Rust | 197 | 9 | 26 | 232 |
| [num-format/src/impls/num.rs](/num-format/src/impls/num.rs) | Rust | 236 | 0 | 23 | 259 |
| [num-format/src/lib.rs](/num-format/src/lib.rs) | Rust | 69 | 227 | 10 | 306 |
| [num-format/src/locale.rs](/num-format/src/locale.rs) | Rust | 5,531 | 0 | 1 | 5,532 |
| [num-format/src/parsing.rs](/num-format/src/parsing.rs) | Rust | 154 | 38 | 29 | 221 |
| [num-format/src/strings.rs](/num-format/src/strings.rs) | Rust | 187 | 61 | 38 | 286 |
| [num-format/src/system_locale.rs](/num-format/src/system_locale.rs) | Rust | 131 | 93 | 28 | 252 |
| [num-format/src/system_locale/nix.rs](/num-format/src/system_locale/nix.rs) | Rust | 193 | 8 | 34 | 235 |
| [num-format/src/system_locale/nix/bsd.rs](/num-format/src/system_locale/nix/bsd.rs) | Rust | 46 | 0 | 7 | 53 |
| [num-format/src/system_locale/nix/encoding.rs](/num-format/src/system_locale/nix/encoding.rs) | Rust | 52 | 9 | 13 | 74 |
| [num-format/src/system_locale/nix/linux.rs](/num-format/src/system_locale/nix/linux.rs) | Rust | 54 | 0 | 8 | 62 |
| [num-format/src/system_locale/windows.rs](/num-format/src/system_locale/windows.rs) | Rust | 358 | 17 | 45 | 420 |
| [num-format/src/to_formatted_str.rs](/num-format/src/to_formatted_str.rs) | Rust | 9 | 5 | 2 | 16 |
| [num-format/src/to_formatted_string.rs](/num-format/src/to_formatted_string.rs) | Rust | 53 | 6 | 8 | 67 |
| [num-format/src/write_formatted.rs](/num-format/src/write_formatted.rs) | Rust | 88 | 20 | 13 | 121 |
| [num-format/tests/common/mod.rs](/num-format/tests/common/mod.rs) | Rust | 42 | 0 | 3 | 45 |
| [num-format/tests/test_errors.rs](/num-format/tests/test_errors.rs) | Rust | 102 | 0 | 13 | 115 |
| [num-format/tests/test_no_bytes_written.rs](/num-format/tests/test_no_bytes_written.rs) | Rust | 63 | 0 | 7 | 70 |
| [num-format/tests/test_non_zero.rs](/num-format/tests/test_non_zero.rs) | Rust | 268 | 18 | 28 | 314 |
| [num-format/tests/test_num_bigint.rs](/num-format/tests/test_num_bigint.rs) | Rust | 177 | 6 | 13 | 196 |
| [num-format/tests/test_serialization.rs](/num-format/tests/test_serialization.rs) | Rust | 34 | 0 | 9 | 43 |
| [num-format/tests/test_signed.rs](/num-format/tests/test_signed.rs) | Rust | 293 | 18 | 27 | 338 |
| [num-format/tests/test_system_locale_unix.rs](/num-format/tests/test_system_locale_unix.rs) | Rust | 24 | 0 | 4 | 28 |
| [num-format/tests/test_system_locale_windows.rs](/num-format/tests/test_system_locale_windows.rs) | Rust | 10 | 0 | 3 | 13 |
| [num-format/tests/test_unsigned.rs](/num-format/tests/test_unsigned.rs) | Rust | 203 | 18 | 27 | 248 |
| [scripts/README.md](/scripts/README.md) | Markdown | 1 | 0 | 1 | 2 |
| [scripts/bench.sh](/scripts/bench.sh) | Shell Script | 1 | 1 | 2 | 4 |
| [scripts/check.sh](/scripts/check.sh) | Shell Script | 8 | 3 | 4 | 15 |
| [scripts/locale.sh](/scripts/locale.sh) | Shell Script | 3 | 1 | 3 | 7 |
| [scripts/readme.sh](/scripts/readme.sh) | Shell Script | 10 | 1 | 4 | 15 |
| [scripts/test.sh](/scripts/test.sh) | Shell Script | 9 | 3 | 5 | 17 |

[summary](results.md)