# sea-query-common-like

[![Coverage Status](https://coveralls.io/repos/github/mpyw/sea-query-common-like/badge.svg?branch=main)](https://coveralls.io/github/mpyw/sea-query-common-like?branch=main)

A Rust crate for enhancing [`sea_query`](https://docs.rs/sea-query/latest/sea_query/) with typical `LIKE` search support, including escape sequences for patterns (`%fuzzy%`, `prefix%`, `%suffix`) and multi-column fuzzy search.

- Documentation: [sea_query_common_like - Rust](https://docs.rs/sea-query-common-like/latest/sea_query_common_like/)

## Compatibility

| `sea-query-common-like` | `sea-query` | `sea-orm` (`with-sea-orm`) | Rust |
| --- | --- | --- | --- |
| 2.x | 1.0 | 2.0 | 1.94 |
| 1.x | 0.31 to 0.32 | 1.0 to 1.1 | 1.80 |
