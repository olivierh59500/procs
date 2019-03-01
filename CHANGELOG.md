# Change Log

## [Unreleased](https://github.com/dalance/procs/compare/v0.5.5...Unreleased) - ReleaseDate

* [Added] Ssb column
* [Added] sort option

## [v0.5.5](https://github.com/dalance/procs/compare/v0.5.4...v0.5.5) - 2019-02-28

* [Added] logical operation for search keywords
* [Changed] default logical operation for search keywords from OR to AND

## [v0.5.4](https://github.com/dalance/procs/compare/v0.5.3...v0.5.4) - 2019-02-27

* [Added] text align option

## [v0.5.3](https://github.com/dalance/procs/compare/v0.5.2...v0.5.3) - 2019-02-27

* [Fixed] panic by overflow

## [v0.5.2](https://github.com/dalance/procs/compare/v0.5.1...v0.5.2) - 2019-02-25

* [Fixed] `cargo install` failure on macOS

## [v0.5.1](https://github.com/dalance/procs/compare/v0.5.0...v0.5.1) - 2019-02-24

* [Fixed] CI issue

## [v0.5.0](https://github.com/dalance/procs/compare/v0.4.8...v0.5.0) - 2019-02-23

* [Added] macOS support
* [Added] ContextSw/Gid*/Group*/Policy/Sig*/Uid*/User* column

## [v0.4.8](https://github.com/dalance/procs/compare/v0.4.7...v0.4.8) - 2019-02-21

* [Added] `color_mode` option to `~/.procs.toml` setting
* [Added] `--pager` commandline option
* [Fixed] pager command of `~/.procs.toml` is not affected

## [v0.4.7](https://github.com/dalance/procs/compare/v0.4.6...v0.4.7) - 2019-02-18

* [Fixed] panic caused by zombie process
* [Fixed] build failure on Rust 1.31.1

## [v0.4.6](https://github.com/dalance/procs/compare/v0.4.5...v0.4.6) - 2019-02-16

* [Fixed] default pager option is not affected

## [v0.4.5](https://github.com/dalance/procs/compare/v0.4.4...v0.4.5) - 2019-02-14

* [Added] Vm*/Wchan column
* [Changed] `VmPeak` is added to default

## [v0.4.4](https://github.com/dalance/procs/compare/v0.4.3...v0.4.4) - 2019-02-11

* [Added] `cut_to_*` options to `~/.procs.toml` setting
* [Changed] default pager is changed to `less -SR`

## [v0.4.3](https://github.com/dalance/procs/compare/v0.4.2...v0.4.3) - 2019-02-07

* [Added] Eip/Esp/MajFlt/MinFlt/Nice/Ppid/Priority/Processor/RtPriority column

## [v0.4.2](https://github.com/dalance/procs/compare/v0.4.1...v0.4.2) - 2019-02-06

* [Changed] default pager is changed to `less`

## [v0.4.1](https://github.com/dalance/procs/compare/v0.4.0...v0.4.1) - 2019-02-06

* [Fixed] failure of text width calculation with tab charactor

## [v0.4.0](https://github.com/dalance/procs/compare/v0.3.5...v0.4.0) - 2019-02-06

* [Added] pager support
* [Fixed] pipe broken error