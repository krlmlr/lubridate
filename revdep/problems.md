# pollen

<details>

* Version: 0.82.0
* GitHub: https://github.com/Nowosad/pollen
* Source code: https://github.com/cran/pollen
* Date/Publication: 2021-12-03 12:20:02 UTC
* Number of recursive dependencies: 78

Run `revdepcheck::cloud_details(, "pollen")` for more info

</details>

## Newly broken

*   checking tests ... ERROR
    ```
      Running ‘testthat.R’
    Running the tests in ‘tests/testthat.R’ failed.
    Complete output:
      > library("testthat")
      > library("pollen")
      > 
      > test_check("pollen")
      [ FAIL 1 | WARN 7 | SKIP 0 | PASS 13 ]
      
      ══ Failed tests ════════════════════════════════════════════════════════════════
      ── Failure ('test-seasons.R:11:3'): results are proper ─────────────────────────
      `x` inherits from `'integer'` not `'character'`.
      Backtrace:
          ▆
       1. └─pollen (local) expect_numeric(results$year) at test-seasons.R:11:3
       2.   └─testthat::expect_is(x, "numeric") at test-seasons.R:3:19
      
      [ FAIL 1 | WARN 7 | SKIP 0 | PASS 13 ]
      Error: Test failures
      Execution halted
    ```

# stationaRy

<details>

* Version: 0.5.1
* GitHub: https://github.com/rich-iannone/stationaRy
* Source code: https://github.com/cran/stationaRy
* Date/Publication: 2020-01-12 06:00:06 UTC
* Number of recursive dependencies: 62

Run `revdepcheck::cloud_details(, "stationaRy")` for more info

</details>

## Newly broken

*   checking tests ... ERROR
    ```
      Running ‘testthat.R’
    Running the tests in ‘tests/testthat.R’ failed.
    Complete output:
      > library(testthat)
      > library(stationaRy)
      > 
      > test_check("stationaRy")
      [ FAIL 3 | WARN 28 | SKIP 0 | PASS 36 ]
      
      ══ Failed tests ════════════════════════════════════════════════════════════════
      ── Failure ('test-get_met_station_data.R:139:3'): The `station_coverage()` fcn can provide an additional data report ──
      `.` inherits from `'integer'` not `'character'`.
      Backtrace:
          ▆
       1. ├─stn_coverage_tbl_year %>% dplyr::pull(year) %>% ... at test-get_met_station_data.R:139:3
       2. └─testthat::expect_is(., "numeric")
      ── Failure ('test-get_met_station_data.R:167:3'): The `station_coverage()` fcn can provide an additional data report ──
      `.` inherits from `'integer'` not `'character'`.
      Backtrace:
          ▆
       1. ├─stn_coverage_tbl_month %>% dplyr::pull(year) %>% ... at test-get_met_station_data.R:167:3
       2. └─testthat::expect_is(., "numeric")
      ── Failure ('test-get_met_station_data.R:171:3'): The `station_coverage()` fcn can provide an additional data report ──
      `.` inherits from `'integer'` not `'character'`.
      Backtrace:
          ▆
       1. ├─stn_coverage_tbl_month %>% dplyr::pull(month) %>% ... at test-get_met_station_data.R:171:3
       2. └─testthat::expect_is(., "numeric")
      
      [ FAIL 3 | WARN 28 | SKIP 0 | PASS 36 ]
      Error: Test failures
      Execution halted
    ```

## In both

*   checking LazyData ... NOTE
    ```
      'LazyData' is specified without a 'data' directory
    ```

