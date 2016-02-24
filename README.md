# Transit For London GTFS Exporter

This simple rust program pulls data from the TFL Unified API
and converts it to a directory with GTFS files in it.

Install multirust (`curl -sf https://raw.githubusercontent.om/brson/multirust/master/blastoff.sh | sh`)

Set to nightly (`multirust default nightly`)

Clone and "cargo run --release" to generate a gtfs directory with all the 
required .txt csv files.
