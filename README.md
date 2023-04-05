# profiling-example
* install flamegraph into cargo
  ```bash
  cargo install flamegraph
  ```
* run `cargo flamegraph`, which runs the application in release mode and creates a `flamegraph.svg`.
  ```bash
  sudo CARGO_PROFILE_RELEASE_DEBUG=true cargo flamegraph
  ````
