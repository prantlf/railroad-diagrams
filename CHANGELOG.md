## [1.0.0](https://github.com/prantlf/railroad-diagrams/compare/e106349a2d8ec6d559c0b588891b1286d9b888e8...v1.0.0) (2020-04-26)

* Introduce the method `Diagram.fromJSON` to create diagrams from machine readable formats convertible to JSON.
* Add a command-line tool `rrd2svg` for converting JSON or YAML diagram input to SVG output.
* Add a command-line tool `rrdlint` for validating JSON or YAML diagram input.
* Support `VerticalSequence`, which is makes sequences with many items more readable than `Stack`. (Authored by Glynn Williams.)
* Remove Python and separate JavaScript implementation for Node.js. Single JavaScript "source of truth".

This is the first version released after forking the [original project](https://github.com/tabatkins/railroad-diagrams).
