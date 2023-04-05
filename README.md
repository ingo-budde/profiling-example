# profiling-example
* **optional**: create a new binary crate (or just use this repository)
  ```bash
  cargo init --bin
  ```
* install flamegraph into cargo
  ```bash
  cargo install flamegraph
  ```
* run `cargo flamegraph`, which runs the application in release mode and creates a `flamegraph.svg`.
  ```bash
  sudo CARGO_PROFILE_RELEASE_DEBUG=true cargo flamegraph
  ````


# Links
* Flamegraph - https://github.com/flamegraph-rs/flamegraph
* Puffin - https://github.com/EmbarkStudios/puffin
* Tracing - https://docs.rs/tracing/latest/tracing/
* Perf
  - https://rust-lang.github.io/packed_simd/perf-guide/prof/linux.html
  - https://rustc-dev-guide.rust-lang.org/profiling/with_perf.html
